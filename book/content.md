### [Go back to Readme](/Readme.md)

## Introduction

This is a study on the structure of web development and it's many moving parts. The goal here is producing a comprehensive and holistic guide on what to study.

I'd first like to set up the game plan on how this study will be structured, I'm going to follow an inside out approach on how to the topics, going from the innermost most simple components and building out to the things that surround it.

I'll try my best to be as much of a generalist as possible, however do note that I have a huge bias towards web development as it is my specialization.

## Methodology

I admit my humbleness in and the power of the giants that came before me, as such during this research I won't be explaining things in depth that I don't feel qualified to explain or that aren't my own insights.

If and when at any point I link an article anywhere I will also assume you understand what that is or that you can do a bit of surface level research on your own, after all I can't do your studying for you.

There are loads of words that we read in tech that we don't bother really understanding what they are, I'll try to provide sources on things I learned from the articles I cite.

#### Learning points

Within this document I'll define what are called Learning Points, these will tangential points of information gathered from external sources that are important to read for the understanding of the context, I will be providing reading times for articles and watch time for videos and etc... 

I will note if and ever I skipped something I considered irrelevant inside of the article, while I'll be reading/watching the entirety of them bare the skipped bits. 

if your goal is to get a surface level understanding of the thing I'm mentioning you can just read the introduction of the articles so you can keep on reading this that's fine, but I highly recommend that you go further and deepen your knowledge of the subjects.

Every time a learning point is introduced, the text that will come after it assumes that you have all of the knowledge from it.

#### Preface for beginners

I should note here as a warning that this is not an article written for anyone who is illiterate in the basics of how to write a simple web application, my intent here is to structure and deepen the fundamentals.

As such I highly recommend that if you don't have any of this base knowledge that you follow these two learning points.

But before you do that there is a reassurance that I want to give to you, please don't be alarmed or stress yourself over not understanding the meaning of the terms that you read or hear while doing the basic learning.

You do not need to understand everything all at once that is going on, it is part of the process of learning to not understand things, if this still bothers you go on Wikipedia for any term that you don't understand and read **only** the first two paragraphs about it, this will give enough information for now.

Pro tip 1: note down every new term that you don't understand, over time this will help you measure how much you know and how much you don't know.

Pro tip 2: when on wikipedia, mousing over links will generally give you a summary of that term.

