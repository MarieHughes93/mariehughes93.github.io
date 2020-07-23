---
layout: post
title:      "Mood-N-Progress - A work in progress"
date:       2020-07-09 23:58:44 -0400
permalink:  mood-n-progress_-_a_work_in_progress
---


*I will be publishing this as soon as I finish writting the initial opening. This way I can update it as I go... Then anyone wanting to follow along will be able to do so as well.*

IT IS THAT TIME AGAIN! Time for another project! I feel I get a little better each time I go to write for these blog posts. The project this time is for us to make a single page application. Our frontend will be built with HTML, CSS, and JavaScript and will communicate with a backend API built using Ruby and Rails. The goal is to really flex on all I have learned so far and apply it to create something wonderful! 

I honestly do not feel like I did my last blog as well as I would like so I will be trying to do better this time around! I want to document what I did on each day to see how things progress. Unfortunately, I am starting a little behind. Project week started four days ago (july 6th and it’s the 9th)  however due to covid affecting everything going on... I had been behind on school work. Luckily I am now caught up and ready to conquer my next big project! I was lucky enough to get help with brainstorming from my friend Kevin. I had spoken with him about having a journal for my son to track any patterns that alter his mood. Kevin brought this up as a great to make into an application! I will create it where you can document activities, meals, sleep patterns and use that information to infer what could be affecting you.

