# Sentiment-Analysis-on-Cloud-Platforms
Sentiment analysis using Traditional Machine Learning Algorithms and Deep Learning Algorithms 

Real-Time Sentiment Analysis using AWS
Image Bhattarai, S M Rafiuddin
Department of Computer Science, Oklahoma State University
image.bhattarai@okstate.edu, srafiud@okstate.edu
Abstract
With the unprecedented growth of social media, the rise of public opinions and emotions has
increased exponentially. These feelings are pivotal for any organization to understand a person’s
satisfaction and inclination towards a cause – be it politics, education or even healthcare.
Analyzing this data would not only help monitor public opinions about events but would also help
understand how a person might react to a future change. Sentiment Analysis is a branch of Natural
Language Processing (NLP) that studies and examines the sentiment of the public in order to
achieve insights about a trend or a cause. In this proposal, we propose an application that utilizes
Sentiment Analysis to study people’s emotion and attitude towards a topic. It uses Amazon
SageMaker to prepare, build, train, and deploy the application. After training the model, and testing
it with various inputs, we would expect that our application will successfully classify sentiment
with significant accuracy.
Index Terms – Sentiment Analysis, Amazon SageMaker, Natural Language Processing
Objectives
This project has been proposed to achieve the following objectives-
• Develop a scalable text classification model that utilizes Amazon SageMaker to classify
the public opinions as positive, negative, or neutral.
• Improve data preprocessing and feature extraction by removing any stop words and nonalphabets so that we get an optimized input data.
• Utilize Amazon Web Services (AWS) to deploy the model to the cloud, thereby removing
the need for it to have a locally deployed machine.
• Optimizing performance by tuning the hyperparameters to get the best accuracy and
performance.
Proposed Dataset
We will use two datasets for our taska. IMDb Movie Reviews:
The IMDB Reviews dataset contains a total of 50,000 movie reviews, with 25,000 reviews labeled
as positive and 25,000 reviews labeled as negative. This dataset is commonly used for sentiment
analysis tasks, where the goal is to classify a given movie review as either positive or negativebased on its content. Each review in the dataset is represented as a plain text document, and the
dataset is split into a training set of 25,000 reviews and a test set of 25,000 reviews. The IMDB
Reviews dataset is widely used in natural language processing research and has been used as a
benchmark for evaluating the performance of many different text classification models.
b. SemEval-2017 Task 4:
The SemEval-2017 Task 4 dataset contains 10,000 tweets in English, which are labeled with one
of three sentiment classes: positive, negative, or neutral. The tweets were selected based on their
relevance to six different topics, including politics, climate change, and feminism. It has been
widely used as a benchmark for evaluating sentiment analysis models on social media data.
Technologies Planned to be Used
From topics covered in the syllabusPySpark
For Sentiment Analysis TasksThere are several traditional machine learning algorithms that can be used to classify text on the
IMDb Reviews and SemEval-2017 Task 4 datasets. Here are a few examples:
a. Naive Bayes
b. Support Vector Machines (SVMs)
c. Logistic Regression
d. Decision Trees
e. Random Forests
And also, some Deep Learning Techniques such asa. Recurrent Neural Networks (RNNs)
b. Long Short-Term Memory (LSTM) Networks
c. Bidirectional RNNs
d. Transformer Networks
Also, we would explore any novel idea that can be implemented along with these techniques.
For Cloud Deployment and Computing:
Amazon AWS
Task Assignment for Each Team Members
1. Report Writing and Presentation –a. S M Rafiuddin
b. Image Bhattarai
2. Literature Review –
a. S M Rafiuddin
3. PySpark Implementation –
a. Image Bhattarai
4. Traditional ML
a. Image Bhattarai
b. S M Rafiuddin
5. Deep Learning Algorithms –
a. S M Rafiuddin
b. Image Bhrattarai
6. Cloud Technologies –
a. Image Bhattarai
b. S M Rafiuddin
