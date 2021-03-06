## Part 1: Creating your Xcode Project
In this tutorial you will be creating a notes app which has two screens:

1. A note list screen containing a tableview used to display a list of notes

![Note List] (assets/P1/screenshot1.png)

2. A note list screen containing a text field and text view where notes can be created, edited, or viewed. 

![Note Screen] (assets/P1/screenshot2.png)

First, create a new Xcode project the same way as in previous tutorials. 

1. Choose "Create a new Xcode project" from the main screen or "File -> New -> Project"
2. Choose "Single View Application" 
3. Product Options
  *	 Product Name - Notes
  *	 Language - Swift
  *	 Devices - Universal
  *	 Uncheck use Core Data/unit tests/ui tests

Next, we're going to delete some stuff that we no longer need.

1. Delete ViewController.swift
2. Open Main.storyboard and delete the only scene in the middle of the file.

### Recap

You set up your Xcode project and deleted some of the default files that we won't need. 
