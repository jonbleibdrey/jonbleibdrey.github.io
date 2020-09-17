---
layout: post
title:      "the fancy side of VIEWS"
date:       2020-09-17 20:35:54 +0000
permalink:  the_fancy_side_of_views
---


ok welcome back! 

today we are talking about JavaScript, horray! This month we went into JavaScript and to be honest I thought it would be a lot harder then it was. I learned that setting up the backend with Rails is super easy, so we can have a wonderful API waiting for us to snatch data from. The most work we did was switch ERB tags to render JSON’s tags and pretty much everything else stayed the same. 

Now we pop to the front end we’re we use only JavaScript. That’s when we built our first single page application. Which pretty much means you won’t have to refresh or go to another page to add your information or see the information you just posted (like when you heart on Instagram or thumbs up on facebook).

To get started we use something called an “event” and to be more specific we use an event called “DOMContentLoaded” that renders whatever you call under it to the page. I forgot to mention the basic/standard index.html folder where we put are “head” and “body” and other html magic! In the head we put meta information(just keyboard language computer stuff),stylesheets to make it look nice, and also where you put in the title of your website. Lastly we put some very basic DIV’S with id’s to have something to grab onto when we use javascript to render our page.

Now after we have the DOM loaded we make a “fetch” call to a specific url on the backend which has all your data. Fetch’s are complicated but I will try to explain the best I can. First line of code is the URL where you are going to get that data from. Second line is getting the response or data and turning it into json (JavaScript Object Notation), basically turns it into a information so we can grab it. Third line is what we are going to do with that information so it usually comes back to us in array of objects. We have to iterate over it most likely and then do whatever you want from there.

once we have that information the fun isn’t over, we now have to put that information into the Dom(document object module). We do that by grabbing the DIV’S we created in the html folder and inserting the information in multiple different ways from our fetch with some createElement, getElemntById and appending children(no that’s not a child’s name, think of it like boxes, you just put one box into another box with “append child”).

Lastly it renders onto our webpage and everything shows up and we are making webpages. Some other useful tips is something called debugger. Debugger allows you to walk through your lines of code seeing what information it is “pooping out” on each line of code. Theres also console.log I used that a lot in my project because I was able to see what information it was outputting in the console in real time( a place only coders go).

So I hope this has been helpful and ill see you on the next one , thank you for your time!

jon

