### [Return to Readme](/Readme.md)

# Table of contents

- [Table of contents](#table-of-contents)
- [Chapter 1: Introduction](#chapter-1-introduction)
  - [Opinions and personal preference](#opinions-and-personal-preference)
  - [Methodology](#methodology)
  - [Learning points](#learning-points)
      - [Abstraction Layer](#abstraction-layer)
  - [A Preface for beginners](#a-preface-for-beginners)
- [Chapter 2: Sources of knowledge](#chapter-2-sources-of-knowledge)
  - [roadmap.sh](#roadmapsh)
  - [freecodecamp](#freecodecamp)
  - [wikipedia](#wikipedia)
  - [computerphile](#computerphile)
  - [OWASP](#owasp)
  - [Build your own X](#build-your-own-x)
- [Chapter 3: A brief history of mathematics, philosophy and technology](#chapter-3-a-brief-history-of-mathematics-philosophy-and-technology)
  - [Painting the canvas](#painting-the-canvas)
      - [Powers of ten](#powers-of-ten)
      - [The Map of Mathematics](#the-map-of-mathematics)
  - [Early history of philosophy and math](#early-history-of-philosophy-and-math)
      - [Numbers](#numbers)
      - [Algebra](#algebra)
      - [Aristotle](#aristotle)
      - [Set theory](#set-theory)
      - [René Descartes](#rené-descartes)
  - [Early history of computers](#early-history-of-computers)
      - [Charles Babbage](#charles-babbage)
      - [George Boole](#george-boole)
      - [Trolls are easily defeated | Shannon's Ghost](#trolls-are-easily-defeated--shannons-ghost)
      - [Claude Shannon](#claude-shannon)
  - [The modern conception of computers](#the-modern-conception-of-computers)
      - [Alan Turing](#alan-turing)
      - [Nuclear Fruit](#nuclear-fruit)
      - [Turing machines explained](#turing-machines-explained)
      - [John Von Neumann](#john-von-neumann)
      - [EDSAC Simulator](#edsac-simulator)
  - [What we take away from history](#what-we-take-away-from-history)
- [Chapter 4: Thinking about problems](#chapter-4-thinking-about-problems)
  - [Breaking problems down](#breaking-problems-down)
      - [Analysis](#analysis)
  - [Looking at real world problems](#looking-at-real-world-problems)
      - [Real world problems and how to reason about them](#real-world-problems-and-how-to-reason-about-them)
- [Chapter 5: Thinking like a programmer](#chapter-5-thinking-like-a-programmer)
  - [Information](#information)
      - [Data](#data)
  - [Communication](#communication)
      - [Computer Program](#computer-program)
      - [Programming languages](#programming-languages)
      - [Algorithm](#algorithm)
- [Chapter 6: Electronic machines](#chapter-6-electronic-machines)
  - [The electronics of computers](#the-electronics-of-computers)
      - [Binary code](#binary-code)
      - [Why Use Binary?](#why-use-binary)
      - [Where did Bytes Come From?](#where-did-bytes-come-from)
      - [Boolean algebra](#boolean-algebra)
      - [Logic Gates](#logic-gates)
  - [Hierarchy of electronic systems](#hierarchy-of-electronic-systems)
      - [System](#system)
      - [Automata theory](#automata-theory)
      - [Chomsky Hierarchy levels](#chomsky-hierarchy-levels)
      - [Turing Machines Explained](#turing-machines-explained-1)
      - [Turing Complete](#turing-complete)
- [Chapter 7: Computers](#chapter-7-computers)
      - [Computer](#computer)
      - [Von Neumann Architecture](#von-neumann-architecture)
  - [The parts of a Von Neumann Computer](#the-parts-of-a-von-neumann-computer)
  - [Processing unit](#processing-unit)
    - [ALU](#alu)
    - [Registers](#registers)
  - [Control unit](#control-unit)
    - [Instruction register](#instruction-register)
    - [Program counter](#program-counter)
  - [Memory](#memory)
  - [External storage](#external-storage)
  - [Input and output](#input-and-output)
  - [Modern Computers](#modern-computers)
      - [Inside the CPU](#inside-the-cpu)
      - [How Computer Memory Works](#how-computer-memory-works)
- [Chapter 8: Machine language and compilers (WIP)](#chapter-8-machine-language-and-compilers-wip)
      - [Complex instruction set computer](#complex-instruction-set-computer)
- [Chapter 9: Programming logic (WIP)](#chapter-9-programming-logic-wip)
      - [Learn JavaScript - Full Course for Beginners](#learn-javascript---full-course-for-beginners)
      - [JavaScript Algorithms and Data Structures](#javascript-algorithms-and-data-structures)
      - [World Wide Web](#world-wide-web)
      - [Full Stack Developer Roadmap](#full-stack-developer-roadmap)
      - [MERN Stack Tutorial with Deployment – Beginner's Course](#mern-stack-tutorial-with-deployment--beginners-course)
- [Chapter 10: Applications, systems and the internet (WIP)](#chapter-10-applications-systems-and-the-internet-wip)
      - [Information Theory \& Coding](#information-theory--coding)
      - [Process (computing)](#process-computing)
      - [Inter-Process Communication](#inter-process-communication)
  - [Full Stack Application](#full-stack-application)
  - [Systems and applications communication](#systems-and-applications-communication)
    - [Applications](#applications)
  - [The layers of communication systems](#the-layers-of-communication-systems)
      - [OSI model](#osi-model)
      - [TCP/IP model](#tcpip-model)
      - [HTTP](#http)
- [Chapter 11: Defining what is Web Development](#chapter-11-defining-what-is-web-development)
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
      - [Data](#data-1)
    - [Data Analyst](#data-analyst)
    - [Data Scientist](#data-scientist)
    - [Machine Learning](#machine-learning)
  - [Infrastructure Focused](#infrastructure-focused)
      - [Data](#data-2)
    - [DevOps engineer](#devops-engineer)
    - [Cloud architect](#cloud-architect)
  - [Reliability Focus](#reliability-focus)
    - [QA](#qa)
    - [Cyber Security](#cyber-security)

# Chapter 1: Introduction

I started writing this book to explore web development which is my area of expertise, but I've since retroactively rewritten it to cover the basics of Computer Science too, so that new developers can have an easier time learning the things that aren't taught in courses these days.

I'd first like to set up the game plan on how the knowledge in this book will be structured, I'm going to follow an inside out approach, starting without any jargon that's common in the field of computer science and slowly building it up, teaching you this jargon step by step so that you don't have to face the mountains of knowledge all at once.

After we're done with the introduction to Computer Science and programming I'll branch into the many specializations within the field of Web Development, note that there are other fields withing programming that you can specialize in such as Game Development or Embedded systems, but since I don't have experience in those areas I won't be able to give much useful information, if I'm able in the future to add information about that I might create some chapters about it but for now that's going to be our game plan.

## Opinions and personal preference

While writing this book I probably won't be able to escape using my opinions to pick and choose what I write about, but I'll try my best to be as pragmatic as possible about my approach.

There are many different arguments that can be made about how we could approach things differently or why I would recommend doing X instead of doing Y.

This won't affect much the earlier chapters of the book, but when discussing the more advanced topics if I believe there is good reasoning of why things should be done a certain way I will point out that I'm giving my opinion and the reasoning behind it.

## Methodology

I admit my humbleness and the power of the giants that came before me, as such during this research I won't be explaining things in depth that I don't feel qualified to explain or that aren't my own insights, since there's a lot of free knowledge available already on the internet I'll instead point you to where you have to go to study.

This book is a guidebook, I want to provide to you a path which you can follow, with this in mind I created sections of this book which I'll call Learning Points, these will be the require reading for this book gathered from external sources, usually in the form of videos, playlists or articles.

After each Learning Point the text that follows expects that you have studied it and will start using terms that are taught in it, 

If I feel examples are needed for better understanding I'll write those in separate files, I will provide a link to the file containing said example and on that file a link to come back to where you were before so you won't get lost if you change files while reading the book.

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

I'll list the relevant sections of the article and my reading time is based on those, some times there's way too much stuff and some concepts that are super complicated to understand, and in depth knowledge about those isn't a requirement, just the knowledge that they exist will suffice.

## A Preface for beginners

Each part of the journey of learning how to program is a marathon that you must run, running a marathon is a very simple thing, you put one foot after the other for 42km and you're done, it is simple but that doesn't mean it isn't hard and that a lot of effort isn't required, the opposite of that is true.

I want to have a gentleman's agreement with you, each of us will do our part of this journey, I want you to expect of me that I do my best to try and teach you, at the same time I expect of you that you do your best to learn and study, as such I do expect you to have already gone through the Abstraction Layers learning point and read it.

There is a reassurance that I want to give to you, please don't be alarmed or stress yourself over not understanding the meaning of the terms that you read or hear while studying. You do not need to understand everything that is going on all at once, it is part of the process of learning to not understand things.

I myself am learning a lot while writing this book and reading the articles that I'll cite throughout it, I've been studying programming for a decade and web development specifically for half a decade, learning takes time and there is no shame in not knowing something or having questions.

Pro tip 1: note down every new term that you don't understand, over time this will help you measure how much you know and how much you don't know.

Pro tip 2: when on wikipedia, mousing over links will generally give you a paragraph about what that term means, it's usually worth it to read that.

# Chapter 2: Sources of knowledge

Gathering knowledge about computer science and technologies is a constant research work, knowing where to look, what is important and what isn't, knowing what to study next, etc...

I have been gathering a lot of these libraries of useful information over the years and here are some of them that I'd like to share with you.

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

## Build your own X

This is a repository filled with projects that you can build hands on if you want to have practical experience with developing some technologies.

[Github repository](https://github.com/codecrafters-io/build-your-own-x)

# Chapter 3: A brief history of mathematics, philosophy and technology

The history behind the things that came to be for computers to exist is fascinating, I often skip the history segment of articles later in the book but here I'll allow myself to drift into history and put into the spotlight the enlightened minds who'se work would eventually coalesce into the invention of computers.

## Painting the canvas

I would like to start this chapter by pointing out that the learning points I'm using in this chapter are purely for curiosity sake and I'm picking them for the sake of telling you a story, my goal with this chapter is to paint you a picture, and the picture I'm trying to paint for you is where all of this world of technology came from. I'll give a brief explanation of what is the important takeaway from them.

I'll start with a thought experiment, think of the biggest thing that you can imagine, you may think of a skyscraper, or our planet or the entire universe, the canvas I'm using to paint the picture for you is going to be of the size of that, the biggest thing you can imagine.

#### [Powers of ten](https://www.youtube.com/watch?v=0fKBhvDjuy0)
- Source: YouTube
- Watch time: 9 minutes

Here is a video from 1977 to help you think about the scale and size of things.

To paint this entire canvas, even if we have millions of people painting it, each person can only paint a small part of it, when you're growing up you learn that you like certain things, and you develop a passion for those things, and it's not only you, all people are like this, so each person develops an interest for a certain part of this canvas and they go paint there.

Our canvas is the canvas of computer science, but this canvas isn't alone in the universe, it is actually a small part of the vastly larger canvas of mathematics.

#### [The Map of Mathematics](https://www.youtube.com/watch?v=OmJ-4B-mS-Y)
- Source: YouTube channel Domain of Science
- Watch time: 11 minutes

This beautiful video shows the whole canvas of mathematics and it shows how narrow our slice of it is, even then when you zoom in on something that seems to be small you always find it to actually be more and more complex.

## Early history of philosophy and math

I believe there is a fundamental understanding that has to be achieved before a person can understand programming, there is a structure and logic to why we do the things the way we do them, it's not all just magic. 

If you ever had to solve a problem you know that you had to look at it for a bit, think of a solution, try that solution, fail, think a bit more, try another solution, etc... until eventually you solve that problem.

#### [Numbers](https://en.wikipedia.org/wiki/Number)
- Source: Wikipedia
- Origins: 3400 BC

Humans have been solving problems for millennia, and one of the first problems that humanity solved is how to keep track of things and how to count.

#### [Algebra](https://en.wikipedia.org/wiki/Algebra#History)
- Source: Wikipedia
- Origins: 1650 BC

Algebra and the field of mathematics was invented to solve complex problems that come up with numbers, counting isn't enough to solve problems, you need to compare things, you need to be able to equate things to other things, the necessity to trade gave birth to mathematic.

Throughout history a lot of brilliant minds have thought about problems and tried to organize their thoughts about them, this was the work of the philosophers.

#### [Aristotle](https://en.wikipedia.org/wiki/Aristotle)
- Source: Wikipedia
- Born: 384 BC
- Invention: [Term Logic](https://en.wikipedia.org/wiki/Term_logic)

The first individual mind that I give the spotlight to is Aristotle, not satisfied with the problem solving of mathematic he tried to abstract the knowledge he had about it and see if he could apply that not only to problems with numbers but to a broader set of problems.

#### [Set theory](https://en.wikipedia.org/wiki/Set_theory)
- Source: Wikipedia
- Time frame: as early as the 3rd century AD

At the ame time that Aristotle was structuring his logic, mathematicians started to develop of how to rigidly define and organize groups of things, this became set theory.

#### [René Descartes](https://en.wikipedia.org/wiki/Ren%C3%A9_Descartes)
- Source: Wikipedia
- Born: 1596
- Invention: 
  - [Cartesian doubt](https://en.wikipedia.org/wiki/Cartesian_doubt)

René Descartes also shared this concern of categorizing things to such a degree that he created a method to define and structure problems, the Cartesian method defines the process of breaking down problems into their most simple parts in order to try and solve them, he was a mathematician and a philosopher, his work of philosophy exposed the nature of problem solving.

## Early history of computers

#### [Charles Babbage](https://en.wikipedia.org/wiki/Charles_Babbage)
- Source: Wikipedia
- Born:1791
- Invention: [Analytical engine](https://en.wikipedia.org/wiki/Analytical_engine)

Babbage's work was a first step on machine automation of computational tasks, the first computers were electromechanical machines, instead of using electronic signals to both store the state and execute the computation, it used gears. 

But because of the nature of gears being a very complex solution to a very complex problem this technology reached it's limitations very quick.

#### [George Boole](https://en.wikipedia.org/wiki/George_Boole)
- Source: Wikipedia
- Born: 1815
- Invention: [Boolean algebra](https://en.wikipedia.org/wiki/Boolean_algebra)

Building upon Descartes, another fundamental stepping stone that was set on the road that lead to the invention of computers was George Boole's work in Boolean Algebra. 

Some problems have too many possible answers to try to put into the same system, if you ask people what their favorite ice cream flavor is you'll get a myriad of possible answers.

So instead of asking questions that can have many different answers, let's focus our work on asking questions that have only 2 possible answers, true or false.

#### [Trolls are easily defeated | Shannon's Ghost](https://www.youtube.com/watch?v=UZ4FdU7px_w)
- Source: Youtube channel AvE (he's a very funny guy)
- Watch time: the video is about an hour long but you don't need to watch it all, the important takeaway is the story of Claude Shannon

#### [Claude Shannon](https://en.wikipedia.org/wiki/Claude_Shannon)
- Source: Wikipedia
- Born:1916

Claude Shannon worked in programming and designing analytical engines, but he also had studied philosophy in university, this broader view of the canvas of science enabled him to combine the computers at the time with Boolean logic

So instead of trying to represent the values and computations with cogs that could have ten, thirty, one hundred different states, let's store this in an electronic signal that only has two states, on or off, true or false.

So he moved computers from a mechanical application using gears to an electromechanical implementation using switches and relays.

## The modern conception of computers

#### [Alan Turing](https://en.wikipedia.org/wiki/Alan_Turing)
- Source: Wikipedia
- Born:1912
- Invention: [Universal turing machine](https://en.wikipedia.org/wiki/Universal_Turing_machine)

Alan Turing's work is too big to put to paper in a short way, but one of his most important takeaways here is the Universal Turing Machine, this is the basic concept of what a system has to have in order to be able to perform computations

#### [Nuclear Fruit](https://www.youtube.com/watch?v=15dxuAbTC0A)
- Source: Youtube channel Ahoy
- Watch time: 1 hour 8 minutes

This is a lovely documentary about the history of computers and videogames, Ahoy is an excellent channel and this video talks a bit about the work of turing and how war shaped how the modern world works and the technology that was developed at the time.

#### [Turing machines explained](https://www.youtube.com/watch?v=dNRDvLACg5Q)
- Source: Youtube channel Computerphile
- Watch time: 5 minutes

Short video explaining what is a turing machine.

#### [John Von Neumann](https://en.wikipedia.org/wiki/John_von_Neumann)
- Source: Wikipedia
- Born: 1903
- Invention: [Von Neumann architecture](https://en.wikipedia.org/wiki/Von_Neumann_architecture)

Neumann's work was on the electronic architecture of we now think of as computers, defining a system where you have an input where values come in, a control unit that takes decisions on what to do with this value, an arithmetic and logic unit to do the calculations, a memory unit to store the instructions of the program and the data, and then an output where the result of the calculation goes out.

#### [EDSAC Simulator](https://www.youtube.com/watch?v=lXJ-tYqPARg)
- Source: Youtube channel Computerphile
- Watch time: 18 minutes

This video talks about one of the first implementations of a Von Neumann machine.

## What we take away from history

The amount knowledge and science that needed to be developed and brought together over the centuries is immense, I don't believe this is a at all a full view of how computer science came to be, but for the purposes of what I need I feel it is good enough for us to begin building programming logic.

# Chapter 4: Thinking about problems

To solve a problem we first need to understand it, we need well defined understanding and lots of information to be able to solve a problem, if I ask you "could you bring me some food?" the problem I'm asking you to solve is very vague, food can be a vegetable or a prepared meal or a sweet, the more vague we are the more solutions we can come up with how to solve a problem but the solution probably won't be good if you bring me cheese and I'm allergic to dairy. 

## Breaking problems down

Trying to classify and organize everything that can be a problem is a very complicated task, and trying to solve a complex problem can be very hard, but usually a complex problem is actually a collection of smaller and simpler problems. This process of breaking down problems is called analysis.

#### [Analysis](https://en.wikipedia.org/wiki/Analysis)
- Source: Wikipedia
- Reading time: ~1 minute
- Recommended sections:
  - Introduction

## Looking at real world problems

Instead of trying to be look in such a broad and theoretical way to problems, let's look at some real world problems and try to solve them, I have an example that shows some of these problems and how they aren't that complicated.

#### [Real world problems and how to reason about them](./examples/problems.md)
- Source: me
- Reading time: ~17 minutes

I hope that these examples were easy to understand, while explaining them I have sneaked a lot of concepts that are used in programming but without the jargon, they are very simple problems that we have to solve in our day to day life.

# Chapter 5: Thinking like a programmer

To solve problems like a programmer you have to learn the words we use to describe problems, we can't build a house without a foundation, in the same way we can't understand what the high levels of abstractions are without understanding the lower levels and what they are made of.

## Information

Let's start by thinking about the objects that we described in those problems, the books and pages, the page number and text in the page, the decks and the cards, the value and suit of the card, in programming all of these pieces of information are what we call data.

#### [Data](https://en.wikipedia.org/wiki/Data_(computer_science))
- Source: Wikipedia
- Reading time: ~2 minutes
- Recommended sections:
  - Introduction

The data is the information about the problem we're trying to solve, it can be numbers, text, images, etc...

## Communication

I can explain a problem to you because we both share a common language, I'm writing this book in english and you know how to read english, so I can transfer information to you this way, but computers don't understand language like this, computers only understand numbers and electronic signals.

To instruct a computer on what it has to do we have to define a set of instructions, this set of instructions that solves our problem is called a program.

#### [Computer Program](https://en.wikipedia.org/wiki/Computer_program)
- Source: Wikipedia
- Reading time: ~2 minutes
- Recommended sections: 
  - Introduction

Since computers don't understand human language we have to write these instructions in a language that it can understand, and that is where programming languages come in.

#### [Programming languages](https://en.wikipedia.org/wiki/Programming_language)
- Source: Wikipedia
- Reading time: ~2 minutes
- Recommended sections: 
  - Introduction

The program itself is the set of instructions we wrote, a program can be quite big, it can be written in many different files each with their own code, each part of the code can have it's own responsibility inside the whole of the program.

A set of instructions that is written to solve a well defined problem involving data is called an Algorithm.

#### [Algorithm](https://en.wikipedia.org/wiki/Algorithm)
- Source: Wikipedia
- Reading time: ~2 minutes
- Recommended sections:
  - Introduction

We are advancing in our understanding of how to think like a programmer but before we start to actually writing programs I want you to have an understanding about how computers work.  

# Chapter 6: Electronic machines

In it's essence a computer is a machine created to execute mathematic calculations, but before we look into how computers work I think it's important to look a bit into the machines that were created before the invention of computers. So let's look on how electronics are used to solve problems.

Let's step down into the trenches of electronic and computer engineering, let's have a deep dive into the very fundamental building blocks so we can start building complexity back up with them. 

## The electronics of computers

We know what a program and what data is, to a computer there is no differentiation between the two, programs are stored in the same way as data is, in a way the set of instructions of a program in itself is data. But how is this stored inside of the computer? 

Computers are electronic systems, so at the lowest level computers store this as electrical energy, the amount of electric energy is called voltage which is measured in volts.

Going back to the examples in chapter 4, the simplest answer to a question is yes or no, true or false, computer store it's data as a sequence of these values called binary code.

#### [Binary code](https://en.wikipedia.org/wiki/Binary_code)
- Source: Wikipedia
- Read time: ~5 minutes
- Recommended sections:
  - Introduction
  - Coding systems

#### [Why Use Binary?](https://www.youtube.com/watch?v=thrx3SBEpL8)
- Source: YouTube channel Computerphile
- Watch time: 9 minutes

The smallest unit of data representation in computers is called a bit, it's a 1 digit binary number, in programming languages the data types that store this amount of data are usually called boolean.

The next size of data storage is called a byte, it's an 8 binary digits number, the highest decimal number that can be represented by a single byte is 255.

#### [Where did Bytes Come From?](https://www.youtube.com/watch?v=ixJCo0cyAuA)
- Source: YouTube channel Computerphile
- Watch time: 11 minutes

While we're on the subject of binary, I feel it's worth it to cover the subject of of the operations that a computer can do between numbers.

When we're doing mathematics to do calculate between decimal numbers we use algebra, with binary numbers we use boolean algebra.

#### [Boolean algebra](https://en.wikipedia.org/wiki/Boolean_algebra)
- Source: Wikipedia
- Read time: ~10 minutes
- Recommended sections:
  - Introduction
  - Values
  - Operations

These basic operations logical operations are the building blocks of computer electronic systems, there are electronic components called logic gates that can do these operations.

#### [Logic Gates](https://www.youtube.com/playlist?list=PLzH6n4zXucko1YVRjhnquPaNOfZrymVQH)
- Source: YouTube channel Computerphile
- Videos: Watch the first 3 videos of the playlist
- Watch time: 20 minutes

In the world of computer engineering logic gates are the building blocks of digital electronics, every more complex electronic system is build by combining these logic gates. 

## Hierarchy of electronic systems

Before we look into electronic systems, which are a specific type of system, let's look at the definition of what a system is.

#### [System](https://en.wikipedia.org/wiki/System)
- Source: Wikipedia
- Reading time: ~3 minutes
- Recommended segments:
  - Introduction
  - Information and computer science

An electronic system then is one that is created using electronic components, but why are they created? they are created to solve a specific problem.

More complex problems require more complex systems, and the scale of complexity of these electronic machines are defined by the Chomsky Hierarchy.

Chomsky Hierarchy is a theorem from linguistics that defines the complexity of problems, given a problem that needs to be solved, this Hierarchy tells us how complex this problem is. 

In Computer Science the different machines that can solve each category of these problems is defined in the Automata Theory.

#### [Automata theory](https://en.wikipedia.org/wiki/Automata_theory)
- Source: Wikipedia
- Reading time: ~3 minutes
- Recommended segments:
  - Introduction

The first level of these machines is what you get if you combine logic gates to solve a simple problem like a comparison, you could use a logic gate to turn on a light bulb if two switches are turned on.

The second level of these machines are called Finite State Machines, the following videos explain the types of problems that these machines solve.  

#### [Chomsky Hierarchy levels](https://www.youtube.com/playlist?list=PLzH6n4zXuckpkgSrHX87sDCmEZSumytL3)
- Source: YouTube channel Computerphile
- Videos: Watch the first 2 videos
- Watch time: 16 minutes

Then we'll skip to the fourth level and talk about Turing Machines, they are a way of creating a machine that could have an infinite amount of different states.

#### [Turing Machines Explained](https://www.youtube.com/watch?v=dNRDvLACg5Q)
- Source: YouTube channel Computerphile
- Watch time: 5 minutes

If one of these machines is built in a way that it can solve any kind of problem based on a program, we call it Turing Complete.

#### [Turing Complete](https://www.youtube.com/watch?v=RPQD7-AOjMI)
- Source: YouTube channel Computerphile
- Watch time: 6 minutes

These are the building blocks, we can now look at what modern computers are like and understand each of their parts.

# Chapter 7: Computers

We know what a system is, in essence a computer is a system built to execute computations.

#### [Computer](https://en.wikipedia.org/wiki/Computer)
- Source: Wikipedia
- Read time: ~3 minutes
- Recommended sections:
  - Introduction

This explains what they are in concept but doesn't help us understand how they work, so we have to look deeper. Computers have an internal structure to how they are built and this structure can be found by looking at the Von Neumann architecture.

#### [Von Neumann Architecture](https://en.wikipedia.org/wiki/Von_Neumann_architecture)
- Source: Wikipedia
- Read time: ~5 minutes
- Recommended sections:
  - Introduction

## The parts of a Von Neumann Computer

This model structures a computer into the following parts:

- Processing unit
  - Arithmetic logic unit (ALU)
  - Processor registers
- Control unit
  - Instruction register
  - Program counter
- Memory
- External storage
- Input and output

## Processing unit

The processing unit has two components, those being the ALU and the registers.

### ALU

The ALU is composed of circuits designed to perform the mathematical operations of algebra: addition, subtraction, multiplication and division; and the logical operations of boolean logic: and, or, not, xor, etc...

### Registers

This is where we store the values that we're going to use for these calculations.

## Control unit

The processing unit is divided into an Instruction register and a Program counter.

### Instruction register

This is where the current instruction that the computer will execute is stored.

### Program counter

A program is a set of instructions, since we have multiple instructions to execute the program counter keeps track of where we are in this list of instructions.

## Memory

Our programs are usually too big to be processed all at once, so we store this program into the memory before processing it, and some times we will need to use the results of our computations later so we can also store these results in memory.

## External storage

The computer memory is only used while the computer is turned on, but we need to store our data and programs somewhere, and this is where we store it.

## Input and output

Some programs require outside information to be executed, if we're using a calculator we need to have buttons so that we can press those and tell the calculator what numbers we want to use in our calculation, these are examples of inputs.

In the same way we need a way of showing the result of our calculations to the user, the screen of a calculator is an example of an output.

## Modern Computers

This architecture defines the most basic look on what a computer is and what it has to have to execute a program, but computers evolved and got more complex, most of what this model describes can be found inside a single component of a computer, the CPU.

#### [Inside the CPU](https://www.youtube.com/watch?v=IAkj32VPcUE)
- Source: Youtube channel Computerphile
- Watch time: 11 minutes

This video explains how a computer like this does it's operations, but how does it load the programs from the storage into memory and how does it saves data into memory?

#### [How Computer Memory Works](https://www.youtube.com/playlist?list=PLzH6n4zXuckoxFPyhsMOYMGqyZOeN2SDJ)
- Source: YouTube channel Computerphile
- Videos: 3 (the first video of this playlist was the last of the previous one)
- Watch time: 24 minutes

# Chapter 8: Machine language and compilers (WIP)

The [Inside the CPU](#inside-the-cpu) video talks about how the computer will fetch instructions from it's memory, these instructions are codes that select which feature of the CPU it's going to use now.

#### [Complex instruction set computer](https://en.wikipedia.org/wiki/Complex_instruction_set_computer)


If you look at a modern programming language you'll see a lot of words in english, the words we use in our programming language to write down the instructions are called the syntax of our programming language.

But a processor only understands binary, ones and zeroes, so how do we write instructions using numbers? this is where machine language comes in.


# Chapter 9: Programming logic (WIP)

boolean logic

functions

truth tables

complexity of problems

big o notation

This chapter is going to be your first contact with actual programming, now that you understand the jargon, the theory, the concepts, it's time to go get your hands dirty. 

Here I will give you two options, both learning points are great and I have followed them myself ages ago, you can pick one of them or do both, it's your choice, doing both will give you more practice anyway.

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


# Chapter 10: Applications, systems and the internet (WIP)

Focusing on the development side of applications

TODO: 

#### [Information Theory & Coding](https://www.youtube.com/playlist?list=PLzH6n4zXuckpKAj1_88VS-8Z6yn9zX_P6)
- Source: YouTube channel Computerphile
- Videos: 5
- Watch time: ~49 minutes

This is a playlist that talks about IT and errors during data transmission


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


# Chapter 11: Defining what is Web Development

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
