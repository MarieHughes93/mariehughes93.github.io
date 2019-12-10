---
layout: post
title:      "The first project: One down.. many more to come!"
date:       2019-12-10 04:59:14 +0000
permalink:  the_first_project_one_down_many_more_to_come
---

The first project! Oh man! This has been no kidding a trip! Let's get down to business.

When we first started talking about the project, I was lucky enough to already have something in mind. I am a really big RPG game player. If you are also one, you know that they involve a lot of gathering of SOMETHING. In the case of one of my favorite games "Persona 5", you are gathering Persona. They are magical entities that make up ones "true self." In Persona 5 there are 225 "monsters" or "persona" you can obtain. They can be from fighting and catching them or by combining monsters to create new ones. 

As a completionist I will say that I have spent more hours than healthy trying to complete the compendium. However, I have yet to do this still. So when thinking of this project I was excited to create something I could personally use.

I spent a good amount of time brain storming before actually getting to the code. I am fortunate to have a friend that has been coding a long time. Their advice was to write it out in english before trying to code anything. So that is simply what I did. I used pen and paper and first started to plan out what I wanted it to do.

 Goal: 
*  List all the persona.
*  Be able to search by persona name
*  Persona when selected will show level, arcana, stats, elemental effects, and any possible combinations to create it.
*  Be able to search for monsters by an element and its effect when used against it.
*  Not go over board

I have a wonderful but nasty habit of always wanting to do that extra step. Most the time this is a wonderful thing. However, with coding I have found that I think so much ahead that I end up over-whelming myself. The goal on the project was to hit the main target points first. Then once I got the basics I would add anything I felt it needed or I could do.

Day 1:
I stared at the screen for hours. I had no idea where to start. I watched a video on building a gem as I saw it was the first video offered and... I wasn't getting anywhere with just looking. Once I saw the video the excitement went through the roof! I decided that with how much scrapping I had to do to start with the persona.rb and compendium.

I spend the next couple days on this... "saving" my work as I went. After several days I went to clone my project down and get back on it. Only to realize I had not been saving. 

LESSON ONE! ALWAYS DOUBT CHECK!!
From this lesson I learned to start checking grit hub even when I felt sure it was saved. 

Not going to lie. There was a full break down and a empty pint of ice cream after finding this error. I hadn't really had any issues with the files. I just couldn't for the life of me remember what I wrote. So I started over. I will call that day two.

Day two: (or 4 if you want to go by the actual days.)
I rebuild what I had just lost. I started with the persona file. For the most part all of it was done. I wanted to have enough in it to then scrape and have info to work and test. With the compendium I had the most issues. Honestly, deciding what the classes had in them was not easy. I had to stop and think often "Is this something the persona would know or the compendium class?" They work so closely hand in hand that a couple times I honestly rolled the dice and picked. 

Day three:
I worked on scraping. It took a whole day and lots of calls to friends for help. Google became my Batman, swooping in to save the day. The site I had originally planned to be my source for my project turned out to actually be on github. AWESOME! Not really. My heart sank for a bit but I had a friend rescue me. With the permission of my mentor, my friend recreated the page for me to then scrape. I assured my mentor that my friend would not make it easy, just to calm any possible negativity about the idea... and boy was I right. (Thanks Matt) I had such a hard time with children attributes. I just could not wrap my head around it. I spent hours googling, youtube, and asking friends. When it finally clicked how to get them, I was speeding through!

Day four:
I worked on the CLI file for hours. After talking to my mentor I realized I work a little odd. The way I did it was to set up the methods in the classes first. Then scrape. Then CLI to put it all together.  Because I had done it this way it was a bit difficult. The way I had set certain things to scrape were not working with the methods as I thought they should have. So after getting all of the CLI put together...... I was back in my other files trying to right my wrong doings. Really only one thing was not working after combining everything together. The method for getting all the possible combinations was not going through. It took way longer than I would like to admit that I was trying to call a method on an object when it required its name. The code was right but I was not using it correctly.  

Day five:
The finishing touches were added. I added color and added in references to the game by having the character ask for input. I am beyond happy with the results from the project. It took a long time and there were points of wanting to quit but all in all it was a very fun adventure.

What I learned:
1.  I learned a better way of how to call method and label variables. I did not realize it but using variable names that are best for the task are key. Sure it is easy to just put a random word or letter..... but after working on something of this size I found that it is easier than you think to remember what your variables are if you do not name them appropriately. 
2.  The more you think of your classes as objects instead of as just code the easier it is. I feel like I have a better understanding of working with them from this.
3.  SAVE AND COMMIT OFTEN!!! I did.... or thought I was and did not realize until later that I had not. It makes it harder to recall what you were struggling with to talk about for such blogs. Going forward I will account for this better. I feel like doing the blog while working would have been a better choice. These days jumbled together with all the work being put in. When going down my timeline it was murky about what I did on each day. I do know I was on it everyday however!
4.  Google is a friend, enemy, hero, and a black hole. If you do not search for things in a good manner you will get lost down the rabbit hole. 
5.  I met all my goals and was able to then add features such as color. This would not have been possible if I had been trying to from the start. OR at least I feel that way. I can't imagine trying to figure out visuals with the code half done. I am glad I took it one bite at a time. I would recommend that to anyone or you will get overwhelmed by what you are trying to do... and what you need to do. 
