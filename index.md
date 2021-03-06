[![ci-meteor-application-template-react](https://github.com/mox-amber/sessh/actions/workflows/ci.yml/badge.svg)](https://github.com/mox-amber/sessh/actions/workflows/ci.yml)

This page documents Mox Amber's project: Sessh. The site is updated regularly
as the project is still in development.

## Table of Contents

* [Overview](https://mox-amber.github.io/#overview)
* [Deployment](https://mox-amber.github.io/#deployment)
* [User Guide](https://mox-amber.github.io/#user-guide)
* [Developer Guide](https://mox-amber.github.io/#developer-guide)
* [Development](https://mox-amber.github.io/#development)


## Overview
### What Is Sessh?
Let's say you need a drummer for your band, looking for someone to teach you how to learn
certain chord pattern, or just want some people to jam with. Finding other
individuals who wish to pursue musical related goals can be difficult, especially
when there is no reliable resource to do so. That's were Sessh comes in, we hope
to develop a web application dedicated to cultivating a network of students who are musically inclined and enrolled at a University of Hawaii affiliated school.

### How Will it Work?
We are aiming to provide the fundamental tools necessary to bring students together
so that they can arrange organized meet ups for anyone interested. We will first start with a CRUD(create, read, update, and delete) based design for our initial tools including:
* Creation of profiles including descriptions such as musical interests, goals, skills, etc.
* Profiles will contain access to musical works they produced with links to other work they
  were involved in.
* Full browsing with dedicated filtering capabilities where a user can search for others based on information listed on their profiles.
* Adding people to your regular sessions list.
* Notifications based on search terms.

Along with the feature suite, there will be a dedicated group of 'super-users' with admin
capabilities that ensure the website adheres to our applications policy.

## Deployment
If you would like to see our application in action you can visit [our live site](https://sessh.xyz/#/).

## User Guide
The following is a walkthrough of the application.

### Landing Page
When visiting the site, a user is greeted with our landing page describing the
purpose of the application.
![](doc/landing-page.PNG)

A user can log in by clicking the link in the upper right corner.

### Log In
When logging in, the user is taken to the log in page where they can enter their
information.
![](doc/login-page.PNG)

### Sign Up
If a user does not have an account they can either signup through the link in
the login dropdown
![](doc/signup-page.PNG)

or the login page itself.
![](doc/signup-from-signin.PNG)

### User Dashboard
After signing in the user is taken to their dashboard where they can view people
within their network and edit their profile.

![](doc/dashboard.PNG)

### Edit Profile
If the user wants to update or change their account, they will be taken to their
edit profile page.
![](doc/edit-profile-page.PNG)

### Search Page
The search page lets users discover and filter musicians based on their preferences.
![](doc/search-page.PNG)

### Messaging
The users can message each other through the send messages page
![](doc/send-message.PNG)

and check the received messages on the messages page.
![](doc/messages.PNG)


### Signing Out
A user can sign out from the same dropdown the used to log in and will be taken
to the sign out page for confirmation that the action was a success.
![](doc/signout-page.PNG)

### Admin Page
An admin page is given that shows the list of all musicians and their information.
![](doc/admin.PNG)

## Community Feedback
The general consensus is that the site had some very unintuitive aspects to it. The singup page was a point of major difficulty for users, they said that the genre field didn't make sense, and that a dropdown menu of choices would have been better. Another thing is that when a user submits their form, while the "your account was created" animation plays, the user is not, then, redirected from the page. This proved to be a cause of some confusion for users. The messaging system was rudimentary to begin with, and users noticed. A suggestion was to make it similar to Twitter, in that it is thread based.
This was the general feedback of our testers. There is much to improve on. 
Some additional things we, the team, identified was the landing page being somewhat... underdeveloped. The editi profile page doesn't match the signup page in it's power with relation to accounts and collection writing. When a user doesn't input a url in the image field, it is displayed as a broken link as opposed to a default image. Along with additional functionality that we were not able to implement.

## Developer Guide
### Download to local machine
Using [github repository](https://github.com/mox-amber/sessh), click on Code to clone the repository into Github Desktop. This will open up Github Desktop and allow you to view the repository in your local machine.

### Editing
Open your editor (ex. IntelliJ Idea) and create a new web project. Link your project to the file containing your repository and the project files will be displayed into your editor.
For any modifications, create a new branch (DO NOT make edits in the master branch) and create your changes.

### Deploying in your local machine
To deploy, run meteor npm install and then meteor npm run start into the command prompt. You will get a link to copy and open into your web browser. This will allow you to view any changes that you have made locally. Once you are satisfied with your changes, push your branch into Github and the changes will be checked before merging into the master branch.

## Development
To bring our application to life we used issue driven management practices
through the sessh [github repository](https://github.com/mox-amber/sessh). Within the repository separate projects were created based on milestones we expected to reach. Our milestones were then divided into issues divided amongst each member.

The Mox Amber team signed a contract that outlined the expectations of each member. You can view a copy of our team contract here: [Team Contract](https://docs.google.com/document/d/1PoUwM7omjHm2AsQrFtHgtw8QwC63vHkxEemNF_xnBQQ/edit).

### Milestone 1
For milestone 1, our goal was to create and deploy a basic working version of our application.

You can view our [project board](https://github.com/mox-amber/sessh/projects/1)
if you would like to see how we divided our tasks.

### Milestone 2
For milestone 2, our goal now is to add the functionalities that we were unable to add in milestone 1. That, and also to make our application look better in general.

You can view our [project board](https://github.com/mox-amber/sessh/projects/2)
if you would like to see how we divided our tasks.

### Milestone 3
For milestone 3, was to build upon our work in milestone 2 by filling the "odds and ends" by
improving the overall application look, fix remaining bugs, and finalizing the project.

You can view our [project board](https://github.com/mox-amber/sessh/projects/3)
if you would like to see how we divided our tasks.

## The Team
* Kaiwi Akioka
* Edward Birtodaso
* Josh Constantino
* Waylon Ho
* Ian Iwata

For further information about Mox Amber and our projects you can visit our [github](https://github.com/mox-amber).

