# Creating flexible e-learning quizzes with literate programming

### OZCOTS presentation (2023-12-15)

<!-- badges: start -->
<!-- badges: end -->

Slides and notes for a presentation about moodlequiz at the 11th
Australian Conference on Teaching Statistics (OZCOTS 2023).

Authored by:
* Mitchell O'Hara-Wild (presenting author)
* Emi Tanaka
* Thomas Fung
* Iris Jiang

#### Abstract

E-learning quizzes with automated marking systems allow educators to
assess students’ abilities, motivate learning, give automatic and
instant feedback, and are scalable to a large number of students. Many
quiz questions prevalent in teaching statistics use numerical and
single/multiple choice responses. These types of questions can be
algorithmically generated to create multiple versions of the question
with different instances of randomised tasks, datasets and/or inputs. In
practice, quiz creators must conform to a constrained and/or rigid
structure due to the limitations of the deployment platform, which may
not align with the natural order of thinking.

In this talk, I provide a higher-order overview of creating algorithmic
e-learning quizzes and propose a set of literate programming design
principles for a robust, yet flexible system to create these quizzes.
The design of this system is implemented in the moodlequiz R package for
the free and open-source learning management platform Moodle. The core
set of literate programming design principles can be extended to other
learning management platforms.

#### Structure

- Introduction
- Moodle quizzes
- Why Moodle? (Own use, open source, question imports)
- Improved quiz creation
- Literate programming in teaching statistics
- Introducing moodlequiz
- Use for writing quizzes
- Randomisation
- Future work (Quarto, other platform formats)

#### Format

12 minute presentation, 3 minutes for questions.

#### Bio

Mitchell O’Hara-Wild (he/him) is a PhD student, teaching associate and
research assistant at Monash University. He teaches applied forecasting,
and specialises in R package development, data analysis and statistical
computing. Mitchell holds a Bachelor of Commerce (Honours) with a major
in econometrics, and a Bachelor of Science majoring in computational
science and mathematical statistics. He develops several widely used R
packages, and operates a data consultancy in which he conducts
workshops, explores data, and creates statistical software tools.
