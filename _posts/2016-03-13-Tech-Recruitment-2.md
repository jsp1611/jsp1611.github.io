---
layout: post
title: "What I've learned about tech recruitment: Pt. 2"
published: false
categories: recruitment
tags: recruitment
--- 

Last time I wrote about this, I talked a little about the CV screening process and how it operates. This time I'm going to talk a bit about technical assessments outside of face to face interviews. These can take the form of telephone assessments, online assessments or larger coding assignments. They come in many shapes and sizes, including some of the following:

1. Locate or fix a bug in a supplied code snippet
2. Write a short peice of code to solve some problem
3. Draw the architecture of a system you've worked on
4. Describe a key concept in Computer Science (Deadlocks, Race conditions, Mutexes, CAP theorem, etc.)
5. Implement a small project to model some problem you've been given
6. Describe the inner workings of something you are expected to know, given your CV (JVM internals, language features, library features etc.) 

At this point I have to note something about the difference between the US and the UK market in this regard; in the UK you will rarely get technical questions that ask you to implement a classical data structure or algorithm from scratch, which seems to be something that is quite common in the US. I find this approach puzzling. Asking someone to implement a Heap, or Graph, or some kind of sorting or traversal algorithm, tells you absolutley nothing about them as a programmer other than they are capable of rote memorisation of much of [Introduction To Algorithms](http://www.amazon.com/Introduction-Algorithms-3rd-Edition-Press/dp/0262033844), or a similar text. I've met people who know this material very well who simply aren't very good programmers, so why spend hours assessing it? 

Okay, now that's out of the way, let's talk about what this kind of questioning is trying to determine. 

Horrible histories
------------------

Every experienced developer has horror stories of poor eningeers that they've worked with in the past. I'm going to give a few examples below; names have been changed to protect the guilty. 

1. "Tom" committed a multitude of coding sins, such as: using [broken double checked locking](https://en.wikipedia.org/wiki/Double-checked_locking) wherever he wanted to initialise a static variable in his code, writing dozens of "Utils" classes that had mutable state, putting "Thread.sleep()" calls in single threaded code that consumed from queues, using bizare naming conventions, and constantly violating every Object Oriented principle there is. As if that were not enough, he was unwilling to learn or grow as a developer, actively avoided code reviews, refused to pay attention to coding standards docs, didn't know his toolset, and responded with hostility to anything that looked like constructive criticism. In the face of all the evidence to the contrary, Tom was also convinced that he was brilliant. 
2. "Dick" never wrote unit tests, and wrote sloppy code that ignored the possibilty of failure conditions. It didn't matter how often he seemed to screw up another developers' day by introducing a new bug into the system, or how often he was lectured on good practise by the team lead. Dick just didn't give a shit. 
3. "Harry" was an adventurer. He went off on his own in what I like to call "adventures in coding". He took advantage of lax project oversight and an overly deferential team to do as he pleased. Harry burned a big enough hole in the company budget to cause serious damage and never delivered anything of value. Harry was admittedly smart, and yet at the same time, he also managed to be a complete idiot. 

Senior developers live in dread of the Tom's, Dick's and Harry's of the world. At best they *cause* additional work and have decent developers cleaning up after their messes for months or years on end. At worst they can kill a project or even a small start-up. I've seen it happen. Clearly, if you're a technologist invovled in recruitment, you will want to do your level best to avoid hiring people like Tom, Dick or Harry. so how do you do that? 

Well, you can look for the qualities that Tom, Dick and Harry collectively lack. 

1. Knowledge of your tools.
2. Knowledge of good practise. 
3. Humility. 
4. A growth mindset. 
5. An ability to work well with others. Some call this "being a team player".
6. A genuine interest in their field. I could have used the word "passion" here, but won't for reasons I will explain in another article. 
7. Communication skills. 