Day one:
I created my folder for my project. Created my api backend and then my index js & html. However, I forgot how to connect postgresql to the project. I had to remind myself how. If anyone is in need of help here is how.
Make sure you have downloaded postgreSQL for Windows (https://www.postgresql.org/download/windows/)
Once downloaded verify with: psql -p 5432 -h localhost -U postgres
\q to quit
Open pgAdmin 4  and right click on postgre and select connect server
Right click on login/group and create new. fill out Name in the General tab, Password in the Definition tab, and enable all permissions in the Privileges tab.
Then to connect to the rails app go to your config/database.yml file under BOTH development: and test: You will need to add a user and password which will correspond to the roles we created in pgAdmin.
Then rails db:create to create the database
Rails s to start server
I had completely forgotten about this part but luckily was sent in the correct direction. 

Now from here I need to roadmap a more of what this will be. I want to do omniauth but I want to allow for people to join from more than one source. However, that is a bit complicated and from reading the information it also is different with an api. Later if I have time I will go back and add omniauth. For now I want to try to think of what I will need before I get started with the actual coding. 
Users have a name, email, secure password. 
Calendars have many entries
Entries have a types, start and stop time, note, and mood belong to a subject
Users have many subjects (subject is who the event is regarding so there can be tracking of multiple people on one account)
As for what the user experience 
Is able to see a calendar with indication of days that have entries
Is able to see graphs showing fluctuation of entered moods for the month so far.
Is able to see each day and their entries so far if current and 
If  in the past they will see a graph for that days mood data if possible
Is able to see a form to add an entry either by clicking a new button and entering the manually or
By going to that day and then from the day clicking add new
This so far is a lot to do… and a lot to work with. Honestly the graphs might have to get the axe. I would really love to try to do them however…. After some looking on the good ole’ google… it might be a little over my head right now. We SHALL SEE!!! 

I took a break from planning to look at templates for my code. I have a new issue that I will need to circle back to. I have no idea how… or why… but I was playing around with a couple free templates and could not get it figured out. The whole structure is confusing me a bit right now. I found several html and css codes but they had all the dates and everything hard coded into them. I realized that I can’t think of how to not hard-code it. Honestly visuals are not my strong point at all so the idea of how to build this out to be functional *visually* is kinda stressing me out. Tomorrow is Friday and I am basically starting a week behind. I will need to really put in some time to get everything. I feel like I might be biting off more than I can chew here. Honestly, I can't say if that is the fear of failing or my gut telling me I need to pull some of this back... . I will come back to this tomorrow after I reach out to my coding senpai for some words of wisdom!
Anyways….
Tomorrow I would like to get started with creating my users while I wait for my friend to have time for a pep talk. Last time I made the mistake of trying to build each model out in entirety one by one. It was a mess and it honestly left me often lost and confused. So I will just go as I go and try to be mindful of what will come as to make it a smoother natural process. I also need to commit more. So far I have been on it and have pretty much after every 3 lines of code. I also feel that I am doing much better at communicating in this blog post. I honestly usually forget till the last days of the project and by then I am already done. I have been having it open while I code for me to type a little as I went. I feel this helped me get more of my thoughts that I usually forget how to word once the moment has passed…. However…. I think it is time I called it a day. I might have rambled a bit. 


Day two & three:
I wasn't able to touch it for a day and honesty.... I forgot to do my blog on the second day I worked on it. I am having a bit of a harder time than I would like to be clear. There is just something about javascript that is not clicking for me and I am hoping it will click while doing this project. On day two I worked mostly on the html. I wanted to have an idea of what things were going to be looking like. I found a pretty cool template Adrià named CSS Grid calendar that I did some tweeking to make work for what I am going for ( https://tinyurl.com/ydgc3yu5). From there I then did a little bit of front and back in developing. I went ahead and created my users model and all basic crud actions for my users. I do not know if I will need all of them but I felt it would be best to go ahead and built it out since it was simple enough to do. Then I can decide on that a bit more later. From the front end I went ahead and built out my javascript user class. I honestly am a little bit weak on that aspect so I was watching and following along with multiple video to try to get a better understanding. I had spent so long on the html that by the time I got to more difficult things, I was to tired to really process what I was needing to do. So I figured I would call it a day and come back to it.

So here we are on day three. I had to take a day to handle life things (with a little one I am suprised I got 2 days back to back without interuption) and now I am back at it! Today I am going to back track a bit and review the javascript classes as I just do not fully grasp the methods vs defintions.. I honestly have a hard time with reading what is in a class. I will circle back at the end of my day for a update on this and what clarity I found from my day. However, life had me busy till evening so.. I do not have much time to play with. So for today no coding will be done more than likely. I need to focus on more understanding!

Just going to be honest.. I have note gotten any time to work on my project. As I was finishing writing this I was contacted my friends I made here in my bootcamp. There project is due in two days and they have been working together... and just lost all their work. So being the anxious person I am. I pulled an all nighter building their projects out so I  can then help them build it without thinking to much.. and I can work on my project while they pop in and out for help.... But man am I tired. Just going to be honest. IT is is now the afternoon of the fourth day... and I am brain dead.

Day - I don't know

SO I am going to be be real. I am still trying to find my voice when doing these blogs. I have tried doing on a day to day matter... but that seems to not work. It has been a week since the last time I wrote. Life got crazy and I am now having to turn in my project late. I am not happy about this but I wanted to instead of erasing the blog... have it be honest a real. This project was a disaster. First let me just say I hate javascript. It was not an easy project. I think this is the most I have struggled. It does not help that I also had so much going on in my personal life. My main struggle with organization. I still do not feel I have the best understanding of that. I ended up half way through scraping my whole front end and starting again. It helped to think of it in the way I had before with models, controllers, and views. I set up a app conotroller that would controll the "Session" like actions. I say like because I did not have it set up to run off setting but off of a simple login. I didn't put any validations either. I plan on doing this later. As of right now I just want to make the requirements for it to be able to be turned in. No kidding as soon as I am done with the blog I will be making a branch to continue. I am absolutely not happy with the app as is. Currently you can create and delete notes. I wanted to have indivindividual show pages but since I am late I made it all viewable on the index page. I plan on changing that as I update and finish it in my personal time. I also created files that acted as the views. The views would get functions from the app class. This then allows for the app controller to connect the adaptor, model, and the views. The adaptor is what is going and connecting to the backend. As of now everything is very minimal.... I need to spend more time with javascript so I can feel more comfortable. Even with all I have done I feel like I am still lacking in ability. Honestly I can't tell if thats the "imposter syndrome" or if I really am just in need of more hands on experince.

Conclusion:
I will have to come back and rewrite this at some point in time. I plan on getting it how I want and then writing a details essay about how everything works together.. including some screenshots. However, I would be embarrassed to with how little it does at this time. I dreamed too big, I lost too much time due to life, and I didn't have the understanding to complete it in the time I was given. The lesson here was Javascript as well as learning to scale back + mange time.

