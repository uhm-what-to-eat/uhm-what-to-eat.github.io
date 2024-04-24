# UHM... What to eat?

## Table of contents
* [Overview](#overview)
* [Features](#features)
* [User Guide](#user-guide)
* [Team](#team)
* [Deployment](#deployment-)
* [M1](#milestone-1)
* [M2](#milestone-2)
* [Walkthrough](#walkthrough)
* [Developer Guide](#developer-guide)

## Overview
UHM...What to eat? is a fun play on words of the University of Hawaii: Manoa's acronym, UHM, and the age-old question we ask when our stomachs grumble. UHM... What to eat? is a UH Manoa food application designed to address the diverse food choices available on campus at the University of Hawaii at Manoa. The app aims to simplify the process of finding specific menu items across various campus dining locations, including campus center, food trucks, Manoa Gardens, Paradise Palms, vending machines, and more.

## Features
Users, who can login to establish preferences for their food choices; 

Vendors, who can login to specify their choices of the day or otherwise modify their profile data;

Admins, who also can login to define users as having the vendor role and otherwise administer the system.

Roles (users, vendors, admin): users can post updated menus  and services, while administrators monitor user behavior and manage categories and other functionalities.

Categories: feature broad categories for goods and services.

Photos: supports upload of photos.

## User Guide
Getting Started:
User Registration/Login: Sign up for a new account or log in using your existing credentials.

Set Preferences: Set your food preferences, including favorite vendors and dietary restrictions, to personalize your experience.

Using the App:
Explore Menus: Browse through menus from various campus dining locations, organized by vendor and menu item type.

Search and Filter: Use the search and filter functionality to quickly find specific menu items or vendors.

View Availability: Check the availability of menu items in real-time and see when your favorite dishes are being served.

Manage Preferences: Update your food preferences at any time to reflect your changing tastes and dietary needs.

### Vendor Features:

Login: Vendors can log in to the app to update their menu offerings for the day.

Update Menus: Vendors can add new items, remove sold-out items, or update existing menu items as needed.

Manage Profile: Vendors can also manage their profile information, including contact details and operating hours.

## Team
Introducing the Culinary Crusaders of UHM – the team behind the mouthwatering magic of "UHM... What to eat?"!
* [Christian Dela Cruz](https://github.com/cdc21)
* [John Paul Alonzo](https://github.com/Johnzo1233)
* [Joshua Sato](https://github.com/joshuanssato)
* [Joshua Pedersen](https://github.com/jspedersen)
* [Spencer Wells](https://github.com/susa-s)
* [Evan Rau](https://github.com/EvanRau)
 
Join us as we redefine the campus dining experience, one delicious dish at a time. UHM... What to eat?: where food meets innovation, and every bite tells a story. Get ready to tantalize your taste buds and indulge in the ultimate dining adventure and embark on a flavor-filled voyage unlike any other!

[UHM... What to eat? Team Contract](https://docs.google.com/document/d/1LNj9PP-zLuOr3zsc3_ZD5KoFJLNKE22pDF2c1CO2s1I/edit#heading=h.hflfh83g7rog)

## Deployment 
[Digital Ocean Deployment]([http://209.38.136.229/](https://uhmwhattoeat.online/))

## Milestone 1
[M1](https://github.com/orgs/uhm-what-to-eat/projects/1)

## Milestone 2
[M2](https://github.com/orgs/uhm-what-to-eat/projects/2)

## Milestone 3
[M3](https://github.com/orgs/uhm-what-to-eat/projects/5)
## Walkthrough
A quick run through of UHM...What to eat?'s user interface. 

### Landing Page
The first thing a user or vendor sees is our landing page and quickly explains what our app is about and how to sign up/log in.
<img src="public/images/updated-landing-page.png" alt="landing page">

### User Sign-up Page
After clicking the sign up link on the landing page or clicking on the sign up button through the log in dropdown menu, a user may sign-up for UHM...What to eat? if they do not already have an account.
<img src="public/images/user-registration-page.png" alt="user sign up page">

### Vendor Sign-up Page
If they are a vendor and want to sell on campus, vendors may click the vendor link on the landing page. The vendor sign-up page allows vendors to specify where their establishment is on campus, store hours, and an image. 
<img src="public/images/n-vendor-page.png" alt="user sign up page">

### Log-in Page
If one already has an account, whether user or vendor, they may click on the log-in link or the log-in button to redirect them to input their information and access their account. 
<img src="public/images/login-page.png" alt="user sign up page">

### User Landing Page
Logging into the User Account, the user is able to see all the food vendor cards on the places to eat page and manage their preferences. Each food vendor card is randommly chosen each time a user logs-in, so its a fun, foody supsrise everytime they log-in. Each food vendor card on the landing page is clickable for easy access to food vendor pages. 
<img src="public/images/n-login-landing-page.png" alt="user sign up page">

### Vendor Landing Page
Logging into the Vendor Account, the vendor is able to see all food vendor(s) they own and and are able to manage and edit them.
<img src="public/images/n-subway-page.png" alt="user sign up page">

### Admin Landing Page
Logging into the Admin Account, the admin is able to see all the users and vendors that are registered on the app. Admin is able to see all the food vendor cards on the places to eat page and manage them.
<img src="public/images/nw-admin-page.png" alt="user sign up page">

### Places To Eat Page 
If users want to see all the available options of where to eat, they may see all available establishments based on different food vendor locations on campus.
<img src="public/images/places-to-eat-page.png" alt="user sign up page">

### Admin Places To Eat Page
On the admin side, the places to eat page becomes a hub to manage food vendor cards on the places to eat page. Admin is able to add or remove food vendor cards. 
<img src="public/images/edit-vendors.png" alt="user sign up page">

### Food Vendor Page
Here's an example of Panda Expresses's food vendor page. Users are able to see the menu items that are available at Panda Express and the hours of operation.
<img src="public/images/vendor_page.png" alt="vendor page">

## Developer Guide
* Install Meteor and  download GitHub Desktop if you have not already
* Go into the [uhm-what-to-eat/source](https://github.com/uhm-what-to-eat/source-code) github repository and click the green "Code" button and select "Open With GitHub Desktop"
* Once in GitHub Desktop, select "Clone", so our source code will be cloned to your local device
* cd into the uhm-what-to-eat/source directory and install libraries by invoking:
```
$ meteor npm install
```
* Once libraries are installed, you are then able to run the application by invoking:
```
$ meteor npm run start
```
* Once completed, click on the link prompted or navigate your way to http://localhost:3000 


