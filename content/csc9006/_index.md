---
title: CSC9006 Real-Time Systems (Spring 2021)
#summary: Here we describe how to add a page to your site.
date: "2021-02-02T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: true  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?
math: true

# Optional header image (relative to `static/img/` folder).
#header:
#  caption: ""
#  image: ""

---

![NTNU logo](../../img/ntnu_logo.png)

**Course Name:** CSC9006 Real-Time Systems 即時系統 <span style="color:red">(Spring 2021)</span>  
**Instructor:** Chao Wang 王超  
**Teaching Assistant:** Cheng-You Lin 林政佑  
**Course Meetings:** Thursdays 9:10-12:10 @ room S406, Gongguan Campus  
**Office Hours:** Tuesdays and Fridays, 8-10am  @ room 511, Applied Science Building, Gongguan Campus; or [by appointment](mailto:cw@ntnu.edu.tw)  

This course is offered in _English_ (with Mandarin support). 此課程為英語授課 (配合中文輔助).

## Contents

* [Course Syllabus](#syllabus) <a name="syllabus"></a>
* [Course Schedule](#schedule)
* [Textbooks and Resources](#resource)
* [Accessibility](#accessibility)
* [Academic Integrity](#accessibility)

## Course Syllabus
Real-time systems are computing systems engineered for the real world.
From self-driving cars to Internet-of-Things (IoT) systems,
a hallmark of real-time systems is that they must interact with
the world outside of the computer
in a _timely_, _dependable_, and _efficient_ way.
In this course,
we will study both the theory and practice of
real-time systems.

This semester we will take a new approach.
We will stress on a comprehensive understanding
of real-time systems, while having some in-depth study
for selected topics.
Overall, the course is structured into four modules:
* From operating systems to real-time systems <span style="color:brown">(Weeks 1--4)</span>
* Real-time models <span style="color:green">(Weeks 5--8)</span>
* Timeliness and dependability <span style="color:blue">(Weeks 9--12)</span>
* System design and validation <span style="color:red">(Weeks 13--16)</span>

Following the school policy, in weeks 17 and 18
we will look at some additional topics,
in the hope to prepare students for further study
in this fascinating field.

**Prerequisites:**  
This is an advanced course for students
who are familiar with operating systems concepts
and are comfortable to C/C++ and Linux.

**Grading:**  
* Hands-On Assignment 60%  
* Literature Study and Critique 30%<a name="schedule"></a>  
* Participation 5%  
* Attendance 5%  

## Course Schedule
The weekly reading assignment is designed for
students to study both _before_ and _after_ each lecture.
Each week we will discuss some topics from the reading assignment
and will cover some additional materials.
For homework assignments and critiques,
students should submit all their work via [Moodle](https://moodle.ntnu.edu.tw/).

| Date | Topic | Homework | Reading | 
| ---  | --- | --- | --- |
| Feb 25 | <span style="color:brown">The Real-Time Environment</span> ([note1](https://github.com/wangc86/csc9006/blob/master/lecture00.pdf); [note2](https://github.com/wangc86/csc9006/blob/master/lecture01.pdf)) | [Homework 0](https://github.com/wangc86/csc9006/blob/master/hw0.pdf) | [A] Chapter 1 | 
| Mar 04 | <span style="color:brown">Real-Time Operating Systems</span> ([note](https://github.com/wangc86/csc9006/blob/master/lecture02.pdf)) | [Homework 1](https://github.com/wangc86/csc9006/blob/master/hw1.pdf) | [A] Chapter 9 | 
| Mar 11 | <span style="color:brown">Real-Time Scheduling (1)</span> ([slides/notes](https://github.com/wangc86/csc9006))| | [A] Chapter 10 | 
| Mar 18 | <span style="color:brown">Real-Time Scheduling (2)</span> | Homework 2 | [A] Chapter 10 |
| Mar 25 | <span style="color:green">Simplicity and The Notion of Time</span> | Critique 1 Due | [A] Chapters 2 and 3 |
| Apr 01 | (spring break) | Homework 3 |  |
| Apr 08 | <span style="color:green">Real-Time Model</span> |  | [A] Chapter 4 |
| Apr 15 | <span style="color:green">Temporal Relations</span> | Homework 4 | [A] Chapter 5 |
| Apr 22 | <span style="color:blue">Dependability</span> | | [A] Chapter 6 |
| Apr 29 | <span style="color:blue">Real-Time Communication</span> | Homework 5 | [A] Chapter 7 |
| May 06 | <span style="color:blue">Patterns for Building Real-Time Software</span> | Critique 2 Due | [12] [13] |
| May 13 | <span style="color:blue">Fault-Tolerant Real-Time Edge Computing</span> | Homework 6 | [6] [9] [10]|
| May 20 | <span style="color:red">System Design</span> | | [A] Chapter 11 |
| May 27 | <span style="color:red">Validation</span> | Homework 7 | [A] Chapter 12; [11] |
| Jun 03 | <span style="color:red">Internet of Things</span> | Critique 3 Due | [A] Chapter 13 |
| Jun 10 | <span style="color:red">The Time-Triggered Archtecture</span> | Homework 8 | [A] Chapter 14 <a name="resource"></a>|
| Jun 17 | <span style="color:black">(Workshop)</span> |  |  |
| Jul 24 | <span style="color:black">(Workshop)</span> |  |  |

## Textbooks and References

[A] Kopetz, Hermann. _Real-Time Systems: Design Principles for Distributed Embedded Applications_. Springer; 2nd ed. 2011 edition. ISBN 978-1441982360. ([Google Books preview](https://books.google.com.tw/books?hl=zh-TW&lr=&id=oJZsvEawlAMC&oi=fnd&pg=PR3&dq=Real-Time+Systems:+Design+Principles+for+Distributed+Embedded+Applications&ots=nMrNn5LB9z&sig=kBRT4x6xnRBh8e-jTTGcC4VCI_k&redir_esc=y#v=onepage&q=Real-Time%20Systems%3A%20Design%20Principles%20for%20Distributed%20Embedded%20Applications&f=false); [Publisher webpage](https://www.springer.com/gp/book/9781441982360))

[B] Buttazzo, Giorgio C. _Hard Real-Time Computing Systems: Predictable Scheduling Algorithms and Applications_ Springer; 3rd ed. 2011 edition. ([Publisher webpage](https://www.springer.com/gp/book/9781461406754))

[1] [Real-Time Linux Wiki](https://rt.wiki.kernel.org/index.php/Frequently_Asked_Questions)

[2] [The TAO Real-Time Middleware](http://www.dre.vanderbilt.edu/~schmidt/TAO.html)

[3] [Pthreads tutorial](https://randu.org/tutorials/threads/)

[4] [Pthreads example code](https://resources.oreilly.com/examples/9781565921153/)

[5] T. Harrison, D. Levine, and D.C. Schmidt, _The Design and Performance of a Real-time CORBA Event Service_, ACM Conference on Object-Oriented Programming, Systems, Languages, and Applications, October 1997. 

[6] C. Wang, C. Gill and C. Lu, _Real-Time Middleware for Cyber-Physical Event Processing_, ACM Transactions on Cyber-Physical Systems, Special Issue on Real-Time Aspects in Cyber-Physical Systems, 3(3), Article 29, August 2019.

[7] Y. Zhang, C. Lu, C. Gill, P. Lardieri and G. Thaker, _Middleware Support for Aperiodic Tasks in Distributed Real-Time Systems_, IEEE Real-Time and Embedded Technology and Applications Symposium (RTAS'07), April 2007.

[8] C. Lu, A. Saifullah, B. Li, M. Sha, H. Gonzalez, D. Gunatilaka, C. Wu, L. Nie and Y. Chen, _Real-Time Wireless Sensor-Actuator Networks for Industrial Cyber-Physical Systems_, Special Issue on Industrial Cyber-Physical Systems, Proceedings of the IEEE, 104(5): 1013-1024, May 2016. 

[9] C. Wang, C. Gill, and C. Lu, _FRAME: Fault Tolerant and Real-Time Messaging for Edge Computing_, IEEE 39th International Conference on Distributed Computing Systems (ICDCS), 2019, pp. 976-985
<a name="accessibility"></a>

[10] C. Wang, C. Gill, C. Lu. _Adaptive Data Replication in Real-Time Reliable Edge Computing for Internet of Things._ 2020 IEEE/ACM International Conference on Internet-of-Things Design and Implementation (IoTDI), 2020. ([pdf](https://wangc86.github.io/publication/iotdi20/iotdi20.pdf))

[11] D. Seto, B. Krogh, L. Sha, and A. Chutinan. (1998, June). _The Simplex Architecture for Safe Online Control System Upgrades_. In Proceedings of the 1998 American Control Conference. ACC (IEEE Cat. No. 98CH36207) (Vol. 6, pp. 3504-3508). IEEE.

[12] [A quick introduction to callback functions](https://developer.mozilla.org/en-US/docs/Glossary/Callback_function).

[13] [An introduction to TAO's asynchronous messagee handling](https://objectcomputing.com/resources/publications/mnb/an-introduction-to-taos-asynchronous-message-handling).

[14] R. I. Davis .(2014). _A Review of Fixed Priority and EDF Scheduling for Hard Real-Time Uniprocessor Systems_. ACM SIGBED Review, 11(1), 8-19.

[15] R. I. Davis and A. Burns. (2011). _A Survey of Hard Real-Time Scheduling for Multiprocessor Systems_. ACM Computing Surveys (CSUR), 43(4), 1-44.

[16] [What really happened on Mars?](https://www.cs.unc.edu/~anderson/teach/comp790/papers/mars_pathfinder_long_version.html) by Glenn E. Reeves.

[17] Liu, C. L., & Layland, J. W. (1973). Scheduling algorithms for multiprogramming in a hard-real-time environment. Journal of the ACM (JACM), 20(1), 46-61.

[18] Keshav, S. (2007). How to read a paper. ACM SIGCOMM Computer Communication Review, 37(3), 83-84.

**In most cases, you can find a PDF copy of each referenced paper via [Google Scholar](https://scholar.google.com/). Access them from the NTNU network for the campus authorization.**

## Accessibility
<a name="integrity"></a>
Students in need please contact the instructor.

## Academic Integrity
Both homework assignments and
literature critiques are designed to be done individually.
Please reflect on the university's [motto](http://archives.lib.ntnu.edu.tw/c2/c2_1.jsp): Sincerity, Integrity, Diligence, Simplicity. Anyone found to be cheating or helping someone else cheat will receive zero score for that assignment.


