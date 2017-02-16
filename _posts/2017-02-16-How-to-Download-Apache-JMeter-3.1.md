---
layout: post
title: How to Download Apache JMeter 3.1
subtitle: #1 Open Source Load Testing Tool
tags: [JMeter,Open Source Tool,Load Testing Tool,Tools]
bigimg: /img/path.jpg
---

## Introduction
--------------------------- 
In this tutorial, we will learn step by step process of how to Install and start JMeter 3.1 on Windows 7 machine. At the same time, we will  also  learn about the basic knowledge of what JMeter is and why we use JMeter.

### What is JMeter?

- The Apache JMeter application is open source software.
- It is 100% pure Java application designed to load test.
- It is designed for analyzing and measuring the performance of a variety of applications, with a focus on web applications.


### Why JMeter?
Some of the benefits of using JMeter are:

0. It is open source testing tool.
0. It is the most popular performance tool.
0. It is very easy to Install. All you need is internet connection to download into your machine and start working. 
0. It is very  userfriendly.
0. Besides HTTP protocol it is compatible with multiple protocols.
0. Finallly, it is very well documented and has a Big community support.In this way you can easily get help when you need it.

**Before you begin this tutorial you'll need the following:**

- Windows 7 machine with internet access to Install JMeter on your machine.

Prerequisites
---------------------- 
- Apache JMeter 3.1 (Requires Java 7 or later). 
- Operating Systems:Any operating system that has a compliant Java implementation.

### Step 1 — Check whether Java Runtime Environment (JRE) is installed on your computer.

Steps to check whether Java Runtime Environment (JRE) is installed in your computer.

There are several ways to check whether Java Runtime Environment (JRE) is installed in your computer.Few of the Tips are presented below.

**The options listed below are for Windows 7.**

#### Using the Command-line to find Java Versions

  Open the Terminal window and type java -version 

#### Java Version under Windows Start Menu

0. Launch the Windows Start menu
0. Click on Programs
0. Find the Java program listing
0. Click About Java to see the Java version

#### Java Version in Windows Programs

0. Click Start
0. Select Control Panel
0. Select Programs
0. Click Programs and Features
0. The installed Java version(s) are listed.

#### By Navigating to the browser

Navigate to this link: https://www.java.com/en/download/installed8.jsp

```
Note:If Java is not installed at all on your machine then you can follow this download link and install Java  https://www.java.com/en/download/
```

**Let us verify by Navigating to the browser.**

**Steps to follow:**

