### [Go back to Readme](/Readme.md)

## Introduction

This is a book on the structure of web development and it's many moving parts. The goal here is producing a comprehensive and holistic guide on how things work and what to study.

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

I should note here as a warning that this is not an article written for anyone who is illiterate in the basics of how to program, my intent here is to structure and deepen those fundamentals.

As such I highly recommend that if you don't have any of this base knowledge that you follow this preface to the risk, it is going to guide you on starting points for learning how to program and the basics of what is software development.

But before you do that there is a reassurance that I want to give to you, please don't be alarmed or stress yourself over not understanding the meaning of the terms that you read or hear while studying.

I myself am learning a lot while writing this book and reading the articles that I'll cite throughout it, there is no shame in not knowing or in having questions.

You do not need to understand everything that is going on all at once, it is part of the process of learning to not understand things.

If this still bothers you to not understand something, a good practice is looking on Wikipedia for any term that you don't understand and reading **only** the first two paragraphs about it, you don't need to understand in depth how things work, just what they are.

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

Doing this will teach you the bare minimum required for following the rest of the book.

# Defining what is Web Development

The field of Software as a whole is a huge mess of things, it's a yarn ball that grows over time, has decades of knowledge, and that no mater how much string you pull out of it while studying it there never will come a point where you'll learn faster then the yarn ball grows, there's always more to learn.

#### Learning Point:
- Article: [System](https://en.wikipedia.org/wiki/System)
- Source: Wikipedia
- Reading time: ~3m
- Recommended segments:
  - Introduction
  - Information and computer science

## Applications and computer processes

When we run

-- I'M CURRENTLY WRITING HERE, SO THINGS MIGHT CHANGE OR MOVE OUT OF ORDER

#### Learning point
- Article: [Process (computing)](https://en.wikipedia.org/wiki/Process_(computing))
- Source: Wikipedia
- Reading time:

#### Learning point
- Article: [IPC](https://en.wikipedia.org/wiki/Inter-process_communication) 
- Source: Wikipedia
- Reading time: ~8m


The term application itself is often used to describe individual parts of the software or the software as a whole. Each part when looked as it's own is actually very simple and they are made to solve individual problems. 

The amount of problems that need to be solved to make a working system is huge, so the logic is split and compartmentalized by it's function within the whole application.

Trying to define everything will drive me into the abyss, so I'll try to keep things simple, on broad strokes these are the categories:

- Frontend
- Backend
- Database
- Devops

The combination of all of them is what we call a "tech stack" or just "stack".

I listed these categories in order of what is closest to the user to what is furthest, although using text only to represent this curses me because devops is actually a wrapper around the rest of the stack, but for now that is not that important.

## Full Stack Application

A full stack application then is one that has all layers of this stack and that is deployed on a computer somewhere on the internet. 

Because the logic of how to do things is distributed between multiple layers, each of these layers has to communicate with each other to be able to solve the whole problem. 

-- todo: 
explanation about: 
  how applications are run 
  operating systems
  processes

## Systems and applications communication

When we talk about communication we have to specify at which level we are talking about, applications can be in the same computer and trying to communicate or they can be different computers in different parts of the world trying to communicate.

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
- Reading time: ~56m
- Skipped segments: 
  - History
  - Layering evolution and representations in the literature
- Recommended segments:
  - Introduction
  - Key architectural principles

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

