---
layout: post
title:      "React-Redux/final project"
date:       2020-10-18 18:31:35 +0000
permalink:  react-redux_final_project
---


Wow what a experience these last six months have been magical…! I have learned so much from the time I started to now . Not to get all sentimental, but it has changed me internally and outwardly FOR THE GOOD. 

I am going to go over some brief information about react-redux. We start with the index.html file that’s where the “DOM” gets passed information to display on the browser.
From there we Hop to index.js and this is where all the magic gets started or our foundation gets laid. We have to import a whole lot of files from react, react-DOM, create Store and Routers just to name a phew. To simplify, all that helps us connect to the “STORE” a place where data is stored from any level of our application.

So in a regular react we would have to pass information from one .JS file to another down a “tree”. That’s ok when we have a few files here and there, But as our apps grow that wont work. It would get supper confusing, passing information down many levels and keeping track where everything is. Insert REDUX our one stop shop to any data we want in any file we want!

Redux starts with an action, that has a reducer that takes a case statement , and takes state and action as arguments. We never try to destroy state or override it but we just add or delete one piece of a “object” from the array or whatever it is held in. We then have to fetch data from our API or backend either adding or deleting or updating our data. We then have access to whatever we want, when we want . Of course we have to import into the files we want to render information in but it’s not so bad once you get used to it.

Next step we have to go into those files, we setup something called ‘JSX’ (fancy JavaScript meets HTML) which basically looks like html made a baby with JavaScript! We then get that data from the “store” and we do that by calling on a method named mapStateToProps and that allows us to have any slice or all the data we need to showcase in that file.  We also have mapDispatchToProps that allows us to pass functions to our file so we can call simple functions inside our “JSX”.

We then use import export tags at the bottom of the file and we have a brand new app up and running. To be honest once to lay the foundation of it , the rest is easy! 

 So that’s my brief and possibly vague over view of react-redux. It has been grand time during my time at flatiron, I have learned so much! I am super grateful for this time, even when I had doubts I kept pushing and I am glad I did. I am excited for the future and what it holds. Till next time thank you and goodnight.

