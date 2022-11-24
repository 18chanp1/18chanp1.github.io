---
layout: post
title: CPEN 2nd year, Part 2
---

### CPEN 212

* Language(s): C, x86-64 assembly

* Tools: gdb, ubc's ssh server, 

* Textbooks: x86-64 Assembly language programming with Ubuntu, Ed Jorgensen (more for the first lab only, no textbooks are required.)

* Professor: Mieszko Lis

#### Verdict:

- Workload: 4/5

- Difficulty: 4/5

- Usefulness: 5/5



This course is the alleged successor to CPEN 211, but it is a course that introduces many fundamental concepts that underlie programs, operating systems, and computers today. While strictly not an operating systems (OS) course, the content overlaps with CPEN 331, an OS course that is part of the CPEN core course requirements. In fact, I sometimes use the slides from CPEN 212 to help me do the assignments for CPEN 331, since Mieszko's slides are so good. 

This course covers topics such as the instruction set architecture abstracton, procedural abstraction and calling conventions, how polymorphism and inherhitance is implemented with dynamic dispatch. A really fun part of the course I enjoyed was the "Haxx" part, where we got to try to hack programs by writing code into the stack.

In the later parts of the course, we move to more topics at a higher level which are required in computing systems. These topics include managing heap and allocating / freeing memory, garbage collection, linking (while compiling programs), virtual memory, process management, files, caching (and strategies), concurrency, and networking. 

I won't expand much into the content covered, since you probably have no idea what they are anyways.

#### Breakdown

1. Labs
   
   These will take up a significant amount of time. I would estimate 4-8 hours per lab, which are due once every 2-3 weeks. The labs are gruelling and a pain to debug and test. Some tests are provided, but they are not exhaustive. However, some of these labs are fun and rewarding, such as the stack manipulation haxx I mentioned above, writing your own memory allocation system, implementing parts of a shell (starting programs, suspending programs, killing programs, etc.), optimizing cache reads, etc. 
   

2. Exams / Midterm
   
   Basically covers the lecture material and lab work. Not a lot of code writing, but mainly tests your conceptual understanding of the material by asking you to go through processes taught in class - e.g. given some memory and some references (depicted with circles and arrows), demonstrate how you would do this garbage collection technique on it. A 1 sided cheat sheet was allowed on the midterm, and 2 sided on the final. The course content 
   
   
   
   I was part of the first batch to take this class, so there were no past midterms / exams to practice with. However, the professor did include a list of very difficult, abstract, and conceptual questions with no solutions. You might wonder how useful this is, but it is a very useful tool for you to gauge your true understanding of the material. Answering the questions made me review the lecture content and helped me do <reasonably> well in the course. 

3. f
