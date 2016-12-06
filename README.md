---
layout: default
permalink: /
---

# <img src="assets/androidmedium2.png" alt="class logo" class="logo"/> Mobile Application Development syllabus

***If you are a teacher or interested in the design of the course, see the [meta](https://github.com/CSCI-490-MobileAppDevelopment/syllabus/blob/gh-pages/meta.md) document.***

* **Course:** CSCI 490-Mobile Application Development
* **Instructor:** Keith Briggs, [kabriggs@g.cofc.edu](mailto:kabriggs@g.cofc.edu)
* **Need help?**
    * [Piazza](https://piazza.com/)
        * This is a question/answer forum for students to interact with one another. I encourage students to interact with one another as a resource as well as provide instructor answers.
    * Look through and create [issues](https://github.com/CSCI-490-MobileAppDevelopment/syllabus/issues)
    * Office Hours: Tue & Thur- 4:30 to 5:30, Web- 5:00 to 6:30
   * [Email](mailto:kabriggs@g.cofc.edu) for 1-on-1 help, or to set up a time to meet

## Course Description

This hands-on, project-oriented course explores the principles and tools involved in the design and construction of applications for mobile devices. Although the course focuses on the Android platform, the basic concepts and experiences extend to other mobile devices. Topics include an overview of mobile application development, the Android application architecture, mobile application lifecycle, managing application resources, designing user interfaces, data storage options, integrating audio and video, location-based services, cross-platform development using a mobile device emulator, and porting applications to actual devices. In addition to several smaller programming assignments to provide experience and reinforce concepts, students will work in teams on a substantial programming project to design, develop, and deploy a mobile application.
Computers are provided in the lab, though you are encouraged to bring a laptop for in-class exercises.

## Prerequisites

* CSCI 230-Data Structures and Alghorithms or equivalent (CSCI 221 for non-majors)
* Understanding of Java programming language, data types, control flow, and basic method usage in Java
* Working knowledge of an IDE such as Eclipse or IntelliJ (IntelliJ preferred)
* Working knowledge of Git and Github

These won't be enforced by the instructor, but you will be pretty lost without understanding those concepts. If you need a refresher, take a look at the [Beginner Materials](#beginner-materials).

## Course Overview

We will dive into the nuances of Android mobile device programming to teach how to write and understand Mobile Application Development and how those applications relate to the Model View Controller design pattern.  Modern tools such as Android Studio, Git, GitHub, and the Debugger will be heavily used.  Piazza will be used so that students and instructor may have a collaborative Question and Answer environment. It is intended to maximum participation with students answering other students' questions if they know the answer.  All projects will be administered through GitHub, where students are expected to Fork the assignment and complete assignments under Version Control (accomplished with Git).  Completing the assignment as assigned will not be enough for an A+. Students must add at least one "WOW" feature to the project and must be successfully demo'd to the Instructor. Topics covered include:

* The Activity Lifecycle
* Debugging Android Applications
* Creating User Interfaces with Layouts and Widgets
* UI Fragments and Fragment Managers
* The Tool Bar
* SQLite Databases
* Explicit and Implicit Intents
* Bluetooth
* and More...


## Homework/Projects

All assignments are listed within the [Course Outline](#course-outline).

### Workflow

If you're using GitHub Desktop, these general instructions will help:

* <https://guides.github.com/activities/forking/>
* <https://help.github.com/desktop/guides/contributing/>

Enabling `Edit`->`Automatically Sync after Committing` is recommended. Here are the steps:

1. Fork the repository for the exercise/project.
1. Clone the repository to your computer.
1. Read the instructions provided by the README file.
1. Modify the files to complete your assignment.
1. Test your solution with both an Android Virtual Device and a real phone.
1. Create and include a screenshots of your application in action.
1. Make sure all of your code is committed.
1. Push/sync up to GitHub.
1. [Create a pull request](https://help.github.com/articles/creating-a-pull-request/) on the original repository. All assignments are due at the start of class on the specified date.
1. You can continue to push fixes and improvements until the close date (listed in Classes) – just add a comment in the pull request to let me know it's been updated.

When the pull request is created, you should see a message saying that "the Travis CI build is in progress" – this means that your solution is being automatically checked for syntax errors.  If this "build" ends up failing (which will show a red "X"), click through the "details" link and scroll to the bottom to see what the errors were.  Per the [requirements](#requirements) below, please fix the issues and push up the changes.

Feedback will be given in the pull request, so please respond with your thoughts and questions!  You are welcome to open the pull request early as a work-in-progress if you are stuck and want to ask a question.  Note that your solution will also be live at `http://USERNAME.github.io/EXERCISE`.

#### Versions

For exercises with multiple Versions (`V1`, `V2`, etc.) listed in the README: these are intended as guidelines for how to complete the assignments in the smallest/simplest possible increments.  You are expected to reach the highest Version for each assignment by the due date. See also: [extra credit](#extra-credit).

### Requirements

* All applications must build, install, and run properly on a real Android phone (of the student's choosing). 
* Assignments must be completed by the due date. Late assignments will only be accepted one week late and will be marked down a whole letter grade.

#### Extra Credit

Bonus points for:

* Automated tests
* Creativity (as long as requirements are fulfilled)
* Anything listed under `BONUS` in the README of the exercise.
* Something that WOW's me.

## Course Schedule (tenative)

### Topics Covered:

Jan. 12 	   Overview of Android Application Development

Jan. 17/19 	Review of Java (classes, interfaces, inheritance, inner classes, etc.)

Jan. 24/26 	User Interface Basics, Saving Activity State, Debugging Android Applications
 
Jan. 31/2 	User Interfaces

Feb. 7/9 	Threads, Network Applications

Feb. 14/16 	Test #1

Feb. 21/23 	Applications with Multiple Activities; Advanced User Interfaces
 
Feb. 28/2 	Data Storage (Preferences, File System, SQLite)

Mar. 7/9 	Data Storage Continued (SQLite, Content Providers, ListView)

Mar. 14/16 	Location-Based Applications

Mar. 21/23 	Spring Break (no class)
 
Mar. 28/30 	Bluetooth, Animation; Multimedia

Apr. 4/6 	Test #2

Apr. 11/13 	2D Graphics; Services

Apr. 18/20 	Selected Topics

Apr. 29 	Project Demonstrations

## Course Outline

### Class 0

1. Introduction
    * Introduce mobile applications and the unique challenges to development of mobile applications.
    * Everyone introduce themselves
        * Name
        * What you "do"
        * What are your goals for the class?
   * Syllabus discussion: ex. what the class is going to cover?
   * Introduce the main references for this course (textbook and online resources)
   * Provide the rationale for the course
   * Discuss important insights about the course and learning in general

#### Homework

* Sign up for [Github](https://github.com) and email your username.
* Download and install [Android Studio](https://developer.android.com/studio/index.html)
* Join the Piazza group [CSCI-490 Group](piazza.com/cofc/spring2017/csci490)
* Skim/Read chapter 1 and 2 of Introduction to Android Application Development


### Class 1

1. Java Overview
2. Android platform
   * Architecture
   * Linux Operating System
   * Android Runtime (ART)
   * Commonly used packages
   * Android Application Framework
3. Setting Up For Development
   * Creating develpment environment
* [Slide Presentation](https://docs.google.com/presentation/d/1OzJWPZaCS3Mugrj9mWqDz2k5C0vxi2xcRftrGBvdfho/edit?usp=sharing)


#### Homework

* Read Chapter 3 of Introduction to Android Application Development
* Post one programming/android question and one answer in Piazza
* GitHub tutorial project (Due Thur, 19 Jan 2017)
* [Project1](https://classroom.github.com/assignment-invitations/07af076e3e3c94a70b812e42c26b3e05)


## Pairing Tips

* Groups of two, unless there is an odd number of students
* Agree on an editor and environment that you're both comfortable with
* Use Github for collaboration, branch/merge model is recommended
* Meet regularly. Use Google Hangouts when you cannot meet in person (Hint: Sharing your screen is very useful)

## Resources

### Required Reading

* [Introduction to Android Application Development](https://www.amazon.com/Introduction-Android-Application-Development-Essentials/dp/0321940261) by Joseph Annuzzi, Jr.

### Beginner Materials

This class assumes you are confident with this material, but in case you need a brush-up...

* [Udacity Courses](https://www.udacity.com/)
* [Developer's Blog](http://android-developers.blogspot.com/)

### Recommended Reading

* [Advanced Android Application Development](https://www.amazon.com/Advanced-Android-Application-Development-Developers/dp/0133892387/ref=pd_bxgy_14_img_2/155-7215792-6116344?_encoding=UTF8&pd_rd_i=0133892387&pd_rd_r=QWRAD2HC9RAM0XXKABE9&pd_rd_w=3xsJo&pd_rd_wg=0ROZw&psc=1&refRID=QWRAD2HC9RAM0XXKABE9) by Joseph Annuzzi, Jr.
* [Android Programming The Big Nerd Ranch Guide](https://www.amazon.com/Android-Programming-Nerd-Ranch-Guide/dp/0134171454/ref=sr_1_1?ie=UTF8&qid=1478874065&sr=8-1&keywords=android+programming+the+big+nerd+ranch+guide+2nd+edition)

### Tools

* [Android Studio](https://developer.android.com/studio/index.html)

#### GitHub

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
    * [Recommended resources](http://hackerhours.org/resources.html#github)
* GitHub Pages
    * [Official site](https://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)

### Reference

* Developer Resources  – [Android Developers](https://developer.android.com/index.html)
* [Android Studio User Guide](https://developer.android.com/studio/intro/index.html)

## Grading

The final grade for the course is based on 6 grades as follows:

* Two assigned in-class tests. Each test counts as a separate grade.
* Daily quizzes and minor assignments – collectively count as 1 grade. (No make-ups will be given, but lowest two quiz grades will be dropped.)
* Programming assignments – collectively count as 2 grades.
* Course project – counts as 2 grades.
* Lowest grade from above 7 grades will be dropped. If the lowest grade corresponds to the course project or the collective grade for the programming assignments, only one of the associated grades will be dropped.


## Statements on Plagiarism

### SCPS

> The College of Charleston takes plagiarism very seriously and regards it as a form of fraud.  The definition of plagiarism that has been adopted by the School of Continuing and Professional Studies is as follows: "Plagiarism is presenting someone else's work as though it were one's own.  More specifically, plagiarism is to present as one's own words quoted without quotation marks from another writer; a paraphrased passage from another writer’s work; or facts or ideas gathered, organized, and reported by someone else, orally and/or in writing.  Since plagiarism is a matter of fact, not of the student's intention, it is crucial that acknowledgement of the sources be accurate and complete.  Even where there is not a conscious intention to deceive, the failure to make appropriate acknowledgement constitutes plagiarism.  Penalties for plagiarism range from failure for a paper or course to dismissal from the University.

### Instructor

Reuse and building upon ideas or code are major parts of modern software development.  As a professional programmer you will never write anything from scratch.  This class is structured such that all solutions are public.  You are encouraged to learn from the work of your peers.  I won't hunt down people who are simply copying-and-pasting solutions, because without challenging themselves, they  are simply wasting their time and money taking this class.

Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate an algorithm or code from elsewhere, credit the original source with an inline comment.
