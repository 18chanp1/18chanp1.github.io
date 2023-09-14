---
layout: post
title: CPEN 2nd year, Part 2
short: Less hell, for now
---

# CPEN 212, 291; ELEC 201; CPSC 221 Review

## CPEN 212

* Language(s): C, x86-64 assembly

* Tools: gdb, ubc's ssh server, 

* Textbooks: x86-64 Assembly language programming with Ubuntu, Ed Jorgensen (more for the first lab only, no textbooks are required.)

* Professor: Mieszko Lis

### Verdict:

- Workload: 4/5

- Difficulty: 4/5

- Usefulness: 5/5

This course is the alleged successor to CPEN 211, but it is a course that introduces many fundamental concepts that underlie programs, operating systems, and computers today. While strictly not an operating systems (OS) course, the content overlaps with CPEN 331, an OS course that is part of the CPEN core course requirements. In fact, I sometimes use the slides from CPEN 212 to help me do the assignments for CPEN 331, since Mieszko's slides are so good. 

This course covers topics such as the instruction set architecture abstraction, procedural abstraction and calling conventions, how polymorphism and inheritance is implemented with dynamic dispatch. A really fun part of the course I enjoyed was the "Haxx" part, where we got to try to hack programs by writing code into the stack.

In the later parts of the course, we move to more topics at a higher level which are required in computing systems. These topics include managing heap and allocating / freeing memory, garbage collection, linking (while compiling programs), virtual memory, process management, files, caching (and strategies), concurrency, and networking. 

I won't expand much into the content covered, since you probably have no idea what they are anyways.

### Breakdown

1. Labs
   
   These will take up a significant amount of time. I would estimate 4-8 hours per lab, which are due once every 2-3 weeks. The labs are grueling and a pain to debug and test. Some tests are provided, but they are not exhaustive. However, some of these labs are fun and rewarding, such as the stack manipulation haxx I mentioned above, writing your own memory allocation system, implementing parts of a shell (starting programs, suspending programs, killing programs, etc.), optimizing cache reads, etc. 

2. Exams / Midterm
   
   Basically covers the lecture material and lab work. Not a lot of code writing, but mainly tests your conceptual understanding of the material by asking you to go through processes taught in class - e.g. given some memory and some references (depicted with circles and arrows), demonstrate how you would do this garbage collection technique on it. A 1 sided cheat sheet was allowed on the midterm, and 2 sided on the final. The midterms and finals were more than reasonable, which is frankly quite rare for an ECE course. 
   
   I was part of the first batch to take this class, so there were no past midterms / exams to practice with. However, the professor did include a list of very difficult, abstract, and conceptual questions with no solutions. You might wonder how useful this is, but it is a very useful tool for you to gauge your true understanding of the material. Answering the questions made me review the lecture content and helped me do <reasonably> well in the course. 

### Course experience

This course is actually one of the reasonable courses by ECE standards, where the labs, midterms, and finals are all reasonably doable in the given time. It strikes a good balance between being easy, while separating those that put the effort in. The professor teaches you how to do things (i.e. for labs), unlike CPEN 221 where you get pushed into a swimming pool without knowing how to swim. However, the professor does not hold your hand too much either, which is good for learning. The content covered is well within grasp for a second-year CPEN student. I would argue this would be one of the most useful courses in computing systems along with CPEN 221 for software development. 

### My recommendations

Start working on the labs early, as is my advice for all assignments in general. This is especially true for this course, since you will heavily rely on ECE SSH servers unless you have your own VM. These ECE servers have a tendency to slow down or crash the day before the deadline, so start early. 

If the professor publishes the list of conceptual questions for the midterm and final again, do them. They are very useful.

Most importantly, have fun with the assignments, midterms and exams! The professor has an interesting sense of humor and this reflects in the final. One of the bonus questions included "write a sonnet" or "name all the TAs". The labs are also incredibly rewarding when you get them done. This makes spending hours on the lab *slightly* more manageable. 

## CPEN 291

Tools: 2nd year parts and tools kit, $40 CPEN 291 project kit

Languages: Python, HTML/CSS, JavaScript

Tools: Conda, Pytorch, Vue/Django/Node.js/Flask (you can choose whatever tools you wish, but here are some JS frameworks we personally used.)

Textbook: None

Professor: Farshid Agharebparast

### Verdict:

- Workload: 2/5

- Difficulty: 2/5

- Usefulness: 3/5

CPEN 291 is a standard second year project course. I would essentially describe it as APSC 100/101 with less fluff and more *practical* work. The class actually varies significantly between professors and what they choose to focus on, so beware.

In the first part of the course, there will be a series of lectures and some labs to help familiarize yourself with the tools that you will use for later projects in the course. The labs are relatively simple and easy to finish, and are basically APSC 160 level (print some pyramids). Some later labs introduce you web development (HTML/CSS), and machine learning (pytorch).

