# 52 weeks, 52 projects

The **52 weeks, 52 projects** challenge states that I should make one projects every week, for 52 weeks. It doesn't state what kind of project should I make or anything else related to that. But I have a long list of technologies I'd like to try and test, so I probably will have a lot to do.


## Week 1
The project I developed in the first week is called [Kotlin on Android](https://github.com/aziflaj/ToDo-kotlin/) and is a simple "ToDo" application built entirely in Kotlin. Read my [blog post](https://aziflaj.github.io/week-1-challenge-kotlin-in-android/) about it.

## Week 2
In the second week of the challenge, I went into front-end web development tools and frameworks, messing around with [AngularJS](http://angularjs.org/) (v1), [Gulp](http://gulpjs.com/) and [Sass](http://sass-lang.com/) (Sassy CSS). I tried to make my own invoice generator, or at least [its front end](https://github.com/aziflaj/simple-invoices-frontend). It is just the frontend, so it doesn't do anything for the moment, but later I will wire it with a backend service which will store the previous invoices by the user into the DB. Here's my [blog post](https://aziflaj.github.io/week-2-report-angularjs-gulp/) for the second week.

## Week 3
In the third week, I dealt with [Vagrant and Chef](https://github.com/aziflaj/vagrant-chef). I use Vagrant for creating virtual environments, and Chef for provisioning the VM. Until now, I've been using [laravel's Homestead](http://laravel.com/docs/5.1/homestead) and [PuPHPet](http://puphpet.com/) for creating these VMs. Instead of Chef, PuPHPet uses [Puppet](http://puppetlabs.com/), but it is focused only in PHP projects. Using Chef and manually configuring VMs, allows me to create Virtual Environments for every kind of project, including other languages except PHP. Here's my [blog post](https://aziflaj.github.io/week-3-challenge-cooking-virtual-machines-with-chef/) for the third week.

## Week 4
In the fourth week, I decided to learn a MVC, Rails-based Node.js framework called [Sails](http://sailsjs.org/) (like Rails, but with an `S` instead of `R`). [The application I developed](https://github.com/aziflaj/Sailor) is not a really complicated one. It is a sample API built with Sails that allows the API consumer get information about different ship types (source: [Wikipedia](https://en.wikipedia.org/wiki/List_of_historical_ship_types)).
You can read my [blog post about this week](https://aziflaj.github.io/week-4-challenge-server-side-javascript/).

## Week 5
In the fifth week I made some small changes to the same application I developed the 4th week. I added a bit of validation and an authorization mechanism, so not everyone could access certain routes. For example, only admin users can delete records. [The repository is still the same](https://github.com/aziflaj/Sailor/), so I added a branch called `week4` for the code writen in the 4th week.

## Week 6
In the sixth week I created an IRC-like application in Java using Sockets. The application allows different clients to connect to a single server process, identified by a hostname and a port number, and chat with each other. [You can find the source code here](https://github.com/aziflaj/IRC), where you can also read how to set up the server and the client and use them

## Week 7
I took a week off from coding and instead answered seven questions I found interesting during time. You can read the answers [in my blog post](https://aziflaj.github.io/seven-questions/).
