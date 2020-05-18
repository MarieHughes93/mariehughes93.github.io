---
layout: post
title:      "DnD Social Media App"
date:       2020-05-18 03:07:35 +0000
permalink:  dnd_social_media_app
---


I am going to be honest here.... I bit off more than I could chew.


Time to start my rails project! I am excited as I think I really might be on to something here. Before I go further I do want to say that I will be doing this entry different than usual. I tend to write my blog on my project after it is all done. When I do this I feel like I do not capture the full emotional, mental, and educational journey it is. I decided to approach this differently this time. I will be writting and updating this as I go to make sure I get the full image going. As of right now it is 5/7/20 and this is day two on the project. In all honesty it is more like week 2. I was a bit ahead and decided to try to use figma to plan out the site before. I think I like designing more as I accidentally spent a full week. Essitially making me no longer ahead... and meaning I needed to get on it asap! I will catch up on what has all been going on with the actual code in a bit. (Mostly to keep this pretty uniform) First I want to talk about the idea and how it is growing like a fire!!

I was thinking over my project while I was scrolling through twiter one evening, when I can accross a tweet. "What if there was something like AirBnB but for DnD... called AirDnD."  I have never *really* played dnd. There was an attempt one time in college... but we ended up never making it happen. The thing is my last project in all honesty.... was just trash. I did what I had to and I was not happy nor interested in the application. I wanted to make something this time with "love." The idea of making something that my friends could really use and test out was thrilling! I have a good amount of friend into dnd and I reached out to them for an opinion.

THEY WERE SO DOWN FOR IT!

It really quickly grew from a small dnd airbnb knock off to a whole socail media website for dnd. They had a million and one things they wanted. I started a discord for them to join with an idea thread. Everyone liked the idea. See dnd already has these things but they are heavily "pay gated." When I found this out my want to create this grew so much more. I see how my friends love dnd. I would like everyone of all walks of life to be able to have the ability to play. 
Growing up in the.... well I will just be honest "hood", I have seen that nerd culture is often a luxury to those in lower finacle situations. Dnd is an escape from reality... and it should be easily accessible to all.

That is how we got here. While I am building my flatiron project on this.. this project is already so much bigger. I have decided that this will be my project to learn, grow and push myself. After even turning this in for muy projetct I plan on building on it for the next year to give my friends the safe and finaially equal place they deserve! I have a list of features. I have already road map a slow devlopment plan for them after the project for school part is completed. I might even continue to update this blog post to show the grow. Honestly... I am really eaxcited about this!

Now that we are all caught up... lets break down the site for what it will be doing in this stage of development and for the requirements that were placed. 

User's can sign up and create a charater. Users can join or create campaigns(dnd groups). Campaign's have sessions(the meet up time for the dnd game).  

That is the lowest level in a nutshell. I could go into the million and one features I will be adding over time but... start simple yea? Now from here on the format of this blog will be changing. I will be adding by day what was done. I will give a little insite into how I am feeling about it at this time and just give the run down on everything.

