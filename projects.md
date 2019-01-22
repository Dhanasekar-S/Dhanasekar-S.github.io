---
layout: page
title: Projects
---
<h3>Amazon Question-Answer Retrieval | (2018-Present)</h3>
The goal of this project is to build and evaluate a simple question-answering system on the Amazon QA dataset based on the sentence embeddings of questions and answers (i.e. without sequential structural information contained in sentences). Sentence embeddings are easy to use because they are quite fast to compute (often linear in number of words in the sentence), and they contain rich semantic information about the sentence in a compressed representation, as opposed to sequences of word embeddings which are often time-consuming to work with. By using a pre-trained architecture ,we can embed question-answer sentence pairs and treat question answering as a retrieval problem whereby a user asks a question, and a trained system retrieves an existing response from an extensive training dataset, as opposed to a generation problem whereby the system is expected to generate a novel response, which is often technically challenging and time-consuming. We wish to evaluate the performance of these simpler retrieval methods on a question answering task by comparing 2 different approaches. We also introduce a method to retrieve only the relevant responses based on any side information (like reviews or description) that we may have. <br>

<h3><a href="https://Dhanasekar-S.github.io/research/ECE_590__NLP_Final_Project.pdf" target="_blank">Project PDF</a></h3>
<br>

<h3>Using Twitter to find Top Influential words across profiles | (2017)</h3>
This work proposes a hybrid approach of recommending social media profiles, articles, and advertisements to a query user. The profiles are recommended based on the similarity score between the query profile, and profile under evaluation. The similarity between a set of profiles is envisaged by identifying the top influential words thus causing a high similarity through an influential score metric for each word. Finally, we analyze the top influential words over a set of profiles through clustering by keeping track of the chronological order of entry of that profile into that cluster. The proposed method was implemented on datasets comprising 1.5 M Tweets obtained from Twitter. Experimental results show that the resultant influential words were highly representative of the relationship between two profiles or a set of profiles and were devoid of stop words and other less representative words.
The work was presented at SocInfo, University of Oxford<br>
<br>

<h3>Predicting topics for Twitter users | (2017)</h3>
In this project, using a Twitter user’s past Tweets and responses as measures, we suggest possible personalized topics to attain maximum reach in terms of likes and retweets. The work is to be presented at ICMLSC, Vietnam
<br>
<br>

<h3>An analysis of non-immigrant work visas in the USA using Machine Learning | (2017)</h3>
The project was about classifying the visa petitions filed from 2011-16 filed as highly skilled or not using Random Forests. Experimental results show the companies that are classified as abusing these visas are well consistent with the ones shown in reports and news articles.
<br>
<br>

<h3> Efficient Recommender Systems using decision Trees  | (2017)</h3>
This work is about the building of efficient Recommender systems that is a hybrid version of Content-based Recommendation system and Collaborative filtering. The sparsity of the Recommender systems is handled through the use of Random Forests comprising of different cases of Decision Trees.
<br>
<br>
<h3>Deep Learning of Airline data | (2016)</h3>
The Exploratory Data Analysis was carried out using R and visualized as different graphs and histograms with plots. The airline data is then 1.Normalized 2.Fed into a neural network 3.Input is AirTime and elapsed time 4.Output is Arrival and Departure delay 5.This training data is learned and tested with sample data. The dimensions of the neural network is 3 x 4 layer 1 4 x 8 layer 2 8 x 32 layer 3 32 x 16 layer 4 16 x 4 layer 5 4 x 2 layer 6<br>
<br>
<br>
<h3>Handwritten Digit Recognizer using Neural Networks | (2016)</h3>
Implemented a Neural Network for classifying handwritten digits from the MNIST data using Tensorflow and compared and contrasted the accuracy of the model by varying the number of iterations of gradient descent optimization.<br>
<br>
<br>

<h3>Application Complexity Analysis | (2015)</h3>
The Application Complexity Analysis deals with capturing the computation and the communication complexities of an application. This enables the architect to analyze the architectural requirements of several applications and help design a core that is capable of utilizing the functional and communication aspects of the application to its fullest. Simultaneously running multiple applications poses a major barrier to reaching higher performances. This may however be solved by efficiently utilizing the detailed analysis of the multiple applications to derive the best possible architecture for such a system using the concepts of Machine Learning.<br>
<br>
<br>

<h3>Customizable Workload | (2015)</h3>
A graph theoretic based workload model was developed. The edge weights are a function of the measure of data in bytes that gets communicated from one node to the other and the frequency of communication. The node weights are either a numeric, semi-numeric or non-numeric algorithm and also, general purpose operations. The algorithms, in-degree and out-degree of the nodes, nodes per level, total number of nodes across all the levels and the number of levels are decided based on the specified distributions of these complexities.
The most striking advantage of the proposed generic model of the workload is application cloning, besides comprehensive workload generation for benchmarking various classes of high performance computing system. In several instances, the user cannot part with the crucial details of the application to avoid IP violation and any government regulation<br>
<br>
<br>

<h3>Heterogeneous Networks using ANN | (2015-2016)</h3>
A Heterogeneous Many-Core network is necessary to transmit data across compute intensive cores. The buffer size in these networks are solved as an AI problem. The buffer size is tuned and perturbed to achieve ideal values using Backpropogation Artificial Neural Networks<br>
<br>
<br>

<h3>An intelligent Chatbot using Deep learning and NLP | (2016) </h3>
Chatbot is a computer program designed to simulate conversation with human users. It uses Natural Language Processing techniques like Stemming, Stop words removal and Lemmatization powered with deep neural networks to find the relations among different words and Natural Language Generation techniques to generate human understandable responses. The concept is novel in the way that neural networks learn dynamically as and when the conversation builds up rather than using predefined datasets.<br>
<br>
<br>

<h3>Bus tracking using GPS, GSM and Arduino | (2015)</h3>
The project aims at tracking the vehicle's location using a GPS module, to know about the location of the vehicle. The location coordinates are then sent to a server database sent through a GSM module. A microprocessor coordinates this process and is controlled by an android application. The live feed of the bus is tracked in the app to save undefined waiting time. This project is being adopted in my college buses.<br>
<br>
<br>

<h3>Heterogeneous Many-Core Architectural Design Space | (2015)</h3> 
A necessary step towards achieving a high-performance computing system is to design the system architecture based on the application rather than the other way around. The architecture should be easily scalable and modifiable to the needs of the application. This is achieved by having an architectural design space. The design space helps us in modifying and scaling various components of the system architecture ranging from the functional units and register banks to the network on chip. Simultaneous Execution Of Multiple APPlication without space & time sharing is made possible through the existence of the architectural design space enabling an application level parallel systemnition
<br>
<br>

<h3>Cache Design and Simulation | (2015-2015)</h3> 
A Multi-Core Cache hierarchy (L1,L2 and L3) supported by MESI protocol to handle data validation and invalidation was implemented. The resultant cache was tested with thousands of fetches and replacement simulations using the Time Model Simulator.
<br>
<br>

<h3>Time Model Simulator | (2015)</h3>
A full-scale Time model simulator is designed so as to give a proof of concept for the proposed Parallel architecture using C++ and Python. The Simulator is modular and may be customized as per the requirements of the architecture to be simulated. Developed in an Object Oriented Fashion, the simulator is also capable of being scaled to any number of cores that satisfy the programming limits. The simulator is customizable to work with heterogeneous many-core architecture which none of the current simulators possess. It simulates the cores that are capable of executing multiple applications simultaneously without Space-Time sharing.<br>
