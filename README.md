Last updated 07 January, 2024

### CIS279L -- Linux+
Winter 2024  
CRN: 28084  
Credits: 4  
Instructor: Joseph Jess  
email: <jessj@linnbenton.edu>

**Initial class note**: We are **_not_** in an introduction course to computer science (CS), though that does not mean most of the materials will be difficult.  We will have an intro to various Linux operationg system concepts, utilities, applications, and some of the code that goes with it all.  We assume that we have some operating systems experience and some knowledge of networking, though we do not go too deeply into the networking side of things beyond basic configuration of networking.  We will expand on many of the concepts covered in an introductory Linux course, going into greater detail in several areas and introducing several supporting technologies that are a bit tricky for new Linux users (we will at least expose you all to some of the topics, since they are often covered in a Comp TIA Linux+ or LPIC certification exam).  We need to expect to do a good bit of reading, much practicing, and much discussion of the topics we cover in the class.

---

### 1. LBCC catalog course description, including pre-requisites/co-requisites:

Follows the CompTIA Linux+ exam outcomes and competencies. Covers the fundamentals of Linux technology, all areas of the Linux infrastructure, and the use of vendor products and software. Addresses the skills needed to work as a Linux administrator, a network technician, in network support, and more.

**Prerequisites**: CS 140U and CIS 151 with a grade of C or better.
---

### 2. Class Time-space:
1. **Note**: This class is delivered in a flexible format (you will not need to attend live sessions).
2. **Lecture + demo + lab**: MW 1200 -- 1350, flexible, see Moodle for details

---

### 3. Measurable student learning outcomes:

On completion of this course, students will be able to:
1. Install, maintain, upgrade and administer from the command line an advanced linux server with network-management applications.  
2. Configure and maintain appropriate security for user accounts and server network management applications.  
3. Research an advanced topic in Linux network management and make a presentation to the class.


---

### 4. Notes about the approach to learning which we'll use in CIS279:

- Our approach in CIS279 will be "All Lab, All The Time" (with plenty of discussion, and "mini-lectures" inserted where appropriate).
- For this approach to work, we must all commit ourselves to it. This means, for example:  
  -- Preparing thoroughly for our class sessions (mostly this will be a bit of searching on a topic and bringing what you find to class for discussion).
  -- Attending and fully participating in all our class sessions (mostly this will involve attempting to set up some system or solve some problems in class).
  -- Taking responsibility for one's own work, while maintaining a cooperative attitude (mostly this will involve participating in solving problems in class, making sure to write a weekly report, and being willing to make mistakes and learn from them).  
  -- Carefully note: that all the software used in this course may be installed on students' home machines for their own noncommercial use. Students are strongly encouraged to install this software on their home computers, and learn by experimenting with it there. This is particularly helpful as a preparation (not a substitute) for our in-class lab work.  Suggestions for installing software will be discussed in class.
    --- _Note, however, that neither the instructor nor LBCC can be responsible for possible loss of data or other inconvenience which may result from students' experimenting with their own computers at home. This caution applies even if the advice given to students turns out to be wrong.  Sorry!  One way to eliminate or reduce accidental data loss is to do so in a constructed environment, such as a virtual machine or container of some sort._

---

### 5. Learning resources:

1. **Note**: All class materials and storage will be freely available in a digital format,  
2. (**recommended**) Access to a computer outside of class to practice and work on assignments,  
3. A text editor.  We could use a smart IDE such as VS Code to do this work as well!  
4. We will discuss some capabilities of smart code editors during the course, 
5. (**strongly recommended**) A desire to learn, experiment, design, test, and problem solve with code (both on and off of a computer).

---

### 6. Grading:

1. Scores for assignments will be available when the instructor gets to it... usually within a week of the due date. Grades and feedback will be made available through Moodle.  
2. Students will be required to turn in all coursework items before 23:59 (Pacific Time Zone) on the date that they are due (generally the first meeting day of the week in my courses)\... though I have an extremely forgiving option for making up for missed work at the end of the term with the final project.  
3. To earn a passing grade in this course you must pass each of the following coursework categories:  
    1. **Demonstration**: Discussion, quizzes, and weekly assignments and projects -- 50%  
        1. A weekly report on a hands-on project (such as VM or container setup, scripting, design, or writing tests for some programmed, network, or system solution to a problem), which will have a number of specific requirements (such as, use if statements and loops to…, create a container that…, describe what function X does, design a program that does Y without coding any of it, write a script that tests whether another function returns a specific result Z when given inputs A, B, and C),. Projects are generally graded roughly based on the following rubric:  
          1. **What went well**,  
          2. **What went poorly**,  
          3. **What was easy**,  
          4. **What was difficult**,  
          5. **Comments and Documentation**,  
    2. **Final project artifact**: Final project design and final project implementation -- 50%
        1. A final project artifact, which will have a number of specific requirements, this is some artifact that could be a presentation aid, or a presentation of the project.
        
> **Note**: Your submission should be explained and able to be compiled and run from just your submitted files in your final submission for that project. This means that you need to include any files provided to you that are necessary for your project to compile or run, especially mentioning how we get ahold of the version of any third-party libraries that you might link to!
>
> **Note** **well**: Source code and related documents submitted must be designed and implemented by the student submitting the work and any code must compile and run on one of the instructor\'s machines in order to be graded (to create a working program quickly: get it working simply, then add to it; if at some point it stops compiling you will better know where an error was introduced).
>
> **This means that while you can use tools like tutoring, [Stackoverflow](https://stackoverflow.com/), or AI systems to help you learn how to write code, documentation, tests, and designs from various sources, you need to cite that you got help from outside sources (we all keep tabs open to various resources on the web!), and you need to understand what you create and make any code your own.**

4. **Make-up Work**: I do not care when you learn it, as long as you learn it. To support this idea I allow missing work, even after the term for many, to be made up for in the final project (just be sure I know you are trying to make it up in the final project submission!).

5. **Final grades** will be given out based on the following based on score in the class:\
    90-100%: A  
    80-89%: B  
    70-79%: C  
    60-69%: D  
    00-59%: F  

6. **Reminder**: A passing grade in order to count for course requirements for CS classes is generally a C or above.

---

### 6. Other Administrative Information:

For a list of general administration information (note that this list is not intended to be exhaustive), such as:
1. contacting me (Discord, in-person, or email),
2. accessibility resources,
3. expectations of student conduct,
4. communications,
5. student assistance,
6. miscellany,
7. nondiscrimination & nonharrasment (don't be a jerk to anybody even if you think they deserve it),

(each section contains a number of sub-sections and is not meant to be exhaustive of all situations)  
see my [*Additional Administrative Information*](https://docs.google.com/document/d/1NTerBXVow4rFbZGEpWJKpkpA9DpyOSAfjzJ4FKhf0FU/ "Additional Administrative Information (Google Doc)" ).

Changelog:
1. 07 January, 2024, v1.0.0: initial release, manually cloned and edited from [my CS290 winter 2024 GH repo](https://github.com/Joseph-I-Jess/cs290_winter_2024)
