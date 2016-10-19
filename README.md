# welcome_Y2_yearlong
Your one-stop shop for all Y2 yearlong materials [2016-2017]

## This is the 2016-2017 Y2 version of the welcome repo!

If this is not your year perform the following steps to find you year's cohort

1. Click on `branch: master` above.
2. Click on your cohort's branch.

# Notes

In the notes folder, you'll find these things:

* [Daily Schedule](notes/daily_schedule.md): What the schedule looks like each day
* [setup.sh](notes/setup.sh): Script for setting up your environment
* [Pairing](notes/pairing.md): Notes on how to pair program
* [Workflow](notes/workflow.md): Notes on programming workflow
* [Git issues](notes/git_issues.md): Commonly encountered git issues
* [Postgres setup](notes/postgres_setup.md): Notes on setting up postgres
* [Blogging](notes/blog): Notes on creating a blog

# Syllabus

This is the syllabus for the course.  Each row represents a day, readings are to be completed before class on the given day.

* __Day:__ Day of the Week
* __Readings:__ Assigned readings for the day. To be completed before coming into class.
* __Repo:__ The repo contains the day's exercise(s) as well as lecture notes and slides. You should be able to complete this in the time allotted (you will not have access until the day of).
* __Lead Instructor:__ The instructor who is the point person for the day.

This document covers much of what we'll teach you, but you are each other's greatest resource and will ultimately learn the most from each other.

## Schedule

