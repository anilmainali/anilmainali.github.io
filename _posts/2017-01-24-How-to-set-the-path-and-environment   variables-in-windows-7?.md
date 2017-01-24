---
layout: post
title: How to set the path and environment variables in windows 7?
subtitle: Fix 'javac' is not recognized as an operable program or batch file.
tags: [Java Path,Java environment, Java-Development-Kit (JDK)]
bigimg: /img/path.jpg
---

Please follow these steps:

Press the Windows key on your keyboard or 
click the Windows Start orb.
Right-click on Computer.
Select and click Properties from the context menu.
Select and click Advanced system settings link.
Select Advanced.Click Environment Variables. 

Scroll down to the section System Variables,find the 

PATH environment variable and select it. 

Click Edit. 

Tips: Select and Copy the Variable value and paste it 

on your favourite text editor and save it.

Note:The PATH environment variable is a series of 

directories separated by semicolons (;)

WARNING: Do not delete this path.Append the path with 

with semicolon;

Add the location of the bin folder of the JDK 

installation to the PATH variable in System 

Variables. This may look like:
C:\Program Files\Java\jdk1.8.0_121\bin

Tips: To find exactly the location of the bin folder 

of the JDK installation follow these steps:

Press the Windows key on your keyboard or 
click the Windows Start orb.

Click on computer.

Click on Windows7_OS(C:)under Hard Disk Drives.
Scrool down select and click on Program Files

Scrool down select and click on Java folder

Click on jdk folder

Click on bin folder
Select the entire path from the address bar

Copy the path

Appending with a semicolon at end of existing path 

paste the Path you just copied.

Now click OK.
Again click OK to close the Environment Variables 

dialog.
Click OK to close the System Properties dialog.

Congratulations, you have successfully set the path 

and environment variables in windows 7
