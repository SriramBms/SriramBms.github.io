---
layout:     post
title:      "Building thumb-friendly designs"
subtitle:   ""
date:       2016-04-02 15:03:03
author:     "Sriram"
tags: [android, ux, design]
categories: [android, development, app]
---

Studies indicate that most people use a single hand and just the thumb while using their mobile devices [^uxmatters]. Keeping this in mind, it makes sense to design apps that are easy to navigate with just the thumb. Though it might seem a bad idea to design the app to suit the preference of only a percentage of total users, making an app 'thumb-friendly' benefits other users too. <!--more-->

![Two ways of holding phones](http://www.uxmatters.com/mt/archives/2013/02/images/HoldPhones_Figure-2.png "Phone usage")

*[source](http://www.uxmatters.com/mt/archives/2013/02/how-do-users-really-hold-mobile-devices.php)*

A few ways to build such 'thumb-friendly' apps

### Use lists

Grids are suitable for images but for content that is primarily text, ListViews and single or double-column CardViews are a better choice since all list elements can be easily scrolled to pass within the range of the thumb. 

### Use FloatingActionButtons

Though the reaction to Android FloatingActionButtons from the design community is mixed, I feel they are a great way to provide the primary features of the app in a way that is accessible and unobstrusive. There are many flavors of the button on the internet that extend their functionality to add muliple buttons and labels. ( If you'd like to check the one I'm working on, you can browse it on [Github](https://github.com/SriramBms/Amoeba). The [Medium](http://medium.com) app has a FloatingActionButton that vanishes when you're scrolling down through content preventing data from being obscured by it. [Tumblr](http://tumblr.com) uses it to present a view with multiple circular buttons. The low-priority, less-used features can be conveniently hidden away in a 'hamburger menu' or in the action bar.

### Use the bottom bar for displaying contextual menus

Contextual menu items can be displayed in the bottom action bar instead of the top one making it more accessible. 

![Bottom action bar](http://developer.android.com/design/media/action_bar_cab.png "Bottom action bar")

*[Figure: top action bar and bottom action bar](http://developer.android.com/design/patterns/actionbar.html)*

I'll be adding more to this list as I think of them. Feel free to share your thoughts.

[^uxmatters]:[How Do Users Really Hold Mobile Devices?][1]
[1]:<http://www.uxmatters.com/mt/archives/2013/02/how-do-users-really-hold-mobile-devices.php>

