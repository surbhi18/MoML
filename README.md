---
layout: home
title: "CIS 3333: Mathematics of Machine Learning (Fall 2025)"
nav_exclude: true
permalink: /:path/
seo:
  type: CIS 3333
  name: "CIS 3333: Mathematics of Machine Learning (Fall 2025)"
---
**Announcement: The lectures will start on Wednesday, August 27, 2025. More details to follow.** 

**Lecture time**: Mondays and Wednesdays 3:30–5:00 PM

**Lecture location**: CHEM 109

**Instructor**: {% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

**Instructor office hours**: Mondays 5:00-6:00 PM (after class) in AGH623

**TAs**: {% assign tas = site.staffers | where: 'role', 'TA' %}
{% for staffer in tas %}
{{ staffer }}
{% endfor %}

**TA office hours**: Tuesdays 5:00-6:00 PM (Maya, location TBA), Wednesdays 2:00-3:00 PM (Ezra, location TBA), Thursdays 2:00-3:00 PM (Guru, AGH 6th floor outside 642)

Please use Ed Discussion for all course communications. You can post privately on Ed to contact me, when needed.

**Registration**: To register, you need to sign up both on [courses.upenn.edu](https://courses.upenn.edu/) and also submit the questionnaire on the [CIS waitlist](https://advising.cis.upenn.edu/waitlist/) before I can add you to the course.

## Course Overview

Machine learning is the science of algorithms that learn patterns from data – whether that's recognizing faces, predicting stock prices, or generating text. Behind every machine learning algorithm lies a rich mathematical foundation: probability theory tells us when models will generalize to new data, linear algebra gives us the language to represent high-dimensional patterns, and optimization theory explains how learning algorithms find good solutions.

While you've likely studied these topics in your prerequisite courses, machine learning demands a deeper, more unified understanding. This course provides a second exposure to these mathematical foundations, specifically tailored for machine learning applications. Based on [Mathematics for Machine Learning](https://mml-book.github.io/), the course is structured around three mathematical pillars, each following a pattern of review → fundamentals → ML applications:

1. **Probability & statistics**
- **Core question**: When do training results generalize to new data? How much data is enough?
- **Tools**: probability spaces and distributions, expectations and variance, concentration inequalities (Markov, Chebyshev, Hoeffding), union bounds, empirical risk minimization.
- **Outcome/example**: Generalization bounds that explain why learning from finite data works.

2. **Linear & functional analysis**
- **Core question**: What functions can our models represent? What inductive biases do we impose?
- **Tools**: vector spaces, inner products, orthogonality and projections, matrix decompositions (SVD), function spaces, reproducing kernel Hilbert spaces (RKHS).
- **Outcome/example**: Representer theorems that characterize solutions to regularized learning problems.

3. **Calculus & optimization**
- **Core question**: How do optimization algorithms find good solutions? When do they converge and how fast?
- **Tools**: gradients and Hessians, convexity and smoothness, constrained optimization, gradient descent and stochastic variants.
- **Outcome/example**: Convergence rates for gradient-based optimization in machine learning.


## Course Attributes

- This course counts as a mathematics elective for engineering degrees.
- This course counts as a standalone co-requisite/pre-requisite for CIS5200.

## Prerequisites
We will assume you’ve taken a basic introductory course in calculus, probability, and linear algebra. For a typical degree in computer science at Penn, this is typically:

- STAT4300 or CIS2610 or equivalent (discrete probability)
- MATH1400 or MATH1410 or equivalent (calculus)
- MATH2400 or equivalent (linear algebra)

If you have 2 out of the 3 pre-requisites, you can review the missing background and take the course. The pre-requisite topics are covered in chapters 2, 5, and 6 of the course textbook.

The following books are useful for background reading.

- Machine Learning (ML) by Tom Mitchell. Available as PDF [here](http://www.cs.cmu.edu/~tom/mlbook.html). A classic introduction to machine learning that assumes no knowledge of statistics or artificial intelligence. 
- Elements of Statistical Learning (ESL) by Trevor Hastie, Robert Tibshirani and Jerome Friedman. Available as PDF [here](https://hastie.su.domains/Papers/ESLII.pdf).
- Probabilistic Machine Learning: An Introduction (PML) by Kevin Murphy. Available as PDF [here](https://probml.github.io/pml-book/book1.html).
- Understanding Machine Learning: From Theory to Algorithms (UML) by Shai Shalev-Shwartz and Shai Ben-David. Available as PDF [here](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf). Refer to this book for a more detailed theoretical exposition of the material covered in class.
- Mathematics for Machine Learning (MML) by Marc Deisenroth, A. Aldo Faisal, and Cheng Soon Ong. Available as PDF [here](https://mml-book.github.io/book/mml-book.pdf).
- Linear Algebra Review and Reference by Zico Kolter. Available as PDF [here](http://www.cs.cmu.edu/~zkolter/course/15-884/linalg-review.pdf).


## Grading

There will be approximately 10 short homeworks (estimated weekly) totaling 40% of your grade which will be submitted handwritten. Homeworks will be due a week after they are assigned. There will also be 3 midterms at 18% each, one per focus area. For the midterms, you will be allowed to resubmit corrected solutions (within a week of receiving the grades) with a clear explanation of the mistake for up to 75% of the points. The remaining 6% will be for in-class participation (2% for each of the three focus areas).

Each student will have 120 cumulative hours (5 days) of late time (as measured on Gradescope), which will be forgiven. After this cumulative amount of time has passed, any assignment that is turned in late will receive zero credit. If you have extenuating circumstances, please reach out to me on Ed.


## Textbook

The primary textbook is [Mathematics for Machine Learning](https://mml-book.github.io/) by Deisenroth, Faisal, and Ong. Additional readings will be assigned from the books listed above.

## AI Tools & Learning Strategy

**Philosophy**: AI tools like ChatGPT and Claude are powerful learning aids when used strategically. However, using them as shortcuts for homework will undermine your mathematical reasoning skills and hurt your performance on exams.

**Strategic Use for Learning**:
- **Concept clarification**: "Explain what a Hilbert space is" or "What's the intuition behind the representer theorem?"
- **Notation help**: "What does this mathematical notation mean?"
- **Study preparation**: Generate practice problems or alternative explanations of textbook concepts
- **Debugging understanding**: "I think X, but I'm getting confused about Y..."

**Why struggle is valuable**: Mathematical reasoning develops through working through challenging problems yourself. If concepts feel difficult at first, that's completely normal and part of the learning process. The moments when things finally "click" after wrestling with ideas are when real understanding develops.

**Bottom line**: Use AI tools to enhance your understanding, not replace your thinking. The goal is to become a better mathematical reasoner, and that requires practicing the hard parts yourself.


## Wellness Statement

Your mental health and wellbeing are incredibly important to me and I recognize the stresses (both school and non-school related) that many of you may be under here at Penn. I encourage you to come speak to me if you have any extenuating circumstances as you progress through this course.

I want to make sure that you are aware of some of the mental health resources here at Penn.
- [Student health and counseling](https://wellness.upenn.edu/student-health-and-counseling): the primary care and psychological care division of Wellness at Penn which can be used to schedule counseling appointments.
- [Mental health at Penn](https://wellness.upenn.edu/): Penn’s mental health hub.
- If there is any urgent concern, please contact CAPS at 215-898-7021 for emergency help.

If you are a victim of, witness, or are otherwise affected by unacceptable behavior:
- In cases of sexual harassment and assault, please consult [DPS Special Services](https://www.publicsafety.upenn.edu/about/special-services/sensitive-crimes/) at 215-573-3333 or 511 from a campus phone; this is a confidential resource.
- To report other bias incidents, contact the [Penn Office of Diversity](https://diversity.upenn.edu/diversity-at-penn)
- For other bias violations of the code of student conduct, the Office of Student Conduct has an [bias incident reporting form](https://diversity.upenn.edu/diversity-at-penn/bias-motivated-incident-report)

## DEI Statement

At Penn and in this class we value and actively seek to include all students and their unique identities (including but not limited to ethnicity, gender, sexual orientation, country of origin, class, religion, and disability status). You belong here, and I am here to help you. If at any time, you feel that this class is not providing an inclusive environment to your or your classmates, please let me know. I want this class, lectures, discussions, and office hours to be an inclusive space where you feel comfortable learning and sharing your opinion.

## Changes

I reserve the right to make changes to the syllabus including lecture contents and homework due dates. These changes will be announced as early as possible.
