The following repository is a collection of my work for the *Applied Data Science* specialization with Python, offered by the University of Michigan on Coursera. This specialization has been a thorough guide on how to clean, manipulate, and visualize data in Python and even provided a thorough background for machine learning concepts and applications. This specialization consisted of the following five courses:

<br />

* **Introduction to Data Science**
* **Applied Plotting, Charting & Data Representation**
* **Applied Machine Learning**
* **Applied Text Mining**
* **Applied Social Network Analysis**

<br />

Each course included coding assignments that helped me gain a better understanding of fundamental data science libraries. In some cases, these assignments involved retrieving and analyzing data to answer a series of detailed questions. In other cases, these assignments served as mini-projects. For all files, I have rewritten some of the background information and questions in order to improve clarity and readability. 

Each course culminated with a final project. In some cases, an optional project was offered by the course; I’ve included these within a project file per course. These projects were a hands-off opportunity for me to put all my new skills to the test and even perform data analysis on real-life data. The coding assignments and projects are located in the main project folder. The data is located within the “data” folder, and then under “course_#” (where “#” represents course number “1”, “2”, “3”, “4”, or “5”). For instance, the data files for Applied Machine Learning in Python are located under data/course_3. 

Overall, this specialization has helped me have a better understanding of the tools and critical analysis that are pivotal for mastering my skills as a data scientist. I have also gained a deeper appreciation for the data science field in general and discovered how many of the challenges that I’ve encountered during this specialization were often solved by thinking outside the box. 

My work for each course can be found in the following repository. Each course contains its own background description, along with my code and data used to complete each assignment. 

<br /> 

# Course 1 - Introduction to Data Science: 

This course dived into fundamental Python libraries to clean and manipulate data as a data scientist. The course began with an introduction to basic techniques, including lambdas and list comprehensions, reading and writing csv files, and querying data frames. Python’s NumPy and Pandas libraries were heavily used in this course, in addition to Python’s Datetime and SciPy libraries. I also learned about handy functions, like Map and Lambda, in addition to list comprehension. 

## *Course 1 Assignments*

### Assignment #1 - Pandas Introduction: 

As the first coding assignment in the specialization, this assignment concentrated on Olympic medal data.  I explored fundamental libraries for data cleaning and manipulation - Pandas and NumPy libraries. The questions mostly related to querying Series and Dataframe data structures and accounting for missing values. 

### Assignment #2 - More Pandas: 

This was the first taste of reading documentation in the course to discover functions and methods in the Pandas library that were not previously taught in lecture. This assignment involved reducing and processing data, using functions like Apply and Groupby. I also gained experience with Datetime objects and merging datasets using joins. 


## *Course 1 Project*

### Project - Hypothesis Testing: 
This final project combined all of the basic Python skills into one project, where I had to clean and process the data from start to finish, on university housing data. Then, I performed hypothesis testing with the Student’s t-test and used Pearson’s p-value to evaluate whether or not there was a significant difference in housing costs between university and non-university towns. This project was fascinating to me, since I had a chance to investigate problems, like the rising cost of living, that affect people every day. 

<br />

# Course 2 - Applied Plotting, Charting & Data Representation:

This course focused on data visualization in Python, using the Matplotlib library. The course began with an introduction to Alberto Cairo’s Graphic Lies, Misleading Visuals. From this reading, I learned about how to create truthful visuals that do not distort a viewers’ perspective of the data.  I also discovered how our biases can distort the data we present to others, including displaying excess or hiding data. To avoid this, I was encouraged to make simple visuals without “chart junk,” as Cairo phrases it, and to only display relevant data so the viewer can understand the graphic without being distracted by superfluous details. 

With these principles in mind, the remainder of the course centered on plotting libraries - Matplotlib and Seaborn. 

## *Course 2 Assignments*

### Assignment #1 - Plotting Weather Patterns: 

This assignment allowed me to explore line graphs overlaid with scatter plots after learning about basic Matplotlib architecture. I used data collected by NOAA and created a line plot to display the daily record high and low temperatures over a decade (2005-2014) for Ann Arbor, Michigan. I then added a scatter plot to the line plot to display days in  2015 where the decade record temperatures were broken. 

### Assignment #2 - Building a Custom Visualization: 

Since barcharts in Matplotlib are notoriously tedious, this project challenged me to create a bar chart for four random normal distributions with different confidence intervals from one another. In the course, we were given the choice to take an easier route and make a simple barchart or take a harder route and create a complex barchart. I selected the “even harder” option and implemented an interactive bar chart that changed color based on the y-value threshold users can select on the chart. I also created a colormap that renders  its colors based on the probability that a bar lies above the interactive threshold.  

The interactive bar-chart was one of my favorite assignments in this course. Many of the graphs throughout the course are static. This bar chart, however, is dynamic and can be updated in near real time based on a user’s mouse click. It was fun to create a visual where users can decide which data will be displayed. 


## *Course 2 Project*
This file is separated into two projects - the optional project and the final project:

### Optional Project - Understanding Distributions through Sampling: 

