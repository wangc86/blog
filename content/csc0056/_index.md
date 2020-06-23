---
date: "2019-08-03T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: true  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?
math: true

---
![NTNU logo](../../img/ntnu_logo.png)

**Course Name:** CSC0056 Data Communication 資料通訊 <span style="color:red">(Fall 2019)</span>  
**Instructor:** [Chao Wang 王超](../../#people)  
**Course Meetings:** Mondays 9:10 - 12:10 in room C007, Gongguan Campus  
**Office Hours:** Wednesdays and Fridays, 10am-noon, in my office (room 511, Applied Science Building, Gongguan Campus), or [by appointment](mailto:cw@ntnu.edu.tw)  
**First Exam:** Nov 4, 9:10 - 12:10, in class  
**Final Exam:** Jan 6, 9:10 - 12:10, in class  

This course is offered as an _all-English_ course.

## Contents

* [Course Syllabus](#syllabus) <a name="syllabus"></a>
* [Course Schedule](#schedule)
* [Textbooks and Other Resources](#resource)
* [Accessibility](#accessibility)
* [Academic Integrity](#accessibility)
* [Homework Assignment](#hw)

## Course Syllabus
**Description:**  
Data communication is an essential part of modern computer networks and Internet-of-Things (IoT) systems. The objectives of this course are for each student to:  

* learn classic data communication algorithms and protocols;
* gain insight into analyzing data communication systems; and
* engage in recent advances in data communication systems.

The first half of this course (i.e., before the first exam) will focus on how to analyze a data communication network. The second half will cover some classic algorithms and protocols in data communications, followed by recent advances in this field.

**Prerequisites:**  
This course is for both senior undergraduate students and graduate students. Students are recommended to be familiar with materials taught in _Computer Networks_ or an equivalent course.

**Grading:**  
* Homework 30%  
* First Exam 25% <a name="schedule"></a>  
* Final Exam 35%  
* Participation 5%  
* Attendance 5%  

## Course Schedule

| \#  | Date | Topic | [Readings](#resource) |
| --- | ---  | --- | --- |
| 1 | Sep 9   | [Course Introduction](lecture01.pdf) | [1] Sections 1.1-1.2|
| 2 | Sep 16  | [Layered Network Architecture](lecture02.pdf);<br>[lecture note](lec2note.pdf) | [1] Sections 1.3, 2.1-2.3|
| 3 | Sep 23  | [Point-to-Point Protocols](lecture03.pdf);<br>[lecture note](lec3note.pdf) | [1] Sections 2.3-2.4.2, 2.8.1-2.8.2, 2.9.1-2.9.4|
| 4 | Sep 30  | (cancelled due to typhoon) | same as above|
| 5 | Oct 7   | [Point-to-Point Protocols (2)](lecture05.pdf);<br>[lecture note](lec5note.pdf);<br>[lecture note 2](lec5note2.pdf) | same as above, plus 2.4.3 and 2.8.4 |
| 6 | Oct 14  | [Queueing Model and Little's Theorem](lec6note.pdf) | [1] Sections 3.1-3.2|
| 7 | Oct 21  | [Markov Chain and Queueing Systems](lec7note.pdf) | [1] Sections 3.3-3.3.1 and Appendix A|
| 8 | Oct 28  | [More on Queueing Systems](lec8note.pdf);<br>[Review of Poisson Distribution](note_PoissonDistribution.pdf);<br>First Exam Review | [1] Sections 3.3.1-3.4.1|
| 9 | Nov 4   | [**First Exam**](Midterm_2019.pdf) | |
| 10 | Nov 11 | [Multiaccess Communication](lecture10.pdf) | [1] Sections 4.1-4.2|
| 11 | Nov 18 | [Aloha protocols](lecture11_annotated2.pdf) | [1] Sections 4.2, 4.4-4.4.1, 4.5 before 4.5.1, and 4.6|
| 12 | Nov 25 | Shortest Path Routing | [1] Sections 5.2-5.2.3|
| 13 | Dec 2  | Network Flow Algorithms;<br>[lecture note](lec13note.pdf) | [1] Section 5.4 before 5.4.1; Sections 5.5-5.6 |
| 14 | Dec 9  | Flow Control | [1] Sections 6.1-6.2.1, 6.3, and 6.5.1|
| 15 | Dec 16 | [Real-Time Data Communication](lecture15.pdf) | see page 4 in the lecture slides|
| 16 | Dec 23 | [Time Synchronization and Timely Data Replication](lecture16.pdf) | see page 4 in the lecture slides|
| 17 | Dec 30 | Error Correction Code, CAN, and Course Review;<br>[lecture note](lec17note.pdf) | [(i)](#lec17ref) and [(j)](#lec17ref) |
| 18 | Jan 6  | [**Final Exam**](FinalExam_2019.pdf) | |

<a name="resource"></a> The readings assignment each week is designed for you to gain some background of the topic _before_ class. Read them and note where you found interesting and/or challenging. Bring your findings to class for further discussion. I will also cover additional materials in class.

## Textbooks and Other Resources

**Textbooks:**

[1] Bertsekas, Dimitri and Gallager, Robert. _Data networks (2nd edition)_. Prentice Hall, 1992. ISBN 0132009161. **(Required)** ([NTNU library](http://www.lib.ntnu.edu.tw/holding/doQuickSearch.jsp?newQuery=true&searchtype=t&search=Data+Networks)) ([author's page](http://web.mit.edu/dimitrib/www/datanets.html))

[2] Harchol-Balter, Mor. _Performance modeling and design of computer systems: queueing theory in action._ Cambridge University Press, 2013. ISBN 9781107027503. ([author's book intro](http://www.cs.cmu.edu/~harchol/PerformanceModeling/book.html))

[3] Kurose, Jim and Ross, Keith. _Computer Networking: A Top-Down Approach (5th edition or newer)_. Pearson, 2010. ISBN 0136079679

[4] Andrew S. Tanenbaum. _Computer Networks (4th edition or newer)_. Peason, 2003. ISBN 0130384887

[5] William Feller. _An Introduction to Probability Theory and Its Applications, Volume I (3rd edition)_. Wiley, 1968. ISBN 0471257087

**Other Resources:**  
A wealth of helpful and relevant articles/tools may be found on-line. Here I picked some for the materials taught in this course:

(a) [AUTOSAR (in particular, its layered software architecture).](https://en.wikipedia.org/wiki/AUTOSAR#Software_architecture)

(b) [Industrial Internet Reference Architecture.](https://www.iiconsortium.org/IIRA.htm)

(c\) Further reading on [error detection/correction](https://www.sciencedirect.com/topics/engineering/hamming-distance) (access it via our campus network to get a proper access authorization).

(d) [A good visual demonstration of Markov chains](http://setosa.io/blog/2014/07/26/markov-chains/)

(e) [Industrial Internet Reference Architecture v1.9](https://www.iiconsortium.org/IIRA.htm)

(f) Chao Wang, Christopher Gill, and Chenyang Lu. _Real-Time Middleware for Cyber-Physical Event Processing._ ACM Transactions on Cyber-Physical Systems 3, 3, Article 29 (August 2019) ([manuscript](https://wangc86.github.io/pdf/tcps-cpep.pdf))

<a name="lec17ref"></a>
<a name="accessibility"></a>
(g) Chao Wang, Christopher Gill, Chenyang Lu. _FRAME: Fault Tolerant and Real-Time Messaging for Edge Computing._ IEEE International Conference on Distributed Computing Systems (ICDCS), 2019. ([manuscript](https://wangc86.github.io/pdf/icdcs19-frame.pdf))

(h) Time synchronization: [Difference between _accuracy_ and _precision_ in measurement](https://en.wikipedia.org/wiki/Accuracy_and_precision)

(i) Joseph A. Gallian. _Contemporary Abstract Algebra (7th edition)_. Brooks/Cole, 2010. ISBN 9780495831532

(j) [CAN Specification, Version 2.0](http://esd.cs.ucr.edu/webres/can20.pdf). You can learn a lot from this very good documentation.

## Accessibility
<a name="integrity"></a>

Students with disabilities are encouraged to bring considerations to the attention of the instructor, potentially including accommodations for exams. 

## Academic Integrity

Homeworks must be completed individually and independently. Exams must be completed individually and independently without reference to materials or devices, except as specifically allowed by the instructor. 

<a name="hw"></a>
Academic integrity is a key component of your education, which is for your benefit. Anyone found to be cheating or helping someone else cheat will receive zero score for that homework/exam. Please reflect on the university's [motto](http://archives.lib.ntnu.edu.tw/c2/c2_1.jsp): Sincerity 誠, Integrity 正, Diligence 勤, Simplicity 樸.

## Homework Assignment 

Students should submit all their homework assignments via [Moodle](https://moodle.ntnu.edu.tw/).

* [Homework1](Homework01.pdf)
* [Homework2](Homework02.pdf)
* [Homework3](Homework03.pdf)
* [Homework4](Homework04.pdf)
* [Homework5](Homework05.pdf)
* [Homework6](Homework06.pdf)
