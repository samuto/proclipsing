# Getting Started : Installing Proclipsing & Creating a Project #

# Introduction #

This Tutorial will show you how to install Proclipsing and Create a Project with it.  It will walk you through adding the Proclipsing Plugin to Eclipse and creating your first Proclipsing project.

# Details #

Initially, we are focusing on project creation.  To this end, the
plugin allows you to select the location of your processing app, which
libraries you want, and then creates a project with the desired libs
(with native libraries), and skeleton package structure and PApplet.

### Download Eclipse: ###

Go to <a href='http://www.eclipse.org/downloads/'>The Eclipse Download Page</a>.  Download the "Eclipse IDE for Java Developers" for your Operating System.

### Download Processing: ###

Go to <a href='http://processing.org/download/'>The Processing Download Page</a>.  Download the most recent version of Processing for your Operating System.


### To add Proclipsing to Eclipse: ###

These steps might vary slightly based on what version of Eclipse you have.  The wording might be slightly different, but the process is pretty much the same.

  * open the eclipse folder, then open eclipse
  * select a workspace (at the beginning the default should be fine)
  * select help>Install New Software

<img src='http://farm3.static.flickr.com/2642/4076374014_9c2e0f8ba7_o.jpg' alt='pro1' width='1022' height='791' />

  * click on the "Add" button on the top right
  * enter "Proclipsing" in the "Name" field
  * enter "`http://proclipsing.googlecode.com/svn/tags/current_releases/proclipsingSite/`" in the "location" field
  * click "ok"

<img src='http://farm3.static.flickr.com/2737/4075620487_d8e5135ef6_o.jpg' alt='pro2' width='1023' height='792' />

  * select both "core" and "export"
  * click "next"

<img src='http://farm3.static.flickr.com/2542/4075620685_c762168546_o.jpg' alt='pro3' width='1023' height='792' />

  * click next (and agree to all following popups)

<img src='http://farm3.static.flickr.com/2487/4076375394_f6be953255_o.jpg' alt='pro4' width='1023' height='792' />

  * when prompted to restart eclipse, agree to it
  * if the "Welcome" tab is open, close that tab

### To set up Global Proclipsing Preferences: ###

<img src='http://farm5.static.flickr.com/4008/4289513888_8f27a9bef1_o.png' alt='Picture 6' width='667' height='535' />

  * Select Eclipse preferences (On a MacOSX, select Eclipse>Prefences)
  * Select Proclipsing
  * Click the "**Browse**" button next to the "**Processing Path**" field (this is the folder that the Processing app is in on **Windows** or **Linux**.  For Processing 1.0+ on **MacOsX**, this the bundled Processing Application).
  * Click the "**Browse**" button next to the "**Processing Sketch Path**" field (this is the folder that the Processing Sketch Folder)

### To create your first Proclipsing Project: ###

<img src='http://8.media.tumblr.com/tumblr_kr226cVmMe1qzqc80o1_500.png' />

  * Select File >> "**New Project**"
  * Open the "**Processing**" folder
  * Select "**Processing Project**" and click next

<img src='http://farm5.static.flickr.com/4006/4289513908_c3227c0d0f_o.png' alt='Picture 7' width='627' height='754' />

  * Enter a name for your project in the "**Project Name**" field
  * Click the "**Browse**" button next to the "**Processing Path**" field (this is the folder that the Processing app is in on **Windows** or **Linux**.  For Processing 1.0+ on **MacOsX**, this the bundled Processing Application).
  * Click the "**Browse**" button next to the "**Processing Sketch Path**" and navigate to your sketch folder, then select the libraries inside (if you don't have a folder named "libraries" in your sketch folder, you might want to create one).
  * Select whether you want the project to be an **Application** or an **Applet** (Applet for the web, Application for local).
  * Select the libraries you want to use in this project with in the libraries windows.
  * Select **Finish**