#### Learning Point:
- Article: [World Wide Web](https://en.wikipedia.org/wiki/World_Wide_Web)
- Source: Wikipedia
- Reading time: ~48 minutes 
- Skipped segments: 
  - History  
  - Nomenclature
  - Website
  - Optical Networking
  - Search engine
  - Deep web
  - Privacy
- Minimum recommended segments:
  - Everything except the skipped bits

#### Learning Point:
- Article: [Full Stack Developer Roadmap](https://roadmap.sh/full-stack)
- Source: roadmap.sh
- Time needed: Variable
- Recommended segments: 
  - HTML, CSS, JavaScript, Node.js, Git, PostgreSQL
- What you should do: 
  - Click on each of these topics, read what is there and then read or watch one of the articles or videos cited.

#### Learning Point:
- Article: [# MERN Stack Tutorial with Deployment – Beginner's Course](https://www.youtube.com/watch?v=O3BUHwfHf84)
- Source: YouTube channel FreeCodeCamp
- Time needed: 2h 16m of video + your own development time
- Recommended segments: Entire video
- What you should do: 
  - Watch the whole video and follow the instructions, this will make you develop a complete application from scratch so by the end of it you'll understand the bare minimum required for understanding the rest of article

# Defining the parts of what is Web Development

The field of Software as a whole is a huge mess of things, it's a yarn ball that grows over time, has decades of knowledge, and that no mater how much string you pull out of it while studying it there never will come a point where you'll learn faster then the yarn ball grows, there's always more to learn.

So it takes a lot of knowledge to be able to start to process what the hell is going on and try to organize things.

The first thing that I will do in this journey is try to provide a definition of how we divide the many technologies we use in the web development world. Trying to define everything will drive me into the abyss, so I'll try to keep things simple, on broad strokes these are the categories:

- Frontend
- Backend
- Database
- Devops

I listed them in order of what is closest to the user to what is furthest, if you work in web development you'll be somewhere amongst this stack, although using text only to represent this curses me because devops is actually a wrapper around the rest of the stack, but never mind that.

A full stack application is one that has all layers of this stack and that is deployed on a computer somewhere on the internet, the layers of the stack communicate with each other through HTTP requests and an user's experience of using this application depends on the combined effort of all of this working together nicely.

This gives us a basis but doesn't actually explain anything, because there's more to it, so let's expand things and let's do it by walking backwards before walking forwards.

## Systems and applications

### Operating System

#### Learning Point:
- Article: [System](https://en.wikipedia.org/wiki/System)
- Source: Wikipedia
- Reading time: ~3m
- Recommended segments:
  - Introduction
  - Information and computer science

### Processes

#### Learning point
- Article: [IPC](https://en.wikipedia.org/wiki/Inter-process_communication) 
- Source: Wikipedia
- Reading time:

### Applications



## The layers of communication systems

Let's imagine a simple scenario: A user accesses a website

How many systems were involved in this? 

On the user side to access it they need a web browser, this web browser is running on top of an operating system, this operating system is running inside a hardware, be it a computer or a cellphone (which is also a computer by the way).

The website has to communicate with the browser to navigate to the website, the browser has to package this information in an HTTP request and send communicate it to the OS, the OS has to package that and then communicate with the outside world.

Thousands of systems are then added into the mixture, radio towers, miles of fiber optic cables, routers, the whole physical network of the internet.

Then it gets to it's destination, it hit's the world of DevOps first, here a plethora of possibilities exist on what can happen.

All of these systems need to know how to communicate with each other, which brings us to two important standards of how these networks work: the OSI model and the TCP/IP model

#### Learning Point:
- Article: [OSI model](https://en.wikipedia.org/wiki/OSI_model)
- Source: Wikipedia
- Reading time: ~50m
- Skipped segments:
  - History
  - Comparison to other networking suites
- Minimum recommended segments:
  - Introduction
  - Definition
  - Layer architecture
- Fun facts: I learned here what the hell is a MAC address and where it comes from

This is an inside out visualization of how the communication between computers work, so now you know where these names come from when I and any further learning point references these layers.

#### Innermost (physical) ⬇
1. Physical layer
2. Data link layer
3. Network layer
4. Transport layer
5. Session layer
6. Presentation layer
7. Application layer
#### Outermost (digital) ⬆

It is a more electronics focused approach because it resides more along the world of computer and electronics engineering then proper computer science and web development.

It is interesting to note that most of the work that is done in web development happens between the Session and Application layers while the Transport layer and all layers below are taken for granted to us.

#### Learning Point:
- Article: [TCP/IP model](https://en.wikipedia.org/wiki/Internet_protocol_suite)
- Source: Wikipedia
- Reading time: 
- Skipped segments: 
  - History
- Recommended segments:
  - Introduction
  - Key architectural principles
- Fun facts:
  - here is where IP addresses are defined

#### Innermost (physical) ⬇
Link layer
Internet layer
Transport layer
Application layer
#### Outermost (digital) ⬆

With both models using the same names but meaning different things it's no wonder people have a hard time learning computer science, luckily for us the good folk that write Wikipedia have explained in both the OSI an the TCP/IP articles how these layers are mapped between the models.

With this we know the definitions and standards put in place to make system communication possible, but we still don't know how applications communicate.

#### Learning Point:
- Article: [HTTP](https://en.wikipedia.org/wiki/HTTP)
- Source: Wikipedia
- Reading time: 
- Skipped segments: History

And now we do, the HTTP standard is the working horse of web development communication.

