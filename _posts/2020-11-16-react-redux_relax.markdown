---
layout: post
title:      "React-Redux relax"
date:       2020-11-16 06:22:56 +0000
permalink:  react-redux_relax
---


This project by far was the most difficult to date.

For the requirement of this project:

Rails API Backend

JS React Redux Frontend

ES6 as much as possible

5 stateless components

3 routes

Use react-router

Redux Middleware for state change

Async actions 

minimal styling

REstful routing


There were several areas I felt I needed to focus on understanding better to complete this project. I want to go over those and what I learned to help those who might be in the same place.

What are async vs sync actions?

Async means it will return to task at hand when it is able to complete. Synchronous.

Javascript by default is Synchronous.

We can use call backs and call back functions to make async actions.


What is react/redux state flow?

AADRS

Action creator - creates the action

Action - creates what the action does (storing. Removing. Updating)

Dispatch - relays the info to the reducer

Reducer-  changes dated based on action from dispatch (think of it as a controller) and returns the updated state.

State - the core of or information 


What is state and props in React?

Props will not change on their own. The state of the object you are working with or you store can hand will more than likely change. Your state is your store while your props are the attributes.


As for what I built my project on I was inspired by a YouTube video I saw. It was explaining the use of making a menu for activities to do in your free time. The web series is one for those with ADHD and about learning ways to help overcome challenges.


I wanted to make a website to catalog these menu options.


My objective was to be able to sign up, login, and have sessions reconnect on reload. As well as make menu items that were separated in columns.


The biggest challenge I honestly faced was with styling. It was not something I had focused on my other projects. I do not believe I had used any bootstrap before this…. That or well I can't remember hah.


I had the hardest time figuring out how to create multiple columns.

I however was able to do this by creating a categories variable that was a string of the options. I then mapped across the array and passed my items into the rendered items list that was rendered by my categories. Then I used bootstraps col and rows to line them up 


All together I say this has been the most time I've spent on a project. I am very satisfied with the outcome.

