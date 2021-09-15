---
date: "2020-08-14T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: true  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?
math: true

---
![NTNU logo](../../img/ntnu_logo.png)

**Course Name:** CSC0056 Data Communication 資料通訊 <span style="color:red">(Fall 2021)</span>  
**Instructor:** Chao Wang 王超  
**Teaching Assistant:** Cheng-Hsun Chuang 莊承勳  
**Course Meetings:** Mondays 14:20--17:20 (mostly online, and on some selected dates in room 001 in the Gongguan-Campus Library; see the schedule below)  
**Office Hours:** Wednesdays and Thursdays, 2--4pm (room 511, Applied Science Building, Gongguan Campus), or [by appointment](mailto:cw@ntnu.edu.tw)  
**Midterm Exam:** Nov 9, Monday 9:10--12:10  
**Final Exam:** Jan 11, Monday 9:10--12:10  

This course is offered _in English_ (with Mandarin support). 此門課程為全英語授課 (配合中文輔助).

## Contents

* [Course Syllabus](#syllabus) <a name="syllabus"></a>
* [Course Schedule](#schedule)
* [Textbooks and Other Resources](#resource)
* [Accessibility](#accessibility)
* [Academic Integrity](#accessibility)
* [Homework Assignment](#hw)

## Course Syllabus

Data communication is essential for networked computing systems. The objectives of this course are for students to get some ideas into systems analysis, to have hands-on experience to systems development, and to engage in recent advances in data communication systems.

In particular, we will
* learn the basics of the standard queueing model;
* learn the widely used MQTT messaging protocol and its practice;
* learn to work with a cloud platform (Amazon AWS as an example); and
* learn to do critical study on scientific papers.

In the 2021 fall semester, this course is structured as a hybrid course (數位課程) and is also offered on [Taiwan Online Campus](https://toc.co.ntnu.edu.tw/). The lectures are divided into three categories: <span style="color:green">asynchronous online</span> (learn at your own pace), <span style="color:red">synchronous online</span> (real-time remote class), and <span style="color:blue">traditional face-to-face</span> (i.e., come). See the course schedule below for detail.

Such a hybrid course is new, and to see how we may improve learning experience, we'd like to collect course-related activity data as well as students' comments. Therefore, most of the course materials will be posted on [Moodle](https://moodle.ntnu.edu.tw/), since it is possible to trace online activities there (e.g., the number of clicks/watches for each subject).

**Prerequisites:**  
Working knowledge in C and Linux.

**Grading:**  
* Homework Assignments 50% (every assignment counts) 
* First Exam 20% <a name="schedule"></a>  
* Final Exam 25%  
* Participation 5%   

## Course Schedule

Color scheme: green for <span style="color:green">asynchronous online lectures</span>; red, <span style="color:red">synchronous online</span>; blue, <span style="color:blue">face-to-face</span>.

| \#  | Date | Topic |
| --- | ---  | --- |
| 1 | <span style="color:blue">Sep 27</span> | Course Introduction |
| 2 | <span style="color:red">Oct 4</span>  | Network Flow Algorithms |
| 3 | <span style="color:green">Async.</span> | Broker-Based Data Communication |
| 4 | <span style="color:red">Oct 18</span> | Data Communication Programming Basics |
| 5 | <span style="color:blue">Oct 25</span> | The Queueing Model |
| 6 | <span style="color:green">Async.</span> | Markov Chain and Queueing Systems |
| 7 | <span style="color:green">Async.</span> | The Aloha System |
| 8 | <span style="color:blue">Nov 15</span> | **Midterm Exam** |
| 9 | <span style="color:green">Async.</span> | Time-Division Multi-Access |
| 10| <span style="color:green">Async.</span> | Data Routing |
| 11| <span style="color:green">Async.</span> | Network Flow Control |
| 12| <span style="color:red">Dec 13</span> | Real-Time Data Communication |
| 13| <span style="color:blue">Dec 20</span> | Error Handling |
| 14| <span style="color:red">Dec 27</span> | Real-Time Fault-Tolerant Communication |
| 15| <span style="color:green">Async.</span> | Time Synchronization |
| 16| <span style="color:blue">Jan 10</span> | **Final Exam** |
| 17| <span style="color:green">Asynch.</span> | Supplementary Topics |
| 18| <span style="color:green">Asynch.</span> | Supplementary Topics |

<a name="resource"></a>

## Textbook and References

We will pick materials from the following textbooks and references:

**Textbook:**

[1] Harchol-Balter, Mor. _Performance modeling and design of computer systems: queueing theory in action._ Cambridge University Press, 2013. ISBN 9781107027503. ([Read it at NTNU library](http://www.lib.ntnu.edu.tw/holding/doQuickSearch.jsp?action=view&param=%2Fsearch*cht%3F%2FtPerformance%2Bmodeling%2Band%2Bdesign%2Bof%2Bcomputing%2Bsystems%2Ftperformance%2Bmodeling%2Band%2Bdesign%2Bof%2Bcomputing%2Bsystems%2F-3%252C0%252C0%252CB%2Fframeset%26FF%3Dtperformance%2Bmodeling%2Band%2Bdesign%2Bof%2Bcomputer%2Bsystems%2Bqueueing%2Btheory%2Bin%2Baction%261%252C1%252C%2Findexsort%3D-). Our library also purchased an e-copy; [click here](https://doi.org/10.1017/CBO9781139226424) via campus network.)

[2] Bertsekas, Dimitri and Gallager, Robert. _Data networks (2nd edition)_. Prentice Hall, 1992. ISBN 0132009161. ([Read it at NTNU library](http://www.lib.ntnu.edu.tw/holding/doQuickSearch.jsp?newQuery=true&searchtype=t&search=Data+Networks)) ([author's page](http://web.mit.edu/dimitrib/www/datanets.html))

[3] Tarjan, Robert Endre. Data Structures and Network Algorithms. Society for Industrial and Applied Mathematics, 1983. ISBN 0898711878.

**References:**  

[1] Kurose, Jim and Ross, Keith. _Computer Networking: A Top-Down Approach (5th edition or newer)_. Pearson, 2010. ISBN 0136079679.

[2] William Feller. _An Introduction to Probability Theory and Its Applications, Volume I (3rd edition)_. Wiley, 1968. ISBN 0471257087.

[3] Chao Wang, Christopher Gill, Chenyang Lu. _Adaptive Data Replication in Real-Time Reliable Edge Computing for Internet of Things._ 2020 IEEE/ACM International Conference on Internet-of-Things Design and Implementation (IoTDI), 2020. ([pdf](https://wangc86.github.io/publication/iotdi20/iotdi20.pdf))

[4] Chao Wang, Kuo-Feng Ssu. _A Distributed Collision-Free Low-Latency Link Scheduling Scheme in Wireless Sensor Networks_ 2010 IEEE Wireless Communication and Networking Conference, 2010. ([pdf](https://wangc86.github.io/publication/wcnc10/wcnc10.pdf))

[5] Luby, Michael. "A simple parallel algorithm for the maximal independent set problem." SIAM journal on computing 15.4 (1986): 1036-1053. ([on Google Scholar](https://scholar.google.com/scholar?hl=zh-TW&as_sdt=0%2C5&q=A+simple+parallel+algorithm+for+the+maximal+independent+set+problem&btnG=))

[6] Ramanathan, Subramanian, and Errol L. Lloyd. "Scheduling algorithms for multihop radio networks." IEEE/ACM Transactions on networking 1.2 (1993): 166-177. ([on IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/222924))

[7] Chao Wang, Christopher Gill, and Chenyang Lu. 2019. _Real-Time Middleware for Cyber-Physical Event Processing._ ACM Trans. Cyber-Phys. Syst. 3, 3, Article 29 (October 2019), 25 pages. DOI:https://doi.org/10.1145/3218816 ([link](https://dl.acm.org/doi/10.1145/3218816))

[8] Chao Wang, Christopher Gill, and Chenyang Lu, _FRAME: Fault Tolerant and Real-Time Messaging for Edge Computing,_ 2019 IEEE 39th International Conference on Distributed Computing Systems (ICDCS), Dallas, TX, USA, 2019, pp. 976-985, doi: 10.1109/ICDCS.2019.00101. ([link](https://ieeexplore.ieee.org/abstract/document/8884849))

[9] Ho, Yao-Hua; Tai, Yun-Juo; Chen, Ling-Jyh. 2021. "COVID-19 Pandemic Analysis for a Country’s Ability to Control the Outbreak Using Little’s Law: Infodemiology Approach" Sustainability 13, no. 10: 5628. https://doi.org/10.3390/su13105628

<a name="accessibility"></a>

## Accessibility
<a name="integrity"></a>

Students in need are encouraged to bring their considerations to the instructor. 

## Academic Integrity

All homework assignments and exams must be completed individually and independently, except as specifically allowed by the instructor. 

<a name="hw"></a>
Academic integrity is a key component of your education, which is for your benefit. Anyone found to be cheating or helping someone else cheat will receive zero score for that homework/exam. Please reflect on the university's [motto](http://archives.lib.ntnu.edu.tw/c2/c2_1.jsp): Sincerity 誠, Integrity 正, Diligence 勤, Simplicity 樸.

## Homework Assignment 

All homework assignments will be announced on [Moodle](https://moodle.ntnu.edu.tw/).

