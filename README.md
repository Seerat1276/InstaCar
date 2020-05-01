# InstaCar

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
This app provides a platform for anyone who wants to buy or sell cars.



### App Evaluation
Evaluation of your app across the following attributes
- **Category:** Social Networking/ Cars
- **Mobile:** This app is developed for only Mobile. This app will only be available for Apple App store.
- **Story:** Connect anyone who wants to buy a car with the one who wants to sell it.
- **Market:** Anyone interested in buying or selling a car can use this app.
- **Habit:** Depends on the user trade requirements
- **Scope:** Connection people for trade of cars.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can Signup
* User can login
* User can logout
* User can upload a picture
* User can upload a text descriptions
* User can view a feed of pictures
* User can find the contact of the seller/buyer


**Optional Nice-to-have Stories**

* User can tap a photo to view a more detailed photo screen with comments

### 2. Screen Archetypes



Registration Screen
User can create a new account
Stream
User can view a feed of photos
User can double tap a photo to like
Creation
User can post a new photo to their feed

* Login Screen
   * User can login
   
* SignUp screen
   * User can sign up
   
*  Activity Feed
   * User can view a feed of photos
   
* Upload Post
   * User can post a new photo to their feed
   * User can attach a text description to their feed
   
   
### 3. Navigation

**Tab Navigation** (Tab to Screen)
* Home Feed
* Post a Photo
* Search Car

**Flow Navigation** (Screen to Screen)

* Login Screen
   * Home
   * Sign Up
* Home
   * Post
   * Search
   * Feed
   * Log out
* Post
   * Home
   * Log out
* Search
   * Feed
   * Home
   * Log out
* Log out
   * Log In
   
  


## Prototype


<img src='https://recordit.co/C5oSypvQmy.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

## Schema 

### Models


| Property | Type | Description  |
| ------- | --- | --- |
| userId | String | unique id for the user |
| image | File | uploading images of car |
| Date | DateTime | Date of the post |
| Comment | String |Comment on the post |

### Networking

* Home Feed Screen
  * (Read/GET) Query all posts where user is author
  * (Create/POST) Create a new comment on a post

* Create Post Screen
  * (Create/POST) Create a new post 
* Profile Screen
  * (Read/GET) Query logged in user object