In the later parts of the course, you will work with a team that you choose on projects related to what you have learned in the first part. For our session, we had 2 projects. For the first project, we constructed a dancing robot using some 3d printed parts in the  project kit, some servos, the itsy bitsy microcontroller, keypad to select moves, and LCD to display some relevant images. The second project was up for us to pick, but we had to cover 2 of the 3selected topics (Machine learning, web development, hardware). Our team chose to implement a web app controlled robot (to save time), but many other groups had impressive ideas, such as a find-four playing machine.

### Breakdown

1. Labs
   
   Labs just familiarize you with the content from lectures and ensure you are reasonably proficient at the skills you need for the projects later. They are mostly basic python, HTML/CSS/JS, pytorch skills. Relatively easy and quick to complete, and happen once a week for ~four weeks

2. Class quizzes
   
   Happens in the once a week class. 3 attempts, due 24 hours later, based on lecture content. Relatively simple if you at least go through the slides for lecture. 

3. Projects
   
   The meat of the course. You will work with a team to create some deliverable. The first one involves building a dancing robot and the second one is up to you. In addition to the deliverable, you will also have to submit a report documenting your design process. This includes plans, wiring diagrams, code, and design considerations (e.g. what did you consider implementing but did not do so?). In addition, you will also have to demonstrate your deliverable to the professor, showing the professor the dance moves. You will also have to give a presentation to the class describing your project briefly (5-8 minutes). Finally, your code will be evaluated to ensure it follows the spec, such as no use of external libraries for some parts. 



### Course Experience

This course is relatively straightforward and easy. It is not difficult to do well in this course at all as long as you follow the instructions / slides that are given to you. The average for this course is also relatively high. The workload for this course is actually not too heavy as long as you spread out your work and you have a team that pulls their wait. The workload is definitely less than some other courses that have less credits (e.g. cpen212). You can obviously go the extra mile with the flexibility offered in the projects, but it is not necessary to do reasonably well.

### My recommendations

Find a good team that will pull their weight and start early. Otherwise, you may find yourself doing the whole project by yourself. Otherwise, this course is easy enough that you do not need my "good luck" or other tips.



## ELEC 201

Language: Multivariable calculus, voltages and currents

Tools: 2nd year parts kit, Calculator, laptop, pen, and paper

Textbook: None

Professor: Alireza Nojeh

### Verdict:

- Workload: 2/5

- Difficulty: 4/5

- Usefulness: 2/5

ELEC 201 is a course that will introduce you to circuits and ways to analyze circuits. I would basically describe this course as "MATH 256 in an electrical engineering context" in the same way MATH 152 was to PHYS 170. In fact, sometimes MATH 256 uses the *way simpler* versions of the ELEC 201 circuits.

In this course, you will essentially dive into more depth regarding the Kirchhoff Voltage Law (KVL) and Kirchhoff Current Law (KCL) and how they can be applied to circuit elements like wires, voltage/current sources, inductors/capacitors, diodes, and transistors. You will see how we describe how these circuit elements change with times with differential calculus techniques, and how you can also use KVL/KCL to solve equations with time-dependent elements. 

In the later parts of the course, you will take a look at advanced techniques to save you time, such as mesh and nodal analysis, and generalizing circuits to standard equivalents (Thevenin and Norton).

Finally, you will take a look at some advanced circuit elements, such as diodes, op-amps, and transistors and how you can solve circuits with those elements. 

### Breakdown

1. Labs
   
   As a one time measure, labs were not assigned any grade weight, and we could choose to attend them online or in person. While there was no weight, the professor said some content from the lab could be testable (not true). Essentially doing problems but with real life components on a breadboard and measuring it with a multimeter instead of answering questions on webwork

2. Webwork homework
   
   Once a week, related to the lectures. Takes some time to do but they are not too difficult. If you watch the lectures it should be relatively straightforward using the techniques taught. Very similar to the midterm and exam questions, so serves as pretty good practice

3. Midterm
   
   Essentially the same webwork problems, but with hard to predict difficulty. The midterms were generally reasonable in that you could complete them within the set time limit, and they were reasonably challenging and doable in the time. We had 2 midterms, where one had a lower average, so the second midterm was set way to easily with the average being too high. I missed a question on the first midterm because I spent too long "debugging" a mistake which happened because I accidentally put in some wrong numbers in a calculator. (see calculator section) This is not a good sign, contrary to popular belief. The questions are done on webwork, and while there are partial marks if you get parts of the questions right, there are no working marks for effort. You can also submit an infinite amount of times to see if you have the correct answer. 

4. Final
   
   Basically the same as the midterm. The difficulty was extreme and the average of the final was 15%. The professor set the exam in an attempt to lower the average of the class to historic levels, but it was just disheartening for many students who were unable to complete the problems (you could see that you got the answers wrong). The pass exam to pass final requirement (which was waived or no one would have passed) was also highly stressful for most of the people in my class. 

### Course Experience

