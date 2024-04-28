# Project 52

The **Project 52** is a personal challenge according to which I should make one project every week, for 52 weeks (one year). It doesn't state what kind of project should I make or anything else related to that. But I have a long list of technologies I'd like to try and test, so I probably will have a lot to do.


## Week 1
The project I developed in the first week is called [Kotlin on Android](https://github.com/aziflaj/ToDo-kotlin/) and is a simple "ToDo" application built entirely in Kotlin. Read my [blog post](https://aziflaj.github.io/posts/2015-10-17-week-1-challenge-kotlin-in-android/) about it.

## Week 2
In the second week of the challenge, I went into front-end web development tools and frameworks, messing around with [AngularJS](http://angularjs.org/) (v1), [Gulp](http://gulpjs.com/) and [Sass](http://sass-lang.com/) (Sassy CSS). I tried to make my own invoice generator, or at least [its front end](https://github.com/aziflaj/simple-invoices-frontend). It is just the frontend, so it doesn't do anything for the moment, but later I will wire it with a backend service which will store the previous invoices by the user into the DB. Here's my [blog post](https://aziflaj.github.io/posts/2015-10-24-week-2-report-angularjs-gulp/) for the second week.

## Week 3
In the third week, I dealt with [Vagrant and Chef](https://github.com/aziflaj/vagrant-chef). I use Vagrant for creating virtual environments, and Chef for provisioning the VM. Until now, I've been using [laravel's Homestead](http://laravel.com/docs/5.1/homestead) and [PuPHPet](http://puphpet.com/) for creating these VMs. Instead of Chef, PuPHPet uses [Puppet](http://puppetlabs.com/), but it is focused only in PHP projects. Using Chef and manually configuring VMs, allows me to create Virtual Environments for every kind of project, including other languages except PHP. Here's my [blog post](https://aziflaj.github.io/posts/2015-10-31-week-3-challenge-cooking-virtual-machines-with-chef/) for the third week.

## Week 4
In the fourth week, I decided to learn a MVC, Rails-based Node.js framework called [Sails](http://sailsjs.org/) (like Rails, but with an `S` instead of `R`). [The application I developed](https://github.com/aziflaj/Sailor) is not a really complicated one. It is a sample API built with Sails that allows the API consumer get information about different ship types (source: [Wikipedia](https://en.wikipedia.org/wiki/List_of_historical_ship_types)).
You can read my [blog post about this week](https://aziflaj.github.io/posts/2015-11-08-week-4-challenge-server-side-javascript/).

## Week 5
In the fifth week I made some small changes to the same application I developed the 4th week. I added a bit of validation and an authorization mechanism, so not everyone could access certain routes. For example, only admin users can delete records. [The repository is still the same](https://github.com/aziflaj/Sailor/), so I added a branch called `week4` for the code writen in the 4th week.

## Week 6
In the sixth week I created an IRC-like application in Java using Sockets. The application allows different clients to connect to a single server process, identified by a hostname and a port number, and chat with each other. [You can find the source code here](https://github.com/aziflaj/IRC), where you can also read how to set up the server and the client and use them

## Week 7
I took a week off from coding and instead answered seven questions I found interesting during time. Some of the questions are:

- A comparison between C# and Java
- The difference between Active Record and Data Mapper, two implementations of an Object-Relational Mapper (ORM)
- How JavaScript is executed in the server?
- How does Siri work?

You can read the answers [in my blog post](https://aziflaj.github.io/posts/2015-11-28-seven-questions/).

## Week 8
This week, I went back into the hybrid app development frameworks I like most, the Ionic Framework. I rewrote an old application of mine, called yalg - Yet Another Logo Game (not a very original name, I know). 
I rewrote the application for 3 reasons:

1. I had completely lost track with Ionic and what Drifty has been doing lately. I wanted to retry the framework and check the latest features they added.
2. While Angular2 is in progress, so is Ionic2. So I rewrote this, using the awesome Angular style guide by John Papa, and later will compare this to the newer Ionic2 framework.
3. I want to try to integrate ngCordova with this application, firstly for the embedded SQLite database and maybe later for other things too.

You can [read the blogpost here](https://aziflaj.github.io/week-8-remaking-ionic-application/).

## Week 9
During a couple of weeks I've been working on some school projects, including [Balut](https://github.com/aziflaj/Balut) and [Restauranteers](http://github.com/aziflaj/restauranteers). Also I've been following an Android course and developing some simple apps during it, which you can find [here](https://github.com/aziflaj/AndroidCourse).

You can [read my blogpost here](https://aziflaj.github.io/posts/2015-12-08-week-8-remaking-ionic-application/).

## Week 10
During the 10th week I finished the applications I started in the 9th week. and also developed another Android application, [Exchangeagram](https://github.com/aziflaj/AndroidCourse/tree/master/Exchangeagram). You can [read my blogpost here](http://aziflaj.github.io/week-10-extends-week-9/).

## Week 11
After a month of exams, I returned to my Project 52 with [jump-starting Sinatra](https://aziflaj.github.io/posts/2016-03-04-week-11-jump-starting-sinatra/), building a simple CRUD application using [Sinatra](www.sinatrarb.com). You can read the blogpost [here](https://aziflaj.github.io/posts/2016-03-04-week-11-jump-starting-sinatra/).
PS: I also changed the theme of my Jekyll blog

## Week 12
This week I went back into following the Android course by Rob Percival, building an Uber clone and after that, a Flappy Bird clone. During this time, I was working with Parse Geolocation API and libGDX for developing the game. Also I followed an introduction to Android Wear, how to build simple applications for smart watches and test these apps in the emulator. Here is [that blogpost](https://aziflaj.github.io/posts/2016-03-13-week-12-uber-and-flappy-bird/).

## Week 13
This week I’ve been working on something I’d like to call “a probability model for playing Blackjack”. If that intrigued you, [please read the blogpost here](https://aziflaj.github.io/posts/2016-04-11-week-13-playing-blackjack-with-machine-learning/).

## Week 14
I decided to write a non code-related article every 7th week, after I saw how many people liked the article on the 7th week. This time I wrote a Medium article called [The Developer's Mindset](https://medium.com/@aziflaj/the-developer-s-mindset-f5da7a4065b0#.gnru7424h).

## Week 15 to 24
During the last 2 - 3 months I haven’t written anything on my blog and the analytics are showing me the EKG of a wooden box. Nevertheless, I haven’t been just staying around, so my Project52 is still going on. [This blogpost](https://aziflaj.github.io/posts/2016-07-11-week-24-fast-forward-9-weeks/) is a fast forward, showing what interesting things I have been doing for the last 9 weeks.

## Week 25
This week I wrote a Ruby script to turn Markdown files into HTML files. The blogpost is posted on [here](https://aziflaj.github.io/posts/2016-07-26-converting-markdown-to-html-using-ruby/).
