# coding-log
A public log of my progress as a developer in 2018.

#@ 10 - 23 Feb 2018

_projects:_
_[Stopify: A Parody Version of Spotify]

_progress:_ These past few weeks, I've been working on my first full stack application. The app is called Stopify (for now), a parody version of Spotify. The app is designed to play music you hate, but it's all just for fun! Here are the technologies used: 

- Spotify API
- Node
- Javascript/Jquery 
- Gulp
- Passport
- Bootstrap
- Express

## 7-9 Feb 2018
_projects:_ 
-[ORM]

_topics:_ Building a basic to-do app using my first ORM model 

_progress:_ Figured out how to set up my directories correctly and build the data models I want. This really is not easy -- I enjoy the structure and documentation offered by Sequelize -- but it's part of the journey of being a wbe developer! Check out the repo here: (https://github.com/jjdaurora/burger).

## 6 Feb 2018
_projects:_ 
-[Express FriendFinder App]

_topics:_ Dealing with POST errors, general debugging

_progress:_ Today's coding exercise resulted in 1.5 hours of finding the issue with my POST route, which I discovered was due to my server file not requiring body-parser. Oh, the joys of little mistakes causing huge problems! This was a really good lesson for me as dev, though, to demonstrate how in many cases, where you can't find what's wrong in the code, there was probably something small I didn't define in the project's setup.

- Read through a bunch of documentation on validations. Fun! 
- Migrated a project ORM to Sequelize by upating API GET and POST routes and creating config.json
## 5 Feb 2018
_projects:_ 
-[Sequelize]

_topics:_ Building Sequelize models, validations, and buidling basic CRUD Applications.

_progress:_    

- Read through a bunch of documentation on validations. Fun! 
- Migrated a project ORM to Sequelize by upating API GET and POST routes and creating config.json

