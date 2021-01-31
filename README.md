# Magic-NewsPaper

An application that detects newspaper images and plays video related to it just like the harry potter movie.

[![](https://img.shields.io/github/followers/DecimatorMind?style=social)](https://github.com/DecimatorMind)

![](https://img.shields.io/github/repo-size/DecimatorMind/Magic-Newspaper)
![](https://img.shields.io/github/issues/DecimatorMind/Magic-Newspaper)
![](https://img.shields.io/github/issues-pr-closed/DecimatorMind/Magic-Newspaper?color=red)
![](https://img.shields.io/github/contributors/DecimatorMind/Magic-Newspaper?color=yellow)
![](https://img.shields.io/github/last-commit/DecimatorMind/Magic-Newspaper)

## ARImageDetection

The application currently uses one image that has been pre-added to the application that is detected and the video related 
to that image is played on the detected node.

## How to run

To run the application you first need to change the image in the application to be detected to an image that you have 
access to.

Also the video related to that image needs to be changed in the application.

## File Structure

    ├── Magic\ NewsPaper
    │   ├── AppDelegate.swift
    │   ├── Assets.xcassets
    │   │   ├── AppIcon.appiconset
    │   │   │   └── Contents.json
    │   │   ├── Contents.json
    │   │   └── NewsPaperImages.arresourcegroup
    │   │       ├── Contents.json
    │   │       └── harryPotter.arreferenceimage
    │   │           ├── Contents.json
    │   │           └── harryPotter.png
    │   ├── Base.lproj
    │   │   ├── LaunchScreen.storyboard
    │   │   └── Main.storyboard
    │   ├── Info.plist
    │   ├── ViewController.swift
    │   ├── art.scnassets
    │   ├── image1.png
    │   ├── image2.png
    │   └── sample.mp4
    ├── Magic\ NewsPaper.xcodeproj
    │   ├── project.pbxproj
    │   ├── project.xcworkspace
    │   │   ├── contents.xcworkspacedata
    │   │   ├── xcshareddata
    │   │   │   └── IDEWorkspaceChecks.plist
    │   │   └── xcuserdata
    │   │       └── pranjalbhardwaj.xcuserdatad
    │   │           └── UserInterfaceState.xcuserstate
    │   └── xcuserdata
    │       └── pranjalbhardwaj.xcuserdatad
    │           └── xcschemes
    │               └── xcschememanagement.plist
    └── README.md


## Where to change

In order to change the image you need to go to the Assets.xcassets folder in the project and you can add as many pictures as
want but at once only one image will be detected.


![my image](Magic%20NewsPaper/image2.png)



In order to change the video, you can drag and drop the video of format mp4 of 360p resolution to the project and in the
ViewController.swift change the name of the video.


![my image](Magic%20NewsPaper/image1.png)
