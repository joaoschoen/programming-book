### [Return to Readme](/Readme.md)

# Table of contents

- [Table of contents](#table-of-contents)
- [Chapter 1: Introduction](#chapter-1-introduction)
  - [Methodology](#methodology)
  - [Learning points](#learning-points)
      - [Abstraction Layer](#abstraction-layer)
  - [A Preface for beginners](#a-preface-for-beginners)
    - [Editor note:](#editor-note)
    - [End of editor note](#end-of-editor-note)
  - [Learning how to program](#learning-how-to-program)
      - [Learn JavaScript - Full Course for Beginners](#learn-javascript---full-course-for-beginners)
      - [JavaScript Algorithms and Data Structures](#javascript-algorithms-and-data-structures)
      - [World Wide Web](#world-wide-web)
      - [Full Stack Developer Roadmap](#full-stack-developer-roadmap)
      - [MERN Stack Tutorial with Deployment – Beginner's Course](#mern-stack-tutorial-with-deployment--beginners-course)
- [Chapter 2: Sources of knowledge](#chapter-2-sources-of-knowledge)
  - [roadmap.sh](#roadmapsh)
  - [freecodecamp](#freecodecamp)
  - [wikipedia](#wikipedia)
  - [computerphile](#computerphile)
  - [OWASP](#owasp)
- [Chapter 3: Defining what is Web Development](#chapter-3-defining-what-is-web-development)
      - [Web development](#web-development)
  - [Career paths and specializations](#career-paths-and-specializations)
  - [Application Focused](#application-focused)
    - [Frontend](#frontend)
      - [User interface](#user-interface)
      - [Web](#web)
      - [Mobile](#mobile)
    - [Backend](#backend)
      - [API](#api)
    - [Full Stack](#full-stack)
  - [Data Focused](#data-focused)
      - [Data](#data)
    - [Data Analyst](#data-analyst)
    - [Data Scientist](#data-scientist)
    - [Machine Learning](#machine-learning)
  - [Infrastructure Focused](#infrastructure-focused)
      - [Data](#data-1)
    - [DevOps engineer](#devops-engineer)
    - [Cloud architect](#cloud-architect)
  - [Reliability Focus](#reliability-focus)
    - [QA](#qa)
    - [Cyber Security](#cyber-security)
  - [Chapter 3: A history of mathematics, philosophy and problem solving (WIP)](#chapter-3-a-history-of-mathematics-philosophy-and-problem-solving-wip)
      - [Set theory](#set-theory)
      - [René Descartes](#rené-descartes)
      - [George Boole](#george-boole)
      - [Trolls are easily defeated | Shannon's Ghost](#trolls-are-easily-defeated--shannons-ghost)
  - [Chapter 4: Problems, problem solving, functions (WIP)](#chapter-4-problems-problem-solving-functions-wip)
  - [Chapter 5: Computers (WIP)](#chapter-5-computers-wip)
      - [Von Neumann Architecture](#von-neumann-architecture)
  - [Chapter 6: Applications, systems and the internet (WIP)](#chapter-6-applications-systems-and-the-internet-wip)
      - [System](#system)
      - [Process (computing)](#process-computing)
      - [Inter-Process Communication](#inter-process-communication)
  - [Full Stack Application](#full-stack-application)
  - [Systems and applications communication](#systems-and-applications-communication)
    - [Applications](#applications)
  - [The layers of communication systems](#the-layers-of-communication-systems)
      - [OSI model](#osi-model)
      - [TCP/IP model](#tcpip-model)
      - [HTTP](#http)

# Chapter 1: Introduction

This is a book on the structure of web development and it's many moving parts. The goal here is producing a comprehensive and holistic guide on how things work and what to study.

I'd first like to set up the game plan on how this study will be structured, I'm going to follow an inside out approach on how to the topics, going from the innermost most simple components and building out to the things that surround it.

I'll try my best to be as much of a generalist as possible, however do note that I have a huge bias towards web development as it is my specialization.

## Methodology

I admit my humbleness in and the power of the giants that came before me, as such during this research I won't be explaining things in depth that I don't feel qualified to explain or that aren't my own insights.

Within this book there will be sections I'll call Learning Points, these will tangential points of information gathered from external sources that are knowledge required for the understanding of the surrounding context.

It is important to note that after each of them the text will assume you have gone through that learning point and that you understand the concept explained in it, there is no point in me explaining things that have already been explained unless I have an insight on it or feel that additional explanation is required.

## Learning points

Learning points will usually look something like this:

#### [Abstraction Layer](https://en.wikipedia.org/wiki/Abstraction_layer)
- Source: Wikipedia
- Reading time: ~5 minutes
- Skipped segments:
  - Input and output
  - Graphics
- My example:
  - [Abstraction](./examples/abstraction.md)

I have read this article, it took me 5 minutes to read it and I considered that a few segments in it were worth skipping because they were unnecessary, some learning points will have more or less sections.

On longer articles I might add the minimum recommended segments that I believe you should read to move along but nothing stops you from reading the whole article if you're interested, anything that is historical knowledge of things used to be will usually be skipped.

I will provide explanations or examples where I believe they are needed but I will usually offload it to the articles themselves.

If a learning point has an example I will contain a link to the file containing said example and on that file a link to come back to the learning point.

## A Preface for beginners

### Editor note:

The structure of this book is changing a lot while I write it, I'm writing this during the writing of chapter 4, I will have to rewrite a lot of it over time to conform to the way I want things to be, as such this preface will be edited out or moved later.

If you want to have a hands on approach to how you do your studying and get a more practical approach then you can still follow my recommendations in this preface, however, I'm working on writing a deeper guidance on computer science.

I do however believe that you can learn through following my suggestions below.

### End of editor note 

If you are a beginner and are using this book as a source of knowledge I do expect you to have already gone through the Abstraction Layers learning point, after all I can't do your studying for you.

My goal on how to present the knowledge will be to introduce a high abstraction level concept and then go to the layers below it as seem fit.

I should note here as a warning that it isn't my intention here to teach you how to program, other people have done a better job then I could in teaching that, so this preface will be aimed in guiding you to the path of learning the basics.

Each part of the journey of learning how to program is a marathon that you must run, running a marathon is a very simple thing, you put one foot after the other for 42km and you're done, it is simple but that doesn't mean it isn't hard and that a lot of effort isn't required, the opposite of that is true.

But there is a reassurance that I want to give to you, please don't be alarmed or stress yourself over not understanding the meaning of the terms that you read or hear while studying. You do not need to understand everything that is going on all at once, it is part of the process of learning to not understand things.

I myself am learning a lot while writing this book and reading the articles that I'll cite throughout it, I've been studying programming for a decade and web development specifically for half a decade, learning takes time and there is no shame in not knowing something or having questions.

If this still bothers you to not understand something, a good practice is looking on Wikipedia for any term that you don't understand and reading **only** the first two paragraphs about it, you don't need to understand in depth how things work, just what they are.

Pro tip 1: note down every new term that you don't understand, over time this will help you measure how much you know and how much you don't know.

Pro tip 2: when on wikipedia, mousing over links will generally give you a summary of that term.

## Learning how to program 

If you don't know anything about programming I will give you two recommendations of where to start, you can pick between the two depending on the way you like to learn.

Both learning points are great and I have followed them myself ages ago, you can pick one of them or do both, it's your choice, doing both will give you more practice.

#### [Learn JavaScript - Full Course for Beginners](https://www.youtube.com/watch?v=PkZNo7MFNFg)
- Learning time: 3 hours 26 minutes of video + the time that you'll take to follow the course

#### [JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/)
- Learning time: variable

So now you know how to program, that is a very good start, but given that this is still the introduction of the book you still have a long way to go.

As such it is important that you understand on broad strokes how the internet works.

#### [World Wide Web](https://en.wikipedia.org/wiki/World_Wide_Web)
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

Now that you know how to program and understand roughly how the internet works it's time to actually get started into your specialization into Web Development

But JavaScript is only one of the many technologies that you will need to know to be a web developer, here are the others:

#### [Full Stack Developer Roadmap](https://roadmap.sh/full-stack)
- Source: roadmap.sh
- Time needed: Variable
- Recommended segments: 
  - HTML
  - CSS
  - JavaScript
  - Node.js
  - Git
  - PostgreSQL
- What you should do: 
  - Click on each of these topics, read what is there and then read or watch one of the articles or videos cited.

Now you have all of the required knowledge to write your first web application, I have always had a hands on approach to learning computer science, I like to get my hands dirty and practice the concepts I'm learning about.

So here is a full course on how to write an entire Full Stack Web Application, if you don't know what that means don't worry, you don't need to know to be able to do it and it will be explained later. 

#### [MERN Stack Tutorial with Deployment – Beginner's Course](https://www.youtube.com/watch?v=O3BUHwfHf84)
- Source: YouTube channel FreeCodeCamp
- Time needed: 2h 16m of video + your own development time
- Recommended segments: Entire video
- What you should do: 
  - Watch the whole video and follow the instructions, this will make you develop a complete application from scratch so by the end of it you'll understand the bare minimum required for understanding the rest of article

I might add more learning points here as time goes on and, but doing all of them will teach you the bare minimum required for following the rest of the book.

# Chapter 2: Sources of knowledge

Gathering knowledge about computer science and technologies is a constant research work, knowing where to look, what is important and what isn't, knowing what to study next, etc...

I have been gathering a lot of these libraries of useful information over the years and here are some of them that I'd like to share

## roadmap.sh

This is a wonderful website to answer the question "what should I study next?", it contains various road maps based on skills or roles and tells you the order of what you should study next. During the course of this book I'll be using them as reference and linking to them when needed.

[website](https://roadmap.sh)

## freecodecamp

As the name implies, freecodecamp is a group that focuses on providing the teaching of coding free for everyone, their website is an amazing platform for learning and their youtube channel is also amazing, containing dozens of courses that some times can be 20 hours long, they are very complete and detailed in their work.

[Website](https://www.freecodecamp.org/)
[YouTube channel](https://www.youtube.com/@freecodecamp)

## wikipedia

Good old reliable source of knowledge wikipedia, don't ignore them as a source of knowledge, they have absurd amounts of knowledge there and are a great source to study specific topics in a variety of different languages.

[Website](https://www.wikipedia.org/)

## computerphile

If you want to acquire very deep and knowledge about Computer Science in general and expand your horizons about the field a great stop is Computerphile, they have amazing videos explaining in a very didactic way the fundamentals of everything related to Computer Science.

[YouTube channel](https://www.youtube.com/Computerphile)

## OWASP

For knowledge of best practices about software security you should definitely always read the latest information provided by OWASP.

[Website](https://owasp.org/)

# Chapter 3: Defining what is Web Development

Call it Software Development, Information Technology, Computer Science, however you put it the field of knowledge is absurdly vast.

It's a yarn ball that grows over time, has decades of knowledge, and that no mater how much string you pull out of it while studying there never will come a point where you'll learn faster then the yarn ball grows, there's always more to learn.

Within this field there are multiple sub-fields that develop solutions to specific problems and have different concerns, web development is just one of them and the one I chose to follow a career in (and write this book about).

#### [Web development](https://en.wikipedia.org/wiki/Web_development)
- Source: Wikipedia
- Reading time: ~46 minutes
- Skipped segments:
  - Evolution of the World Wide Web and web development
  - Server-side languages
  - Agile methodology in web development

I can't really convey into words how much from this point onwards the complexity of what we have to discuss grows exponentially. Reading the article will give you an idea of how big it is.

## Career paths and specializations

Since we can't cover everything at once and honestly I don't believe I have the skill to do so while maintaining my sanity in check, I have chosen to divide the field in 4 categories based on the focus of their concerns, these being:

- Application
- Infrastructure
- Data
- Reliability

So let's discuss those briefly.

## Application Focused

Some career paths are focused on the development of software products that provide a business solution to a problem. We can further divide this focus further into two groups:

- Frontend
- Backend

### Frontend

This group of career paths is focused on programming all that is related to what the user sees and interacts with.

#### [User interface](https://en.wikipedia.org/wiki/User_interface)
- Source: Wikipedia
- Reading time: ~29 minutes
- Skipped segments:
  - Terminology
  - History

Developers in this space often interact with a few non-programmer professionals such as User Interface(UI) Designers, User Experience(UX) Designers and Product Managers.

There are two major platforms where frontend applications live:

#### Web

These are websites that can be accessed through Web Browsers both on Mobile devices and Personal Computers.

#### Mobile

These are applications that run natively on either Android or iOS smartphones.

### Backend

This group of career paths is focused on manipulation, storage and retrieval of the state of the data of an application.

#### [API](https://en.wikipedia.org/wiki/API)
- Source: Wikipedia
- Reading time: ~33 minutes
- Skipped segments:
  - History of the term
  - Dispute over copyright protection for APIs

Backend developers often interact with frontend developers, other non-technical teams in a company such as marketing or finance, product managers, users and clients, in order to define the business logic of the application.

### Full Stack

These developers don't tend to specialize in one either frontend or backend, instead their approach is to work in both at the same time, integrating UI with APIs and Databases 

## Data Focused

#### [Data](https://en.wikipedia.org/wiki/Data)
- Source: Wikipedia
- Reading time:
- Skipped segments:
  - History of the term
  - Dispute over copyright protection for APIs


This group of career paths is focused on working with the data itself, there are four major routes:


### Data Analyst

Focuses on interpreting existing data to generate insights and support decision-making. Their work is more descriptive and diagnostic — answering what happened and why.

### Data Scientist

Focuses on interpreting existing data to generate insights and support decision-making. Their work is more descriptive and diagnostic — answering what happened and why.

### Machine Learning

Machine Learning is a branch of artificial intelligence where systems learn from data to make predictions or automate decisions without being explicitly programmed for each task.

## Infrastructure Focused

#### [Data](https://en.wikipedia.org/wiki/IT_infrastructure)
- Source: Wikipedia
- Reading time: ~7 minutes

This group of career paths is focused on not on the application itself but on the environment surrounding the application. I'll divide this into two career paths

### DevOps engineer

The job of the DevOps engineer is to establish the continuous integration and delivery of software, building systems to automate tasks such as testing, deployment and monitoring.

### Cloud architect

The cloud architect is the other side of the coin of DevOps, focusing on the design and maintenance of cloud infrastructure. 

Their job is to analyze the security, scalability and cost-effectiveness of web solutions in cloud environments such as AWS, Azure or GCP, as well as setup all of the resources that will be necessary to run the application.

## Reliability Focus

This group of career paths is focused on the quality of the software being delivered. This can be divided into two concerns:

### QA

A Quality Assurance specialist's job is to guarantee the integrity of the software development processes and products.

### Cyber Security

A cyber security specialist's job is to protect systems and networks from attacks, create defense mechanisms and strategies to guarantee that sensitive information and systems are secure and that only authorized users can access it.

## Chapter 3: A history of mathematics, philosophy and problem solving (WIP)

I believe there is a fundamental understanding that has to be achieved before a person can understand programming, there is a structure and logic to why we do the things the way we do them. In it's essence what we are trying to do is to solve problems, and not only that but automate the resolution of problems so that a machine can do it for us instead of us doing ourselves.

As such we need to define what a problem is to then be able to look at problems and decompose them into pieces of information we can solve. 

The history behind the things that came to be for computers to exist is fascinating, I often skip the history of things later in the book but here I'll allow myself to drift into that and put into the limelight the enlightened minds who'se work would eventually coalesce into the invention of computers.

The learning points in this chapter are purely for curiosity sake and aren't necessarily required reading because at times they'll be very hard to understand because they are talking about very abstract mathematical constructs, but if you're interested in the history of computers they are names worth knowing, I'll give a brief explanation of what is the important takeaway from them.

#### [Set theory](https://en.wikipedia.org/wiki/Set_theory)
- Source: Wikipedia
- Time frame:

#### [René Descartes](https://en.wikipedia.org/wiki/Ren%C3%A9_Descartes)
- Source: Wikipedia
- Born: 1596
- Invention: 
  - [Cartesian doubt](https://en.wikipedia.org/wiki/Cartesian_doubt)

The first mind I'll bring upon this topic is that of René Descartes to show that the concern about how to define and structure problems isn't something new, the Cartesian method defines the process of breaking down problems into their most simple parts in order to try and solve them, he was a mathematician and a philosopher, his work of philosophy exposed the nature of problem solving.

#### [George Boole](https://en.wikipedia.org/wiki/George_Boole)
- Source: Wikipedia
- Born: 1815
- Invention: [Boolean algebra](https://en.wikipedia.org/wiki/Boolean_algebra)

Building upon Descartes, another fundamental stepping stone that was set on the road that lead to the invention of computers was George Boole's work in Boolean Algebra. Some problems have too many answers to try to put into the same system, if you ask people what their favorite ice cream flavor is you'll get a myriad of possible answers

#### [Trolls are easily defeated | Shannon's Ghost](https://www.youtube.com/watch?v=UZ4FdU7px_w)
- Source: Youtube channel AvE (he's a very funny guy)
- Watch time: the video is about an hour long but you don't need to watch it all, the important takeaway is the story of Claude Elwood Shannon

## Chapter 4: Problems, problem solving, functions (WIP)

boolean logic

functions

truth tables

complexity of problems

big o notation

## Chapter 5: Computers (WIP)

At this point we've been taking a look into the highest end of the complexity curve and what problems the field of web development is concerned with solving.

Let's step down into the trenches of electronic and computer engineering, let's have a deep dive on how computer systems work on a very fundamental level so we can start building complexity back up.

But how much down do we have to go? at some point the knowledge becomes historical curiosity

#### [Von Neumann Architecture](https://www.youtube.com/watch?v=Ml3-kVYLNr8)
- Source: Youtube channel Computerphile
- Watch time: 16 minutes



## Chapter 6: Applications, systems and the internet (WIP)

Focusing on the development side of applications

#### [System](https://en.wikipedia.org/wiki/System)
- Source: Wikipedia
- Reading time: ~3 minutes
- Recommended segments:
  - Introduction
  - Information and computer science

So we use systems, we write programs and execute them inside this system, and since the logic of our application is spread between multiple parts 

#### [Process (computing)](https://en.wikipedia.org/wiki/Process_(computing))
- Source: Wikipedia
- Reading time: ~20m
- Skipped segments:
  - Inter-process communication
  - History

#### [Inter-Process Communication](https://en.wikipedia.org/wiki/Inter-process_communication) 
- Source: Wikipedia
- Reading time: ~8m 

The term application itself is often used to describe individual parts of the software or the software as a whole. Each part when looked as it's own is actually very simple and they are made to solve individual problems. 

The amount of problems that need to be solved to make a working system is huge, so the logic is split and compartmentalized by it's function within the whole application.

Trying to define everything will drive me into the abyss, so I'll try to keep things simple, on broad strokes these are the categories:


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

#### [OSI model](https://en.wikipedia.org/wiki/OSI_model)
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

Innermost (physical) ⬇
1. Physical layer
2. Data link layer
3. Network layer
4. Transport layer
5. Session layer
6. Presentation layer
7. Application layer
Outermost (digital) ⬆

It is a more electronics focused approach because it resides more along the world of computer and electronics engineering then proper computer science and web development.

It is interesting to note that most of the work that is done in web development happens between the Session and Application layers while the Transport layer and all layers below are taken for granted to us.

#### [TCP/IP model](https://en.wikipedia.org/wiki/Internet_protocol_suite)
- Source: Wikipedia
- Reading time: ~56m
- Skipped segments: 
  - History
  - Layering evolution and representations in the literature
- Recommended segments:
  - Introduction
  - Key architectural principles

Innermost (physical) ⬇
- Link layer
- Internet layer
- Transport layer
- Application layer
Outermost (digital) ⬆

With both models using the same names but meaning different things it's no wonder people have a hard time learning computer science, luckily for us the good folk that write Wikipedia have explained in both the OSI an the TCP/IP articles how these layers are mapped between the models.

With this we know the definitions and standards put in place to make system communication possible, but we still don't know how applications communicate.

#### [HTTP](https://en.wikipedia.org/wiki/HTTP)
- Source: Wikipedia
- Reading time: 
- Skipped segments: History

And now we do, the HTTP standard is the working horse of web development communication.

