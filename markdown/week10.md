---
title: Week 10 Guide
...

# Goals

At the start of the semester, we used a counting argument to show that there must be some
uncomputable functions ("some" here means infinitely many). This week, we prove
that a particular function is uncomputable, and explore the
implications of finding an uncomputable function.

The main goals for Week 10 are to:

- Identify specific functions that cannot be computed by Turing Machines
- Develop skills for identifying uncomputable problems
- Build strategies for showing new problems to be uncomputable
- Undertand the definition of Universality in the context of Turing Machines

# Reading

You should read through the end of Section 9.3 (including the "optional" section 9.3.2). (We will cover Section 9.4 and 9.5 next week.)

The material in Sections 9.1 &ndash; 9.3 covers the same concepts as
we do in the lectures, but in a somewhat different order and with a
focus on <em>HALT</em> rather than <em>ACCEPTS</em>. You should
consider how similar and different these two functions are, and
compare the proof that <em>ACCEPTS</em> is uncomputable from the
lectures to the one in the book that <em>HALT</em> is uncomputable.

# Problem Set

These are the problems you should discuss and solve first independently, then with your cohort (supposing you're in one). These problems focus on material discussed in the April 4 and April 6 lectures.

[PS9 [PDF]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps9_blank.pdf)

[PS9 [ZIP]](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps9.pdf)

Note that this problem set does not have a programming portion.


## Submission Instructions


1. Download the [PS9 template](https://www.cs.virginia.edu/~njb2b/cstheory/s2022/files/ps/ps9.zip)
1. In Overleaf, click on *Create First Project* or *New Project in Overleaf* and select *Upload Project* from the menu.
1. Click *Select a .zip file* then select the *ps9.zip* you downloaded in step 1
1. Look in `ps9.tex` for the line, `submitter{TODO: your name}` and replace the `TODO: your name` with either (if you're working alone) your name and UVA id ( e.g. `submitter{Nathan Brunelle (njb2b)}`) or (if you're working in a cohort) your cohort name (e.g. `submitter{Cohort Lamport}`)
1. Answer each question in the corresponding `.tex` file after the `\answer` line. 
1. When you're ready to submit, replace the line, `\usepackage{toc}` (the second line in the file) with `\usepackage[response]{toc}`. You can do this by using the LaTeX comment token, %. The rest of the line after a % is treated as a comment. 
1. Rebuild the PDF by clicking *Recompile*. You should see many things disappear and other things reappear
1. Download the pdf to your machine, name it `ps9.pdf`.
1. Upload your pdf to [kytos](https://kytos.cs.virginia.edu/cstheory) to submit.


# Optional Videos

