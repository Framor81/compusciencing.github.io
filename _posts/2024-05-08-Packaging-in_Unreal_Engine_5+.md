---
layout: post
title: "Packaging in Unreal Engine 5+"
tags: ["ARCSLaboratory", "Packaging", "PackagingInUE", "UnrealEngine", "Pomona"]
author: "Francisco X. Morales Puente"
---

Here are some instructions on how to package games for Unreal Engine, and share them with a team.

## Unreal Engine 
The first step is to open the folder of whatever project you want to package. Inside of this folder, navigate into the plugins folder and remove "UEGitPlugin-3.12". This plugin sometimes causes packaging or zipping projects to fail.

![Plugin Folder](/assets/2023-10-15-Packaging_in_Unreal_Engine_5+/1.png)

![Remove UEGitPlugin](/assets/2023-10-15-Packaging_in_Unreal_Engine_5+/2.png)

Next, launch Unreal Engine 5+ and open the project that you want to package, and save one last time before continuing.

For both Mac and Windows you may want to change some settings for packaging or building certain aspects of the game. In order to do so, you can find these options on the top right corner once you click settings, and navigate into project settings.

![Project Settings](/assets/2023-10-15-Packaging_in_Unreal_Engine_5+/4.png)

Here you can scroll on the left to find "Project-Packaging" to change options like how the game is built, what the project is named, etc.

![Packaging Settings](/assets/2023-10-15-Packaging_in_Unreal_Engine_5+/5.png)

It is essential to note that you may only package for the system that you are logged into. Meaning that Windows can only package for Windows, and Mac can only package for Mac.

## Packaging for Windows

To package for Windows you may use any computer with the desired project and Unreal Engine 5+ installed. However, it might be easiest to do so on either of the two lab computers.

Once inside your chosen project. Navigate to the top of the screen to the 'Platforms' button. Once clicked you will see a dropdown menu that looks like so:

![Plugin Folder](/assets/2023-10-15-Packaging_in_Unreal_Engine_5+/6.png)

Since we are packaging for a windows machine you will hover over Windows. Once you do you should get more options to the right of it.

![Remove UEGitPlugin](/assets/2023-10-15-Packaging_in_Unreal_Engine_5+/7.png)

You may choose a specific package option below the 'Package Project' and 'Cook Content' button. Choose Development if you need the console for specific commands, otherwise Shipping will run the most smoothly and take up the least amount of space. After selecting your package setting, click Package Project, select the folder you want to download the package .exe, and wait around 5~10 minutes.

![Plugin Folder](/assets/2023-10-15-Packaging_in_Unreal_Engine_5+/8.png)

Eventually you will see the following Until Packaging complete prompt, at which point you will be done packaging your game for Windows!

![Remove UEGitPlugin](/assets/2023-10-15-Packaging_in_Unreal_Engine_5+/9.png)


## Packaging for MAC

In order to package for Mac we must use one of the two computers in the back row, closest to the door in Edmunds 219 as Unreal Engine 5.2 and Xcode 14.2 are installed on them. Much of the same steps will be followed as before except when choosing to package the content you will hover over Mac instead!

### Optional Steps Assuming the Project is on a Windows Device:

    If your desired project is on a Windows device there are a few steps you must first take.

    1. You will need to save your project, and on the top-left corner select File. Here you will click Zip project and choose where you would like to save this zip file.

    ![Remove UEGitPlugin](/assets/2023-10-15-Packaging_in_Unreal_Engine_5+/2.5.png)

    2. After zipping your desired project, you may either upload it to GitEA, send it through Slack, Google Drive, or any other project hosting site that you can download from on a Mac machine.

    3. Next, on the Mac machine you will be using to package the project you must download the zip file and uncompress it. 

    4. After uncompressing your project you can continue like normal.