**Day/Entry One & Two:**
I spent a lot of time on associations. I honestly stuggle with many to many. As well as having multiple assocaitons from a table. When asking about creating one... honestly I was just told not to. It was incredibly discouraging because I felt like I really wanted to push and learn. This time around I have again though it out with one of my tables having multiple associations to another. This time I decided not to mention it to anyone. I mean if it blows up in my face... It is a learning process. Instead of being fearful.. I am embracing the chance of failure. I just do not want to say no without trying. This one aspect is in my opinon for me... very important. It will show me if I can learn something and put it into use on my own. We will seee. I will not be removing anything in my writing as I go. So hopefully I do not have an entry about how I gave up and took it out... (Future me if you are reading this... You got this! Don't give up! Dust yourself off and try again)... I am writing this on day two. Luckly yesterday is fresh on the mind! I went ahead today and started some of the actual coding. I have a user table set up with devise. I already have my home page set with a sign up or sign in option. With a little bit of my dear friend google I was able to find how to change the settings for devise via intializer/devise.rb. I wanted to go ahead and changed the min length for password... honestly because it was set to 6 and I wanted to just be fast/lazy by entering "test" for the password. Currently... feeling pretty good about this. I haven't had issues of not know or having to really good just yet. When I was planning for a week... I spent a good time googling  a lt of things for future features. This actually was very helpful as I had a good idea of how I wanted to go about it and how to. Currently I have just created the characters table and I am working on that. I will be calling it a day soon but I want to get these all set up before I do!... And I am back after a couple hours... I am having trouble with devise. I realized it has strong prams built in and I am try to figure out how to create the params for me to use and I am not understanding how to CRUD at this time. I have been at it all day tho so.. Will commit and come back tomorrow. Time to step away and let what I read marinate. 

**Entry Three:**
* *Goal*: Complete User, Character
* *Morning thoughts*: I have not started just yet. Forgive me as I feel these day to days will have time laspe in them as the last one did. I ended yesterday a little frustrated. I thought I had a good understanding of devise and had set it up. However, I am seeing now that I do not recall like I thought I did. Today I will be reviewing a class from last week (https://www.youtube.com/watch?v=dZTxa5Lsowk&feature=youtu.be) and trying to get a better understanding. After that todays goal is to finish my users and characters models, and views.. or at least finish what can be done alone with just the two of them at this time. I think I will break this down into 3 part per day. The start, the halfway, and the end. In an effort to not tire myself out on code like I normally do, this will force me to step away for a second and process what it is I am doing and have done. Also will give me a chance to "stop and smell the roses" as they say. Making this app is a big feat and a huge improvement from where my abilities were in october. I should be very proud and sometimes I beat myself up too much.  I now have a schedule for coding and and end time for ach day. I will check in at the hald way mark.
* *Half-way*:So I am realizing that I jsut really do not understand Devise as I thought. I will be spending today I guess looking into that further. I know that with devise if I want to add to the params that they have that I need to make a method for it in my application controller. The only thing is with devise now in place... how does this effect my user params on my user controller? Does it effect it at all? I am not sure so... I am pretty sure I am over thinking it and stressing myself out. I hopefully will finish today with some answers.
* *Conclusion of the day*: Today.... was a lot of wasted time. I have confirmed that because devise is handling the actions that I would just need to update the params. However, my github signin that I created is half working. Honestly a bit disapppointed. I wants to have users and characters done today. I have views for neither. Still just tring to get the sign in with other websites feature working. Right now after signing in and it redirects you... it goes too apage not found on github. Honestly, after working from 6am to 7pm... I am done for the day. Tired, frustrated and not sure where it s wrong. I will come back to it tomorrow!

**Entry Four:**
* *Goal*: Get Divise working!
* *Morning thoughts*: I really just do not want to touch this today but we have to just incase something takes longer than planned again. 
* *Half-way*: So I have tried 3 different ways of getting devise working. I spent hours reading documentation but I am still having a hard time understanding the user class now. Does it still need a controller? How do I get to the show or efine it. The controller it made with devise is something else.
* *Conclusion of the day*:  Devise is up and running! I learned from a great youtube video (https://www.youtube.com/watch?v=Dd8dOAL6WYs) that covered legit everything I needed. I also learned about the encrypted files through ruby that can house the key and secrete for my github authentication with omniauth. I was having a hard time wrapping my head around the users controller still. There are so many different ways to get it done that I am not sure what is best. Tonight I do more reading and we get back to it tomorrow!

**Entry five:**
* *Goal*: Complete Assocaitions
* *Morning thoughts*: I spent a lot of time working on devise. Honestly, it was mostly what I was doing. Took me 4 days but after a little more work after when I said I would stop... I got it working. The issue was with in the devise folder. I had a couple errors in spelling. No I have been doing research for a while on has_and_belongs_to_many VS has_many through. 
* *Conclusion of the day*: So today was mostly spent doing research. I need to understand more of how to join everything before I get onto actually doing it. I found some promising leads but they have so much extra gem's that it seems like more work than help. I will be giving it some thought and time till tomorrow to decided what is best to do.


**Entry six:**
* *Goal*: Get the associations DONE
* *Morning thoughts*:  I have no idea what I am doing. If this all works at this point.. I will be amazed!
* *Half-way*: So I reached out to our group general for some help. I have to say... I really hate when peopel tell you jsut don't do something. Give a reason or explain why someone shouldn't. The reason I was so stuck on doing a HMABT was because I thought my users should own groups.. but be able to be apart of them as well. I get it is not an easy task but I am determined to get it done. I have decided the route to take. I have found someone attemping to do the same thing has asked a question (https://stackoverflow.com/questions/20128806/how-to-use-owner-id-instead-of-user-id-as-foreign-key) about it already so I will be using this a a little bit of a guid to "getter" done haha.
* *Conclusion of the day*:  I DID IT!!!! However.... there is more not working now... Sicne the biggest part of this for me was this relation ship... I will break it down for ya before having the next day entered.
So to get the ownership I had to give my campaign an owner_id with a forgeign_key of the user_id

User:
has_many :campaign_memberships, dependent: :destroy
  has_many :campaigns, through: :campaign_memberships
  has_many :owned_campaigns, class_name: "Campaign", foreign_key: :owner_id
	
Campaign:
has_many :campaign_memberships, dependent: :destroy
  has_many :users, through: :campaign_memberships
  has_many :characters, through: :campaign_memberships
  belongs_to :owner, class_name: "User", foreign_key: :owner_id
  has_many :characters

CampaignMembership:
 belongs_to :user
    belongs_to :campaign
    belongs_to :character
I already gave everything a test through rails c.. and everything is now working.. However, the variables in my controller do not seem to be giving me the things I would like. I am getting Nil:NilClass errors left and right. Today was the biggest and scariest part of my project.. no kidding if I could not get it working I would have to replan everything. It is a great relief to have this done. Now I just have to focus on the views and everything else. Currently we have no design for the website. I wasn't focused on that this time around. I focused on it working how I wanted more than looks. I suppose that currentl I rather be a good coder than one focused on its apperance. 

**Entry Six:**
* *Goal*: Get the views shorted out and campagin set up to later refactor for character nested build from campaign.
* *Morning thoughts*: I have several things not working. Before I go through and add more I am going to take time to fix what I have 
* *Half-way*: Everything is looking a lot better but I am stuggling to understand the difference between helpers and scope and when to use which. I will do some futher research on that today.
* *Conclusion of the day*: Today was eventful to say the least. I managed to get the nested resources for my character taken care of. Currently right now the character edit is not working along with almost all of my campaign_members. 


**Entry Seven:**
* *Goal*:  Finish it all by 8pm or cry my eyes out?
* *Morning thoughts*: So I have been so busy on just getting the thing done that I honestly have not wrote anything. So while this says entry seven.. if we were going by days it would be like 10. I am not going to lie. I am really worries. Project is due at 8... I have a great deal of things not working. I keep getting "Unable to autoload constant CampaignMembershipsController" when trying to go to my campaigns members index. I need to finish up the index for the campaign members, the campaigns home, add a form to the show for campaign to join with a selected character. I need destroy methods on all my classes, validations, seed data, my characters edit is creating new instances, and then need to record my walk through. That is a lot to get done in a day. Had I not wasted so much time on the appearance than I would be done. What is worst is that I am not going to have enough time to even add the visuals because I am crunching on time. Lesson learn... code... then visual because now I have spent a week on thigns that I wont even be touching... and I might not make deadline for project. It is okay! I have called in reinforcements! I have a meeting with a lead later today, and I have one of my coding buddies who is going to try to help me pin point where exactly the issue is with my campaign members table. I am a littl over whelmed... I am trying to have faith... this is at least the first project that has not blown up in my face.... theres that. 
* *Half-way*: So I changed campaigns_membership to just membership. Roolled it all back to make the corrections. That must have been my issue. NEW LESSON.. don't name things closely. To be honest I am still not sure where the issue was but my users delete is now working and member index is working!!!! WE are on a roll. This isn't even half way that I am adding this. I started at 10 today. It's only 11:51! YES!!! Okay! Now I need to figure out delete method, and nested form. Then I am pretty much done with the views and controllers.
* *Conclusion of the day*: WE DID IT! So... not on time but at least in the same day. It is now 10 pm. I am about to record the video for it and then post it up. It was not easy. There was a lot of issues with the nested forms for me but after playing with it it finally clicked!

I will come back to spell check this.. but at this time I am going to go ahead and put it in so it is not any later than it is already.
