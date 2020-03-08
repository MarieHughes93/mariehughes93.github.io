---
layout: post
title:      "Database table relationship"
date:       2020-03-08 05:42:24 +0000
permalink:  database_table_relationship
---


I wanted to give a quick helpful review for database table relationships. It seems to be something that I am often looking up for reminders. I figured that someone else might be doing the same or at the very least I can always bring this up myself for a refresher.

Relationships are formed by correlating rows from different tables. When a parent tables primary id is referanced as a forgeign key on the child table a table relationship is formed. There are only three ***types*** of relationship tables.

**One to Many**
The most common relationship of the three, a row from the (A) table can have multiple  rows in multiple records of  (B) tables. Picture you are buying something at a store. Let's say you buy a candy bar with your card 6 different times.  If you where to ask the store to pull up your reciepts by your card number all your reciepts would show up. (let's say they dont allow split payments) You would have a lot of them. They would not have another credit card that would come up with your reciept. You (one) have MANY reciepts

**One to One**

This is not a common relationship type because it is usually used for very specific purposes. This is when (A) table has one row matching in a row with the (B) table and vice versa.  Let's stick to the image from the one to many. Lets say when you first went and asked that the employee tried to look up by card but could not. He had to go get the manager. Lets say that in the database the way they have it set up is that the way the recieps are organized in their database is with a table for purchases by the list of products in a row, the amount in a row, the time it was in a row, and then a card_id. In the card table is card_id and the card number. IT is stored like this so not every employee can pull up cards.... Because that could get messy.

**Many to Many**
This is the more difficult of the reationship types. The (A) and (B) table have their primary id in a joing table. So let's keep going with the story we have but focus more on the store.... The manager saw that you bought a ton of one thing. He pulls your oder up on the comupter. Your oder shows your  debt card, it hascared an order id, and it show the products id. If he were to click on your debt card it would pull up only your purchases. However if he was to click on your poduct id. That would lead him to the product. If  he looked up oders for that product, he would have millions of different oders with different card. SO to picture that as tables. A customer table with an id, name and card. A oders table with a id, a card payment, and the product purchased. A product table with an id, a name, a price, and a experation date.

Hopefully writting this out help someone else. I honestly get pretty confused when trying to visualize it myself sometimes. It is not always so easy. When you have many to many it can get pretty over whelming if you are not careful. 
