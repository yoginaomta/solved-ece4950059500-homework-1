Download Link: https://assignmentchef.com/product/solved-ece49500_59500-homework-1
<br>
<strong>Task 1  </strong>Create an Ubuntu virtual machine and submit the screenshot for <strong>spyder</strong> running on it. <strong> </strong>

Install VMWare Player or Virtual Box for Running a Virtual Machine

<strong>VMWare Player Installation  </strong>

<ul>

 <li>Download VMWare workstation player from <a href="https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html">https://www.vmware.com/products/workstation</a><a href="https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html">–</a><a href="https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html">player/workstation</a><a href="https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html">–</a><a href="https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html">player</a><a href="https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html">html</a></li>

 <li>You may Refer <a href="https://www.youtube.com/watch?v=9QXXyG0hKtI">https://www.youtube.com/watch?v=9QXXyG0hKtI</a> for installation</li>

 <li>Download Ubuntu image from <a href="https://releases.ubuntu.com/bionic/ubuntu-18.04.5-desktop-amd64.iso">https://releases.ubuntu.com/bionic/ubuntu</a><a href="https://releases.ubuntu.com/bionic/ubuntu-18.04.5-desktop-amd64.iso">–</a><a href="https://releases.ubuntu.com/bionic/ubuntu-18.04.5-desktop-amd64.iso">04.5</a><a href="https://releases.ubuntu.com/bionic/ubuntu-18.04.5-desktop-amd64.iso">desktop</a><a href="https://releases.ubuntu.com/bionic/ubuntu-18.04.5-desktop-amd64.iso">–</a><a href="https://releases.ubuntu.com/bionic/ubuntu-18.04.5-desktop-amd64.iso">amd64.iso</a> § Refer link <a href="https://websiteforstudents.com/how-to-create-new-virtual-guest-machines-on-vmware-workstation-player/">https://www.youtube.com/watch?v=9rUhGWijf9U</a><a href="https://websiteforstudents.com/how-to-create-new-virtual-guest-machines-on-vmware-workstation-player/">/</a>for creating an Ubuntu virtual machine.</li>

</ul>

<strong>Virtual Box installation (For those who have Mac book) </strong>

<ul>

 <li>Refer <a href="https://www.youtube.com/watch?v=lEvM-No4eQo">https://www.youtube.com/watch?v=lEvM</a><a href="https://www.youtube.com/watch?v=lEvM-No4eQo">–</a><a href="https://www.youtube.com/watch?v=lEvM-No4eQo">No4eQo</a> for virtual box installation</li>

 <li>Download Ubuntu image from <a href="https://releases.ubuntu.com/bionic/ubuntu-18.04.5-desktop-amd64.iso">https://releases.ubuntu.com/bionic/ubuntu</a><a href="https://releases.ubuntu.com/bionic/ubuntu-18.04.5-desktop-amd64.iso">–</a><a href="https://releases.ubuntu.com/bionic/ubuntu-18.04.5-desktop-amd64.iso">04.5</a><a href="https://releases.ubuntu.com/bionic/ubuntu-18.04.5-desktop-amd64.iso">desktop</a><a href="https://releases.ubuntu.com/bionic/ubuntu-18.04.5-desktop-amd64.iso">–</a><a href="https://releases.ubuntu.com/bionic/ubuntu-18.04.5-desktop-amd64.iso">amd64.iso</a></li>

 <li>Refer link <a href="https://www.youtube.com/watch?v=fh8OdDd0K30">https://www.youtube.com/watch?v=fh8OdDd0K30</a> for creating Ubuntu virtual machine.</li>

</ul>




<h1>Python Editor Installation</h1>

<ul>

 <li>Python3 is already installed in Ubuntu 18.04</li>

 <li>Login to Ubuntu VM after installation and open the terminal Type sudo apt-get install spyder to install the <strong>spyder</strong> editor</li>

 <li>Type sudo apt-get install python3-pandas to pandas library, this also contains numpy library</li>

 <li>Once spyder is installed, you can launch it from the terminal by typing spyder or search it in <strong>show applications</strong> (bottom left).</li>

</ul>




<strong>Task 2 </strong>Assume in an ATM, there are $100, $50, $20, and $10 bills. Write a python script <strong>atm.py</strong> for the ATM machine that will accept the amount to be withdrawn and dispense the cash with a <strong>minimum</strong> number of bills if the amount can be withdrawn. Following are a few test cases for your program:




Enter the amount for withdrawal: 150  Please collect your bills as follows:

$100: 1

$20: 2

$10: 1

Enter the amount for withdrawal: 75  The amount cannot be withdrawn.




<strong>Task 3 </strong>Write a <strong>registrar.py</strong> script that will load the <strong>records.txt</strong> file (uploaded with the assignment). The file has students’ scores for different subjects. The script will be user interactive and it will ask for user choice. Based on the choice, it will perform following tasks:

<ol>

 <li>Display students’ letter grades for each subject. You may consider this grading scale:</li>

</ol>

F &lt; 60, 60 &lt;= D &lt; 70, 70 &lt;= C &lt; 80, 80 &lt;= B &lt; 90, and 90 &lt;= A.  The output format should be as follows:

<table width="348">

 <tbody>

  <tr>

   <td width="90"><strong>student </strong></td>

   <td width="90"><strong>ece595 </strong></td>

   <td width="90"><strong>ece547 </strong></td>

   <td width="78"><strong>ece354 </strong></td>

  </tr>

  <tr>

   <td width="90">ahmad</td>

   <td width="90">A</td>

   <td width="90">B</td>

   <td width="78">A</td>

  </tr>

  <tr>

   <td width="90">…</td>

   <td width="90">…</td>

   <td width="90">…</td>

   <td width="78">…</td>

  </tr>

 </tbody>

</table>




<ol>

 <li>Display the highest score and scorer in each subject. The output format should be as follows:</li>

</ol>

<table width="270">

 <tbody>

  <tr>

   <td width="90"><strong>subject </strong></td>

   <td width="90"><strong>scorer </strong></td>

   <td width="90"><strong>score </strong></td>

  </tr>

  <tr>

   <td width="90">ece595</td>

   <td width="90">Hailu</td>

   <td width="90">93</td>

  </tr>

  <tr>

   <td width="90">…</td>

   <td width="90">…</td>

   <td width="90">…</td>

  </tr>

 </tbody>

</table>




<ol>

 <li>Display the GPA of each student. The grade points for A, B, C, D, and F are 4, 3, 2, 1, and 0, respectively. Assume that the credit hours for each course is same, then GPA will be average of the grade points. The output format should be as follows:</li>

</ol>

<table width="180">

 <tbody>

  <tr>

   <td width="90"><strong>student </strong></td>

   <td width="90"><strong>Gpa </strong></td>

  </tr>

  <tr>

   <td width="90">ahmad</td>

   <td width="90">3.667</td>

  </tr>

  <tr>

   <td width="90">…</td>

   <td width="90">…</td>

  </tr>

 </tbody>

</table>




<strong>Task 4 [25 points] </strong>Review the attached paper titled as “<em><u>The pathologies of big data</u></em>” and summarize your findings in 400-500 words.