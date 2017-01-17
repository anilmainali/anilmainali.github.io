---
layout: post
title: How To  Install Chocolatey on Windows 7
subheadline: The package manager for Windows
tags: [Installation,Chocolatey,Package Manager For Windows]
---

Before you begin this guide you'll need the following:

- Internet Connection.

## Step 1 — Install Chocolatey

Please follow the below steps in order to install Chocolatey on your windows 7 Machine.

0. Open an administrative command prompt as an Administrator.

Note: If you not aware as how to open the command prompt as an Administrator,Please follow these steps.


   ![01_windows](https://cloud.githubusercontent.com/assets/10678180/17673749/34f35ebe-62e8-11e6-9271-8ed95d43d1e2.png)

- Click on the Windows Icon 

   ![02_rightclick](https://cloud.githubusercontent.com/assets/10678180/17673750/35011856-62e8-11e6-9575-1797a46a5571.png)

- Right click on Windows Command Processor, Select and Click on Run as Administrator.
- If User Account Control dialog opens Click Yes.

   ![03_administrator](https://cloud.githubusercontent.com/assets/10678180/17673752/350a6ff0-62e8-11e6-9abb-95aaadf65eaf.png)


Now you have opened command prompt successfully as an administrator.

0. Navigate to the URL: https://chocolatey.org/
 
   ![choco_clickinstall_02](https://cloud.githubusercontent.com/assets/10678180/22045188/5d00ccdc-dcde-11e6-892f-ec89796d1fe5.png)

0. Click on Install.

   ![choco_clickmoreoptions_03](https://cloud.githubusercontent.com/assets/10678180/22045235/97e23d7c-dcde-11e6-924f-ad0598f2e19e.png)

0. Click on More Options under More Install Options 

![05_copyicon](https://cloud.githubusercontent.com/assets/10678180/17673755/350f5c86-62e8-11e6-859e-a3236f595c94.png)

0. Click on the Copy Icon image next to  Cmd.exe-  


   ```
   @powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin
```

   Note:It copies the code needed to invoke on command line.

0. Switch back to command prompt.

   ![06_paste](https://cloud.githubusercontent.com/assets/10678180/17673751/35091c9a-62e8-11e6-8ec6-1c2b35302f55.png)

0. Paste the code which you just copied earlier.

   ```
   @powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin
```

0. Hit Enter on your keyboard. 

   ![07_pdownloaded](https://cloud.githubusercontent.com/assets/10678180/17673754/350bb126-62e8-11e6-82a7-ed881abd1758.png)

0. It downloads the Chocolatey and adds to the Windows Path system **C:\ProgramData\chocolatey\bin** and it is ready to use.

Since chocolatey is installed in our machine.Let us try to Install CC Cleaner as a demo with the help of using chocolatey.

Follow these steps:

0. Navigate to https://chocolatey.org/packages

   ![08_searchccleaner](https://cloud.githubusercontent.com/assets/10678180/17673756/3515debc-62e8-11e6-9cb1-b8e5a52a46b5.png)

0. From the search box search for CCleaner

   ![09_searcha-copycode](https://cloud.githubusercontent.com/assets/10678180/17673757/35192734-62e8-11e6-9755-dbd24c6b9443.png)
   
   At the time of writing this tutorial the latest version of CCleaner was 5.20.5668. You might see a new version now.
   
0. Copy the code : 

   ```
      choco install ccleaner
   ```
   
  Do not copy C:\> which is infront of the code.

   ![10_searchb-pastecode](https://cloud.githubusercontent.com/assets/10678180/17673761/35215990-62e8-11e6-8a86-d2cd963cc78c.png)

0. Switch back to command prompt and paste the code which you just copied.

0. Hit Enter.

   ![11_searchc-patecode](https://cloud.githubusercontent.com/assets/10678180/17673758/351a1982-62e8-11e6-9d5e-f2d8502654b3.png)

   Installation starts...

   ![12_searchd_pastecode](https://cloud.githubusercontent.com/assets/10678180/17673759/351da6e2-62e8-11e6-9f19-6027b5ca214d.png)

0. Type Y and hit Enter.

   ![13_searche_successful](https://cloud.githubusercontent.com/assets/10678180/17673760/3520bd28-62e8-11e6-89af-5e6a531c9739.png)

0. The install of ccleaner was successful message appears.

Congratulations! 
