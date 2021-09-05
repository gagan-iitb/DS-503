# DS-503 (Advanced Data Analytics)

This is the course web-page for Advanced Data Analytics being taught at [IIT Bhilai, India](https://www.iitbhilai.ac.in/index.php) in the Monsoon Semester of 2021.
<br> Course Instructor: [Dr. Gagan Raj Gupta ](https://www.iitbhilai.ac.in/index.php?pid=gagan)

Motivation
----------

* Getting data is becoming easier day by day, but we have _too much_ to analyze (e.g. web, transactional data, text)
* Data has _errors_ of various types (missing, incorrect etc.), is _incomplete_ and is _hard to clean_ (e.g. user reviews/ratings, distorted images) 
* Data is usually _high-dimensional_ (involving lot of columns or features) (e.g. text, images, videos, graphs)
* Data usually has _complex correlations_ and i.i.d. assumptions don't always work very well (e.g. graph data, time-series data) 
* Data is _incomplete_ (matrix completion, compressed sensing, signal re-construction)
* Data is being generated at a _great speed_ and it is too _expensive to store_ all of it (e.g. user or machine transactions, queries)
* Data (packets) on the network is _encrypted_ 

__We are often asked to answer difficult questions from this messy data__

__We have to make decisions (often in real-time)__. 

In this course, we want to learn how that is being done and solve real-life problems that we are interested in.

Course Objectives
-----------------

* Equip students with the __mathematical toolkit__ (linear algebra, statistics, optimization), needed for understanding and implementing the important data analysis and ML algorithms
* Explain new paradigms of __algorithm design__ for handling complex datasets including __streaming algorithms__
* Explore robust and state of the art __(SOTA)__ techniques in large scale ML
* Introduce Graph neural networks __(GNN)__ and its applications to Knowledge Graphs and Bio-informatics
* Introduce __DTW__, __Matrix Profile__ and related techniques for analyzing complex time-series data (clustering, anomaly detection, pattern mining, prediction)
* Provide hands-on experience to students in analyzing datasets in diverse fields __(NLP, Image/Video, Graphs, Networks, Bio-informatics, Finance)__


Pre-requisites
--------------
* Basic knowledge of Python (most assignments will be based on Python)
* Knowledge of basic computer science principles and skills
* Math
  * Linear Algebra ( Matrix-factorization, Eigenvalues, Column and row spaces, Norms)
  * Probability theory (Conditional, Bayes Rule, Concentration Inequalities, Distributions, Gaussian, Multi-variate) 
  * Basic Data Structures, Algorithms and Asymptotic Analysis (graphs, heaps, lists, dynamic programming)
  * Calculus (Multi-variate)
  
If you don't meet one or more pre-requisites, be prepared to spend more time before or during the course in learning them.

Tentative Course Outline (per fractal)
--------------------------------------
![image](https://user-images.githubusercontent.com/79624301/125885925-07826a96-29d8-4833-aeb5-79bb29330acc.png)
* Last fractal will focus on course project and presentations.
* Useful resources have been posted 

| Week | Topics covered in class | Text Book Reference |
| --- | --- | ---- |
| 1, Aug 2| Math of Data: Algebraic, Geometric and Statistical Views; High-dimensional geometry: Curse of dimensionality, Gaussian Annulus theorem, Volume of unit ball, orthogonal directions| FoDS Chapter 2|
| 2, Aug 9 | Projection Techniques: Auto-encoder view, Best fit subspaces; PCA (maximize variance), Variants of PCA, Eigenfaces; SVD and applications, Power-iteration methods; Random projections: JL Lemma; Linear Regression as projection to column space using Normal Equations, Pseudo-inverse and QR methods; Data visualization| FoDS Chapter 3, MML Chapter 10|
|3, Aug 16|Locality Sensitive Hashing (LSH): Shingling, Min-hash, LSH, tradeoff with r and b; LSH for other metrics (Cosine, Euclidean); Compressed sensing: Solving Under-determined system of linear equations using Convex Optimization (L1 norm), Sparsity, Incoherence, Restricted Isometry Property (sparse vectors)| MMDS Chapter 3, Reference Papers |
|4, Aug 23|Streaming Data Analytics: Limitations of Random Sampling, Reservoir Sampling, Sliding Window Queries, DGIM algorithm, Recent Itemsets, Bloom Filters, Count Distinct, Frequency Estimation (MG, Space Saving, Count-Min), Moment Estimation |MMDS Chapter 4, SSBD|
|5, Aug 31|Intro to Machine Learning Algorithms: Examples of supervised, unsupervised and re-inforcement learning, Requirements of good ML, Feature Extraction, Learning with Prototypes, K nearest neighbors, Linear Models, Perceptron, SVM, Decision Trees  |   |
|6, Sep 13 |Convex Optimization Formulations of ML problems, Convexity, Computing Gradients, Gradient Descent and Variants, Autodiff and backpropagation||
|7, Sep 20|Neural Networks, DNN, CNN Architecture, Resnet |[Reading](https://towardsdatascience.com/illustrated-10-cnn-architectures-95d78ace614d) |
|8, Sep 27|Graphs, Graph Kernels, Graph Neural Networks, Attention Models|GRL|
|9, Oct 4|Knowledge graphs, Scalable Graph Learning|GRL|
|10, Oct 18 |GANs, Text Embeddings, Graph Embeddings||
|11, Nov 8|Clustering, Mixture Models||
|12, Nov 15|Sequence Models, LSTM, Distance functions for time series||
|13, Nov 22|Matrix Profile, FFT||

Meeting Times
-------------
* Lectures (Mon 2:30 p.m., Tue 4:00 p.m.) on https://iitbhilai.webex.com/meet/b204
* Extra Class on Sat, Aug 28 (11 am) : Check link on whatsapp group/email 

Books/References/Practice materials
-----------------------------------
* Course Textbook
  Mining of Massive Datasets (MMDS) : http://www.mmds.org/
  
* Reference Materials
  * Foundations of Data Science (FoDS) : https://www.cs.cornell.edu/jeh/book.pdf
  * Graph Representation Learning (GRL) : https://www.cs.mcgill.ca/~wlh/grl_book/
  * Small Summaries of Big Data (SSBD) : http://dimacs.rutgers.edu/~graham/ssbd.html
    
* Research Papers (will be added to the folder)
* Handouts (short notes on various important topics)
* Sample code snippets will be posted in the Handouts section for students to practice data analysis programming
* Useful datasets will also be provided for practice

Similar Courses
----------------
* https://web.stanford.edu/class/cs246/index.html#content
* http://web.stanford.edu/class/cs224w/
* https://courses.cs.washington.edu/courses/cse547/21sp/
* https://www.cs.rpi.edu/~zaki/courses/datamining/
* https://www.cs.utah.edu/~jeffp/DMBook/DM-AGP.html
