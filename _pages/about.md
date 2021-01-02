---
permalink: /
title: "Welcome to David Kim's Homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
## Life Goal
 I vision a future where Artificial Intelligence (AI) collaborates with people by augmenting human capabilities, educating and training people in various tasks and activities. To achieve such a goal, I believe AI must have a solid understanding of human cognitive state and it's transitions, in other words, AI must understand what humans are thinking.

## My Academic Goal and Research

 My research goal is to understand human cognition by analyzing their behavior using Machine Learning models. More specific statement can be found in my [Statement of Purpose](https://daki7711.github.io/blob/master/files/Statement_of_Purpose.pdf).

 I am currently working with my advisor [Michael C. Mozer](https://www.cs.colorado.edu/~mozer/index.php) as a Research Assitance for about an year. During this period we have published one [Workshop paper](https://www.cs.colorado.edu/~mozer/Research/Selected%20Publications/reprints/Kimetal2020.pdf) and continuing to produce more results. The overall research project focus on developing intelligent textbooks which infer student understanding based on students' interactions with the textbooks. Given a model of the student's knowledge state, we then hope to customize material for further study and review.

<!---Data were collected in collaboration with [OpenStax](https://openstax.org/), a nonprofit organization that supports open-access college-level digital textbooks. For two full semesters data were collected in Biology, Physics, Sociology, and History classes with 11,134 students. In these classes, students were able to highlight and add annotations to their e-textbooks while reading. Of the 11,134 students, 2,829 used the highlighting facility. Given the record of these highlights and annotation, we attempt to infer student comprehension, as assessed by a quiz that students take at the end of each section as well as delayed review questions administered about a week after initial reading.--->

<!---The goal is to predict quiz performance from the pattern of highlighting. In the previous workshop paper, we built separate linear models for each section of text.  (A section of text is the unit we analyze and the unit that students are quizzed on.) The input data used for prediction is a high dimensional binary feature vector where each feature indicates whether or not a given word of a section is highlighted. The first hurdle was to find the best representation of highlights as input to the linear model. In my [previous work](https://www.cs.colorado.edu/~mozer/Research/Selected%20Publications/reprints/Kimetal2020.pdf), we found that parsing the whole passage into words and reducing the dimension using PCA (Principal Component Analysis) can explain about 13% variance of the test performance. Although, this is an exciting result, this method has two problems. First, is that it is yet to be proven to be generalized in different sections and second it is extremely limited in that it is text dependent: we build a separate model for each section of text and therefore require training data for each section.
--->


