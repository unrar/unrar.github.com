---
layout: post
title:  "MVC, RMVC and concensus"
date:   2014-09-18
categories: blog
---
### "Ruby without Rails." RMVC and a practical case. ###

No one can deny that MVC (model-view-controller) is a leading programming style. Most people associate it to Ruby on Rails, so if you're a RoR developer you already know how great MVC is. But what if you don't like Rails? You probably don't know anything about MVC, and if you do, you're confused because you have never had the chance to use it (because it's unexistant outside the Rails environment, or is it?).

MVC is great. But it's also complicated. Rails is also great, but it's also complicated. MVC and Rails go hand in hand, but what if someone wanted to do MVC without doing Rails?

That's why I created [RMVC](http://github.com/unrar/rmvc) - Ruby Model-View-Controller. A framework that creates all the files and all the jazz required to create a simple (or complex) Ruby MVC application - without the Rails.

It may sound stupid, but it's really helpful. Not only does it create the whole structure itself, but it also lets you create new models, views or controllers. And the best part is - if you follow the conventions (which almost no one does), you have to do almost nothing - just focus on your code!

MVC is like OOP. It's confusing in the beggining, but then you kinda like it, and before you realize, you can't live without it.

Okay, the RMVC development is kinda frozen - but it's stable and bug free. I'm now working on some kind of `merge`-like action to ease database creation. That's the bottleneck of RMVC right now, you have to create the databases yourself and it provides no tools for assisting you with it. But that's to change soon!

And, what about [concensus](http://github.com/unrar/concensus)? It started as *yet another RMVC example*, but it's quickly evolving into something bigger. The idea was to create a not-that-complex tool but not-that-simple tool to manage a census (or similar kinds of databases), so you could see how MVC helps you organize the code.

Just look at its repo - it's all nice and clean, organized, readable, and very clear. 

Don't hesitate to clone it and experiment the magic of MVC (and RMVC) by yourself!

**Note**: You can download RMVC as a gem:

    $ gem install rmvc
