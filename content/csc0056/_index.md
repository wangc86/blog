---
date: "2020-08-14T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: true  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?
math: true

---
![NTNU logo](../../img/ntnu_logo.png)

**Course Name:** CSC0056 Data Communication 資料通訊 <span style="color:red">(Fall 2020)</span>  
**Instructor:** Chao Wang 王超  
**Course Meetings:** Mondays 9:10 - 12:10 in room B102, Gongguan Campus  
**Office Hours:** Wednesdays and Fridays, 8-10am (room 511, Applied Science Building, Gongguan Campus), or [by appointment](mailto:cw@ntnu.edu.tw)  
**Midterm Exam:** Nov 9, Monday 9:10 - 12:10, in class  
**Final Exam:** Jan 11, Monday 9:10 - 12:10, in class  

This course is offered as an _all-English_ course. 此門課程為全英語授課.

## Contents

* [Course Syllabus](#syllabus) <a name="syllabus"></a>
* [Course Schedule](#schedule)
* [Textbooks and Other Resources](#resource)
* [Accessibility](#accessibility)
* [Academic Integrity](#accessibility)
* [Homework Assignment](#hw)

## Course Syllabus

In the 2020 edition of this course, the theme is _messaging in cloud/edge computing systems_.

Data communication is essential for networked computing systems. The objectives of this course are for students to:  

* gain insight into analyzing data communication systems;
* have hands-on experience in systems performance evaluation; and
* engage in recent advances in data communication systems.

In particular, we will

* learn the basics of the queueing model and analysis;
* learn ~~both Google's gRPC framework and~~ the widely-used MQTT communication protocol; and
* learn to study selected research papers.

**Prerequisites:**  
Basic working experience in C, C++, and Linux.

**Grading:**  
* Homework 45% (will count the highest six out of seven assignments) 
* First Exam 20% <a name="schedule"></a>  
* Final Exam 25%  
* Participation 5%  
* Attendance 5%  

## Course Schedule

| \#  | Date | Topic | [Readings](#resource) |
| --- | ---  | --- | --- |
| 1 | Sep 14   | Course Introduction ([slides](lecture01.pdf))  | Sec. 1.1-1.2 |
| 2 | Sep 21   | Layered Network Architecture and The Physical Layer ([slides](lecture02.pdf)) ([note](note1.pdf) regarding convolution and the use of Fourier transform) | Sec. 1.3; 2.1-2.2.2; 2.2.6 |
| 3 | Sep 28   | Error Detection and Correction ([note](note2.pdf)) | Sec. 2.3 |
| 4 | Oct 5   | Hamming Code and Data Retransmissioin Strategies ([slides](lecture04.pdf))([note](lecture04-note.pdf)) | Sec. 2.4-2.4.1 (the note has been updated and merged to the file on the left)|
| 5 | Oct 12   | Queueing Model and Little's Theorem ([note](1012.pdf)) | Sec. 3.1-3.2 |
| 6 | Oct 19   | Markov Chains and The M/M/1 Queueing Systems ([note](1019.pdf)) | Sec. 3.3-3.3.1 and Appendix A |
| 7 | Oct 26   | (continuning the topic of Oct 19) |  |
| 8 | Nov 2   | Applications and The M/M/m Queueing Systems ([note](1102.pdf)) | Sec. 3.4.1 |
| 9 | Nov 9   | **Midterm Exam** ([solution](midterm2020.pdf)) |  |
| 10 | Nov 16   | Introducing Multiaccess Communication ([note](CAN-note.pdf)) | Sec. 4.1; [CAN Specification, Version 2.0](http://esd.cs.ucr.edu/webres/can20.pdf) |
| 11 | Nov 23   | The Aloha System and Its Analysis ([note](1127.pdf))| Sec. 4.2 |
| 12 | Nov 30   | Scheduling Sensor Network Communication | [5][6][7] |
| 13 | Dec 7   | TDMA Scheduling and Broker-Based Data Communication | [5][6][7]; in particular, [5] |
| 14 | Dec 14   | Real-Time Data Communication ([slides](real-time-data-communication.pdf))| [8] |
| 15 | Dec 21   | Real-Time Fault-Tolerant Edge Computing | [9] |
| 16 | Dec 28   | Network Flow Control | Sec. 6.1-6.2.1; 6.3 |
| 17 | Jan 4   | Time Synchronization and Review ([slides](sync.pdf)) | Sec. 6.3 |
| 18 | Jan 11   | **Final Exam** ([solution](final_solution.pdf)) | |

<a name="resource"></a> The readings assignment each week is designed for you to gain some background of the topic _before_ class. Read them and note where you found interesting and/or challenging. Bring your findings to class. We will cover additional materials when needed.

## Textbook and References

**Textbook:**

[1] Bertsekas, Dimitri and Gallager, Robert. _Data networks (2nd edition)_. Prentice Hall, 1992. ISBN 0132009161. ([Read it at NTNU library](http://www.lib.ntnu.edu.tw/holding/doQuickSearch.jsp?newQuery=true&searchtype=t&search=Data+Networks)) ([author's page](http://web.mit.edu/dimitrib/www/datanets.html))

**References:**  

[1] Harchol-Balter, Mor. _Performance modeling and design of computer systems: queueing theory in action._ Cambridge University Press, 2013. ISBN 9781107027503. ([Read it at NTNU library](http://www.lib.ntnu.edu.tw/holding/doQuickSearch.jsp?action=view&param=%2Fsearch*cht%3F%2FtPerformance%2Bmodeling%2Band%2Bdesign%2Bof%2Bcomputing%2Bsystems%2Ftperformance%2Bmodeling%2Band%2Bdesign%2Bof%2Bcomputing%2Bsystems%2F-3%252C0%252C0%252CB%2Fframeset%26FF%3Dtperformance%2Bmodeling%2Band%2Bdesign%2Bof%2Bcomputer%2Bsystems%2Bqueueing%2Btheory%2Bin%2Baction%261%252C1%252C%2Findexsort%3D-))

[2] Kurose, Jim and Ross, Keith. _Computer Networking: A Top-Down Approach (5th edition or newer)_. Pearson, 2010. ISBN 0136079679.

[3] William Feller. _An Introduction to Probability Theory and Its Applications, Volume I (3rd edition)_. Wiley, 1968. ISBN 0471257087.

[4] Chao Wang, Christopher Gill, Chenyang Lu. _Adaptive Data Replication in Real-Time Reliable Edge Computing for Internet of Things._ 2020 IEEE/ACM International Conference on Internet-of-Things Design and Implementation (IoTDI), 2020. ([pdf](https://wangc86.github.io/publication/iotdi20/iotdi20.pdf))

[5] Chao Wang, Kuo-Feng Ssu. _A Distributed Collision-Free Low-Latency Link Scheduling Scheme in Wireless Sensor Networks_ 2010 IEEE Wireless Communication and Networking Conference, 2010. ([pdf](https://wangc86.github.io/publication/wcnc10/wcnc10.pdf))

[6] Luby, Michael. "A simple parallel algorithm for the maximal independent set problem." SIAM journal on computing 15.4 (1986): 1036-1053. ([on Google Scholar](https://scholar.google.com/scholar?hl=zh-TW&as_sdt=0%2C5&q=A+simple+parallel+algorithm+for+the+maximal+independent+set+problem&btnG=))

[7] Ramanathan, Subramanian, and Errol L. Lloyd. "Scheduling algorithms for multihop radio networks." IEEE/ACM Transactions on networking 1.2 (1993): 166-177. ([on IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/222924))

[8] Chao Wang, Christopher Gill, and Chenyang Lu. 2019. _Real-Time Middleware for Cyber-Physical Event Processing._ ACM Trans. Cyber-Phys. Syst. 3, 3, Article 29 (October 2019), 25 pages. DOI:https://doi.org/10.1145/3218816 ([link](https://dl.acm.org/doi/10.1145/3218816))

[9] Chao Wang, Christopher Gill, and Chenyang Lu, _FRAME: Fault Tolerant and Real-Time Messaging for Edge Computing,_ 2019 IEEE 39th International Conference on Distributed Computing Systems (ICDCS), Dallas, TX, USA, 2019, pp. 976-985, doi: 10.1109/ICDCS.2019.00101. ([link](https://ieeexplore.ieee.org/abstract/document/8884849))

<a name="accessibility"></a>

## Accessibility
<a name="integrity"></a>

Students in need are encouraged to bring considerations to the instructor. 

## Academic Integrity

All homework assignments and exams must be completed individually and independently, except as specifically allowed by the instructor. 

<a name="hw"></a>
Academic integrity is a key component of your education, which is for your benefit. Anyone found to be cheating or helping someone else cheat will receive zero score for that homework/exam. Please reflect on the university's [motto](http://archives.lib.ntnu.edu.tw/c2/c2_1.jsp): Sincerity 誠, Integrity 正, Diligence 勤, Simplicity 樸.

## Homework Assignment 

Students should submit all their homework assignments via [Moodle](https://moodle.ntnu.edu.tw/).

* [Homework1](https://github.com/wangc86/csc0056/blob/master/Homework1.md), due on Oct 5th, 9AM.
* [Homework2](https://github.com/wangc86/csc0056), due on Oct 26th, 9AM. ([solution](hw2_solution.pdf))
* [Homework3](https://github.com/wangc86/csc0056); Part 1 is due on Nov 6th, 9PM (Friday) and Part 2 is due on Nov 12th, 9PM (Thursday). ([solution for part 1](hw3_solution_part1.pdf))
* [Homework4](https://github.com/wangc86/csc0056); due on Dec 12th, 9PM. ([solution](hw4_solution.pdf))
* [Homework5](https://github.com/wangc86/csc0056); due on Dec 28th, 9PM. ([solution](hw5_solution.pdf))
* [Homework6](https://github.com/wangc86/csc0056); due on Jan 8th, 9PM. ([solution](hw6_solution.pdf))
* [Homework7 (bonus)](https://github.com/wangc86/csc0056); due on Jan 15th, 9PM. ([solution](hw7_solution.pdf))
