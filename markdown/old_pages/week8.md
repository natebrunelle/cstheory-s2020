---
title: Week 8 Guide
...

# Goals

This week, we introduce the most important and widely used model of
computation, the Turing machine, and start to address the big question
of what can and cannot be computed by any machine with a finite
description.

The main goals for Week 8 are to:

- Understand what cannot be computed by a finite automaton and why.
- Use and understand Turing Machines as a model of computing.
- Study a definition of computability.
- Explore the powers and limitations of Turing Machines.
- Understand why some numbers are _uncomputable_, and what this means.
- Learn different variations on Turing Machines and how they can be transformed.

# Schedule


|       Day       | "Tuesday" Cohort | "Wednesday" Cohort | "Thursday" Cohort  |  "Friday" Cohort   |   "Sunday" Cohort  |
| :-------------: | :--------------: | :----------------: | :----------------: | :----------------: | :----------------: |
|**Thurs** 25 Mar|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|
|**Fri** 26 Mar|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|
|**Sat** 27 Mar|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|Preparation|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|
|**Sun** 28 Mar|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|Preparation|Preparation|<font color="lightgray">(Week 7)</font>|
|**Mon** 29 Mar|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|Preparation|Preparation|<font color="lightgray">(Week 7)</font>|
|**Tues** 30 Mar|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|**Prep Cohort Meeting**|Preparation|Preparation|
|**Wed** 31 Mar|<font color="lightgray">(Week 7)</font>|<font color="lightgray">(Week 7)</font>|Revision|**Prep Cohort Meeting**|Preparation|
|**Thurs** 01 Apr|Preparation|<font color="lightgray">(Week 7)</font>|<font color="red">**Assessed Meeting**</font>|Revision|Preparation|
|**Fri** 02 Apr|Preparation|Preparation|**Writeup Due**|<font color="red">**Assessed Meeting**</font>|**Prep Cohort Meeting**|
|**Sat** 03 Apr|Preparation|Preparation|<font color="lightgray">(Week 9)</font>|**Writeup Due**|Revision|
|**Sun** 04 Apr|**Prep Cohort Meeting**|Preparation|<font color="lightgray">(Week 9)</font>|<font color="lightgray">(Week 9)</font>|<font color="red">**Assessed Meeting**</font>|
|**Mon** 05 Apr|Revision|**Prep Cohort Meeting**|<font color="lightgray">(Week 9)</font>|<font color="lightgray">(Week 9)</font>|**Writeup Due**|
|**Tues** 06 Apr|<font color="red">**Assessed Meeting**</font>|Revision|<font color="lightgray">(Week 9)</font>|<font color="lightgray">(Week 9)</font>|<font color="lightgray">(Week 9)</font>|
|**Wed** 07 Apr|**Writeup Due**|<font color="red">**Assessed Meeting**</font>|<font color="lightgray">(Week 9)</font>|<font color="lightgray">(Week 9)</font>|<font color="lightgray">(Week 9)</font>|
|**Thurs** 08 Apr|<font color="lightgray">(Week 9)</font>|**Writeup Due**|<font color="lightgray">(Week 9)</font>|<font color="lightgray">(Week 9)</font>|<font color="lightgray">(Week 9)</font>|

# Cohort Problems

These are the problems you should discuss in your Cohort Meeting, and
everyone in your cohort should be prepared to present and discuss
solutions to at the Assessed Cohort Meeting:

- [Cohort Problems for Week 8 [PDF]](/files/ps/week8_blank.pdf)
- [LaTeX Template for Week 8 [ZIP]](/files/ps/week8.zip)

The problems are posted here and we think its a good idea to look at
them early, but you're not expected to be able to solve them until
after doing the readings and watching the videos below.

There is no programming portion for this week.


# Reading

This week we discuss the material contained in [Chapter 7: Loops and Infinity](https://introtcs.org/public/lec_06_loops.html).

Turing Machines and other similar models of computing are taught in
many different ways in many different places. In addition to the
course materials, you'll find plenty of other presentations of this
material available on youtube, other textbooks, lecture slides from
other universities, blog posts, etc. Please be advised that there are
many subtly different presentations of Turing machines, and so what
you see elsewhere may differ from what we covered, but the key ideas
are universal and should be the same in any good
presentation. Typically minor changes are made to the model either for
convenience of the context, or so real-world running times are more
similar to the running time of the model (more on this in future
weeks).

You can read Turing's paper here: Alan M. Turing, [_On Computable Numbers, with an Application to the
Entscheidungsproblem_](/files/computablenumbers.pdf). 1936.


# Videos

You can play all the videos using this playlist, but don't forget to take breaks: [Week 8 Playlist](https://www.youtube.com/playlist?list=PLZ9Gk_8DtbmGERGozYoSd-kmz-tsTn2yu)
<p>
Some videos are edited from these cs3102 classes (we don't generally recommend watching the unedited versions, but they are available if you want to):

- (Fall 2019) [Class 13: Machines](https://uvatoc.github.io/f19/class13/): [Full Video](https://uva.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=89195d73-1989-4b2f-8b70-aae8014178c4), [Slides](https://www.dropbox.com/s/36tv9no453ffmkn/class13_written.pptx?dl=0)

- (Fall 2019) [Class 14: Computability](https://uvatoc.github.io/f19/class14/): [Full Video](https://uva.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=e086e67f-71aa-45e1-a59d-aaed01412ded), [Slides](https://www.dropbox.com/s/nw9zh8a0vahvaqy/class14-inked.pdf?dl=0)

</p>


<p>Applications of Finite State Automata (6:27) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/fPAxt4LvEaU' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Warm-Up: Life on Mars (2:16) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/zpKVDZB7JiE' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Limitations of Finite Automata (6:40) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/KmAJEKRZaGY' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Turing Machines (5:37) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/Xx_GeourSOQ' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>Turing Machine Example (17:59) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/6S6suD3aRxY' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Turing Machine Definition (8:31) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/qH6Ffc9H2js' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>

<p>What was Turing’s Model Modeling? (14:08) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/vcGxEtT3wsc' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>Busy Beavers (5:12) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/yJApEB69gXo' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>


<p>On Uncomputable Numbers (8:13) <br><iframe width='800' height='450' src='https://www.youtube-nocookie.com/embed/Cuf4zkYwGlQ' frameborder='0' allow='accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe><br></p>
