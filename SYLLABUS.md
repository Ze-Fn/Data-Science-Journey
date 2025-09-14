# Data Science Self-Study Syllabus: From Fundamentals to Mastery

![Data Science Badge](https://img.shields.io/badge/Data%20Science-Self%20Study-blue?style=for-the-badge&logo=python&logoColor=yellow)  
**Last Updated:** September 14, 2025  
**Author:** Ze-Fn (Zelvy Fauzan, M.Pd.)  
**Repository:** [https://github.com/Ze-Fn/Data-Science-Journey]  

Welcome to my personal journey in mastering Data Science! This syllabus outlines a structured, self-paced curriculum inspired by top Bachelor's-level programs (e.g., from universities like Northeastern, Stanford, and UC Berkeley). I'll document every step—notes, code, projects, and reflections—right here in this repo. Each course has a dedicated folder with Jupyter notebooks, datasets, and progress trackers. Feel free to fork, star, or contribute ideas!

## Overview
This program is divided into three levels: **Fundamental** (math & programming basics), **Intermediate** (data handling & analysis), and **Advanced** (applied ML & big data). Expect 6-12 months to complete, assuming 10-15 hours/week. Track your progress with weekly commits and badges (e.g., via Shields.io).

**Why this syllabus?** It's designed for real-world applicability, blending theory with hands-on projects. By the end, you'll have a portfolio showcasing end-to-end data science workflows.

## Learning Objectives
By completing this syllabus, you'll be able to:
- Apply mathematical foundations to data problems.
- Clean, analyze, and visualize datasets using Python tools.
- Build and deploy machine learning models.
- Handle big data ethically and scalably.
- Communicate insights through visualizations and reports.

## Prerequisites
- Basic computer literacy.
- Access to a machine with Python 3.10+ (use Anaconda for easy setup).
- GitHub account for version control and showcasing.

## Schedule Suggestion
- **Weeks 1-8:** Fundamentals (2 courses/week).
- **Weeks 9-20:** Intermediate (2-3 courses/week).
- **Weeks 21-32:** Advanced (1-2 courses/week + capstone).
- **Ongoing:** Weekly reviews and portfolio updates.

Use this [Notion template](https://www.notion.so/templates/self-study-tracker) or Trello for personal tracking, and mirror updates in GitHub issues.

---

## Fundamental Level: Building the Foundation
Focus: Math and programming essentials. Estimated time: 8 weeks.

### Calculus I
**Description:** Covers limits, derivatives, and integrals with applications to data rates (e.g., optimization in models).  
**Duration:** 4 weeks.  
**Folder:** `/fundamentals/calculus-i/`  

**Relevant Materials:**  
- Textbook: [Calculus by Michael Spivak](https://www.amazon.com/Calculus-4th-Michael-Spivak/dp/1464094994) or [OpenStax Calculus Volume 1](https://openstax.org/details/books/calculus-volume-1) (free).  
- Online: [3Blue1Brown Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5r9) (videos); [Khan Academy Calculus 1](https://www.khanacademy.org/math/calculus-1) (interactive).  

**Practice Sessions:**  
- Daily: 20 problems on limits/derivatives from [Pauls Online Math Notes](https://tutorial.math.lamar.edu/problems/calci/calci.aspx).  
- Weekly: Khan Academy unit tests on motion and optimization.  
- Tool: SymPy for symbolic computation—try notebooks in repo.  

**Portfolios/Projects:**  
- **Project 1:** Jupyter notebook modeling population growth with derivatives. Visualize with Matplotlib. [Link to notebook](https://github.com/yourusername/data-science-journey/blob/main/fundamentals/calculus-i/population_growth.ipynb).  
- **Reflection:** Commit a blog post (Markdown) on how calculus applies to gradient descent in ML.

### Linear Algebra
**Description:** Vectors, matrices, eigenvalues—key for dimensionality reduction and neural nets.  
**Duration:** 4 weeks.  
**Folder:** `/fundamentals/linear-algebra/`  

**Relevant Materials:**  
- Textbook: [Linear Algebra with Applications by Otto Bretscher](https://www.pearson.com/en-us/subject-catalog/p/linear-algebra-and-its-applications/P200000006774/9780136680321).  
- Online: [MIT OCW Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) (Gilbert Strang); [Coursera: Linear Algebra for ML](https://www.coursera.org/learn/machine-learning-linear-algebra) (free audit).  

**Practice Sessions:**  
- Hands-on: NumPy exercises from [freeCodeCamp](https://www.freecodecamp.org/news/linear-algebra-for-data-science/).  
- Problems: Matrix decompositions on [GeeksforGeeks](https://www.geeksforgeeks.org/linear-algebra/).  
- Weekly: 3Blue1Brown video + implementation challenges.  

**Portfolios/Projects:**  
- **Project:** PCA on Iris dataset with scikit-learn. [Notebook](https://github.com/yourusername/data-science-journey/blob/main/fundamentals/linear-algebra/pca_iris.ipynb). Deploy a simple Streamlit app.  
- **Reflection:** Video demo (record via Loom) explaining eigenvectors in recommendations.

### Probability and Statistics
**Description:** Probability distributions, hypothesis testing—foundation for inference in data.  
**Duration:** 4 weeks.  
**Folder:** `/fundamentals/prob-stats/`  

**Relevant Materials:**  
- Textbook: [Introduction to Probability by Blitzstein](https://projects.iq.harvard.edu/stat110/book/introduction-probability-0).  
- Online: [Bertsekas & Tsitsiklis PDF](http://www.mit.edu/~dimitrib/Probability_Book/book.pdf) (free); [Coursera: Statistics with Python](https://www.coursera.org/specializations/statistics-with-python).  

**Practice Sessions:**  
- Coding: SciPy hypothesis tests on [StrataScratch](https://www.stratascratch.com/).  
- Book exercises: [Think Stats PDF](https://greenteapress.com/thinkstats2/thinkstats2.pdf).  
- Interactive: DataCamp guided stats projects.  

**Portfolios/Projects:**  
- **Project:** A/B test on e-commerce data with p-values. [Notebook + Viz](https://github.com/yourusername/data-science-journey/blob/main/fundamentals/prob-stats/ab_testing.ipynb).  
- **Reflection:** Markdown report on assumptions and limitations.

### Introduction to Programming (Python)
**Description:** Basics of Python syntax, libraries like NumPy/Pandas for data tasks.  
**Duration:** 4 weeks.  
**Folder:** `/fundamentals/python-intro/`  

**Relevant Materials:**  
- Textbook: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) (free).  
- Online: [freeCodeCamp Python for DS](https://www.freecodecamp.org/learn/data-analysis-with-python/); [DataCamp Intro](https://www.datacamp.com/courses/intro-to-python-for-data-science).  

**Practice Sessions:**  
- Challenges: 50+ from [Dataquest](https://www.dataquest.io/blog/python-practice/).  
- Problems: [GeeksforGeeks Python](https://www.geeksforgeeks.org/python-programming-language/).  
- Repo: Clone and solve [78 DS problems](https://github.com/rougier/numpy-100).  

**Portfolios/Projects:**  
- **Project:** Web scraper + sentiment analysis dashboard. [Streamlit App](https://github.com/yourusername/data-science-journey/tree/main/fundamentals/python-intro/scraper).  
- **Reflection:** Code review pull request to a sample repo.

---

## Intermediate Level: Data Wrangling and Insights
Focus: Handling real data. Estimated time: 12 weeks.

### Data Structures and Algorithms
**Description:** Efficient data handling with trees, graphs—optimizes DS code.  
**Duration:** 4 weeks.  
**Folder:** `/intermediate/dsa/`  

**Relevant Materials:**  
- Textbook: [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms).  
- Online: [Google DSA Guide](https://techdevguide.withgoogle.com/paths/data-structures-and-algorithms/); [LeetCode DS](https://leetcode.com/problemset/all/?topicSlugs=data-structures).  

**Practice Sessions:**  
- Implement: [W3Schools DSA](https://www.w3schools.com/dsa/).  
- Challenges: [HackerRank](https://www.hackerrank.com/domains/data-structures).  
- Projects: [Codegnan DSA](https://codegnan.com/data-structures-algorithms-projects/).  

**Portfolios/Projects:**  
- **Project:** Hash table search engine. [Code + Benchmarks](https://github.com/yourusername/data-science-journey/blob/main/intermediate/dsa/search_engine.ipynb).  
- **Reflection:** Time complexity analysis in a blog post.

### Database Management Systems
**Description:** SQL/NoSQL for querying and storing data.  
**Duration:** 4 weeks.  
**Folder:** `/intermediate/databases/`  

**Relevant Materials:**  
- Textbook: [Database System Concepts](https://db-book.com/).  
- Online: [LearnSQL](https://learnsql.com/); [Coursera SQL for DS](https://www.coursera.org/learn/sql-data-science).  

**Practice Sessions:**  
- Queries: [LeetCode Database](https://leetcode.com/problemset/database/).  
- Design: [ProjectPro SQL](https://www.projectpro.io/projects/sql-projects).  
- Sims: [DataWars](https://datawars.com/).  

**Portfolios/Projects:**  
- **Project:** E-commerce DB with queries. [Schema + Queries](https://github.com/yourusername/data-science-journey/tree/main/intermediate/databases/ecommerce_db).  
- **Reflection:** ER diagram in Draw.io, committed as image.

### Data Visualization
**Description:** Telling stories with charts using Matplotlib/Seaborn/Tableau.  
**Duration:** 4 weeks.  
**Folder:** `/intermediate/viz/`  

**Relevant Materials:**  
- Textbook: [Storytelling with Data](https://www.storytellingwithdata.com/book).  
- Online: [Tableau Resources](https://www.tableau.com/learn/articles/free-data-visualization-books); [DataCamp Viz](https://www.datacamp.com/tracks/data-visualization).  

**Practice Sessions:**  
- Projects: 10 from [DataCamp](https://www.datacamp.com/projects/data-visualization).  
- Interactive: [Plotly Tutorials](https://plotly.com/python/).  
- Exercises: Coursera viz projects.  

**Portfolios/Projects:**  
- **Project:** COVID dashboard in Tableau. [Public Viz Link](https://public.tableau.com/app/profile/yourprofile/viz/COVID_Dashboard).  
- **Reflection:** A/B test on viz effectiveness.

### Data Mining
**Description:** Extract patterns via clustering, association rules.  
**Duration:** 4 weeks.  
**Folder:** `/intermediate/data-mining/`  

**Relevant Materials:**  
- Textbook: [Introduction to Data Mining](https://www-users.cs.umn.edu/~kumar/dmbook/index.php).  
- Online: [Statistical Learning PDF](https://www.statlearning.com/); [Coursera Mining](https://www.coursera.org/specializations/data-mining).  

**Practice Sessions:**  
- Rules: [Analytics Vidhya](https://www.analyticsvidhya.com/blog/2021/06/market-basket-analysis/).  
- Clustering: [DataWars](https://datawars.com/projects).  
- Kernels: Kaggle mining.  

**Portfolios/Projects:**  
- **Project:** Market basket analysis. [Apriori Notebook](https://github.com/yourusername/data-science-journey/blob/main/intermediate/data-mining/basket_analysis.ipynb).  
- **Reflection:** Insights report as PDF.

---

## Advanced Level: Scaling and Application
Focus: Production-ready DS. Estimated time: 12 weeks.

### Machine Learning
**Description:** Supervised/unsupervised models, evaluation metrics.  
**Duration:** 6 weeks.  
**Folder:** `/advanced/ml/`  

**Relevant Materials:**  
- Textbook: [Hands-On ML](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/).  
- Online: [Andrew Ng Coursera](https://www.coursera.org/learn/machine-learning); [fast.ai](https://course.fast.ai/).  

**Practice Sessions:**  
- Projects: 50 from [ProjectPro](https://www.projectpro.io/article/machine-learning-projects-for-beginners/441).  
- Nets: DataCamp ML.  
- Comps: Kaggle ML.  

**Portfolios/Projects:**  
- **Project:** House price predictor with XGBoost. [Flask Deploy](https://github.com/yourusername/data-science-journey/tree/main/advanced/ml/house_predictor).  
- **Reflection:** Model tuning journal.

### Big Data Analytics
**Description:** Spark/Hadoop for large-scale processing.  
**Duration:** 4 weeks.  
**Folder:** `/advanced/big-data/`  

**Relevant Materials:**  
- Textbook: [Data Science for Business](https://www.oreilly.com/library/view/data-science-for/9781449361327/).  
- Online: [edX Big Data](https://www.edx.org/learn/big-data); Databricks tutorials.  

**Practice Sessions:**  
- Spark: [ProjectPro](https://www.projectpro.io/projects/big-data-projects).  
- Guides: [Dataquest](https://www.dataquest.io/blog/big-data-python-tutorial/).  
- Dask: GeeksforGeeks.  

**Portfolios/Projects:**  
- **Project:** Twitter sentiment with PySpark. [Notebook](https://github.com/yourusername/data-science-journey/blob/main/advanced/big-data/twitter_sentiment.ipynb).  
- **Reflection:** Scalability comparison.

### Data Science Capstone Project
**Description:** Integrate everything in a full pipeline.  
**Duration:** 2 weeks.  
**Folder:** `/advanced/capstone/`  

**Relevant Materials:**  
- Textbook: [Doing Data Science](https://www.oreilly.com/library/view/doing-data-science/9781449363895/).  
- Online: [UCSD Guide](https://cseweb.ucsd.edu/~gdkundu/data_science_project_guide.html); Kaggle workflows.  

**Practice Sessions:**  
- Iterations: [DataPen](https://datapen.io/resources).  
- Mocks: Coursera guided.  

**Portfolios/Projects:**  
- **Project:** Titanic end-to-end (EDA to deploy). [GitHub Pages Site](https://yourusername.github.io/data-science-journey/capstone/titanic/).  
- **Reflection:** Medium article linking repo.

---

## Additional Resources
- **Tools Stack:** Python, Jupyter, Git, Streamlit, Tableau Public.  
- **Communities:** r/datascience, Dataquest forums, Kaggle discussions.  
- **Progress Tracking:** Use GitHub Projects for kanban; add badges like ![Progress](https://progress-bar.dev/50).  
- **Ethics Note:** Always consider bias/privacy—dedicated notebook in `/ethics/`.

## Contributing & Contact
Star this repo if it helps! Open issues for feedback. Follow my progress via [commits](https://github.com/Ze-Fn/Data-Science-Journey/commits/main). Questions? [E-mail](zelvy.fauzan2000@gmail.com).

**License:** MIT—feel free to adapt!  
![Footer](https://img.shields.io/badge/Built%20with-Grok%204-orange)