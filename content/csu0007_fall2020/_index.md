---
date: "2020-08-15T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: true  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?
math: true

---
![NTNU logo](../../img/ntnu_logo.png)

**Course Name:** CSU0007 Basic Electronics 基礎電子學 <span style="color:red">(Fall 2020)</span>  
**Instructor:** Chao Wang 王超  
**Teaching Assistant:** Eric Mei 梅志碩  
**Course Meetings:** Tuesdays 9:10--10:00 and Fridays <span style="color:red">15:30--17:20</span>, in room <span style="color:red">E302</span>, Gongguan Campus  
**Office Hours:** Wednesdays and Fridays, 8-10am (room 511, Applied Science Building, Gongguan Campus), or [by appointment](mailto:cw@ntnu.edu.tw)  
**Midterm Exam:** Nov 13, Friday 14:20--16:20, in class  
**Final Exam:** Jan 15, Friday 14:20--16:20, in class  

This course is offered as an _all-English_ course. 此門課程為全英語授課.

## Contents

* [Course Syllabus](#syllabus) <a name="syllabus"></a>
* [Course Schedule](#schedule)
* [Textbook and Additional References](#resource)
* [Accessibility](#accessibility)
* [Academic Integrity](#accessibility)
* [Homework Assignment](#hw)

## Course Syllabus
This course is designed for first-year undergraduate students, in particular for those who major in computer science and information engineering. The goal is to unveil some part of the "mysterious connections" between physics and computing systems. It is our hope that through this course, students will acquire basic skills to explore modern computing systems such as those for Internet of Things (IoT).

**Grading:**  
* Homework 45% (will count the highest six out of seven assignments) 
* First Exam 20%<a name="schedule"></a> ([solution](midterm_solution.pdf)) 
* Final Exam 25%  
* Participation 5%  
* Attendance 5%  

## Course Schedule

| \#  | Date | Topic | [Reading](#resource) |
| --- | ---  | --- | --- | 
| 1 | Sep 15, 18   | The Circuit Abstraction ([slides](lecture01-1.pdf); [lecture note](lecture01-2.pdf)) | Chapter 1; Appendix A.1 |
| 2 | Sep 22, 25, 26   | Resistive Networks ([lecture note](lecture02.pdf)) | Chapter 2 to Sec. 2.5 |
| 3 | Sep 29   | The Node Analysis Method ([lecture note](lecture03.pdf)) | Sec. 3.1-3.3 (except Sec. 3.3.3) |
| 4 | Oct 6   | Superposition ([lecture note](lecture04.pdf)) | Sec. 3.5 up to Example 3.16 |
| 5 | Oct 13, 16   | Thevenin's Theorem, Norton's Theorem, and Their Applications ([lecture note 1](lecture05-1.pdf)) ([lecture note 2](lecture05-2.pdf))| Sec. 3.6 |
| 6 | Oct 20, 23   | Nonlinear Circuits and Basic Analysis ([lecture note 1](lecture06-1.pdf)) ([lecture note 2](lecture06-2.pdf)) | Sec. 4 up to Sec. 4.3 |
| 7 | Oct 27, 30   | Approximation and The Small-Signal Analysis ([lecture note](lecture07.pdf)) | Sec. 4.4-4.5 |
| 8 | Nov 3, 6   | The Digital Abstraction ([lecture note 1](lecture08-1.pdf))| Sec. 5 |
| 9 | Nov 10, 13   | review session on Nov 10 ([exercise](small-signal-exercise.pdf)); **Midterm Exam on Nov 13** | [solution](midterm_solution.pdf) |
| 10 | Nov 17   | Discussion of Exam Questions |  |
| 11 | Nov 24, 27   | The MOSFET Switch | Sec. 6.1-6.8 (self-study: Sec. 6.8.1) |
| 12 | Dec 1, 4   | Amplification: Concepts and Applications | Sec. 6.9 and more |
| 13 | Dec 8, 11   | The MOSFET Amplifier | Sec. 7.1-7.6 |
| 14 | Dec 15, 18   | MOSFET Circuit Analysis ([lecture note up to Dec 15](note-uptoDec15.pdf))| Sec. 7.6-7.7 (skip BJT) |
| 15 | Dec 22, 25   | Advanced Analysis and Difference Amplifier ([lecture note](note-Dec15-to-Dec25.pdf))| Chapter 8 |
| 16 | Dec 29   | Difference Amplifier | Chapter 8 |
| 17 | Jan 5, 8   | Selected Topics and Review |  |
| 18 | Jan 12, 15 | ([lecture note since Dec 25](note-since-Dec25.pdf)) **Final Exam on Jan 15** ([solution](final_solution.pdf)) |  |

## Textbook
<a name="resource"></a>

[1] Agarwal, Anant and Lang, Jeffrey H. _Foundations of Analog and Digital Electronic Circuits._ Morgan Kaufmann; 1 edition (July 18, 2005). ISBN 978-1558607354 **(Required)**

Purchase a copy of the book from [Elsevier](https://www.elsevier.com/books/foundations-of-analog-and-digital-electronic-circuits/agarwal/978-0-08-050681-4), [books.google.com](https://books.google.com.tw/books?id=lGgP7FDEv3AC&printsec=copyright&redir_esc=y#v=onepage&q&f=false), etc. You may also read it at [the NTNU library](http://www.lib.ntnu.edu.tw/holding/doQuickSearch.jsp?newQuery=true&searchtype=t&search=Foundations+of+Analog+and+Digital+Electronic+Circuits).

[Click here](csu0007_note_2020spring.pdf) for the lecture notes of the 2020 Spring edition of this course.

## Additional References

* [Link](2012.2.pdf) <-- A great introduction to semiconductor science, from the EE department at National Taiwan University.
* Neamen, Donald A. Semiconductor physics and devices: basic principles. New York, NY: McGraw-Hill. 2012. ([NTNU library](http://www.lib.ntnu.edu.tw/holding/doQuickSearch.jsp?action=view&param=%2Fsearch*cht%3F%2Ftsemiconductor%2Bphysics%2Band%2Bdevices%2Bbasic%2Bprinciples%2B4th%2Bedition%2Bsolution%2Ftsemiconductor%2Bphysics%2Band%2Bdevices%2Bbasic%2Bprinciples%2B%2B%2B%2B%2B%2B%2B%2B4th%2Bedition%2Bsolution%2F-3%252C0%252C0%252CB%2Fexact%26FF%3Dtsemiconductor%2Bphysics%2Band%2Bdevices%2Bbasic%2Bprinciples%261%252C2%252C%2Findexsort%3D-); also, [Google Scholar](https://scholar.google.com/scholar?hl=zh-TW&as_sdt=0%2C5&q=semiconductor+physics+and+devices+basic+principles+4th+edition+solution&btnG=)) (I personally found this textbook wonderful)

## Accessibility
<a name="integrity"></a>
Students in need should bring your considerations to the instructor.

## Academic Integrity
<a name="hw"></a>
Please reflect on the university's [motto](http://archives.lib.ntnu.edu.tw/c2/c2_1.jsp): Sincerity, Integrity, Diligence, Simplicity. Anyone found to be cheating or helping someone else cheat will receive zero score for that assignment.

## Homework Assignment 

Students should submit all their homework assignments via [Moodle](https://moodle.ntnu.edu.tw/).

* [Homework1](homework01.pdf); due on October 6th, 9AM. ([solution](hw1_solution.pdf))
* [Homework2](homework02.pdf); due on October 27th, 9AM. ([solution](hw2_solution.pdf))
* [Homework3](homework03.pdf); due on November 10th, 9AM. ([solution](hw3_solution.pdf))
* [Homework4](homework04.pdf); due on December 4th, 9PM. ([solution](hw4_solution.pdf))
* [Homework5](homework05.pdf); due on December 19th, 9PM. ([solution](hw5_solution.pdf))
* [Homework6](homework06.pdf); due on Jan 5th, 9PM, 2021. ([solution](hw6_solution.pdf))
* [Homework7 (bonus)](homework07.pdf); due on Jan 14th, 5PM, 2021. ([solution](hw7_solution.pdf))
