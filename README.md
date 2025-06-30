# Windows-Fundamentals-1
This is a walkthrough of the TryHackMe room of the same name found here: https://tryhackme.com/room/windowsfundamentals1xbx. It is part of the Cyber Security 101 learning path.

<h2>Description</h2>
The Windows fundamentals module from TryHackMe provides a general overview of the Windows OS. I improved my ability to navigate the user interface and make system changes by completing this walkthrough.

<h2>Environments Used </h2>

- <b>Windows Server 2019 Standard</b>

<h2>Project walk-through:</h2>

- <b>Windows Editions</b>
<p>In the first section of this room I learned a bit of the history of the previous Windows editions as well as information about the differences between the home and pro versions of the current Windows edition - Windows 11.</p>
<br>
<p align="center">After reading the informational text in the TryHackMe room, I consulted the comparison table for the Winows 11 home vs. Windows 11 pro editions<br/>
  <img src="https://github.com/user-attachments/assets/ef3895f7-304b-45c6-b6d9-bbd7d2e83513" height="80%" width="80%" alt="image one"/>
 Using the information in the comparison table, I was able to answer the question "What encryption can you enable on Pro that you can't enable in Home?" with the name Bitlocker.<br />
  <img src="https://github.com/user-attachments/assets/6f81553e-9dea-4db5-bdae-7640025912c3" height="80%" width="80%" alt="image two"/>
</p>
<br />
<br />
- <b>The Desktop (GUI)</b>
<p>This section gave a map for the Windows desktop, start menu, and various settings such as display, background, and the taskbar. </p>
<br>
<p align="center">After reading about navigating the desktop, and using the attached virtual machine to explore myself, I searched the desktop environment for the answers to the questions at the end of the sectio. The First question was "Which selection will hide/disable the Search box?" I found the answer to this question by right clicking on the taskbar and then clicking on search, which gave me the option to either show search icon, or select hidden.<br/>
  <img src="https://github.com/user-attachments/assets/5e9e31b0-ecea-4664-9e3d-0e291badf01b" height="80%" width="80%" alt="dark gray menu for the taskbar settings with search selected. A second smaller menu is seen to the right of the main menu with the options hidden and show search icon. A red rectangle is around this smaller menu to draw attention to this information."/>
  <br />
  <br />
In the same taskbar menu, I can see an option which answers the second question "Which selection will hide/disable the Task View button?" Currently the selection "Show task view button" has a checkmark next to it, indicating it is currently enabled. By clicking it again I can disable it.<br />
  <img src="https://github.com/user-attachments/assets/30d83f6f-e049-430f-92cf-652b9d6ebfe6" height="80%" width="80%" alt="dark gray menu for the taskbar with a red rectangle around the option show task view button"/>
  <br />
  <br />
For the last question in this section, "Besides Clock and Network, what other icon is visible in the Notification Area?" I found the name of the icon by right clicking on it, which brought up a menu that says "open action center" at the top. From this I was able to conclude that the icon in the notification area is that for the action center.
<br />
  <img src="https://github.com/user-attachments/assets/72b9d263-436d-4203-824e-81df8d6cc951" height="80%" width="80%" alt="the action center menu is shown with a red rectangle around the option open action center"/>
   <br />
  <br />
After exploring and finding those options in the various menus I was able to correctly answer all of the section questions.<br />
  <img src="https://github.com/user-attachments/assets/ef40e855-ce4e-424f-b26e-db457d4540eb" height="80%" width="80%" alt="white background with green text that reads answer the questions below followed by 3 question and answer pairs. The questions are printed in black and the answers are in gray rounded rectangles with lime green correct answer icons to the right of the answer. Question 1 reads which selection will hide disable the search box and the answer reads hidden. Question 2 reads which selection will hide disable the task view button and the answer reads show task view button. Question 3 reads besides clock and network what other icon is visible in the notification area and the answer reads action center."/>
</p>
- <b>The File System</b>
<p>In this section I learned about the file system currently in use in the Windows OS - New Technology File System (NTFS). I also read about past file systems like FAT16/FAT32 which are still in use for flash media, and HPFS (High Performance File System). Some of the limitations of previous file systems addressed by NTFS are file size, the ability to set specific permissions on folders and files, folder and file compression, and encryption.</p>
<br>
<p align="center">After reading about the file system I learned the different permission types (full control, modify, read & execute, list folder contents, read, and write) and where to view the permissions for a given folder or file. Here is an example image of where to find this information in the security tab of of the properties window for a folder.<br/>
  <img src="https://github.com/user-attachments/assets/f366d923-8cec-46c5-815e-c8f7798338e4" height="80%" width="80%" alt="a set of windows from the C drive of a windows computer to the far left this pc is selected, then to the right of that a folder with the name Windows is selected in the windows properties to the right of that column the middle tab, security, is indicated with a red rectangle, below that in the group or user names the line Users is highlighted in blue and the bottom of the window shows the permissions for users. From the list on the left which reads top to bottom Full control, Modify, Read and execute, list folder contents, read, and lastly write, the options for read and execute, list folder contents, and read have check marks in the allow column to in the middle of the window."/>
  <br />
  <br />
As a final step in this section I answered the question "What is the meaning of NTFS?" with the answer "New Technology File System".<br />
  <img src="https://github.com/user-attachments/assets/0641af50-c66c-4ed3-815f-7eddff7c6219" height="80%" width="80%" alt="white background with the question in black text and the answer in a gray rectangle with rounded corners and next to the answer field is a lime green correct answer. The question says what is the meaning of NTFS and the answer says new technology file system."/>
</p>
- <b>Section Name</b>
<p>Description</p>
<br>
<p align="center">Step One: <br/>
  <img src="" height="80%" width="80%" alt="image one"/>
  <br />
  <br />
  Step Two: <br />
  <img src="" height="80%" width="80%" alt="image two"/>
  <br />
  <br />
  Step Three: <br />
  <img src="" height="80%" width="80%" alt="image three"/>
   <br />
  <br />
  Step Four: <br />
  <img src="" height="80%" width="80%" alt="image four"/>
   <br />
  <br />
  Step Five: <br />
  <img src="" height="80%" width="80%" alt="image five"/>
</p>
