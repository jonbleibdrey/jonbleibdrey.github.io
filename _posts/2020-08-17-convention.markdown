---
layout: post
title:      "convention"
date:       2020-08-17 21:00:17 +0000
permalink:  convention
---


this blog post is a quick tour through convention

Controllers are where the url makes an http request through a route and goes to controller action to get the info. Some basic information is as follow's: The name for controllers are camel case which is this: "CamelCase". Controllers suffix is always singular and they also follow a restful routes "direction" or a "crud" path. C.R.U.D stands for create, read, update and delete. 
 
C, or create portion, of it has two main routes: 1) its "new" route renders a new form and 2) the "create" uses the info the user inputs and posts it into the data base as a "params hash". 
 
R, for read, is either "index" which renders ALL the data for that particular object or it also stands for "show": that shows a specific item(singular) from that list.
 
U, or update, in my understanding is that "edit" renders the form and "update(patch)" actually updates the new info the user just inputed but not before finding the specific object by id or name.
 
Lastly, D is for delete which, deletes specific items from your data base!

Models and database hang out together. We use active record to extract data from the database. Model class names use CamelCase (explained above). The attributes and methods use snake case "this_is_snake_case". We associate them with has_many, has_many:through, and belongs_to, to name a few. belongs_to are singular while has_many is plural. Joint tables use foreign keys in the database and they have to have an _id suffix. That helps us connect our models together.

For Database or Tables we usally run: "rake db:create_migration NAME=create_dogs" and make sure it’s PLURAL! It usually comes out always CamelCase’d and we also throw in a "create". So it would look something like this:
 
(class CreateJournals < ActiveRecord::Migration).
 
We make sure our tables match together or with associations but,  we could also run it in tux. We would have to create a new instance, then we save it inside of a variable. Kind of like this:

sophie = Owner.create(name: "Sophie")
maru = Cat.new(name: "Maru", age: 3, breed: "Scottish Fold")
maru.owner = sophie
maru.save

Or we could call "build" on it. (haha).... that won’t create/save anything but make a new object in memory so that the view can take this object and display something mostly used in associations.

Lastly VIEWS. That’s where the user interacts with your website and app. It's considered the "front end " of programming, kind of where we make everything look pretty and usually where we display information. Also, it’s where we make forms where we get information from the user and then the controller uses that info in a params hash.


thank you, jonathan
