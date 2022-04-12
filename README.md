
# CS455Project -react native mobile computing
<h1 align="center"> Recursive note maker </h1> <br>


<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents


 
 
 
 
 
 Troubleshooting tips
 Credits and acknowledgments
 - [Introduction](#Introduction)
- [Configuration and Installation instructions](#Configuration-and-Installation-instructions)
- [Operating instructions](#Operating-instructions)
- [Manifest (list of files)](#Manifest-(list-of-files))
- [Copyright information](#Copyright-information)
- [Contact information](#Contact-information)
- [Bug list](#Bug-list)
- [Acknowledgments](#acknowledgments)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introduction

<p align="center">
    <a href="https://ibb.co/6sv24tb"><img src="https://i.ibb.co/jgvWTzT/image.png" alt="mig" border="0"></a>
</p>

The purpose for this project is to use the knowledge gained on mobile computing during the
semester and develop an application. User interface, API and other functionalities will be in use.<br>
Purpose of making this app is to enhance the experience of being a student.

## Configuration and Installation instructions

**Expo Go app Required on the smartphone.**<br>

**Make sure to have NodeJS installed on your system** <br>

Go to <a href="https://reactnative.dev/docs/environment-setup">React native set up</a> to get more info on how to install Expo CLI on the system. <br>

```
npm install -g expo-cli
expo init <project-name>

cd <project-name>
npm start  # you can also use: expo start
```
<br>
Inside the project folder, replace the default App.js file with the provided App.js file <br>
Add the other .js files in the same location as the App.js file.<br>
After saving the files, in the command prompt, in folder location type ```npm start``` or ```expo start``` <br>
Scan the QR code

**Available for both iOS and Android.**


## Operating instructions

The things you can do with Recrsive Note Maker:

* Add notes to homescreen
* click on note which opens up a new screen which furthur can be opened to another screen.
* Camera for each deatils/note screen
* press and hold the note to delete it
* Restart from home button
* go back button

The user can add notes/tasks and on clicking it, a new screen dedicated to that note/task is built. In the new screen, more tasks can be created, upon click more screens are created for each task. We can go tasks task to tasks recursively.
<br>
Camera Feature is added too for each dedicated screen.











<span align="left">
  <img src = "https://i.ibb.co/6DNqhDY/IMG-0169.png"  width=290>
</span>
<span align="center">
  <img src = "https://i.ibb.co/gb1xH3p/IMG-0172-min.png"  width=290>
</span>
<span align="right">
  <img src = "https://i.ibb.co/SP105tY/IMG-0168.png"  width=290>
</span>


## Manifest (list of files)
* App.js
* todoItem.js
* camera.js
* ListRender.js
* addTodos.js

These are the main files where all the work is done, if you have all the prerequisites for running a react native apps then add the given files in the react-native folder.

## Copyright information
Please check the comments in the above Manifest.


## Contact information

Feel free to send me feedback on my email, tanwarkeerat@gmail.com and please feel free make changes to add new features. 


## Bug list

<span align="left">
  <img src = "https://i.ibb.co/WPxz4GF/IMG-0173.png"  width=290>
</span>
<span align="center">
  <img src = "https://i.ibb.co/GsJqxF7/IMG-0170.png"  width=290>
</span>
1. Some issues with ScrollView. ("VirtualList should not be nested inside ScrollView")
2.
## Acknowledgments

Thanks to [JetBrains](https://www.jetbrains.com) for supporting us with a [free Open Source License](https://www.jetbrains.com/buy/opensource).