## 17 Jan 2018
_projects:_ 
-[CLI Constructor Hangman](https://github.com/jjdaurora/constructor-hangman)

_topics:_ Constructor Obkects 

_progress:_    

- Completed Word constructor, which is basically responsible for the gameplay functionality of the hanngman words.
- Struggled with figuring out how to determine the state of each word's letter, i.e. how to write logic that understands whether each letter has been guessed yet. If no, post a blank space ("_"), if yes post the letter itself.
- Implemented some things I've never learned before, like Javascript .map
- Failed at implementing other new things, like array.every...
- Was able to accomplish the aforementioned letter issue by creating a handy dandy counter variable, which keeps track of the amount of visible letters and compares agains the length of the gameplay word. 

## 14 Jan 2018
_projects:_ 
-[CLI Constructor Hangman](https://github.com/jjdaurora/constructor-hangman)

_topics:_ Constructor Obkects 

_progress:_    

- Completed Word constructor, which is basically responsible for the gameplay functionality of the hanngman words.
- Struggled with figuring out how to determine the state of each word's letter, i.e. how to write logic that understands whether each letter has been guessed yet. If no, post a blank space ("_"), if yes post the letter itself.
- Implemented some things I've never learned before, like Javascript .map
- Failed at implementing other new things, like array.every...
- Was able to accomplish the aforementioned letter issue by creating a handy dandy counter variable, which keeps track of the amount of visible letters and compares agains the length of the gameplay word. 

_thoughts:_ I have found that games, even the simple ones, are some of the hardest things to program. I'm putting everything I have into this project to improve those JS skills! 


## 11 Jan 2018
_projects:_ 
-[CLI Constructor Hangman](https://github.com/jjdaurora/constructor-hangman)

_topics:_ Constructor Obkects 

_progress:_    

- Opened a repo and cloned a local one to my CPU. 
- Began pseudocode and architecing game logic. 
- Wrote 2 constructor objects containing properties and methods essential to the app's logic: Words and Letters.
- Words: Used to create an object representing the current word the user is attempting to guess. 
- Letters: used to display the letter of each word or a blank "_" if the letter has not yet been guessed.

_thoughts:_ I have found that games, even the simple ones, are some of the hardest things to program. I'm putting everything I have into this project to improve those JS skills! 

## 10 Jan 2018
_projects:_ 
- mySQL practice
_topics:_ SQL Basics 

_progress:_    

In my pursuit of becoming a full-stack developer, I've finally made it SQL! The first thing I did: download Sequel Pro. The next thing I did: learn important mySQL basics such as:

- CREATE, USE, PRIMARY KEYS, AUTO INCREMENTING INTS, AND MORE 

## 2 - 6 Jan 2018
_projects:_ 
- LIRI - a command line language recognition tool ran on node.js
- Sass

_topics:_ package.json file // omdb database movie calls

_progress:_    

[Learn Sass at LevelUp Tuts](https://www.youtube.com/watch?v=fbVD32w1oTo&list=PL2CB1F80266E986EA)

## 1 - 2 Jan 2018
_projects:_ LIRI - a command line language recognition tool ran on node.js

_topics:_ Spotify npm packages // switch case functions + structuring code
_progress:_   Spotify --  after reading about the virtues of expressive and clean code, I continued my work from 30 Dec. With the new knowledge instilled in my impressionable young developer mind, it didn't take much for me to reaize my working code was garbage and begin architecting something better. To begin, I decided to employ a switch case function in the beginning of my code. 

This code structure provides a more meaningful context to someone reading it. The switch case serves almost like a table of reference, conveying succintly what the code will execute. There is something about Twitter, something about Spotify, and something about a movide database. If you want to learn how these things work, just take a look at the corresponding functions beneath them. The code is like a book. 

## 30 - 31 Dec 2017
_projects:_ LIRI - a command line language recognition tool ran on node.js

_topics:_ Twitter / Spotify npm packages 

_progress:_  

	1) Twitter - posts 20 of my most recent tweets on command; 
	2) Spotify - searches a song's details by searching the song's title

## 29 Dec 2017
_projects:_ "Side Games and activities"

_topics:_ Javascript practice // scoping // session vs local Storage 

_progress:_  Sometimes you just don't have time to code, especially when you're travelling. That doesn't mean you can't _practice_ coding, though, which is what I did today. I use apps Py and SoloLearn to pratice exercises when I'm crunched for time but still want to keep the coding muscles streteched. In this case, I read a number of posts on sesison vs localStorage and messed around with a few JS algorithm challenges on SoloLearn. 

## 26 - 28 Dec 2017
_projects:_ "Rudolph" - a fun webpage for a friend 

_topics:_ Project overhaul // CSS Grid

_progress:_ After reviewing my code, I realized that I needed to make a lot of changes in order to achieve the project's goal. This decision, inevitably, led me down a rabbit hole that I never quite climed out of. I did learn some great CSS Grid basics. My takeaway from this project is that some projects are supposed to suck. In this case, I needed to waste a lot of time messing around with div arrangements and columns/rows layout in order to get a feel for CSS grid. My next step is to take a class on CSS Grid and truly get the hang of it.

I also implemented some nice jQuery easing features into the project's scroll functionality. Yes, I know I abandoned pure JS for this project. But, due to the amount of work put into CSS Grid, I gave myself a break. 

_time spent:_ ~10 hours
## 25 Dec 2017
_projects:_ "Rudolph" - a fun webpage for a friend 

_topics:_ Code Review

_progress:_ Due to the holiday, I spent this time cleaning up the HTML and styles documents. Cleaned up project folders and created a package.json file. 


## 24 Dec 2017
_projects:_ "Rudolph" - a fun webpage for a friend 

_topics:_ jQuery trivia game

_progress:_ Incorporated a small trivia game that prevents the user from proceeding to th e next section until all questions have been answered. 

## 23 Dec 2017
_projects:_ "Rudolph" - a fun webpage for a friend 

_topics:_  CSS Modals // Slideshows 

_progress:_ Created a photography slideshow that displays within the modals built on Dec 22. 

## 22 Dec 2017
_projects:_ "Rudolph" - a fun webpage for a friend 

_topics:_ Pure CSS modals

_progress:_ Built modal windows using pure CSS. The goal of this entire project has been to build a basic application with a beautiful user interface without using any frameworks. I abandoned this goal early on in order to build more aesthetically appealing checkboxes. Otherwise, the project has been built in pure CSS. My intention is to build the site using vanilla Javascript.  

## 21 Dec 2017 
_projects:_ Coding Log

_topics:_ The desire to become a better web developer and learner of all things code. 

_progress:_ Starting this log today as a way to track my progress and share my experiences with developers, recruiters, and nerds. 






