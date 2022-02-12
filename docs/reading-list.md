# Pull together some reading lists on machine learning

- **Topics covered**: econometrics vs machine learning vs deep learning
- **Release date, edition**: newly released books vs established textbooks
- **Programming language**: Python vs R vs Julia (also other open source and proprietary)
- **Access**: free vs paid
- **Code**: repository with code examples

### Scipy Lectures

Great reading that starts with Python bascis and goes into [machine learning tasks](http://scipy-lectures.org/packages/scikit-learn/index.html) with `scikit-learn` in final chapter.

### Approaching (Almost) Any Machine Learning Problem by Abhishek Thakur ("AAAMLP")

![](https://m.media-amazon.com/images/I/41mmATswuAL.jpg)

- [amazon](https://www.amazon.com/Approaching-Almost-Machine-Learning-Problem-ebook/dp/B089P13QHT).
- [author](https://twitter.com/abhi1thakur)
- [Rahul Dave recommends this book](https://twitter.com/rahuldave/status/1280080859681271816)

Annotation:

> This book is for people who have some theoretical knowledge of machine learning and deep learning and want to dive into applied machine learning. The book doesn't explain the algorithms but is more oriented towards how and what should you use to solve machine learning and deep learning problems. The book is not for you if you are looking for pure basics. The book is for you if you are looking for guidance on approaching machine learning problems. The book is best enjoyed with a cup of coffee and a laptop/workstation where you can code along.

### Hands-On Machine Learning by Aurélien Géron

Hands-On Machine Learning with Scikit-Learn, Scikit-Learn, Keras and TensorFlow
by [Aurélien Géron](https://twitter.com/aureliengeron)

> You’ll learn a range of techniques, starting with simple linear regression and progressing to deep neural networks.

- [website](https://homl.info/amazon)
- [TOC](https://www.oreilly.com/library/view/hands-on-machine-learning/9781491962282/)
- [amazon](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow-ebook-dp-B07XGF2G87/dp/B07XGF2G87/)
- [code](https://github.com/ageron/handson-ml2)

![](https://images-na.ssl-images-amazon.com/images/I/51aqYc1QyrL._SX379_BO1,204,203,200_.jpg)

### Julia for Pythonistas by Aurélien Géron

This is a walk-through on Julia programming language by author of Hands-On Machine Learning.

- [code](https://colab.research.google.com/github/ageron/julia_notebooks/blob/master/Julia_for_Pythonistas.ipynb)

## Regression and other stories

Regression and other stories ("ROS") by [Andrew Gelman](https://twitter.com/StatModeling), Jennifer Hill, and [Aki Vehtari](https://twitter.com/avehtari)

- [website](https://avehtari.github.io/ROS-Examples/)
- [TOC](https://assets.cambridge.org/97811070/23987/toc/9781107023987_toc.pdf)
- [PDF](https://users.aalto.fi/~ave/ROS.pdf)
- [code repo](https://github.com/avehtari/ROS-Examples)
- ROS is a newer edition of the predecessor book [Data Analysis Using Regression and Multilevel/Hierarchical Models](http://www.stat.columbia.edu/~gelman/arm/).

## For further review

This section collects items I might add to learning path later. For now please ignore.

Books:

- [@avehtari "BDA" course and book](https://github.com/avehtari/BDA_course_Aalto) (has links to simplier bayesian courses)
- [@rlmcelreath "Statistical rethinking" (SR)](http://xcelab.net/rm/statistical-rethinking/) and [video](https://www.youtube.com/watch?v=4WVelCswXo4&list=PLDcUM9US4XdNM4Edgs7weiyIguLSToZRI&index=1)
- [Full text of ISLR-7](http://faculty.marshall.usc.edu/gareth-james/ISL/ISLR%20Seventh%20Printing.pdf)
- [Data Science at the Command Line](https://twitter.com/jeroenhjanssens/status/1280559408020365318)

Papers:

- [P Huenermund on Causal Inference in Machine Learning and AI"](https://twitter.com/PHuenermund/status/1258480147407257605) (with lessons for econometrics)
- [Athley, Imbens. Machine Learning Methods That Economists Should Know About](https://www.annualreviews.org/doi/abs/10.1146/annurev-economics-080217-053433)
- [Varian. Big Data: New Tricks for Econometrics](https://www.aeaweb.org/articles?id=10.1257/jep.28.2.3)

R learning resources (in response to DataCamp disaster):

- [@djnavarro](https://twitter.com/djnavarro/status/1278470778879569920)
- [@tladeras](https://twitter.com/tladeras/status/1278508718385029120)

Posts:

- Anatomy of a plot and visualisation cheatsheets:
  - [ggplot](https://twitter.com/_isabellamb/status/1269815940629184514)
  - [matplotlib](https://github.com/matplotlib/cheatsheets)

## Quotes

Some quotes to mind awake and open, fooun don Twitter, July 2020.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Statistics means never having to say you’re certain.</p>&mdash; Daniela Witten (@daniela_witten) <a href="https://twitter.com/daniela_witten/status/1281577211456188417?ref_src=twsrc%5Etfw">July 10, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">There are a lot more people who know how to move data around than who know what to do with it.</p>&mdash; Probability Fact (@ProbFact) <a href="https://twitter.com/ProbFact/status/1278359305620729857?ref_src=twsrc%5Etfw">July 1, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Everyone has an idea, what sets people apart is execution.</p>&mdash; Shane Parrish (@ShaneAParrish) <a href="https://twitter.com/ShaneAParrish/status/1278145179032195072?ref_src=twsrc%5Etfw">July 1, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">just because you made the mistakes doesn’t mean you learned the lesson</p>&mdash; Rob Rix (@rob_rix) <a href="https://twitter.com/rob_rix/status/1275224570413359104?ref_src=twsrc%5Etfw">June 23, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

# Glossary

`confounding (factors)`\_
смешанные факторы

`covariate`\_
независимая переменная, предиктор

feature
независимая переменная (в машинном обучении)

feature engineering (FE)
темная магия выбора независимых переменных (в машинном обучении)

inference, `statistical inference`\_
вывод (свойств генеральной совокупности по выборке)

.. \_statistical inference: https://en.wikipedia.org/wiki/Statistical_inference
.. \_confounding (factors): https://en.wikipedia.org/wiki/Confounding
.. \_covariate: https://en.wikipedia.org/wiki/Dependent_and_independent_variables#Statistics_synonyms

# Reading list in machine learning and econometrics

Motivating questions:

- Is econometrics pushed off by machine learning? Why?
- Once you learned some basic methods in Econometrics I class, what is there to learn next?
- How one can update skills and knowledge if you took that class 20 years ago?
- What can economists and econometricians learn form other fields?

## Watching now (2021-05-21)

- [Aubrey Clayton](https://www.youtube.com/playlist?list=PL9v9IXDsJkktefQzX39wC2YG07vw7DsQ_) - reading of The Logic of Science by E.T. Jaynes
- [Paul Hünermund. Causal Inference in Machine Learning and AI](https://twitter.com/PHuenermund/status/1258480147407257605)
- [Sean Taylor keynote Causal Data Science CDSM20](https://www.youtube.com/watch?v=oTeygIetj34)

## Econometrics vs ML

- [Varian, Hal R. 2014. Big Data: New Tricks for Econometrics. Journal of Economic Perspectives, 28 (2): 3-28.](https://www.aeaweb.org/articles?id=10.1257/jep.28.2.3)
  - [extra link](https://people.ischool.berkeley.edu/~hal/Papers/2013/ml.pdf)
- [Machine Learning Methods Economists Should Know About by Susan Athey and Guido W. Imbens
  March 24, 2019](https://www.gsb.stanford.edu/faculty-research/working-papers/machine-learning-methods-economists-should-know-about)

## Causal inference

- [Paul Hünermund. Causal Inference in Machine Learning and AI (with lessons for econometrics)](https://twitter.com/PHuenermund/status/1258480147407257605)

## Probability

- [Probability Theory: The Logic of Science by E.T. Jaynes](https://bayes.wustl.edu/etj/prob/book.pdf), first three chapters
  - by chapter reading of the book by [Aubrey Clayton](https://www.youtube.com/playlist?list=PL9v9IXDsJkktefQzX39wC2YG07vw7DsQ_)
- [stat101 videos](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo) and [Joe Blitzstein, Jessica Hwang Probability book](http://probabilitybook.net)
- [Modern intro to probability and statistics](https://cis.temple.edu/~latecki/Courses/CIS2033-Spring13/Modern_intro_probability_statistics_Dekking05.pdf) by Dekking, Kraaikamp, Lopuhaa, Meester (2005)

## Books

- Scott Cunningham. [Causal Inference: The Mixtape](https://mixtape.scunning.com/).
- Will Kurt. [Bayesian Statistics the Fun Way](https://nostarch.com/learnbayes).
- Richard McElrath. [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking), [video series](https://www.youtube.com/watch?v=h5aPo5wXN8E)
- Judea Pearl. [The Book of Why](https://en.wikipedia.org/wiki/The_Book_of_Why).
- Allen B. Downey. [Think Bayes](http://allendowney.github.io/ThinkBayes2/index.html) или [другая этого автора](https://greenteapress.com/wp/)

## Time series (draft)

- https://twitter.com/SeguraAndres7/status/1398360963330580486

## ML in finance (draft)

- [Marcos Lopez de Prado](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3365271), <https://www.quantresearch.org>
- [Dixon, Halperin, Belokon](https://github.com/mfrdixon/ML_Finance_Codes)

## Next (draft)

- [Causal Data Science CDSM20 – Keynotes](https://causalscience.netlify.app/programme/keynote-videos/)
  - [Sean Taylor (Lyft)](https://www.youtube.com/watch?v=oTeygIetj34)
  - [Elias Bareinboim (Columbia)](https://www.youtube.com/watch?v=kMo2ChRAvuo)
- [Book list by Dimitri Bianco](https://www.youtube.com/watch?v=pOThNItNuqE)
- [Upcoming book in August 2020 - Bernoullis-Fallacy](https://www.amazon.com/Bernoullis-Fallacy-Statistical-Illogic-Science/dp/0231199945)
