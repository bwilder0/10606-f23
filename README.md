# 10-606: Mathematical Foundations for Machine Learning

Instrutor: Bryan Wilder (bwilder@andrew.cmu.edu)

TAs: \
Valerie Chen (vchen2@andrew.cmu.edu)\
Nandini Neralagi (nneralag@andrew.cmu.edu)\
Meghana Rajeev (mrajeev@andrew.cmu.edu)\
Jocelyn Tseng (jocelynt@andrew.cmu.edu)

Office hours: see schedule in Canvas

## Logistics

Questions: Piazza\
Assignment submission: Gradescope\
Both of the above can be accessed through the course Canvas page.

## Course Description
This course provides a place for students to practice the necessary mathematical background for further study in machine learning. Topics covered include probability (random variables, modeling with continuous and discrete distributions), linear algebra (inner product spaces, linear operators), and multivariate differential calculus (partial derivatives, matrix differentials). The course assumes some background in each of the above, but will review and give practice in each. (It does not provide from-scratch coverage of all of the above, which would be impossible in a course of this length.) Some coding will be required: the course will provide practice with translating the above mathematical concepts into concrete programs.

## Course Schedule

| Week | Dates       | Topic                                               | Assignments                              |
|:----:|-------------|-----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1    | Mon: Aug 28  | Class intro, sets [[Lecture notes]](files/notes_sets.pdf)||
| 1    | Wed: Aug 30  | Data types and functions [[Lecture notes]](files/notes_types.pdf) [[Colab notebook](https://colab.research.google.com/drive/1XllrOrSr0a9YP9jfwet9QiBe2zUaNVbx?usp=sharing)]||
| 1    | Fri: Sep 1  | No recitation|[Homework 1](files/Homework-1.pdf) due Sunday|
| 2    | Mon: Sep 4  | No class (Labor day)||
| 2    | Wed: Sep 6  | Linear algebra foundations [[Lecture notes]](files/notes_linalg.pdf) [[Slides]](files/Lecture_3.pptx)|||
| 2    | Fri: Sep 8  | Recitation [[Slides]](files/recitation1slides.pdf)|[Homework 2a](files/hw2a.pdf) due Sunday|
| 3    | Mon: Sep 11  | __Quiz 1__ + Vector spaces [[Lecture notes]](files/notes_vectorspace.pdf) [[Notebook]](https://colab.research.google.com/drive/1oadgRcfa1FX_vq1PxdixC0rLL9WfMJIE?usp=sharing)||
| 3    | Wed: Sep 13  | Matrix operations and Gaussian elimination [[Lecture notes]](files/notes_matrices.pdf) [[Slides]](files/Lecture5.pptx)| |
| 3    | Fri: Sep 15  | Recitation|[Homework 2b](files/hw2b_updated.pdf) due Sunday|
| 4    | Mon: Sep 18  | Matrix factorization, SVD, and linear regression||
| 4    | Wed: Sep 20  | Matrix calculus||
| 4    | Fri: Sep 22  | Recitation|[Homework 3](files/Homework-3.pdf) due Sunday|
| 5    | Mon: Sep 25  | __Quiz 2__ + Convexity and optimization||
| 5    | Wed: Sep 27  | Lagrange multipliers, linear regression and regularization||
| 5    | Fri: Sep 29  | Recitation|Homework 4 due Sunday|
| 6    | Mon: Oct 2  | Probability||
| 6    | Wed: Oct 4  | Joint, marginal, and conditional distributions||
| 6    | Fri: Oct 6  | Recitation|Homework 5 due Sunday|
| 7    | Mon: Oct 9  | Bayes' rule, maximum likelihood and MAP estimators||
| 7    | Wed: Oct 11  | Moments, independence, correlation + review||
| 7    | Fri: Oct 13  | __Quiz 3__ |Homework 6 due Sunday|


## Relationship between 10-606 and 10-607
These two minis are intended to prepare students for further study in machine learning – particularly for taking 10-601 and 10-701. One of the courses (10-606) focuses on mathematical background, and the other course (10-607) focuses on computational background. Most students take both mini courses, but this is not required. 10-606 is not a prerequisite of 10-607.

## Prerequisites
Below is a summary of the background required for 10-606 (consistent with previous offerings):

* We’re assuming mathematical maturity: you should be familiar with the idea of derivations and proofs, and of building formal representations for objects given their English­ language description.
* We’ll assume that you can take scalar derivatives.
* We’ll assume that you’ve seen real vector spaces and matrices (linear operators) and know how to reason about things like matrix multiplication and solving systems of linear equations.
* We’ll assume that you’ve seen sets and data types.
* We’ll assume that you’ve worked with probabilities (e.g., conditioning, Bayes rule).
* We will also assume familiarity with coding. The assignments and in-class activities will include some Python.

For the above topics, we intend to give complete definitions and/or resources to learn from, but often we will go over them quickly: we expect that most people will know a lot of the definitions, and will be willing to work outside of class to understand the ones they don’t know. So, for each topic that you’re unfamiliar with, you should expect to do some extra work; if you’re unfamiliar with several of them, that could make it hard to keep up. Please see the instructor if you are unsure whether your background is suitable for these courses.

## Assignments and grading

The grade of the course is calculated as follows:

* Homeworks: 50%. There will be one homework assignment due at the end of each week.
* Quizzes: 50%. There will be three quizzes, given in class. Roughly, these are scheduled for the beginning of the third week, beginning of the fifth week, and during the last week. Dates will be announced at least one week before. You are required to attend class and complete these in person unless you have an excused absence (for exceptional circumstances only, defined below).

We plan to use the following cutoffs:

≥ 90%:	A\
≥ 80%:	B\
≥ 70%:	C\
≥ 60%:	D\
lower:	R

Some programs use +/- grades as well as full letter grades. If your program is one of these, the cutoffs are at intervals of 3 and 7 percentage points within each letter grade. So, within the A grade, cutoffs are

≥ 97%:	A+\
≥ 93%:	A\
≥ 90%:	A-

and similarly for B, C, D. Each individual component (e.g. a quiz) may be curved upwards at the end. As well, the cutoffs above are merely an upper bound, at the end they may be adjusted down (i.e., to your benefit).

## Resources

There is no required textbook for this course. Lecture notes will be posted that acompany each topic. The following textbooks may be useful as references or sources of additional explanation:
* [Mathematics for Machine Learning](https://mml-book.github.io/). by Marc Peter Deisenroth, A. Aldo Faisal, and Cheng Soon Ong.
* [Matrix Analysis (2nd ed.)](http://www.cambridge.org/us/academic/subjects/mathematics/algebra/matrix-analysis-2nd-edition?format=PB&isbn=9780521548236). Roger A. Horn, Charles R. Johnson. Cambridge University Press, 2013.
* [Advanced Calculus (5th ed.)](https://books.google.com/books/about/Advanced_Calculus.html?id=wywnAQAAIAAJ). Wilfred Kaplan. Pearson, 2002.
* [Introduction to Probability (2nd ed.)](http://www.athenasc.com/probbook.html). Dimitri P. Bertsekas, John N. Tsitsiklis. Athena Scientific, 2008.
* [The Elements of Statistical Learning: Data Mining, Inference and Prediction (2nd ed.)](http://statweb.stanford.edu/~tibs/ElemStatLearn/). Trevor Hastie, Robert Tibshirani, Jerome Friedman. Springer, 2008.

## Course Policies

### Regrade requests
If you believe an error was made during homework grading, you’ll be able to submit a regrade request on Gradescope. For quizes, please visit office hours to request a regrade. Regrade requests will be open for a maximum of 1 week after the grades have been published. This is to encourage you to check the feedback you’ve received early!

### Late policies
You will have 4 flex days across all homework assignments. Late days *cannot* be used for the in-person quizzes. If you miss a quiz due to truly extenuating circumstances (defined below), email the instructor and we will handle the situation on a case by case basis. For homeworks, flex days are handled as follows: 
* Flex days are counted by the granularity of days. For example, if you turn in your assignment 30 minutes after the deadline, that will count as one full flex day.
* You may use these at your discretion, but they are intended for minor illness and other disruptive events outside of your control, and not for poor time management
* You do not need to provide the reason: simply email the teaching staff and tell them how many of your flex days you would like to use.
* You are responsible to keep track of your own flex days. Gradescope will not enforce the total number of flex days
* Once you’ve exhausted your flex days, then point deductions will occur for any assignment submitted after the deadline.
* An assignment submitted 24 hours after the due date will only be eligible for 80% of the maximum number of points allotted.
* Assignments submitted more than 24 hours after the due date will not be accepted.
* Note that you cannot use your flex days for in-class quizzes.

### Extensions and missed quizzes

Aside from flex days there will be no extensions on assignments in general, and there are no excused misses for the in-person quizzes. Such accomodations will be granted only in exceptional circumstances outside of your control (e.g., due to severe illness or major personal/family emergencies, but not for competitions, club-related events or interviews). If you have such a circumstance, please email the instructor as soon as you become aware that you will miss an assignment or quiz. The instructor will require confirmation from University Health Services or your academic advisor, as appropriate.

Nearly all situations that make you run late on an assignment homework can be avoided with proper planning — often just starting early. Here are some examples:
* I have so many deadlines this week: you know your deadlines ahead of time — plan accordingly.
* It's a minute before the deadline and the network is down: you always have multiple submissions - it's not a good idea to wait for the deadline for your first submission.
* My computer crashed and I lost everything: Use Dropbox or similar to do real-time backup - recover your files onto AFS and finish your homework from a cluster machine.
* My fraternity/sorority/club has that big event that is taking all my time: Schedule your extra-curricular activities around your classes, not vice versa.

### Collaboration among Students

The purpose of student collaboration is to facilitate learning, not to circumvent it. Studying the material in groups is strongly encouraged. It is also allowed to seek help from other students in understanding the material needed to solve a particular homework problem, provided no written notes (including code) are shared, or are taken at that time, and provided learning is facilitated, not circumvented. The actual solution must be done by each student alone. The presence or absence of any form of help or collaboration, whether given or received, must be explicitly stated and disclosed in full by all involved. Each assignment concludes with a set of collaboration questions that must be answered to disclose any help given or received. If you gave help after turning in your own assignment and/or after answering the questions above, you must update your answers before the assignment’s deadline, if necessary by emailing the course staff. Collaboration without full disclosure will be handled severely, in compliance with CMU’s Policy on Academic Integrity.

### Previously Used Assignments

Some of the assignments used in this class may have been used in prior versions of this class, or in classes at other institutions, or elsewhere. Solutions to them may be, or may have been, available online, or from other people or sources. It is explicitly forbidden to use any such sources, or to consult people who have solved these problems before. It is explicitly forbidden to search for these problems or their solutions on the internet. You must solve the homework assignments completely on your own. We will be actively monitoring your compliance. Collaboration with other students who are currently taking the class is allowed, but only under the conditions stated above.

### Policy Regarding “Found Code”:

You are encouraged to read books and other instructional materials, both online and offline, to help you understand the concepts and algorithms taught in class. These materials may contain example code or pseudo code, which may help you better understand an algorithm or an implementation detail. However, when you implement your own solution to an assignment, you must put all materials aside, and write your code completely on your own, starting “from scratch”. Specifically, you may not use any code you found or came across. If you find or come across code that implements any part of your assignment, you must disclose this fact in your collaboration statement.

### AI Assistance

To best support your own learning, you should complete all graded assignments in this course yourself, without any use of generative artificial intelligence (AI). Please refrain from using AI tools to generate any content (text, video, audio, images, code, etc.) for an assignment or classroom exercise. Passing off any AI generated content as your own (e.g., cutting and pasting content into written assignments, or paraphrasing AI content) constitutes a violation of CMU’s academic integrity policy. If you have any questions about using generative AI in this course please email or talk to the instructor.

### Accommodations for students with disabilities
If you have a disability and have an accommodations letter from the Disability Resources office, we encourage you to discuss your accommodations and needs with us as early in the semester as possible. We will work with you to ensure that accommodations are provided as appropriate. If you suspect that you may have a disability and would benefit from accommodations but are not yet registered with the Office of Disability Resources, we encourage you to visit their website.
 
### Statement on student wellness 

Please take care of yourself. Do your best to maintain a healthy lifestyle this semester by eating well, exercising, getting enough sleep, and taking some time to relax. This will help you achieve your goals and cope with stress. All of us benefit from support during times of struggle. There are many helpful resources available on campus. Please take advantage of them to support your overall health and wellness during challenging and stressful times (see, for example, Counseling and Psychological Services).

## Diversity Statement
We must treat every individual with respect. We are diverse in many ways, and this diversity is fundamental to building and maintaining an equitable and inclusive campus community. Diversity can refer to multiple ways that we identify ourselves, including but not limited to race, color, national origin, language, sex, disability, age, sexual orientation, gender identity, religion, creed, ancestry, belief, veteran status, or genetic information. Each of these diverse identities, along with many others not mentioned here, shape the perspectives our students, faculty, and staff bring to our campus. We, at CMU, will work to promote diversity, equity and inclusion not only because diversity fuels excellence and innovation, but because we want to pursue justice. We acknowledge our imperfections while we also fully commit to the work, inside and outside of our classrooms, of building and sustaining a campus community that increasingly embraces these core values.

Each of us is responsible for creating a safer, more inclusive environment.

Unfortunately, incidents of bias or discrimination do occur, whether intentional or unintentional. They contribute to creating an unwelcoming environment for individuals and groups at the university. Therefore, the university encourages anyone who experiences or observes unfair or hostile treatment on the basis of identity to speak out for justice and support, within the moment of the incident or after the incident has passed. Anyone can share these experiences using the following resources:

Center for Student Diversity and Inclusion: csdi@andrew.cmu.edu, (412) 268-2150
Ethics Reporting Hotline. Students, faculty, and staff can anonymously file a report by calling 844-587-0793 or visiting https://cmu.ethicspoint.com
All reports will be documented and deliberated to determine if there should be any following actions. Regardless of incident type, the university will use all shared experiences to transform our campus climate to be more equitable and just.

## Attribution

Material throughout is sourced from previous editions by [Pat Virtue](https://www.cs.cmu.edu/~10606-f21/), [Geoff Gordon](http://www.cs.cmu.edu/~ggordon/10606s22/syllabus-and-lecture-outline.html), [Leila Wehbe](https://www.cs.cmu.edu/~lwehbe/10606607_M20/), and [Hoda Heidari](https://www.cs.cmu.edu/~10606-f22/).