This assignment allowed me to explore more advanced Matplotlib plots for four random probability distributions - Normal, Gamma, Exponential, and Uniform. 
My first two visuals served as fun ways to compare individual probability distributions to one another before I explored them all together in the same visual. For my first visual, I included a side-by-side comparison of the Normal and Uniform distributions (each sampled with 100 bins) in histogram and heatmap form. For my second visualization, I compared the Gamma and Exponential distributions on the same axis, and then animated each distribution separately on corresponding subplots. 

I also compared all four random probability distributions to one another in the same visual. For my third visualization, I created a boxplot for the four distributions. I overlaid a histogram of the random Normal Distribution on top of the boxplot, to showcase how each of the distributions appears in histogram form compared to its box plot representation. For the fourth visual, I created a simple button GUI to change the display between the four different distributions. I also created an “Exit” button for users to stop the visual’s interactive mode. This fourth visual was a fun way to allow users to engage with the graph and explore the four random probability distributions. 

### Final Project - Becoming an Independent Data Scientist: 

This project was one of my crowning achievements and one of the best opportunities I had to have full-reign over a project during this specialization. The project involved choosing a graph to investigate an assigned topic - weather patterns in Ann Arbor. From these guidelines, I designed my project to investigate climate-induced precipitation variations in Michigan. Since climate changes have worsened over the years, including unprecedented storms and droughts, I created visualizations to reveal whether or not climate changes are noticeable in locations that are relatively close to one another.

I created a radar chart to plot the average monthly rainfall and snowfall by inches in Ann Arbor and compared to the two most populous cities in Michigan (Detroit and Grand Rapids). I’ve also interlaid a line graph of the precipitation among the counties which each city belongs to in order to draw further comparison among the three regions. Even though the locations were nearby each other, the visuals revealed that there were noticeable variations in weather among the locations. 

This project was definitely one of the hardest assignments I faced throughout the specialization. Despite the challenges I faced, it was one of the most rewarding assignments because I had a chance to design my very own project. It was also my first opportunity to create radio buttons in Python.

<br />

# Course 3 - Applied Machine Learning:

After completing Python basics into cleaning and visualizing data, this third course focused on a new way to analyze data: machine learning. Using the Scikit-learn library, the course began with an introduction to supervised vs. unsupervised learning, before exploring basic ML classifiers. The course introduced classifiers, such as k-nearest neighbor (KNN),  Support Vector Machines (SVM), and Decision Trees. Next, the course explored optimizing model performance and using difference evaluation metrics to assess a classifier’s performance, before concluding with a final project.

## *Course 3 Assignments*

### Assignment #1 - Introduction to Machine Learning: 
This assignment was an introduction to Scikit-learn fundamentals, using the Breast Cancer Wisconsin Diagnostic Database. I learned how to extract features and create training and testing data for a K-nearest neighbor classifier. My final model predicted the probability that a patient’s tumor was malignant or benign, to aid breast cancer diagnosis.

### Assignment #2 - Model Complexity and Generalization Performance: 
This assignment explored more complex tasks in supervised machine learning, compared to the previous breast cancer model. I explored feature scaling and feature importance, and assessed a model’s generalization performance. I also used ridge and lasso regression on a linear regression model, in addition to creating a Decision Tree Classifier. 

### Assignment #3 - Evaluation: 
This assignment involved optimizing the performance of machine learning models to predict credit card fraud, using data collected from Kaggle. I even created a confusion matrix to assess the performance of my Support Vector Classifier (SVC). I also used different evaluation metrics - including accuracy, precision-recall, and an ROC Curve - to evaluate a Logistic Regression Classifier I optimized via cross-validation.

## *Course 3 Project*

Final Project - Understanding and Predicting Property Maintenance Fines: As the course’s final project, I used data from Detroit Open Data Portal to predict the probability that residents will pay their blight tickets on time. Since this project involved numerous categorical variables, I found one-hot encoding extremely helpful in preparing my data for classification. I also imputed missing data and used feature reduction to account for the additional dummy variables in order to reduce the complexity of my Random Forest classifier.

<br />

# Course 4 - Applied Text Mining:

This course concentrated on working with raw text in Python, using regular expressions (RegEx) and the NLTK library to perform Natural Language Processing (NLP). While textual data is notoriously messy, this course provided me with a strong foundation to tackle text mining. I learned how to tokenize raw text, extract meaningful information - including parts of speech and topic distribution, and even employ machine learning techniques to build classifiers and spelling recommendation systems. I also learned how to clean data, including removing stop-words, lemmatization, and stemming words with similar word derivations, in order to build robust, complex text models.

## *Course 4 Assignments*

### Assignment #1 - Working with Text: 

This assignment explored the first tool in my text-mining arsenal: Regex. Regular expressions were key for extracting calendar dates within the disordered medical data I was tasked on cleaning. There was an element of creativity in this assignment: I had to think of all the possible ways dates were written and misspelled. Since dates were written in words, numbers, and a combination of the two, I had to account for all occurrences before ordering all dates in ascending chronological order.