I personally did not enjoy the class at all. Firstly, there were lecture videos to watch before class, and these were often long and boring. The professor often describes concepts in a very theoretical manner that I believe is not beneficial for our learning (or for solving problems). In fact, I find that watching the videos labelled "tutorial" are often more useful as he actually goes through ways of how to solve the problems. 

The professor also had a once a week class where he asks some conceptual questions and demonstrates the answers to them. While useful for understanding the concepts, these demos are not very useful for the midterm or final. 

Finally, the final and its difficulty just made my blood boil and I almost started swearing during the final. Ideally, one should set the assessments such that they can be solved within the timeframe if you understand the concepts and have some practice. However, when you exam is unpassable even by one of the smartest students in the cohort, then there is something seriously wrong with the exam. 

### My recommendations

I would recommend obtaining a fancy graphing calculator (e.g. TI-Nspire), preferably one that can solve systems of differential equations. Since the exams are open book, you can also use wolfram alpha or other calculator sources. The calculator is really important because it can really save you time when calculating various values for the circuits. 

The webwork homework problems and practice questions are also really good resources for practicing for exams.

Finally, I wish you good luck, since if you get an exam where everyone fails it, there is not much you can do to prepare for the exam. All I can say is don't give up until the last minute. You can hopefully still score some part marks. 

## CPSC 221

Language: C++

Tools: VSCode / CLion (your editor of choice)

Textbook: None?

Professor: Geoffrey Tien

### Verdict:

- Workload: 3/5

- Difficulty: 3/5

- Usefulness: 4/5

Design and analysis of basic algorithms and data structures; algorithm 
analysis methods, searching and sorting algorithms, basic data 
structures, graphs and concurrency. 

The course description gives a reasonably good description of the course. We begin with a review of runtimes, followed by some sroting algorithms. We then move on to data structures their runtimes, including linked lists, stack, queues, along with a review of pointers in C++. We once again revisit the land of sorts with mergesort and the limits on sorting. Moving forward, we take a look at trees as a data structure and their runtimes, and ways we can make them better, by balancing them and turning them into AVL trees, or storing many keys in them so they are memory block sized (b-trees). We stray a little into hashes and collisions, before returning to data structures such as priority queues, disjoint sets. We end the term on graphs and ways of going through the graphs (some of which you will be familiar, because CPEN 221. Told you it'd be useful).

This course will be useful, in addition to CPSC 320 for grinding leetcode questions for your interviews. IMO, this course should be before CPEN 221, and would make some of those PPT questions actually doable. 

### Breakdown

1. Homework assignments
   
   They are essentially more theoretical, long-form assignments that expand on what you have learned. Think of them as theoretical extensions of the course material to help you really understand the concepts, but don't have enough time to discuss in class. Can be done in partners. Takes a decent amount of time to do, so start early.

2. Programming Assignments
   
   Essentially applying what you learn in class in a more practical sense than the homework assignments. For example, you would manipulate an image which is actually a linked list, or use a breadth first search to change pixels in an image. It can be kind of fun, but also takes some time to do. You can submit on prairielearn to run the test cases on them, and you have unlimited attempts (subject to the fact that if everyone is trying to submit, it will take a while to run your submission). The test cases are not very descriptive but I do not believe they are hidden from you. 

3. Labs
   
   Essentially graded with a trivial amount of test cases and relatively easy. I took slightly longer than the assigned lab time to finish them, but you have a week and the instructions are given ahead of time (and solutions during the lab), so this is relatively straightforward.

4. Examlets
   
   Essentially low-stake 5% quizzes that test you on the content for that week, and occur every week in class. I personally did not like this style of asssessment as I spended more time preparing for the examlets than I would for a midterm or final, but it was nice not having to stress about reviewing the midterm or the final. You will do them on your laptop, but they are not open book. There are also sometimes "coding" questions that show up once every two weeks (they do not tell you when), that are essentially rehashed versions of the labs. You can also book these sessions to be done during lecture or in a computer room at selected timeslots. 

5. Final
   
   Similar to examlets, but longer, and worth approximately 10-20% instead of 5%. Covers all content. You can book your selected time to take the examlet, which I really liked. 

### Course Experience

In general CPSC courses are run so much better than CPEN courses that taking this course will make you wonder why you did not switch to CPSC. CPSC courses hold you hand and teach you everything you will need to know for assignments and exams. In addition, your exposure to concepts and software development in CPEN 221 will help you go through this course easily. However, do not let your guard down, because you still need to practice for the examlets and learn the material (CPEN 221 is not a free pass).

Overall very reasonable and well run course. Do not worry about this course. You can worry about other courses you are taking. 

### My recommendations

Other than being a good student (going to lecture, do your homework), the only pieces of advice I can give you are:

1. Start the programming assignments early to avoid the crowd on prairielearn. Find a good partner to save time (I did them myself, so it is technically possible unlike CPEN 211)

2. Do the practice examlets, they are very similar in style to the actual examlets (sometimes even the same questions)

3. The course starts off easy, so do not let your guard down so fast. Stay vigilant as the difficulty will go up. 
