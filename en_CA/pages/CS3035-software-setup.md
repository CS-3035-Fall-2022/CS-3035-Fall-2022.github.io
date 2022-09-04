# CS 3035 Software Setup

## TL;DR

- We will be using Java 8 with IntelliJ
- If at all possible install all course software on your own computer
- Otherwise, install software so you can get access to a virtual machine containing all of the course software
- All course software is free and should run on Windows, Mac and Linux
- We also use git but the version built into IntelliJ will be sufficient


## Installing Software for your own computer

### Minimum Hardware Requirements

- The Faculty of Computer Science has made recommendations about the minimum requirements for your coursework.
- These are also appropriate and sufficient for this course.
- Please see: <https://www.cs.unb.ca/help/students/recommended-hardware.shtml>

### Install Java 8

- Download and install the latest version of the Oracle Java 8 SDK: [Oracle 8 JDK](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)
  - see below for why we should use Java version 8
- On Windows, it will also be a good idea to set your JAVA_HOME environment variable: [instructions for setting JAVA_HOME on Windows](https://confluence.atlassian.com/doc/setting-the-java_home-variable-in-windows-8895.html)

### Install IntelliJ Community Edition

- We will be using IntelliJ for writing Code, and there are a number of helpful extensions that should be installed
- [Download and Install IntelliJ Community Edition](https://www.jetbrains.com/idea/download/) - make sure it is Community Edition!
- Once you install you can configure how you like
- But there is an additional step below for adding in Scene Builder
- When you open for the first time you may have two tell IntelliJ where Java 8 is located

### Install Scene Builder

There are two general options for getting Scene Builder. Option 1 will be the most convenient for both installation and use, but you are able to do both.

#### Scene Builder Option 1

- Scene Builder is a JavaFX app for building JavaFX interfaces that can be integrated into IntelliJ
- The easiest way to to do this is to create a new JavaFX project and download it automatically
  - From the launch window choose "New Project"
  - Choose "JavaFX" for the project type
  - Name the project anything you like
  - Open the sample.fxml file
  - At the bottom of the editor window click the "SceneBuilder" tab
  - Click the "Download Scene Builder Kit" link

#### Scene Builder Option 2

- This is not needed if you did the above but you can also [Download Scene Builder as a standalone app for Java 8](https://gluonhq.com/products/scene-builder/#download)
- You can then manually associate your Scene Builder executable with IntelliJ: ```Settings → Languages & Frameworks → JavaFX → Path to SceneBuilder```

## Git

There is a lot of software available to assist in working with Git. Our use should be relatively straightforward and so the version built into IntelliJ will be the one that is supported for the course. See [Using Git](pages/../CS3035-assignments-with-git.md)

## Why do Java Versions Matter

Java is going through some rapid changes that have made things a little complicated. The purpose of this guide is to assist you in installing a version of Java and VS Code that will work on your personal system.

One major challenge that has arisen is that beginning with Java 11, JavaFX is a separate download... getting Java 11 or later, and Java FX to work can be tough. So, we recommend using Oracle Java 8 on your personal computers, since it includes JavaFX.