0. Navigate to this URL: https://www.java.com/en/download/installed8.jsp 
 
   ![01_install_jmeter__verifyjava](https://cloud.githubusercontent.com/assets/10678180/17453542/0f97be1e-5b43-11e6-9a57-59eb2fcda899.png)

0. Click on the big red button Verify Java Version.
 
   ![05a_install_jmeter__run](https://cloud.githubusercontent.com/assets/10678180/17455213/7ccd0060-5b76-11e6-9734-cf761728181d.png)

0. The Java detection app will ask for permission to run. Click Run to allow the verification process to continue.

   ![03_install_jmeter__congratulation](https://cloud.githubusercontent.com/assets/10678180/17454252/6f85781e-5b54-11e6-8300-38295633559f.png)
  
0. If Java is already installed on your computer and is up to date then you will get this Congratulation Massage. 

   **NOTE:** If you see this message then you need not follow the below steps. You may proceed with Step 2 --
 
   ![03_install_jmeter__installed](https://cloud.githubusercontent.com/assets/10678180/17455239/79819816-5b77-11e6-8136-350a55f2129f.png)

    Note: if the Java is installed and if it’s not up to date then you will get this screen.
 
    ![05a_install_jmeter__run](https://cloud.githubusercontent.com/assets/10678180/17455257/d22e45ae-5b77-11e6-8b0b-dc20bdcb3d61.png)
 
 0. If you wish to update with the latest version then go ahead and click on Run to update.
 
    ![downloadjavanow](https://cloud.githubusercontent.com/assets/10678180/17455329/c190ea7e-5b79-11e6-90be-e1a45fc7ec15.png)
 
0. Click on big red Download Java Now button.

    ![install_jmeter_agreeandinstall](https://cloud.githubusercontent.com/assets/10678180/17458061/3cee4c4a-5bcd-11e6-9bcd-1ef90ab39cb6.png)

0. Follow the Java install wizard dialog and complete the download process.

   Now we have verified,updated and Installed Java 7 or later version in our system, we are ready to kick off with our Apache JMeter 3.1 installation.

### Step 2 — Install Apache JMeter 3.1 on Windows 7

0. Navigate to this URL: **http://jmeter.apache.org/**

   ![01_installjmeter_drealeases](https://cloud.githubusercontent.com/assets/10678180/17459658/981e443c-5c07-11e6-8b89-093135acc9bd.png)

0. Under **Download**, click on **Download Releases.**

   ![01_binaryzip-2](https://cloud.githubusercontent.com/assets/10678180/23039364/edf645a6-f452-11e6-8d3d-e059ea1ca398.png)   


0. Under Binaries,choose and click  (apache-jmeter-3.1.zip md5 sha pgp) to download the zip file as shown in figure above.

   ![02_zipfiledownloaded](https://cloud.githubusercontent.com/assets/10678180/23039367/edf9906c-f452-11e6-959f-3125e51e38ed.png)

0. Zip file is downloaded.

   ![03_showinfolder](https://cloud.githubusercontent.com/assets/10678180/23039363/edf539d6-f452-11e6-8fec-5ba0b4db0182.png)

0. Double click or  click on the drop down arrow. Select and Click on **Show in folder** 


0. Double click on apache-jmeter-3.1.zip folder.

   ![05_delectdesfilesdialog](https://cloud.githubusercontent.com/assets/10678180/23039366/edf8e626-f452-11e6-8541-1c97163c6226.png)

0. Now you have to unzip the file. Click on **Extract all files**

   ![06_selectandextract](https://cloud.githubusercontent.com/assets/10678180/23039368/ee039120-f452-11e6-93a5-a7333d96e219.png)  

0. Select a Destination and Extract Files dialog box opens.


 


0. Click on **Browse** , select a destination where you want to place your JMeter File and Click on **Extract*

     ```
        Note: In my case I have selected C:/Software
      ```

    ![07_extractionprocessstarts](https://cloud.githubusercontent.com/assets/10678180/23039369/ee03ca32-f452-11e6-900d-10aeed4d1926.png)

0. Extraction Process Continues ...

    ![08_extractsundersoftware](https://cloud.githubusercontent.com/assets/10678180/23039370/ee0d4a9e-f452-11e6-99d6-bb3532d4b245.png)

0. Extraction Process completes and you can see the extracted **apache-jemeter-3.1** folder under C:\Software directory.


Congratulation ! You have successfully installed JMeter 3.1 on Wondows 7. We will learn how to open the JMeter tool in Step 3. 

### Step 3 — Open JMeter


   ![01_navigate](https://cloud.githubusercontent.com/assets/10678180/17460092/82449f0c-5c1c-11e6-9f3f-03313ddf9387.png)


0. Navigate to the folder where you had previously unzipped and saved your JMeter file. For Example: In my case - I Click ed on windows >Computer>Windows7_OS(C:)>Software

   ![02_select](https://cloud.githubusercontent.com/assets/10678180/17460095/890430a0-5c1c-11e6-9a0f-7ffc0a78ff5e.png)

0. Select **apache-jemeter-3.0** folder and double click.

   ![03_binfolder](https://cloud.githubusercontent.com/assets/10678180/17460097/8ec604f0-5c1c-11e6-8487-a67117efdadf.png)

0. Double Click on **bin folder**

   ![04_batfile](https://cloud.githubusercontent.com/assets/10678180/17460098/947726ea-5c1c-11e6-8322-9036bb665c61.png)

0. Double Click on **jmeter.bat file**

   ![05_run](https://cloud.githubusercontent.com/assets/10678180/17460099/9afb626a-5c1c-11e6-836e-3d681acd6b42.png)

0. Click on **Run** from the pop up window.

    ![06_cmd](https://cloud.githubusercontent.com/assets/10678180/17460100/a08dfb98-5c1c-11e6-86e0-899fd9400936.png)
   

0. Command line interface pops up. 


 Note: Do not close the command line pop up.


   ![07_jmeterinterface](https://cloud.githubusercontent.com/assets/10678180/17460102/a72bd9c0-5c1c-11e6-8be9-64e9c2656541.png)
  
0. After couple of seconds, Apache JMeter interface opens.


Conclusion
------------------------
Congratulation! In this article you learned how to download and Install JMeter successfully on Windows 7.Thank you for taking out your time and going through the turorial.

Follow the blog for the next **JMeter step by step Tutorial on how to sett up the proxy and Work with our First JMeter Script.**
