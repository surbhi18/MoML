---
layout: home
title: Foundations of Modern Machine Learning
nav_exclude: true
permalink: /:path/
seo:
  type: CIS 7000
  name: Foundations of Modern Machine Learning - Theory and Empirics
---

**Lecture time**: Tuesdays and Thursdays 1:45-3:15 PM

**Lecture location**: Zoom (for September), DRLB 3C8

**Instructor**: {% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

**Instructor office hours**: Tuesday at 10:30-11:30AM (Zoom / Levine 505)

We will be using Ed Discussion for all course communications. You can post privately on Ed to contact me, when needed.

**Waitlist information**: This course is capped at 25, and will require active participation from the students including role-playing style discussions, and paper presentations. If you are on the waitlist and you think the course is a good fit for you, please email me.

## Course Overview

This advanced graduate-level course will focus on the latest theoretical and empirical developments in modern machine learning, with a primary focus on deep learning. We will explore cutting-edge machine learning methods such as transformers, diffusion models, self-supervised learning, and more, with an emphasis on the conceptual basis behind their design, success, and limitations. In addition to evaluating in-distribution performance, we will also assess out-of-distribution performance, robustness, emergent behavior, and optimization challenges and mysteries of these models. We will cover classical theoretical results in statistical machine learning and optimization, and explore their connections (or lack thereof) to recent empirical and theoretical research findings.

The [course schedule](calendar.md) contains the tentative schedule including topics we will cover in the lectures and relevant reading material. 

## Grading

Your grade will be based on three components: **Paper Presentation + Review 30%; Class Participation 25%; Final Project 45% (10% proposal + 10% progress report + 15% final report + 10% presentation)**. There will be no homeworks or exams.

## Class Format

This course will feature a combination of lectures, and student presentations, with a significant portion of class time dedicated to in-depth discussions of the presented material. There will also be a few guest lectures from leading researchers from industry and academia. The lectures will typically cover the core technical concepts. This will be followed by paper discussions involving role-playing inspired by [Alec Jacobson and Colin Raffel](https://colinraffel.com/blog/role-playing-seminar.html). We will be adopting a subset of the following roles:

- _Reviewer_: The paper has been submitted to NeurIPS, and you have been assigned to review it. Follow the [review form](https://neurips.cc/Conferences/2023/ReviewerGuidelines) from NeurIPS as a guideline and submit a review for this paper. 
- _Archaeologist_: You’re an archeologist who must determine where this paper sits in the context of previous work. You must find and report on atleast one _older_ paper cited within the current paper that substantially influenced the current paper and atleast one _newer_ paper that cites this current paper. Look out for follow-up work that offers criticism of the current paper.
- _Student Researcher_: You are looking for a new research problem and the paper piqued your interest. You have to come up with follow-up project ideas based on the paper. These can be direct improvements of the paper, or projects that use the papers results as building blocks.
- _Reproducibility Checker_: You want to check whether the claims of the paper are valid. You decide to create a small experiment (toy dataset, or toy model) and verify if the results hold. Make sure to check how robust they are to various choice of hyperparameters.
- _Quanta Correspondent_: You want to write an article on the paper for Qanta. You must explain to a broad audience the main problem the paper is addressing, why it is impotant, and what the main technical contributions are.

Paper readings will be posted a week prior to the lecture. You will be able to access them from the schedule, at least one week prior to the class. The readings marked as _discussion_ will be presented in the above-mentioned role-play style. A sign-up sheet will be provided for discussion roles for each such reading - eight students will take a subset of the above mentioned role. This role defines the lens through which you must read the paper and what you should prepare for the in-class discussion. Each student will be expected to take the 'Reviewer' role for approximately 3 readings. Along with the review, the 'Reviewer' role also requires the student to present the paper to the class. For those, who are not assigned a role, you will be required to submit at least one question (_clarification or discussion point_) prior to the lecture. This will count towards your class participation grade.

## Prerequisites
There are no official prerequisites however students are expected to have mathematical maturity and proficiency in probability, linear algebra, statistics, and fundamental machine learning concepts. Familiarity with the topics covered in CIS 5200 is recommended, but not required. While the course will primarily focus on concepts and theory, some small-scale empirical explorations will be expected, requiring a basic understanding of Python or the ability to learn it through self-study. 

The following books are useful for background reading.

- Machine Learning (ML) by Tom Mitchell. Available as PDF [here](http://www.cs.cmu.edu/~tom/mlbook.html). A classic introduction to machine learning that assumes no knowledge of statistics or artificial intelligence. 
- Elements of Statistical Learning (ESL) by Trevor Hastie, Robert Tibshirani and Jerome Friedman. Available as PDF [here](https://hastie.su.domains/Papers/ESLII.pdf).
- Probabilistic Machine Learning: An Introduction (PML) by Kevin Murphy. Available as PDF [here](https://probml.github.io/pml-book/book1.html).
- Understanding Machine Learning: From Theory to Algorithms (UML) by Shai Shalev-Shwartz and Shai Ben-David. Available as PDF [here](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf). Refer to this book for a more detailed theoretical exposition of the material covered in class.
- Mathematics for Machine Learning (MML) by Marc Deisenroth, A. Aldo Faisal, and Cheng Soon Ong. Available as PDF [here](https://mml-book.github.io/book/mml-book.pdf).
- Linear Algebra Review and Reference by Zico Kolter. Available as PDF [here](http://www.cs.cmu.edu/~zkolter/course/15-884/linalg-review.pdf).

## Resources 

We will be reading several seminal works in machine learning as well as very recent works that have not yet been peer-reviewed. Therefore, learning how to effectively read, review, and present research papers will be a primary focus of the class. [Learning Theory Alliance](www.let-all.com) has some very helpful resources on tips for effectively reading papers ([read1](https://let-all.com/assets/slides/How-to-ALT22-Aaditya.pdf) and [read2](https://let-all.com/assets/slides/How-to-ALT22-Sam.pdf)) and reviewing ([review1](https://let-all.com/assets/slides/How-to-ALT22-Csaba.pdf)) that I encourage you to check out. The first lecture will cover some of this material.

## Wellness Statement

Your mental health and wellbeing are incredibly important to us and we recognize the stresses (both school and non-school related) that many of you may be under here at Penn. We encourage you to come speak to the us as well as the TAs if you have any extenuating circumstances as you progress through this course.

We want to make sure that you are aware of some of the mental health resources here at Penn.
- [Student health and counseling](https://wellness.upenn.edu/student-health-and-counseling): the primary care and psychological care division of Wellness at
Penn which can be used to schedule counseling appointments.
- [Mental health at Penn](https://wellness.upenn.edu/): Penn’s mental health hub.
- If there is any urgent concern, please contact CAPS at 215-898-7021 for emergency help.

If you are a victim of, witness, or are otherwise affected by unacceptable behavior:
- In cases of sexual harassment and assault, please consult [DPS Special Services](https://www.publicsafety.upenn.edu/about/special-services/sensitive-crimes/) at 215-573-3333 or 511 from a campus phone; this is a confidential resource.
- To report other bias incidents, contact the [Penn Office of Diversity](https://diversity.upenn.edu/diversity-at-penn)
- For other bias violations of the code of student conduct, the Office of Student Conduct has an [bias incident reporting form](https://diversity.upenn.edu/diversity-at-penn/bias-motivated-incident-report)

## DEI Statement

At Penn and in this class we value and actively seek to include all students and their unique identities (including but not limited to ethnicity, gender, sexual orientation, country of origin, class, religion, and disability status). You belong here, and we are here to help you. If at any time, you feel that this class is not providing an inclusive environment to your or your classmates, please let us know. We want this class, lectures, discussions, and office hours to be an inclusive space where you feel comfortable learning. 
