# Intro to 3DPrinterOS

3DPrinterOS is the management platform that allows you to access all 3D printers in the SHED. To access 3DPrinterOS, click the link below;

[3DPrinterOS (RIT SSO Link)](https://cloud.3dprinteros.com/ssosaml/rit/auth){:target="_blank" .md-button}

!!! warning
    <img src="..\assets\3dprinteros SSO.png" class="image-float-right" width=20%>
    You **must** access the printers via SSO (single sign-on) with your RIT account. Do so at the link above, or on the 3DPrinterOS login page, hit "SSO" and select "Rochester Institute of Technology" from the list.

    Creating an account any other way, or using a standard 3DPrinterOS account, will not work. Even if it uses your RIT email address! Attempting to bypass SSO requirements will break the system and you will not be able to access 3D printers.
    <p class = "clear-float"></p>

## Navigating 3DPrinterOS

The 3DPrinterOS website is broken into a number of pages, accessible at the top of the screen. Let's go through each of them;

<img src="../assets/3dprinteros navigation.png" class="image-float-left" width=100%>

 <p class = "clear-float"></p>

### Projects

 This is where your files live. You have 1GB of storage space on the 3DPrinterOS cloud for 3D models and prepared machine files (GCode).

 Files can be uploaded with the "Add files" button. Suggested file types are STL and OBJ, but other file types can be uploaded and converted in the cloud.

<img src="../assets/3dprinteros selected file.png" class="image-float-right" width=30%>

 By default, files will go into your "Files" tab. You can organize files into folders, called "Projects", where they will then appear in your Projects tab. To create a Project, hit the "..." menu next to the "Add files" button, and select "Create project". Files can then be moved by selecting the toggle next to their icon, and hitting "Move to project". 

<p class = "clear-float"></p>

A new project is automatically created whenever you make a derivative of a file as well. For instance, converting an uploaded 3MF to an STL will put both the 3MF and the STL into a new project together. 

The projects page is also where you prepare files for 3D printing, see [3D Model Preparation](#3d-model-preparation) below for more information on this.

### Activity

The activity page shows all your past activity on 3DPrinterOS. Submitted prints will be shown here, as well as their status (success, failure, in progress). You can click on a print to get more information. 

By hitting the "..." menu to the right of a job, you can also restart it, see details (same as clicking) or view any notes from staff on your 3D print. 

<img src="../assets/3dprinteros activity.png" class="image-float-left" width=100%>

<p class = "clear-float"></p>

### Printers

<img src="../assets/3printeros print queues.png" class="image-float-right" width=50%>

The "Printers" tab lets you see print queues you have access to, and where your parts are in queue. 

Parts nearer the top will be printed next. You can see a time estimate next to each print. Your print is the only one(s) that have details visible. 

If you hit the "..." menu you can cancel your own prints if they are not already started.

If you do not see any printers, you probably are missing trainings! Check make.rit.edu for more info.

<p class = "clear-float"></p>

## 3D Model Preparation