---
layout: post
title:  "Parse.com Hacks #1"
date:   2014-02-02 13:00
categories: parse.com javascript cloud
---

In working very closely with [parse.com](http://parse.com) in the last year and a half, I've had to overcome a number of technical challenges that I'll explain in the next few posts.  Some of these "hacks" required some parse.com source code changes, and others required me to jump through a few hoops to get what I needed.

Let's start with the source code that I had to change.

### Parse.com Javascript Library and Events

It's no secret that the [parse.com](http://parse.com) JavaScript library is a fork of the [backbone.js](http://backbonejs.org) codebase (notice I didn't call it backbone library).  I will be outlining here the changes I had to make and they involved coping the Event class from the latest version backbone.js and putting it in place of the Event class in the parse.com JavaScript Library.

TO BE CONTINUED