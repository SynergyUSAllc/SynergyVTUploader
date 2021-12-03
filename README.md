### **Virus Total Uploader Automation**
# **Never have your software product marked as malware again!**

 ![image1](https://user-images.githubusercontent.com/94911727/144462279-b64cf0e4-c1d2-4214-8168-630786fd66b3.png)

## **The Problem**

Uploading our software products to Virus Total for checking, takes a lot of effort and time.
 Especially if a project consists of multiple files.
 We as developers have to use a browser every time and wait for each upload to finish before sending the next one.

## **The Solution**

We created a simple application that automates this process.
 You can now upload your files to VT via our application and let it run in the background. When it&#39;s finished you can review the results and proceed accordingly.

By submitting your files via SynergyVTUploader and therefore to Virus Total you are contributing to raise the global IT security level.

Malware signatures are updated frequently by Virus Total as they are distributed by antivirus companies, this ensures that SynergyVTUploader uses the latest signature sets without the need of updates.

SynergyVTUploader can automatically upload to Virus Total any file you want and does all the work for you with with just a click.

All you have to do by yourself is register for a free API key at [VirusTotal - Join us](https://www.virustotal.com/gui/join-us) , copy and paste it to the APIkey.txt file (included in the zip file) just once and you are ready to upload your files for check.

• No installation needed

• Saving time by automatically uploading your products to Virus Total

• Upload multiple files

• No need for manually locally updating AV Engine

• Runs through CMD or Batch file

• Can be added directly to your code editor

• Upload to VT without the need of a browser

• The only Windows product that automates the VT upload procedure

(As of Dec/2021)

## **How to use**

You can simply run the application through command line and pass the file to be checked as a parameter. See image below for an example:

_SynergyVTUploader.exe_ _YourFileName_

 ![image2](https://user-images.githubusercontent.com/94911727/144462433-80d8825b-7fc8-4e4b-bc46-abc1f9791693.png)

## **Batch file:**

You can also use the batch file _\_CheckVT.bat_ which is also included in the zip file you downloaded
 To use the Batch file type the file name for any file you want and the path of SynergyVTUploader.exe folder
 Batch file can be stored to any directory as long it has the correct path to the SynergyVTUploader.exe

 ![image3](https://user-images.githubusercontent.com/94911727/144462514-bba2016c-7622-4edb-86fc-0de3b4a6745c.png)

_ **Bach file Example:** _

@echo off

cls

REM JUST CHANGE THE EXECUTABLE OR DLL FILENAME AND RUN

Set FileName=_RandomFile.exe_

 &quot;_C:\Users\USER\Desktop\SynergyVTUploader_\SynergyVTUploader.exe&quot; %FileName%
 
Pause

## **Results:**

The posible results after the procedure completes are the following:
 Harmless, Type-unsupported, Suspicious, Confirmed-timeout, Timeout, Failure, Malicious
 Followed by a number .

**Results Example:**

 ![image4](https://user-images.githubusercontent.com/94911727/144462617-e09d3a3d-63f4-45e4-a396-d6950bd7189b.png)
 
 
 ### **Watch Video**
 
 
 [![Watch the video](https://user-images.githubusercontent.com/94911727/144583227-611c21c4-7dbb-4a6d-b182-76320e5bf87f.png)](https://youtu.be/8dZMzDT8onA)
 
 

 
## **F.A.Q**

1. Can SynergyVTUploader run on a Linux machine?

    Answer: NO

    &quot;The application runs on Windows OS.&quot;


2. Wich .Net version SynergyVTUploader uses?

    Answer: 4.5
    

3. Can I run SynergyVTUploader without an API key from Virus Total website?

    Answer: NO

    &quot;Visit [VirusTotal - Join us](https://www.virustotal.com/gui/join-us) for a Free API Key&quot;
    

4. Do I need to download other files or programs to run SynergyVTUploader?

    Answer: NO

    &quot;All the files you need are included in the zip file you downloaded you don&#39;t need to download
     anything alse, we recommend you extract the files in a separated folder&quot;
