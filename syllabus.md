# Syllabus

CPSC 121 (Programming Language Concepts)  
Ben Blazak <ic07@csu.fullerton.edu>  
<https://github.com/2015-fall-csuf-benblazak-cpsc-121>

**Note: These course documents are not yet final.  No extra credit will be
given for errors found in any of these documents until this notice is removed
(though, pull requests are still welcome before then).**


## Calendar

[XML] (https://www.google.com/calendar/feeds/os02kggflfvf2oqrdceu18js9o%40group.calendar.google.com/public/basic)
| [ICAL] (https://www.google.com/calendar/ical/os02kggflfvf2oqrdceu18js9o%40group.calendar.google.com/public/basic.ics)
| [HTML] (https://www.google.com/calendar/embed?src=os02kggflfvf2oqrdceu18js9o%40group.calendar.google.com&ctz=America/Los_Angeles)

### Meeting Times
|   |   |   |   |
|---|---|---|---|
Lecture | Tu Th | 08:30--09:20 | CS 110B
Lab     |    Th | 09:30--11:20 | CS 204

<!-- TODO -->
Midterm: Thursday, October 15, during normally scheduled lecture and lab
Final Exam: Thursday, December 17, from 09:30--11:20, location TBA

### Office hours
<!-- TODO -->
Location and time TBA

### Homework and Lab Assignments, and Quizzes

Homework and lab assignments will be given approximately every week (or more or
less, depending on the difficulty of the assignment).  These will mostly be
programming assignments, but may include other work that I feel contributes to
the course overall.

Quizzes will be given at every meeting, or as often as I feel is necessary to
provide students with ample opportunity to assess their knowledge.


### Tests

There will be two tests.  The first may cover everything discussed to that
point.  The second (the final exam) may cover everything listed in the course
[standards][] (whether we cover it in class or not).

### Tentative Schedule [1](#footnotes)

| Topic | Chapter(s) (from the Gaddis textbook) | Number of Weeks |
|-------|---------------------------------------|-----------------|
                        Review of CPSC 120 | 1--6, 8 | 3
                          OOP Introduction | 7       | 2
                                  Pointers | 10      | 1
Searching, Sorting, and Algorithm Analysis | 9       | 1.5
                                  (Test 1) |         | 0.5
                                  More OOP | 11      | 2
                                 Recursion | 14      | 1
                              Advanced OOP | 15      | 2
                        Thanksgiving Break |         |
        Exceptions, Templates, and the STL | 16      | 2
                     (Test 2 (Final Exam)) |         |


## Course Information

### Description

|   |   |
|---|---|
units         | 3
time          | 2 hours lecture, 2 hours activity
prerequisites | CPSC 120 or passing score on Computer Science Placement Exam
topics        | The object-oriented programming paradigm: classes, member functions, interfaces, inheritance, polymorphism, and exceptions. Design practices including encapsulation, decoupling, and documentation.  Pointers/references and memory management. Recursion.

### Objectives

To reinforce the material covered in CPSC 120, introduce Object Oriented
Programing, and prepare students for the material covered in CPSC 131.

### Learning Goals

To be proficient in all listed [standards][].

### Required Texts and Other Required Materials

No materials (books, etc.) are required.  Access to a personal computer on
which to do homework assignments is strongly recommended.  If you wish for a
book, the one I will be referencing is "Starting Out with C++: Early Objects,
8th ed" by Gaddis, Walters, and Muganda (which you may already have from CPSC
120).

### Etiquette (Classroom Expectations)

Personal electronics shall not be used in either lecture or lab, unless they
are silent, lying flat on your desk, and being used solely to take notes and/or
record the lecture (with the permission of all present).  Non-personal
electronics shall be used solely for the completion of assigned work, and shall
also, in all cases, be silent, and used as unobtrusively as possible.

Communication, including body language and general attitude, are expected to be
respectful at all times.  Everyone present is also expected to be focused and
participating in the current classroom activity.

If you are unable or do not wish to abide by these rules, you may be asked to
leave.


## Grading

### Method

The grading for this course will be standards based.  This means that your
grade will depend on demonstrating competency on a number of [standards][]
rather than on your performance on any particular test, quiz, or homework
assignment.

### Homework and Lab Assignments

Homework and lab assignments will be posted to the course [GitHub page][].
They will be graded for feedback, but the only score that will be recorded is
whether or not the assignment was completed.  You are encouraged to work
together with other students, but discouraged from using material generated by
anyone outside our class.  You are required to clearly document the source of
any code, algorithms, information, etc. that you use or reference while
completing your work.  You are also required to explicitly state the copyright
and licence under which you release your code.

Your percentage score for homework and lab assignments will be the percentage
of homework and lab assignments completed.

### Quizzes and Tests

Quizzes and tests will be given primarily on paper, but may be posted to the
course [GitHub page][].  Applicable [standards][] will be listed, and you will
receive a grade for each as follows:

| score | description |
|:------|:------------|
1    | not enough information to assess
2    | you have heard of the skill
3    | you understand and can apply the skill at a basic level
3.5  | you are between basic competency and mastery
3.75 | you have mastered the skill, but your presentation has trivial errors
4    | you have mastered the skill

Most standards will be assessed several times.  I will look at the trend of
these assessments and use my judgement to assign you an overall grade.  For
instance, given the assessments for some standard below, I might assign overall
grades as follows [2](#footnotes):

| A1 | A2 | A3 | A4 | A5 | Overall Grade |
|----|----|----|----|----|---------------|
|2   |3   |3   |3.5 |3.5 |3.5

In this case it is apparent that the scores are trending upward and that the
student's skill level is currently around 3.5.

| A1 | A2 | A3 | A4 | A5 | Overall Grade |
|----|----|----|----|----|---------------|
|2   |3   |4   |2   |3   |3

In this case the scores are oscillating around basic competency, and the
student's current skill level is probably around 3.

| A1 | A2 | A3 | A4 | A5 | Final Exam | Overall Grade |
|----|----|----|----|----|------------|---------------|
|1   |2   |1   |1   |2   |4           |4

In this case, the student's scores were awful for the entire semester... but it
looks like they managed to finally figure things out before the final.

| A1 | A2 | A3 | A4 | A5 | Final Exam | Overall Grade |
|----|----|----|----|----|------------|---------------|
|3   |3.5 |4   |3.75|4   |1           |3

This example is somewhat of a special case: if your overall score is 4 going
into the final, the worst I will give you on that standard is a 3.

If the overall grade is less than 3, the percentage score for that standard
will be 0%.  Otherwise, the percentage score for that standard will be the
grade divided by 4.

### Extra Credit

For each programming error I make in code posted on the course [GitHub page][],
the first person to submit a pull request for a correct, well written, and well
formated fix will receive 1 extra credit point.

For each non-programming error I make in anything posted on the course [GitHub
page][], the first person to submit a pull request for a correct, well written,
and well formatted fix will receive 0.5 extra credit points.

Other opportunities for extra credit points may be offered throughout the
course.  See [Extra Credit][].

Extra credit points will be worth 0.2% of your final grade each.

### Conversion to Letter Grade

The percentage score for each standard in a group will be summed and the result
will be divided by the number of standards in that group to give the percent
score for that group.  The percent score for each group will be multiplied by
the percent of the total grade it contributes (see [Standards][]), and the
results for each group will be summed.  The percentage points due to extra
credit will be added, and the resulting percentage will be converted to a
letter grade according to the following table

|   |   |
|---|---|
grade &isin; \[97,100\] | A+
grade &isin; \[93,97\)  | A
grade &isin; \[90,93\)  | A-
grade &isin; \[87,90\)  | B+
grade &isin; \[83,87\)  | B
grade &isin; \[80,83\)  | B-
grade &isin; \[77,80\)  | C+
grade &isin; \[70,77\)  | C
grade &isin; \[50,70\)  | D
grade &isin; \[0,50\)   | F

except that if for any standard your overall grade is less than 3, the highest
grade I will give you for the course is an A-.

Note that plus/minus grading is only used for grades above C.  Note also that
Computer Science majors must earn a grade of C or higher in this course to
receive credit; if a lower grade is earned, the course will have to be
repeated.  Please keep all assignments and exams returned to you so that any
discrepancies can be easily and fairly corrected.  Except in cases of actual
error on my part, final grades will not be changed.

### Late Assignments

Late assignments will not be accepted for credit.  However, when I grade the
assignments for feedback, I will grade the latest version that I have on hand.

### Alternative Procedure for Submitting Work

In case of technical difficulties with GitHub, assignment due dates will be
postponed, or an alternate method of submission will be communicated.  In the
case of an emergency that disrupts normal campus operations or causes the
University to close for a prolonged period of time due to circumstances such as
an earthquake, we will continue our class online, via methods to be
communicated.  In the case of a simultaneous internet outage effecting myself
of the majority of the class, you are requested to continue studying according
to the [tentative schedule][]; classes may well be canceled, but learning on
your own will give you the opportunity to challenge the course when the
University reopens.

### Attendance

I reserve the right to drop you if you are absent without notifying either me
or the departmental office within 24 hours after any meeting missed during the
first week of classes, or if you do not meet the course prerequisites.

I expect you to be present for the entirety of the first meeting, and for roll
call during the first week.  Apart from this attendance is not required, nor
will roll be taken.

### Standards

See [Standards][]


## University Information

### Students with Special Needs

Please inform the instructor during the first week of classes about any
disability or special needs that you may have that may require specific
arrangements related to attending class sessions, carrying out class
assignments, or writing papers or examinations.  According to California State
University policy, students with disabilities must document their disabilities
at the Disability Support Services (DSS) Office in order to be accommodated in
their courses.  Additional information can be found at the [DDS
website](http://www.fullerton.edu/dss/), by calling 657-278-3112, or by
emailing <dsservices@fullerton.edu>.

### Academic Dishonesty Policy

Academic dishonesty includes such things cheating, inventing false information
or citations, plagiarism, and helping someone else commit an act of academic
dishonesty.  It usually involves an attempt by a student to show a possession
of a level of knowledge or skill, which he/she in fact does not possess.
Cheating is defined as the act of obtaining or attempting to obtain credit for
work by the use of any dishonest, deceptive, fraudulent, or unauthorized means.
Plagiarism is defined as the act of taking the work of another and offering it
as one's own without giving credit to that source.  An instructor who believes
that an act of academic dishonesty has occurred (1) is obligated to discuss the
matter with the student(s) involved; (2) should possess reasonable evidence
such as documents or personal observation; and (3) may take whatever action
(subject to student appeal) he/she deems appropriate, ranging from an oral
reprimand to an F in the course.  Additional information on this policy is
available from [University Policy Statement 300.021]
(http://www.fullerton.edu/senate/documents/PDF/300/UPS%20300.021.pdf) found at
the [UPS section of the Academic Senate website]
(http://www.fullerton.edu/senate/documents/ups.asp).

### Emergency Contact

In the event of an emergency, call 911, or contact the University Police at
657-278-2515 (dispatch).  Additional information can be found at the [CSUF
Emergency Preparedness website] (http://emergencypreparedness.fullerton.edu).

### Supplemental Instruction (SI)

The SI program provides weekly, peer-led group study sessions for students
taking historically difficult, gateway, and bottleneck courses.  I was an SI
leader as an undergrad, and I strongly recommend the program (even if you don't
feel you need it!).  If you are interested, more information will be provided.


## Footnotes

1: Adapted from the model schedule on the [ECS Wiki][]'s [CPSC 121 page]
(https://wiki.ecs.fullerton.edu/twinkie/CPSC_121)

2: Adapted from Dr. Glesser's Fall 2013 Math 307 [Grading FAQ]
(https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxhZGFtZ2xlc3NlcnxneDo0NzcxOGM5ZTcwOGViZGQ3)


[GitHub page]: https://github.com/2015-fall-csuf-benblazak-cpsc-121
[extra credit]: ./extra-credit.md
[standards]: ./standards.md
[tentative schedule]: #tentative-schedule
[ECS Wiki]: https://wiki.ecs.fullerton.edu

-------------------------------------------------------------------------------
Copyright &copy; 2015 Ben Blazak <ic07@csu.fullerton.edu>  
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>  
Project located at <https://github.com/2015-fall-csuf-benblazak-cpsc-121>


References:

- [Syllabus and related work by Dr. Adam Glesser for Fall 2013 Math 307]
  (https://sites.google.com/site/adamglesser/Home/all-courses/f13-math-307-linear-algebra/f13-math-307-files)

- The [template]
  (http://fdc.fullerton.edu//teaching/Sample%20Syllabus%20Template%20Rev%208-16-15.docx)
  available via the CSUF [Faculty Development Center]
  (http://fdc.fullerton.edu//teaching/basics.php)
