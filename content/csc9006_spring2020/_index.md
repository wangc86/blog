---
title: CSC9006 Real-Time Systems 即時系統 (Spring 2020)
#summary: Here we describe how to add a page to your site.
date: "2020-01-06T00:00:00Z"

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

![NTNU logo](../img/ntnu_logo.png)

<span style="color:red">Note: This page is for the past semester. For historical data, see the [archives](https://web.ntnu.edu.tw/~cw/shares/courses/).</span>

**課程名稱:** CSC9006 Real-Time Systems 即時系統 <span style="color:red">(Spring 2020)</span>  
**授課教師:** [王超](../../#people)  
**課程網頁:** https://wangc86.github.io/csc9006  
**上課時間:** 每週四 9:10-12:10 in room S403, 公館校區  
**Office Hours:** 每週二週三 9:10 - 11:10, in room 511, 公館校區應用科學大樓, or [by appointment](mailto:cw@ntnu.edu.tw)  

## Contents

* [Course Syllabus](#syllabus) <a name="syllabus"></a>
* [Course Schedule](#schedule)
* [Textbooks and Other Resources](#resource)
* [Accessibility](#accessibility)
* [Academic Integrity](#accessibility)
* [Homework Assignment](#hw)

## Course Syllabus
**Description:**  
本課程介紹即時系統領域的重要原理、系統架構、以及當前的相關研究成果和應用。本學期課程包含以下六項主題，並著重文獻研讀 (<span style="color:red">Critique</span>)、實作演練 (<span style="color:blue">Lab</span>) 及團體專題 (<span style="color:brown">Project</span>):

1. Real-Time Scheduling: Theory and Practice
2. Real-Time Operating Systems
3. Real-Time Systems Engineering
4. Distributed Real-Time Middleware
5. Real-Time Edge Computing
6. Power and Energy Awareness in Real-Time Cyber-Physical Systems


**Prerequisites:**  
此課程為碩士班及大學部合班授課，預期修課學生已具備大三(含)以上之電腦科學與工程相關知識。課程將使用 C++ 及 Linux 作業系統。

**Grading:**  
* Homework 40%  
* Project 50%<a name="schedule"></a>  
* Participation 5%  
* Attendance 5%  

## Course Schedule

| Date | Topic | Homework Assignment | Related Material |
| ---  | --- | --- | ---|
| Mar 5  | Course Overview | Lab 0 | |
| Mar 12 | Real-Time Scheduling (1) | Lab 1 | |
| Mar 19 | Real-Time Scheduling (2) |  | |
| Mar 26 | Real-Time Operating Systems; Project Proposal Presentation | Critique 1 | |
| Apr 2  | 補假 |  | |
| Apr 9  | Real-Time Event Service |  | |
| Apr 16 | Real-Time Systems Engineering |  | |
| Apr 23 | Real-Time Multi-threaded Programming;<br>[(CPS-IoT Week)](https://www.cse.unsw.edu.au/~cpsiot/cpsweek2020/index.html) | Lab 2;<br>[pthreads tutorial](https://randu.org/tutorials/threads/)|
| Apr 30 | <span style="color:brown">Project Demo 1</span>; | |
| May 7  | Serving Periodic/Aperiodic Real-Time Tasks | Critique 2 | Textbook 3, Sections 5.1-5.4; 5.6|
| May 14| Patterns for Building RealTime Software |  | Textbook 2, Chapter 11 |
| May 21| <span style="color:brown">Project Demo 2</span> | | |
| May 28| Fault-Tolerant Real-Time Messaging | Lab 3 | Reference 9|
| Jun 4 | Real-Time CPS: Power and Energy Awareness | Critique 3 | |
| Jun 11| The Time-Triggered Architecture |  | |
| Jun 18| <span style="color:brown">Project Final Demo</span> |  | |
| Jun 25| 端午節放假 |  | |
| Jul 2 | In-Class Workshop |  | |

## Textbooks and References

**Textbooks:**  

1. Kopetz, Hermann. _Real-Time Systems: Design Principles for Distributed Embedded Applications_. Springer; 2nd ed. 2011 edition. ISBN 978-1441982360 (_A comprehensive treatment of the subject_)
2. Gomaa, Hassan. _Real-Time Software Design for Embedded Systems_. Cambridge University Press, 2016. ISBN 978-1107041097 (_Focus on systems engineering aspects_)
3. Buttazzo, Giorgio C. _Hard Real-Time Computing Systems: Predictable Scheduling Algorithms and Applications_ Springer; 3rd ed. 2011 edition. ([book webpage](https://link.springer.com/book/10.1007/978-1-4614-0676-1))


<a name="accessibility"></a>
**References:**  

1. [Real-Time Linux Wiki](https://rt.wiki.kernel.org/index.php/Frequently_Asked_Questions)
2. [gRPC - A High Performance, Open-Source Universal RPC Framework](https://www.grpc.io/)
3. [The TAO Real-Time Middleware](http://www.dre.vanderbilt.edu/~schmidt/TAO.html)
4. McConnell, Steve. _Code Complete: A Practical Handbook of Software Construction_. Microsoft Press; 2nd edition (June 19, 2004). ISBN 978-0735619678
5. T. Harrison, D. Levine, and D.C. Schmidt, _The Design and Performance of a Real-time CORBA Event Service_, ACM Conference on Object-Oriented Programming, Systems, Languages, and Applications, October 1997. (<span style="color:red">Critique 1</span>)
6. C. Wang, C. Gill and C. Lu, _Real-Time Middleware for Cyber-Physical Event Processing_, ACM Transactions on Cyber-Physical Systems, Special Issue on Real-Time Aspects in Cyber-Physical Systems, 3(3), Article 29, August 2019.
7. Y. Zhang, C. Lu, C. Gill, P. Lardieri and G. Thaker, _Middleware Support for Aperiodic Tasks in Distributed Real-Time Systems_, IEEE Real-Time and Embedded Technology and Applications Symposium (RTAS'07), April 2007. (<span style="color:red">Critique 2</span>)
8. C. Lu, A. Saifullah, B. Li, M. Sha, H. Gonzalez, D. Gunatilaka, C. Wu, L. Nie and Y. Chen, _Real-Time Wireless Sensor-Actuator Networks for Industrial Cyber-Physical Systems_, Special Issue on Industrial Cyber-Physical Systems, Proceedings of the IEEE, 104(5): 1013-1024, May 2016. (<span style="color:red">Critique 3</span>)
9. C. Wang, C. Gill, and C. Lu, _FRAME: Fault Tolerant and Real-Time Messaging for Edge Computing_, IEEE 39th International Conference on Distributed Computing Systems (ICDCS), 2019, pp. 976-985


## Accessibility
<a name="integrity"></a>
特殊需求的學生，請與授課教師聯繫。  
Students in need please bring your considerations to the instructor.

## Academic Integrity
<a name="hw"></a>
請謹記本校[校訓](http://archives.lib.ntnu.edu.tw/c2/c2_1.jsp): 誠、正、勤、樸。舞弊或協助他人舞弊者以零分計算。  
Please reflect on the university's [motto](http://archives.lib.ntnu.edu.tw/c2/c2_1.jsp): Sincerity, Integrity, Diligence, Simplicity. Anyone found to be cheating or helping someone else cheat will receive zero score for that assignment.

## Homework Assignment 

作業請一律至 [Moodle](https://moodle.ntnu.edu.tw/) 繳交.  
Students should submit all their homework assignments via [Moodle](https://moodle.ntnu.edu.tw/).