| Week | Date | Topic |
| --- | --- | --- |
| 1 | 1/04/16 | [Software Engineering ](#week-1-software-engineering--eda) |
| 2 | 1/11/16 | [Statistics and Probability](#week-2-statistics-and-probability) |
| 3 | 1/18/16 | [Regression](#week-3-regression) |
| 4 | 1/25/16 | [Supervised Learning](#week-4-supervised-learning) |
| 5 | 2/01/16 | [Special Topics](#week-5-special-topics) |
| 6 | 2/08/16 | [Unsupervised Learning](#week-6-unsupervised-learning) |
| - | 2/15/16 | BREAK WEEK! |
| 7 | 2/22/16 | [Data Engineering](#week-7-data-engineering) |
| 8 | 2/29/16 | [Case Studies](#week-8-case-studies) |
| 9 | 3/07/16 | [Project](#week-9-project) |
| 10 | 3/14/16 | [Project](#week-10-more-project) |
| 11 | 3/21/16 | [Project](#week-11-even-more-project) |
| 12 | 3/28/16 | [Interview Prep](#week-12-interview-prep) |

--
## Solutions
Here is the link to the [solutions repo](https://github.com/zipfian/solns-sf11). Each day's sprints, including assessments, will be added by the end of the day.

### Week 1: Software Engineering + EDA
| Day | Readings | Repo | Lead Instructor | Slides |
|:--:|:--|:--:|:--|:--:|:--:|
| Monday | <ul><li>[Development Workflow][1]</li><li>[Pair Programming][2]</li></ul> | <ul><li>[assessment-day1][2.1]</li><li>[python-intro][3]</li></ul> | Isaac |  |
| Tuesday | <ul><li>[Learn Python the Hard Way (ex 40-42)](http://learnpythonthehardway.org/book/ex40.html)</li><li>Extra: Learn Python the Hard Way ex 43</ul> | [OOP][8] | Isaac |  |
| Wednesday | <ul><li>[SQLZOO (tutorial: 1-9)][10]</li><li>Postgres Tutorial ([Chapter 1][11])</li><li>[Visual Explanation of Joins][12]</li></ul> | [sql][13] | Clayton |  |
| Thursday | <ul><li>[Intro to IPython Notebook][18]</li><li>[10 minutes to Pandas][19] (not as cute as you would think)</li><li>[Pandas Top 10][21]</li><li>[EDA with pandas (Extra)][22]</li><li>[Data Wrangling with pandas (Extra)][20]</li></ul>| <ul><li>[sql-python][25.1]</li><li>[pandas][23]</li> | Brad | <ul> <li>[sql-python](https://github.com/zipfian/DSI_Lectures/blob/master/sql-python/brad_jacobs/brad-psql-python-lecture.ipynb)</li><li>[pandas](https://github.com/zipfian/DSI_Lectures/blob/master/pandas/Afternoon_lecture.ipynb)</ul></li> |
| Friday | No Readings | [pandas-seaborn][24.1] | Isaac |  |

--

### Week 2: Statistics and Probability
| Day | Readings | Repo | Lead Instructor | Slides |
|:--:|:--|:--:|:--|:--:|:--:|
| Monday    | <ul><li>[Probability Review (1.2-4.3),  1 hour][25]</li></ul>                                                | <ul><li>[assessment 2][28.0]</li><li>[Probability][28]</li></ul> | Brad | [slides](https://github.com/zipfian/DSI_Lectures/blob/master/probability/brad_jacobs/baj-lecture.pdf) |
| Tuesday   | <ul><li>[Bootstrapping Intro][38.1]</li><li>[Central Limit Theorem][40.1]</li><li>[Confidence Interval][38.0]</li><li>[Confidence Interval 2][38.01]</li><li>[MLE](https://www.youtube.com/watch?v=I_dhPETvll8)</li></ul> | [Sampling and Estimation][38] | Clayton |[slides](https://github.com/zipfian/DSI_Lectures/tree/master/estimation-sampling/clayton_schupp)  |
| Wednesday | <ul><li>[z-test VS t-test][39.1]</li><li>[Hypothesis Testing][39.2]</li></ul> | [Frequentist Hypothesis Testing][39] | Brad | [slides](https://github.com/zipfian/DSI_Lectures/blob/master/ab-testing/tammy_lee/lecture.pdf) |
| Thursday  | <ul><li>[Power Analysis](https://www.youtube.com/watch?v=lHI5oEgNkrk)</li><li>[Bayesian Statistics 1][40.0]</li></ul>  | [Power Calculation and Bayes][40] | Clayton | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/power-bayesian/clayton_schupp) |
| Friday    | <ul><li>[Bayesian Statistics 2](https://www.youtube.com/watch?v=r0tRgR74n_g&index=28&list=PLFDbGp5YzjqXQ4oE4w9GVWdiokWB9gEpm)</li><li>[Bayesian AB and Multi-Arm Bandit](http://stevehanov.ca/blog/index.php?id=132)</li></ul>| [multi-arm-bandit][44] | Susan |  |

--

### Week 3: Regression
| Day | Readings | Repo | Lead Instructor | Slides |
|:--:|:--|:--:|:--|:--:|:--:|
| Monday | <ul><li>[Linear Algebra and Numpy](https://github.com/zipfian/precourse/blob/master/Chapter_2_Linear_Algebra/notes.md)</li><li>[StatLearning][47.1]: Linear Regression (3-3.2, pg 59-82)</li><li>Optional: [Linear Algebra Notes](http://cs229.stanford.edu/section/cs229-linalg.pdf)</ul> | [Linear Algebra, EDA, Linear Regression ][48] | Brad | <ul><li> [Linear Algebra](https://github.com/zipfian/DSI_Lectures/blob/master/linear-algebra-eda/zach_alexander/za_linear_algebra_lecture.ipynb)</li><li>[EDA](https://github.com/zipfian/DSI_Lectures/blob/master/linear-algebra-eda/zach_alexander/za-EDA-Regression.ipynb)</li></ul> |
| Tuesday | <ul><li>[StatLearning][47.1]: Linear Regression cont'd (3.3-3.4, pg 82-104)</li></ul> | [Linear Regression 2][58] | Brad | [slides](https://github.com/zipfian/DSI_Lectures/blob/master/linear-regression/zach_alexander/za_Linear_Regression.pdf)  |
| Wednesday | <ul><li>[StatLearning][47.1]: Cross Validation (5-5.1.4, pg 175-184)</li><li>[StatLearning][47.1]: Shrinkage Methods (6.2, pg 214-228) (optional: pg 203-214)</li></ul> | [Regularized Regression][54] | Clayton | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/regularized-regression/clayton)  |
| Thursday | <ul><li>[StatLearning][47.1]: Classification (4-4.4, pg 127-137)</li><li>[Machine Learning in Action][MLIA] (section 7.7, pg 142-148)</li></ul> | <ul><li>[assessment-3][A3]</li><li>[logistic-regression][log-reg]</li></ul> | Clayton | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/logistic-regression/clayton_schupp)  |
| Friday | <ul><li>[Machine Learning in Action][MLIA] (ch 5, pg 83-90) (optional 90-96)</li><li>Optional (for more rigor): [Andrew Ng Notes (p. 1-7, 16-19)][51]</li></ul>| [gradient-descent][52] | Isaac | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/gradient-descent/isaac_laughlin)  |

--

### Week 4: Supervised Learning
| Day | Readings | Repo | Lead Instructor | Slides |
|:--:|:--|:--:|:--|:--:|:--:|
| Monday | <ul><li>[Machine Learning in Action][MLIA] (2.1, pg 18-24, 3.1 pg 37-48)</li><li>[Recursion][recursion]</li><li>[Recursion practice](readings/recursion)</li><li>Optional: [StatLearning][47.1] (8.1 pg 303-316)</li><li>[Decision Tree Visual Explanation](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)</li></ul> | [non-parametric-learners][65] | Susan |  |
| Tuesday | <ul><li>[StatLearning][47.1] (8.1.2-8.2.2, pg 311-321)</li></ul> | [random-forest][68] | Clayton | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/random-forest/clayton_schupp)  |
| Wednesday | <ul><li>[StatLearning][47.1] (9-9.2, pg 337-349)</li><li>Optional: [StatLearning][47.1] (9.3-9.3.2, pg 349-353)</li></ul> | [svm][71] | Isaac | [slides](https://github.com/zipfian/DSI_Lectures/blob/master/svm/isaac_laughlin/lecture.pdf) |
| Thursday | <ul><li>[StatLearning][47.1] (8.2.3, pg 321-324)</li><li>Optional (more depth): [Elements of Stats Learning][esl] (10-10.6, pg 337-350)</li></ul> | [boosting][boosting] | Brad | [slides](https://github.com/zipfian/DSI_Lectures/blob/master/boosting/tammy_lee/lecture.pdf) |
| Friday | No Readings | [regression-case-study][reg-case-study] | Clayton |  |
--

### Week 5: Special Topics
| Day | Readings | Repo | Lead Instructor | Slides |
|:--:|:--|:--:|:--|:--:|:--:|
| Monday | <ul><li>[Data Science for Business][DSBus] (pg 194-203, 212-214)</li><li>Optional (mostly review): [Data Science for Business][DSBus] (rest of ch 7-8, pg 187-232)</li></ul> | <ul><li>[assessment-4][A4]</li><li>[profit-curves][profit]</li></ul> | Clayton | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/profit-curve/michael_jancsy) |
| Tuesday | <ul><li>[Precourse - Web][75]</li><li>[Basic Web Scaping][76]</li><li>[Little book of MongoDB][76.1]</li></ul>| [web-scraping][77] | Isaac | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/web-scraping/isaac_laughlin) |
| Wednesday | <ul><li>Text feature extraction (tf-idf) [I][tfidf1], [II][tfidf2], [III][tfidf3]</li><li>[Natural Language Processing with Python][NLP] (3.6, pg 107-108)</li><li>Optional: [Natural Language Processing with Python][NLP] (ch 3, pg 79-122)</li></ul> | [nlp][84] | Asim | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/nlp/asim_jalis) |
| Thursday | <ul><li> [Forecasting: principles and practice][hyndman] (Ch. 1, 2, & 6-8) </li><li> [Time Series Analysis and Its Applications][timeseries] (ch 1-3)</li><li>[ARIMA models in Python][arima]</li></ul> | [time-series][time-series] | Clayton | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/time-series/clayton_schupp)  |
| Friday | No Readings | [case-study][200] | Clayton |  |

--

### Week 6: Unsupervised Learning
| Day | Readings | Repo | Lead Instructor | Slides |
|:--:|:--|:--:|:--|:--:|:--:|
| Monday | <ul><li> [StatLearning][47.1] (pg 385-400)</li></ul>| [clustering][104] | Clayton | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/clustering/zach_alexander)  |
| Tuesday | <ul><li>[Machine Learning in Action][MLIA] (ch 13-14.3 pg 269-286)</li><li>[StatsLearning][47.1] (ch 10.2 pg 374-385)</li><li>Optional: [Mining Massive Datasets ch 11][mmd11]</ul> | [dimensionality-reduction][107] | Asim | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/dimensionality-reduction/asim_jalis) |
| Wednesday | <ul><li>[NMF in Python][nmf-reading]</li</ul> | <ul><li>[assessment-5][A5]</li><li>[nmf][nmf]</li></ul> | Clayton | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/topicmodeling/clayton_schupp) |
| Thursday | <ul><li>[Machine Learning in Action][MLIA] (ch 14.4-14.5 pg 286-295)</li><li>Optional: [Mining Massive Datasets ch 9][mmd9] (especially 9.1, 9.3, 9.5)</li></ul> | [recommendation-systems][118] | Isaac | [slides](https://github.com/zipfian/DSI_Lectures/blob/master/recommendation-systems/dan_becker) |
| Friday | <ul><li>[Matrix Factorization Techniques for Recommender Systems][mftr]</li><li>[Graphlab: Choosing a recommender][graphlab-rec]</li><li>Optional: [Mining Massive Datasets ch 9][mmd9] (ch 9.4, pg 328-337)</li><li>Optional: [Recommender systems: from algorithms to user experience][rec-paper]</li></ul> | [recommender-case-study][rec2] | Isaac |  |

--

### Week 7: Data Engineering
| Day | Readings | Repo | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|:--:|:--:|
| Monday |  <ul><li>[Multiprocessing in Python][multiproc-python]</li><li>[Intro to Parallel Processes][parallel-intro]</li><li>[Intro to Threading][threading]</li></ul> | [high-performance-python][hp-python] | Isaac | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/high-performance-python/asim_jalis) |
| Tuesday | <ul><li>[Python Functional Programming Generators][generators]</li><li>[Python Functional Programming built-in functions][funcprog]</li><li>[Mining Massive Datasets ch 2][mmd2] (ch 2-2.3 pg 21-41)</li><li>Optional: [Data-Intensive Text Processing with MapReduce][mrbook] (ch 1-3 pg 1-69)</li></ul> | [map-reduce][129] | Asim | [slides](https://github.com/zipfian/DSI_Lectures/tree/master/map-reduce/asim_jalis) |
| Wednesday | <ul><li>[Learning Spark][LearningSpark] (ch 1-2, pg 1-22)</li><li>Optional: [Learning Spark][LearningSpark] (ch 11: MLlib, pg 183-212)</li><ul>| [spark][spark] | Isaac | [Notes](https://github.com/zipfian/DSI_Lectures/tree/master/spark/asim_jalis) |
| Thursday | <ul><li>[Spark on AWS][131.8]</li><li>[Learning Spark][LearningSpark] (pg 135-139)</li><ul>| [spark-aws][spark-aws] |Isaac  | [Notes](https://github.com/zipfian/DSI_Lectures/tree/master/spark-aws/asim_jalis) |
| Friday | <ul><li>[Social Network Analysis][sna] (ch 2 pg 19-38)</li><li>[Mining Massive Datasets][mmd10] (10.1-10.2 pg 343-356)</li></ul> | [graphs][graphs] | Susan | [Notes](https://github.com/zipfian/DSI_Lectures/tree/master/graphs/s_eraly) |
--

### Week 8: Case Studies
| Day | Readings | Repo | Lead Instructor | Slides |
|:--:|:--|:--:|:--:|:--:|:--:|
| Monday |  | [data-viz](https://github.com/zipfian/data-viz-for-ds) | Isaac |  |
| Tuesday |  <ul><li>[Setup Flask][132.1] (5min)</li><li> [Flask Tutorials][132.2] (Do as many as you see fit, dont worry about setting up the virtual environment)</li><li>[Get vs Post](http://www.w3schools.com/tags/ref_httpmethods.asp)</li></ul> | [data-products][132.0] | Giovanna |  |
| Wednesday |<li> *Final project proposals due at 9:30am* </li> | [fraud-detection-case-study][135] | Clayton |  |
| Thursday | | [fraud-detection-case-study][135] | Clayton |  |
| Friday | <ul><li> [Optional] [Data Science for Business][DSBus] (ch 1-2, 14, pg 1-42, 331-346)</li><li>[Optional] [Data Science Use Cases](https://www.kaggle.com/wiki/DataScienceUseCases)</li></ul> | [final-assessment][131.1] | Clayton |  |

--

--
### Week 9: Project
| Day | Activities | Repo |
|:--:|:--|:--:|
| Monday - Friday | Daily Scrum Meeting at 9 | [project-proposals][proj] |

--

### Week 10: More Project
| Day | Activities | Repo |
|:--:|:--|:--:|:--:|:--|
| Monday - Friday | Daily Scrum Meeting at 9 | [project-proposals][proj] |

--

### Week 11: Even More Project
| Day | Activities | Repo |
|:--:|:--|:--:|
| Monday | Daily Scrum Meeting at 9</br>Practice Presentations | [project-proposals][proj] |
| Tuesday | Daily Scrum Meeting at 9</br>Practice Presentations | [project-proposals][proj] |
| Wednesday | Morning: Presentation Dry Run<br/>Afternoon: Company Overview, Interview Practice | [project-proposals][proj] |
| Thursday | Hiring Day | [project-proposals][proj] |
| Friday | *Day Off: Recover* |  |

--

### Week 12: Interview Prep
| Day | Activities | Repo | Lead Instructor |
|:--:|:--|:--:|:--:|
| Monday | Morning: Review<br/>Afternoon: Whiteboarding Practice | [interview-prep][137.2] <br/> [interview-week][137.3] |  |
| Tuesday | Morning: Review<br/>Afternoon: Algorithms | [interview-prep][137.2] <br/> [interview-week][137.3] |  |
| Wednesday | Model Comparison | [interview-prep][137.2] <br/> [interview-week][137.3] |  |
| Thursday | 120 Interview Questions<br/>Job Application Prep | [interview-prep][137.2] <br/> [interview-week][137.3] |  |
| Friday |  Mock Interviews<br/>Salary Negotiation Workshop<br/>GRADUATION!! (in the evening) | [interview-prep][137.2] <br/> [interview-week][137.3] |  |

--

## Textbooks

We will focus on a few canonical texts for the class and readings will be assigned from them. If they are not in a physical form in our library, they are located in digital form on the Time Capsule or the Internet.

* [Doing Data Science](http://www.amazon.com/Doing-Data-Science-Straight-Frontline/dp/1449358659): One of the best treatments of the field with plenty of case studies.
* [Python for Data Analysis](http://shop.oreilly.com/product/0636920023784.do): Some of the `pandas` methods have changed (always reference `pandas` [online documentation](http://pandas.pydata.org/)) but a solid book on data analysis in Python.
* [Practical Data Science with R](http://www.manning.com/zumel/): through we will not use R, this is a stellar book and we will use it for its content/theory

## Getting Help

* [Data Science Stack Exchange](http://datascience.stackexchange.com/)
* [Stats Stack Exchange](http://stats.stackexchange.com/)
* [MetaOptimize: ML and Datascience forum](http://metaoptimize.com/qa)

## References

### Machine Learning

* [Machine Learning in Action](http://www.manning.com/pharrington/)
* [Programming Collective Intelligence](http://www.amazon.com/Programming-Collective-Intelligence-Building-Applications/dp/0596529325)
* [Machine Learning for Hackers](http://shop.oreilly.com/product/0636920018483.do)
* [An Introduction to Machine Learning](http://alex.smola.org/drafts/thebook.pdf)


### Statistics

* [Probabilistic Programming and Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
* [Think Stats](http://www.greenteapress.com/thinkstats/)
* [Think Bayes](http://www.greenteapress.com/thinkbayes/)
* [All of Statistics](http://www.stat.cmu.edu/~larry/all-of-statistics/)
* [Mostly Harmless Econometrics](http://www.amazon.com/Mostly-Harmless-Econometrics-Empiricists-Companion/dp/0691120358)

### Computer Science/Programming

* [Think Python](http://www.greenteapress.com/thinkpython/thinkpython.html)
* [Algorithms (Papadimitriou)](http://www.cs.berkeley.edu/~vazirani/algorithms)
* [Stacks and Queues](https://github.com/zipfian/graph-datastructures/tree/master/lecture/stacks_and_queues.md)
* [Think Complexity: Analysis of Algorithms](http://www.greenteapress.com/compmod/html/thinkcomplexity004.html)


### Numpy

* [Official Numpy Tutorial](http://wiki.scipy.org/Tentative_NumPy_Tutorial)
* [scipy Lectures](https://scipy-lectures.github.io/intro/numpy/index.html)
* [Crash Course in Python for Scientist](http://nbviewer.ipython.org/gist/rpmuller/5920182)
* [Scientific Python Lectures](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-2-Numpy.ipynb)
* [Numpy Broadcasting](http://wiki.scipy.org/EricsBroadcastingDoc)
* [Pyton Bootcamp Lectures](http://nbviewer.ipython.org/github/profjsb/python-bootcamp/blob/master/Lectures/05_NumpyMatplotlib/IntroNumPy.ipynb)

### SQL

* [http://sqlfiddle.com/](http://sqlfiddle.com/)
* [http://use-the-index-luke.com/](http://use-the-index-luke.com/)
* [http://missqlcommand.com/](http://missqlcommand.com/)
* [http://sql.learncodethehardway.org/book/](http://sql.learncodethehardway.org/book/)
* [SQL School](http://sqlschool.modeanalytics.com/)

### Scipy

* [scipy Lectures](https://scipy-lectures.github.io)

### scikit-learn

* [Introduction to Machine Learning with sklearn](http://researchcomputing.github.io/meetup_spring_2014/python/sklearn.html)
* [scikit-learn workshop](https://github.com/jakevdp/sklearn_pycon2014)
* [Machine Learning Tutorial](https://github.com/amueller/tutorial_ml_gkbionics)
* [Introduction to scikit-learn](http://nbviewer.ipython.org/github/tdhopper/Research-Triangle-Analysts--Intro-to-scikit-learn/blob/master/Intro%20to%20Scikit-Learn.ipynb)
* [Data analysis with scikit-learn](http://sebastianraschka.com/Articles/2014_scikit_dataprocessing.html)
* [Advanced Machine Learning with scikit-learn](https://us.pycon.org/2013/community/tutorials/23/)

### Extra

* [University of Colorado Computational Science workshops](http://researchcomputing.github.io/meetup_spring_2014/)
* [Networkx tutorial](http://snap.stanford.edu/class/cs224w-2012/nx_tutorial.pdf)

<!-- ************************** References **************************************** -->

<!-- PLEASE DO NOT REMOVE ANY OF THESE LINKS (Just add more if you need to change anything with syllabus) -->

<!-- Week 1 -->
[1]: notes/workflow.md
[2]: notes/pairing.md
[2.1]: https://github.com/zipfian/assessment-day1
[3]: https://github.com/zipfian/python-intro
[8]: https://github.com/zipfian/OOP
[10]: http://sqlzoo.net/wiki/Main_Page
[11]: http://www.postgresql.org/docs/9.4/static/tutorial-start.html
[12]: http://blog.codinghorror.com/a-visual-explanation-of-sql-joins/
[13]: https://github.com/zipfian/sql
[18]: http://nbviewer.ipython.org/github/jvns/pandas-cookbook/blob/master/cookbook/A%20quick%20tour%20of%20IPython%20Notebook.ipynb
[19]: http://pandas.pydata.org/pandas-docs/stable/10min.html
[20]: http://nbviewer.ipython.org/github/cs109/content/blob/master/lec_04_wrangling.ipynb
[21]: http://manishamde.github.io/blog/2013/03/07/pandas-and-python-top-10/
[22]: http://nbviewer.ipython.org/github/cs109/content/blob/master/labs/lab3/lab3full.ipynb
[23]: https://github.com/zipfian/pandas
[24]: https://github.com/zipfian/graphing-basics
[24.1]: https://github.com/zipfian/pandas-seaborn
[25.1]: https://github.com/zipfian/sql-python

<!-- Week 2 -->
[25]: http://cs229.stanford.edu/section/cs229-prob.pdf
[28.0]: https://github.com/zipfian/assessment-week2
[28]: https://github.com/zipfian/probability
[38]: https://github.com/zipfian/estimation-sampling
[38.0]: http://onlinestatbook.com/2/estimation/confidence.html
[38.01]: http://onlinestatbook.com/2/estimation/mean.html
[38.1]: https://www.youtube.com/watch?v=_nhgHjdLE-I
[39]: https://github.com/zipfian/ab-testing
[39.1]: https://www.youtube.com/watch?v=5ABpqVSx33I
[39.2]: https://www.youtube.com/watch?v=-FtlH4svqx4
[40]: https://github.com/zipfian/power-bayesian
[40.0]: https://www.youtube.com/watch?v=i567qvWejJA&index=15&list=PLFDbGp5YzjqXQ4oE4w9GVWdiokWB9gEpm
[40.1]: https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/central-limit-theorem
[44]: https://github.com/zipfian/multi-armed-bandit

<!-- Week 3 -->
[47.1]: http://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf
[48]: https://github.com/zipfian/linear-algebra-eda
[51]: http://cs229.stanford.edu/notes/cs229-notes1.pdf
[52]: https://github.com/zipfian/gradient-descent
[54]: https://github.com/zipfian/regularized-regression
[58]: https://github.com/zipfian/linear-regression

<!-- Week 4 -->
[65]: https://github.com/zipfian/non-parametric-learners
[68]: https://github.com/zipfian/random-forest
[71]: https://github.com/zipfian/svm
[reg-case-study]: https://github.com/zipfian/regression-case-study

<!-- Week 5 -->
[75]: https://github.com/zipfian/precourse/tree/master/Chapter_8_Web_Awareness
[76]: readings/web_scrape/scraping_tutorial.md
[76.1]: http://openmymind.net/mongodb.pdf
[77]: https://github.com/zipfian/web-scraping
[84]: https://github.com/zipfian/nlp
[200]: https://github.com/zipfian/ml-case-study

<!-- Week 6 -->
[NN]: https://www.youtube.com/watch?v=bxe2T-V8XRs
[104]: https://github.com/zipfian/clustering
[107]: https://github.com/zipfian/dimensionality-reduction
[118]: https://github.com/zipfian/recommendation-systems

<!-- Week 7 -->
[hp-python]: https://github.com/zipfian/high_performance_python
[parallel-intro]: http://sebastianraschka.com/Articles/2014_multiprocessing_intro.html
[multiproc-python]:https://www.youtube.com/watch?v=X2mO1O5Nuwg
[threading]: http://pymotw.com/2/threading/
[121.5]: https://github.com/zipfian/image_featurization
[129]: https://github.com/zipfian/data-at-scale
[131.1]: https://github.com/zipfian/final-assessment
[131.8]: https://aws.amazon.com/articles/4926593393724923

<!-- Week 8++ -->
[132.0]: https://github.com/zipfian/data-products
[132.1]: http://flask.pocoo.org/
[132.2]: http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

[135]: https://github.com/zipfian/case-study
[137.2]: https://github.com/zipfian/interview-prep
[137.3]: https://github.com/zipfian/interview-week

[MLIA]: https://drive.google.com/file/d/0B1cm3fV8cnJwcUNWWnFaRWgwTDA/view?usp=sharing
[A3]: https://github.com/zipfian/assessment-3
[log-reg]: https://github.com/zipfian/logistic-regression
[boosting]: https://github.com/zipfian/boosting
[profit]: https://github.com/zipfian/profit-curve
[A4]: https://github.com/zipfian/assessment-4
[recursion]: http://interactivepython.org/runestone/static/pythonds/index.html#recursion
[DSBus]: https://drive.google.com/file/d/0B1cm3fV8cnJwNDJFNmx2a2RBaTg/view?usp=sharing
[proj]: https://github.com/zipfian/project-proposals
[esl]: http://web.stanford.edu/~hastie/local.ftp/Springer/OLD/ESLII_print4.pdf
[tfidf1]: http://blog.christianperone.com/?p=1589
[tfidf2]: http://blog.christianperone.com/?p=1747
[tfidf3]: http://blog.christianperone.com/?p=2497
[NLP]: http://victoria.lviv.ua/html/fl5/NaturalLanguageProcessingWithPython.pdf
[A5]: https://github.com/zipfian/assessment-5
[mmd9]: http://infolab.stanford.edu/~ullman/mmds/ch9.pdf
[mmd10]: http://infolab.stanford.edu/~ullman/mmds/ch10.pdf
[mmd11]: http://infolab.stanford.edu/~ullman/mmds/ch11.pdf
[nmf]: https://github.com/zipfian/topicmodeling
[rec2]: https://github.com/zipfian/recommender-case-study
[nmf-reading]: http://www.quuxlabs.com/blog/2010/09/matrix-factorization-a-simple-tutorial-and-implementation-in-python/
[graphlab-rec]: http://blog.dato.com/choosing-a-recommender-model
[mrbook]: http://lintool.github.io/MapReduceAlgorithms/MapReduce-book-final.pdf
[time-series]: https://github.com/zipfian/time-series
[spark]: https://github.com/zipfian/spark
[spark-aws]: https://github.com/zipfian/spark-aws
[mftr]: http://citeseer.ist.psu.edu/viewdoc/download;jsessionid=59FAB1A333AB979B48239AA22D9F3476?doi=10.1.1.147.8295&rep=rep1&type=pdf
[rec-paper]: http://files.grouplens.org/papers/algorithmstouserexperience.pdf
[funcprog]: https://docs.python.org/2/howto/functional.html#built-in-functions
[generators]: https://docs.python.org/2/howto/functional.html#generators
[mmd2]: http://infolab.stanford.edu/~ullman/mmds/ch2.pdf
[arima]: http://conference.scipy.org/proceedings/scipy2011/pdfs/statsmodels.pdf
[hyndman]: https://www.otexts.org/fpp
[timeseries]: http://www.stat.pitt.edu/stoffer/tsa3/tsa3EZ.pdf
[LearningSpark]: https://drive.google.com/file/d/0B1cm3fV8cnJwc2ZnMFJmT2RLOXM/view?usp=sharing
[sna]: readings/Social_Network_Analysis_for_Startups.pdf
[graphs]: http://github.com/zipfian/graphs
