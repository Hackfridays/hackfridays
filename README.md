# Internal Hack Friday projects
On Fridays, we work on Hack Friday projects. This markdown is a first effort in collating past projects, as well as projects that are currently in progress or are being thought about.

In time, the aim is to integrate all the hack projects fully with GitHub, with this markdown providing a quick summary of links, requirements, team compositions and outstanding work, amongst other things.

## Table of contents
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Internal Hack Friday projects](#internal-hack-friday-projects)
	- [Table of contents](#table-of-contents)
	- [MuchVote](#muchvote)
		- [Description](#description)
		- [Information](#information)
		- [Status](#status)
	- [Event Looping + ElasticSearch](#event-looping-elasticsearch)
		- [Description](#description)
		- [Information](#information)
		- [Status](#status)
	- [Theramin with Node+Arduino](#theramin-with-nodearduino)
		- [Description](#description)
		- [Information](#information)
		- [Status](#status)
	- [Image detection Cordova plugin](#image-detection-cordova-plugin)
		- [Description](#description)
		- [Information](#information)
		- [Status](#status)
	- [RethinkDB and Node basics](#rethinkdb-and-node-basics)
		- [Description](#description)
		- [Information](#information)
		- [Status](#status)
	- [HR App](#hr-app)
		- [Description](#description)
		- [Information](#information)
		- [Status](#status)
	- [Hacktool](#hacktool)
		- [Description](#description)
		- [Information](#information)
		- [Status](#status)
	- [Wolfbot (in progress)](#wolfbot-in-progress)
		- [Description](#description)
		- [Information](#information)
		- [Status](#status)
	- [Dudebot (in progress)](#dudebot-in-progress)
		- [Description](#description)
		- [Information](#information)
		- [Status](#status)
	- [My Meme (in progress)](#my-meme-in-progress)
		- [Description](#description)
		- [Information](#information)
		- [Status](#status)

<!-- /TOC -->

## MuchVote
### Description
MuchVote was created as a way to collect opinions instead of asking for people to rise their hands counting them.

The backend was made using Python-Flask and MySQL database.
The frontend is a multiplatform mobile application (Android & iOS) made using ReactNative.

The application provides two ways of voting: using numerals (0-9) and using a set colors. It also allows for offline and online voting with a simple result page for the online part.

### Information
- **Team members:** Cátia, Délio, Maria, Edgar
- **GitHub repo URL:**
 - [MuchVote API](https://github.com/Cloudoki/MuchVote-API)
 - [MuchVote APP](https://github.com/Cloudoki/MuchVote)
 - [MuchVote Website](https://github.com/Cloudoki/MuchVote-site)
- **Web URL (if applicable):** [Much](http://muchvote.cloudoki.com/)


## Event Looping + ElasticSearch
### Description
With Elastic-event-js, you can catch web browser events, send them to an ElasticSearch instance for analytics purposes.
In this project the events from mouse movements and clicks are represented in a canvas environment in realtime.

### Status
- Is there outstanding work? _No, but the application can be improved with a webversion/in app version to see and remove old voting sessions. It would also be good to look for a meetup group (frontend/React) to participate and present this project._
- Is there a blog post written? _[Going native with React Native](http://blog.cloudoki.com/going-native/), [Getting started with RESTful APIs using the Flask microframework for Python](http://blog.cloudoki.com/getting-started-with-restful-apis-using-the-flask-microframework-for-python/)_
- Are you proud of the content of this post, or should it be amended? _Yes, No need to amended_
- Can the code use a refactor and/or cleanup (does it follow best practice)? _The code could use refactor since best practice + hacking don't usually result in a good blend_
- Would there be value in presenting this work to others (internal/external)? _Yes, in a frontend meetup_

### Information
- **Team members:** Edgar
- **GitHub repo URL:**
 - [Elastic Event JS](https://github.com/Cloudoki/elastic-event-js)
 - [Docs](http://cloudoki.github.io/elastic-event-js/docs/)
- **Web URL (if applicable):** [Blog Post](http://blog.cloudoki.com/event-logging-elasticsearch/)

### Status
- Is there outstanding work? _Not sure, most likely no_
- Is there a blog post written? _[Event logging with ElasticSearch
](http://blog.cloudoki.com/event-logging-elasticsearch/)_
- Are you proud of the content of this post, or should it be amended? _Yes_
- Can the code use a refactor and/or cleanup (does it follow best practice)? _Yes_
- Would there be value in presenting this work to others (internal/external)? _Yes_

## Theremin with Node+Arduino

### Description
A NodeJS and Arduino implementation of a Theremin with a web page visualizer of the sound wave produced.

### Information
- **Team members:** Delio
- **GitHub repo URL:** [Arduino + NodeJS = Theremin w/ Visualizer](https://github.com/Cloudoki/donder-theremin)
- **Web URL (if applicable):** [Blog Post](http://blog.cloudoki.com/arduino-nodejs-theremin-w-visualizer/)

### Status
- Is there outstanding work? _Yes a more descriptive blog post. The current one is more code and less text_
- Is there a blog post written? _[Arduino + NodeJS = Theremin w/ Visualizer](http://blog.cloudoki.com/arduino-nodejs-theremin-w-visualizer/)_
- Are you proud of the content of this post, or should it be amended? _Yes. Nothing to be amended but a video of the working solution must be added_
- Can the code use a refactor and/or cleanup (does it follow best practice)? _Yes it can be refactored_
- Would there be value in presenting this work to others (internal/external)? _Yes. An IoT meetup for example. However, its only purpose was to show a cool thing working. It's not that difficult or impressive to do_

## Image detection Cordova plugin
### Description
A Cordova plugin to detect when a certain trigger image is visible on the camera feed. For Android and iOS.

### Information
- **Team members:** Delio
- **GitHub repo URL:** [Image Detection Plugin (Android & iOS)](https://github.com/Cloudoki/ImageDetectionCordovaPlugin)
- **Web URL (if applicable):** [Blog Post](http://blog.cloudoki.com/mobile-image-detection/)

### Status
- Is there outstanding work? _Yes, tests, refactor and code cleanup_
- Is there a blog post written? _[Image Detection/Tracking in Mobile (iOS & Android)](http://blog.cloudoki.com/mobile-image-detection/)_
- Are you proud of the content of this post, or should it be amended? _Yes. Nothing to amend_
- Can the code use a refactor and/or cleanup (does it follow best practice)? _Yes refactor_
- Would there be value in presenting this work to others (internal/external)? _Yes, on a frontend meetup_

## RethinkDB and Node basics
### Description

The project started with a blog post about basic usage of RethinkDB with Node.js.
The main objective is reached, the things that need to be improved:


### Information
- **Team members:** Ricardo, Simon
- **GitHub repo URL:**
- **Web URL (if applicable):**

### Status
- Is there outstanding work? Yes, definitely
- Is there a blog post written? http://blog.cloudoki.com/rethinkdb-first-things-first/
- Are you proud of the content of this post, or should it be amended? No
- Can the code use a refactor and/or cleanup (does it follow best practice)? No, need to create a repo with examples or the nodeschool wizzard thing
- Would there be value in presenting this work to others (internal/external)? Yes (nodejs or NoSQL meetup)

## HR App
### Description
This app is designed to centralize the process of requiring tech savvy resources from external consulting companies and other parties.

### Information
- **Team members:** Nuno, Maria, Tiago
- **GitHub repo URL:**
 - [HR APP](https://github.com/Cloudoki/hr-app)
 - [HR API](https://github.com/Cloudoki/hr-app-api)
- **Web URL (if applicable):**

### Status
- Is there outstanding work? _Yes_
- Is there a blog post written? _No_
- Are you proud of the content of this post, or should it be amended? _Yes_
- Can the code use a refactor and/or cleanup (does it follow best practice)? _Yes_
- Would there be value in presenting this work to others (internal/external)? _Yes_

## Hacktool
### Description

Hacktool is a new face to GitHub in order to take advantage of its features to have:

Login and authorization for free by the GitHub
Users in a hackathon (users in a repo in GitHub)
Articles/ blog posts (a file in the repo)
Event schedule (a file as the article)

And everything we could put in a file useful to hackathon organization. Hannes will be our first "client"

### Information
- **Team members:** Ricardo, Cátia, Tomas, Rui
- **GitHub repo URL:**
 - [Hacktool Backend](https://github.com/Cloudoki/hacktool-backend)
 - [HackTool Frontend](https://github.com/Cloudoki/hacktool-backoffice)
- **Web URL (if applicable):** http://hacktool.hackfridays.com/ (demo version)

### Status
- Is there outstanding work? _Yes, could be a Github Blogger tool to external users_
- Is there a blog post written? _No_
- Are you proud of the content of this post, or should it be amended? _Yes, no amendments needed._
- Can the code use a refactor and/or cleanup (does it follow best practice)? _Yes_
- Would there be value in presenting this work to others (internal/external)? _Yes, for a general web development meetup_

## Wolfbot (in progress)
### Description
Ask wolfbot and it will answer you using wolfram-alpha. This was made to be used with Dudebot.

### Information
- **Team members:** Tiago, Edgar
- **GitHub repo URL:**
- **Web URL (if applicable):**

### Status
- Is there outstanding work? _Yes_
- Is there a blog post written? _No_
- Are you proud of the content of this post, or should it be amended? _N/A_
- Can the code use a refactor and/or cleanup (does it follow best practice)? _N/A_
- Would there be value in presenting this work to others (internal/external)? _Yes_

## Dudebot (in progress)
### Description
This bot will answer the wolfbot question with voice. This project uses Slack input, Text To Speech technology and Raspberry Pi for audio playback.

### Information
- **Team members:** Tiago, Edgar
- **GitHub repo URL:** [Dudebot](https://github.com/Cloudoki/dude-bot)
- **Web URL (if applicable):**

### Status
- Is there outstanding work? _Yes, it is not finished yet_
- Is there a blog post written? _No_
- Are you proud of the content of this post, or should it be amended? _N/A_
- Can the code use a refactor and/or cleanup (does it follow best practice)? _N/A_
- Would there be value in presenting this work to others (internal/external)? _Yes, on an IoT meetup_

## My Meme (in progress)
### Description
Create your own 9Gag like site using nodeJS, featuring a Slack integration.

### Information
- **Team members:** Ricardo, Edgar, Délio, Erik
- **GitHub repo URL:**
 - [minegag Frontend](https://github.com/Cloudoki/mine_gag)
 - [minegag Backend](https://github.com/Cloudoki/minegag)
 - [Slack integration](https://github.com/Cloudoki/minegag-slack)
- **Web URL (if applicable):**

### Status
- Is there outstanding work? _Yes, finish the development_
- Is there a blog post written? _No_
- Are you proud of the content of this post, or should it be amended? _N/A_
- Can the code use a refactor and/or cleanup (does it follow best practice)? _N/A_
- Would there be value in presenting this work to others (internal/external)? _Yes, on an IoT meetup_
