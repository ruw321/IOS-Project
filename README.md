How are you?
===

# iOS Group Project
Team members
1. Meng-Chuan C
2. Sakshi R
3. Ruifan W

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)
## Overview
### Description
How are you? is a mental health state tracking application. The app is meant to be used as a private journal to keep track of your moods, thoughts and see patterns in your mental health state.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Mental health; Personal use
- **Mobile:** This app is meant for mobile users, just like a small journal always on your person.
- **Story:** Today, "how are you?" has become more of a greeting than a genuine question. The purpose of this app is to help you actually reflect on your mental state and ask yourself how you are. Moreover, the tracking feature helps you see trends or reflect back on how you felt on certain days.
- **Market:** Anyone who wants to keep a secret journal that tracks how their days went and their moods.
- **Habit:** Users will be using this app daily like a real life journal. 
- **Scope:** We would start by having users around UPenn, but the application can be accessible to anyone.
## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User is able to create new profile
* User is able to login
* User is able to logout
* User is able to be logged in persistently
* User is able to create a new entry
    * User is able to track mood
    * User is able to do a quick mental state check-in based on a dynamic question of the day
    * User is able to add today's thoughts
    * User is able to add picture of the day
    * User is able to track today's gratitude
* User is able to see their mood trends
    * Calendar view
    * Pie chart
    * Line graph
* User is able to see previous entries by date
    * Accessible via calendar view


**Optional Nice-to-have Stories**

* User is able to track song of the day
    * Link from the song to a music app
* App welcome/User onboarding
* Daily notifications
* 

### 2. Screen Archetypes

* Login/Sign up Screen
   * User is able to create new profile
   * User is able to login
* Home Screen
   * User is able to create a new entry
        * User is able to track mood
        * User is able to do a quick mental state check-in based on a dynamic question of the day
        * User is able to add today's thoughts
        * User is able to add picture of the day
        * User is able to track today's gratitude
* Calendar Screen
    * User is able to see previous entries by date
* Date Entry Screen
    * User is able to see previous entries by date
    * Accessible via calendar view
* Mood Trend Screen
    * User is able to see the mood trend
* Photo Diary Screen
    * User is able to see a collection of uploaded photos 
* Thought Diary Screen
    * User is able to see the uploaded diaries 
* Gratitude Diary Screen
    * User is able to see the uploaded gratitude diaries
* Mental State checkin log Screen
    * User is able to see all the checkin questions and answers

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home Tab
* Calendar Tab
* Trends Tab
    * Mood Trends Tab
    * Photo Diary Tab
    * Thought Diary Tab
    * Gratitude Diary Tab
    * Checkin Log Tab

**Flow Navigation** (Screen to Screen)

* Login/Sign up Screen
    * Login and navigate to Home Screen
    * Sign up and navigate to Home Screen
* Home Screen
    * Create new entry
    * If entry is created, view entry for today
    * Click the calendar tab to enter the calendar view 
    * Click the trends tab to see the trends 
    * Log out (goes to log in screen)
* Day Entry Screen
    * Click the home tab to enter today's entry
    * Click the calendar tab to enter the calendar view 
    * Click the trends tab to see the trends 
* Calendar Screen
    * Click a date and navigate to day entry screen 
    * Click the home tab to enter today's entry
    * Click the trends tab to see the trends 
* Trends Screen
    * Click back arrow to go back to Home Screen
    * Click mood trend tab to go to mood trend screen
    * Click photo gallery tab to go to photo gallery screen
    * Click thought diary tab to go to thought diary screen
    * Click gratitude diary tab to go to gratitude diary screen
    * Click checkin log tab to go to checkin log screen
* Photo Diary Screen
    * Click the photo gallery tab to open and view photo
* Thought Diary Screen
    * Click the arrow next to thought to enter date entry screen
    * Click back arrow to go back to Home Screen
* Gratitude Diary Screen
    * Click the arrow next to gratitude to enter date entry screen
    * Click back arrow to go back to Home Screen

## Wireframes
### [BONUS] Digital Wireframes & Mockups
![](https://i.imgur.com/5z37HaN.png)


### [BONUS] Interactive Prototype
https://www.figma.com/proto/GF6QuWnueEDQGCAhZjlh9R/iOS-Final?node-id=51%3A210&scaling=scale-down&page-id=0%3A1&starting-point-node-id=51%3A268

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