### Assignment #2 - Introduction to NLTK: 

This assignment provided me with another powerful tool for tackling text-mining: Python’S NLTK package. I tokenized words and sentences from Herman Melville’s Moby Dick and analyzed the word distribution and most common unique tokens. I also created spelling recommendation systems, using Jaccard's distance on trigram and 4-gram of words, and Damerau-Levenshtein's distance to measure the edit distance between two words with transpositions. 
Overall, I gained confidence in my abilities to extract textual information. I witnessed, in the previous assignment, how frequent misspellings occur while making textual analysis. This assignment taught me how to account for these frequent mistakes and make accurate predictions on misspelled words and their corrected spellings.

### Assignment #3 - Text Classification: 

This assignment combined text-mining concepts from the previous weeks with machine learning techniques from the previous course.  I created Countvectorizers and Tfidfvectorizers to turn training text into a tokenized number of words, digits, and remaining Ascii characters. I also created several classifiers - Multinomial Naive Bayes, Support Vector Classifier (SVC), and Logistic Regression - to determine whether a text message was spam or not.

## *Course 4 Project*

Final Project - Document Similarity and Topic Modeling: For the course’s finale, I computed the similarity of text documents. I also created topic distributions, using Genism’s LDA (Latent Dirichlet Allocation). This project challenged me to navigate the NLTK Corpus package which I previously had not explored during the course. 

<br />

# Course 5 - Applied Social Network Analysis:

As the final component in the specialization, this course challenged me to use all of the fundamentals I learned in the previous courses to pursue social network analysis. Before diving into coding, this course taught me the fundamentals of social networks, including basic graphs and how to extract information from specific pairs of nodes and edges. For coding, Python’s NetworkX library was instrumental in creating and dissecting social networks. I learned how to analyze the connectivity of nodes, and even measure how pivotal specific nodes are within a social network. The course culminated with a machine learning project applied to employee salary and relationship social networks.

## *Course 5 Assignments*

### Assignment #1 - Creating and Manipulating Graphs: 
After learning about different social networks (such as directed, undirected, weighted, and signed graphs), this assignment challenged me to put my understanding of the basics to the test. I explored a Bipartite graph to access nodes and degrees from an employee social network. Afterwards, I analyzed a Multigraph on employees’ favorite movies to uncover whether or not colleagues with higher relationship scores would possess similar movie preferences as one another. 

### Assignment #2 - Network Connectivity: 
As the next challenge within the course, I analyzed the connectivity within an employee email connection network. I used distance measures to infinity central and peripheral nodes. I also practiced extracting information from a social network, including the eccentricity, the shortest path between nodes, and even isolating nodes that would prevent a communication channel between specific nodes. This assignment pushed me to dissect a social network and learn how to quickly find key relationships among nodes and edges. 

Assignment #3 - Network Centrality: While the last assignment taught me how to evaluate the connectivity between nodes and edges, this assignment showed me how to measure the importance of certain nodes and edges within a social network. I used centrality measures (degree, closeness, and betweenness) to analyze a friendship and blog network. I also learned another measure for ranking nodes - the HITS Algorithm (hubs and authority). In sum, I gained a solid grasp of algorithms commonly employed in search engines. 

## *Course 5 Project*

### Final Project - Link Prediction: 

For the course’s final project, I combined machine learning concepts (from Course #3) with social network analysis to analyze a network on employee salary status and the likelihood of an employee forming future connections. As a warm-up, I practiced identifying algorithms used to randomly generate NetworkX graphs. 

After building up my knowledge of degree distributions, I was ready to analyze an employee social network.  I first isolated missing data on employee salaries. I divided my data into training and testing sets, and chose a Logistic Regression classifier to predict the probability that employees were receiving a  management position salary. I then applied link prediction - including Resource Allocation index and Preferential Attachment score - to an employee relationship network. 

After isolating node pairs without a connection, I used a Gradient Boosting Tree to predict how likely colleagues would share a future connection together. This final project challenged me to apply machine learning concepts to social networks I would likely encounter in the real-world.

<br />

In conclusion, this specialization helped me master data science fundamentals, from data cleaning to visualizing complex social network graphs - while further igniting my enthusiasm for data science. I learned more ways to make my data interactive, with graphs users can click on and decide the data they want to see displayed. I gained a greater understanding of how data science can help find answers to many problems we encounter in the world around us- whether it’s cancer research (as I investigated in the machine learning course) or understanding how new relationships can blossom (as seen in the social network course). Most importantly, data science can provide answers simply to broaden our understanding of the world. The visualizations and insight we can provide from all the data around us can really help improve scientific research and deepen our knowledge about phenomena around us, like climate change (as I investigated in the second course). 

While navigating through the basics, I learned a darker side of data analytics as well - how easy it is to infiltrate bias into our visualizations and analysis, perhaps without us even realizing it. While data science is an art, it is in our best interest to use the insights it yields for the best interest in mind - to deepen our knowledge and improve the lives of those around us. I look forward to applying my new skills to future projects.
