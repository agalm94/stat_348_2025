# Modern Methods of Applied Statistics (Spring 2025) STAT 34800
Instructor: Aaron Schein <br>
TAs: Jimmy Lederman, Sean O'Hagan, Jinwen Yang <br>

Term: Spring 2025 <br>
The University of Chicago

---

## Logistics:
- Time: Tuesday and Thursday, 3:30am-4:50pm
- Place: Eckhart room 133
- TA office hours (starting week of March 31): 
    - Jimmy: Fri 9-10am (Jones 304)
    - Sean: Wed 10-11am (Jones 304)
    - Jinwen: Thu 11am-12pm (Jones 303)


## Assignments
- [Assignment 1: Bayesian linear regression](https://github.com/aschein/stat_348_2025/blob/main/assignments/hw1.ipynb). Due **Sunday April 6 at 11:59pm** on GradeScope. 
- [Assignment 2: Hierarchical models and Gibbs sampling](https://github.com/aschein/stat_348_2025/blob/main/assignments/hw2/hw2.ipynb). Due **Sunday April 13 at 11:59pm** on GradeScope. 

## Schedule

### Lecture 1 (March 25): Intro to probabilistic modeling and Bayesian statistics
- Reading / resources (optional; for reference) roughly in the order as they appeared in lecture:
    - [Materials for L1-L2](https://dynalist.io/d/ehiGZbaDzYG4q9tJvuCrag3U#z=Hu-cB8VnWnu5IXOgZ-3MaF6C) from Mathew Stephens' STAT 348 (2021) on **the two-class problem and decision theory** 
    - [Section 8.6](https://www.cs.ubc.ca/~murphyk/MLbook/pml-toc-1may12.pdf) of Kevin Murphy's _Machine Learning: a Probabilistic Perspective_ (2012) on **generative vs discriminative classifiers**
    - [Section 3.5](https://www.cs.ubc.ca/~murphyk/MLbook/pml-toc-1may12.pdf) of Kevin Murphy's _Machine Learning: a Probabilistic Perspective_ (2012) on **Naive Bayes classifiers**
    - [Wikipedia on "Additive smoothing"](https://en.wikipedia.org/wiki/Additive_smoothing) aka **"Laplace smoothing"**
    - [Section 3.3](https://www.cs.ubc.ca/~murphyk/MLbook/pml-toc-1may12.pdf) of Kevin Murphy's _Machine Learning: a Probabilistic Perspective_ (2012) on **the beta-binomial model**
    - [Chapter VI "On Induction"](https://www.ditext.com/russell/rus6.html) of Bertrand Russell's _Problems of Philosophy_ on **"Bertrand's chicken"**
    - [Chapter 2.2 "The meaning of probability"](https://www.inference.org.uk/itprnn/book.pdf) of David Mackay's _Information Theory, Inference, and Learning Algorithms_ (2003), on **frequentist versus subjectivist interpretations of probability**
    
- Lecture notes: 
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_1.pdf) (apologies for the handwriting)

### Lecture 2 (March 27): Bayesian linear regression, prior/posterior predictives, model evaluation
- Reading / resources (optional; for reference) roughly in the order as they appeared in lecture:
    - [Chapter 9 "Linear Regression" of Deisenroth et al.'s _Mathematics for Machine Learning_](https://mml-book.github.io/book/mml-book.pdf) which contains many derivations for quantities in **Bayesian linear regression**
    - [Jeffrey Miller's slides](https://jwmi.github.io/BMB/5-Bayesian-linear-regression.pdf) on **Bayesian linear regression**
    - [Scott Linderman's slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture01-bayes_normal.pdf) on **Bayesian analysis of Gaussian models**
    - ["Conjugate Bayesian analysis of the Gaussian distribution" by Murphy (2007)](https://www.cs.ubc.ca/~murphyk/Papers/bayesGauss.pdf)
    - [Chapter 28 "Model Comparison and Occam’s Razor"](https://www.inference.org.uk/itprnn/book.pdf) of David Mackay's _Information Theory, Inference, and Learning Algorithms_ (2003)
      
- Lecture notes: 
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_2.pdf)
 
### Lecture 3 (April 1): Hierarchical models, Gaussian variance priors, preview to MCMC and PGMs
- Reading / resources (optional; for reference) roughly in the order as they appeared in lecture:
    - [Materials for L4](https://dynalist.io/d/ehiGZbaDzYG4q9tJvuCrag3U#z=Hu-cB8VnWnu5IXOgZ-3MaF6C) from Mathew Stephens' STAT 348 (2021) on **shrinkage, empirical Bayes, the "Normal means" problem** 
    - [Scott Linderman's slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture01-bayes_normal.pdf) on **Bayesian analysis of Gaussian models**
    - [Chapter 5 "Hierarchical models"](https://sites.stat.columbia.edu/gelman/book/BDA3.pdf) of Andrew Gelman et al.'s _Bayesian Data Analysis_
      
- Lecture notes: 
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_3.pdf)
 
### Lecture 4 (April 3): Gibbs sampling and MCMC
- Reading / resources (optional; for reference) roughly in the order as they appeared in lecture:
    - [Parts 1 and 2 of David Blei's lecture notes](https://www.cs.columbia.edu/~blei/fogm/2016F/doc/graphical-models.pdf) on the **basics of directed PGMs**
    - Chapters 11.2-11.3 of Bishop (2006) [_Pattern Recognition and Machine Learning_](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) on **MCMC and Gibbs sampling**
    - [Matthew Stephen's vignette](https://stephens999.github.io/fiveMinuteStats/gibbs1.html) on **Gibbs sampling**
    - [Scott Linderman's slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture04_mcmc.pdf) on **MCMC**
    - ["Getting it Right: Joint Distribution Tests of Posterior Simulators" by Geweke (2004)](http://qed.econ.queensu.ca/pub/faculty/ferrall/quant/papers/04_04_29_geweke.pdf) (**the original Geweke testing paper**)
    - [Roger Grosse's blogpost](https://lips.cs.princeton.edu/testing-mcmc-code-part-2-integration-tests/) on **Geweke testing**"
      
- Lecture notes: 
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_4.pdf)

### Lecture 5 (April 8): Bayesian mixture models, conjugacy and exponential familes
- Reading / resources (optional; for reference) roughly in the order as they appeared in lecture:
    - Chapters 9.1-9.2 of Bishop (2006) [_Pattern Recognition and Machine Learning_](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) on **mixture models**
    - [Scott Linderman's slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture07-mixtures.pdf) on **Bayesian mixture models**
    - [David Blei's lecture notes](http://www.cs.columbia.edu/~blei/fogm/2016F/doc/gibbs.pdf) on **Bayesian mixture models**
    - ["Dealing with label switching in mixture models" by Stephens (2000)](https://stephenslab.uchicago.edu/assets/papers/Stephens2000b.pdf)
    - [David Blei's lectures notes](https://www.cs.columbia.edu/~blei/fogm/2015F/notes/exponential-family.pdf) on **conjugacy and exponential families**
    - [Jeffrey Miller's slides](https://jwmi.github.io/BMB/3-Conjugate-priors.pdf) on **conjugate priors**
      
- Lecture notes: 
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_5.pdf)

### Lecture 6 (April 10): The EM algorithm
- Reading / resources (optional; for reference) roughly in the order as they appeared in lecture:
   - Chapter 9 of Bishop (2006) [_Pattern Recognition and Machine Learning_](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) on **mixture models and EM**
   - [Scott Linderman's slides](https://github.com/slinderman/stats305c/blob/spring2023/slides/lecture08-em.pdf) on **EM**
   - Section 6.2.1 (and related sections) of ["Graphical models, exponential families, and variational inference" by Wainwright & Jordan (2008)](https://www.cs.princeton.edu/courses/archive/fall11/cos597C/reading/WainwrightJordan2008.pdf) on **EM in exponential families**
   - ["Homeomorphic-Invariance of EM..." by Kunstner et al. (2021)](https://proceedings.mlr.press/v130/kunstner21a/kunstner21a.pdf) on the **convergence properties of EM**

- Lecture notes: 
    - [iPad notes](https://github.com/aschein/stat_348_2025/blob/main/lecture_materials/ipad_notes/lecture_6.pdf)






