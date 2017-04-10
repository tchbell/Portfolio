---
layout: post
title: BlocChat
thumbnail-path: "img/screen-shot.png"
short-description: BlocChat is my first attempted at combining AngularJs and Firebase.
---

{:.center}
![]({{ site.baseurl }}/img/screen-shot.png)

## Summary
BlocChat was my first attempt combining AngularJs and Firebase. I created a basic chat app that could take a have someone create a username, create a new chat room, and submit messages to that specific chat room that were then saved into that specific room.

## Problem
The largest problem for this project was that it was my first time using Firebase. I had previous redone a music player application with AngularJs but this was only my second time applying it to a real project. Having to use Firebase as my database was a new experience that I had to get used to quickly. Storing chat rooms, usernames, and messages were all new to me so I had to study up quickly.

## Solution
Lucky for me Bloc had a good layout of how to approach each of the problems. From adding data to Firebase's database or saving username with cookies. 

The first issue that had to be dealt with was using the Firebase database to list the chat rooms. First I had to make some fake rooms in my database then figure out how to display them in my BlocChat view. Again luckily the curriculum held my hand for most of the way with this challenge mostly because it was the first time I had ever used this technology. Learning how to reference my data and adding the rooms to the view were fairly simple tasks that led the way for some future problems that were to be had. 

Now that I had figured out how to show the chat rooms I had to figure out how to create new chat rooms from the view. This time the curriculum taught me how to use the UI Bootstrap which I used to create a modal window for whenever someone wanted to create a new chat room. The modal would allow the user to create a room name of their choice and then once they submitted it it would be added to the list of active rooms. Learning how to appropriately use bootstrap took some time but its absolutely a technology that I will use in the future. 

For the new problem at hand I had to figure out how to link messages to specific chat rooms. First I created some fake messages that were associated with relating roomId's to the chat rooms. Following that I had to figure out how to show the messages that their roomId's matched the currently selected room. Again the curriculum showed me how to sort my data in Firebase to allow me to do such a thing. After some hard work, googling, and talking to my mentor I got it figured out and working.

Setting the username was the next task at hand that I had never dealt with. For this the use of cookies and a run block would be applied. Cookies were something I knew about but again had never applied them to anything before. I truly enjoyed being able to learn about how to use something that I heard so much about before. Once I added the cookies to the applications main module creating a new pop up modal to ask the user to input their username was not too challenging. Creating another modal was relatively easy since I had just recently created one. Once the user opens the application if they are not already previously logged in they will be immediately asked to enter a user name and then they are allowed to chat to their hearts content.

The final challenge for this project was to create a way so that when a user sends a message it goes into the Firebase database with all the properties it needs to be saved and added to the corresponding room. Luckily it was very similar to adding a chat room like I had done prior. Just some small tweaking so each message had a date, username, roomId, and content property. 
