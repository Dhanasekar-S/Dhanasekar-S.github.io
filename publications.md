---
layout: page
title: Publications
---

<h1>Methods for Numeracy-Preserving Word Embeddings</h1>
<h2><a href="https://www.aclweb.org/anthology/2020.emnlp-main.384/" target="_blank">EMNLP 2020</a></h2>

<h3> Dhanasekar Sundararaman, Shijing Si, Vivek Subramanian, Guoyin Wang, Devamanyu Hazarika, Lawrence Carin</h3>
<h4>Appeared in the Proceedings for EMNLP 2020</h4>

<b>Abstract:</b>
Word embedding models are typically able to capture the semantics of words via the distributional hypothesis, but fail to capture the numerical properties of numbers that appear in the text. This leads to problems with numerical reasoning involving tasks such as question answering. We propose a new methodology to assign and learn embeddings for numbers. Our approach creates Deterministic, Independent-of-Corpus Embeddings (the model is referred to as DICE) for numbers, such that their cosine similarity reflects the actual distance on the number line. DICE outperforms a wide range of pre-trained word embedding models across multiple examples of two tasks: (i) evaluating the ability to capture numeration and magnitude; and (ii) to perform list maximum, decoding, and addition. We further explore the utility of these embeddings in downstream tasks, by initializing numbers with our approach for the task of magnitude prediction. We also introduce a regularization approach to learn model-based embeddings of numbers in a contextual setting.<br>
<br>
<br>


<h1>Syntax-Infused Transformer and BERT models for Machine Translation and Natural Language Understanding</h1>

<h3> Dhanasekar Sundararaman, Vivek Subramanian, Guoyin Wang, Shijing Si, Dinghan Shen, Dong Wang, Lawrence Carin</h3>
<b>Abstract:</b>
Attention-based models have shown significant improvement over traditional algorithms in several NLP tasks. The Transformer, for instance, is an illustrative example that generates abstract representations of tokens inputted to an encoder based on their relationships to all tokens in a sequence. Recent studies have shown that although such models are capable of learning syntactic features purely by seeing examples, explicitly feeding this information to deep learning models can significantly enhance their performance. Leveraging syntactic information like part of speech (POS) may be particularly beneficial in limited training data settings for complex models such as the Transformer. We show that the syntax-infused Transformer with multiple features achieves an improvement of 0.7 BLEU when trained on the full WMT 14 English to German translation dataset and a maximum improvement of 1.99 BLEU points when trained on a fraction of the dataset. In addition, we find that the incorporation of syntax into BERT fine-tuning outperforms baseline on a number of downstream tasks from the GLUE benchmark.<br>
<br>
<br>


<h1>Learning Compressed Sentence Representations for On-Device Text Processing</h1>
<h2><a href="http://www.acl2019.org/EN/index.xhtml" target="_blank">Association for Computational Linguistics 2019</a>, Florence, Italy</h2>

<h3> Dinghan Shen, Pengyu Cheng, Dhanasekar Sundararaman, Xinyuan Zhang, Qian Yang, Meng Tang, Asli Celikyilmaz, Lawrence Carin</h3>
<h4>Appeared in the Proceedings for ACL 2019</h4>
<h3><a href="https://www.aclweb.org/anthology/P19-1011/" target="_blank">Pdf</a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/Linear95/BinarySentEmb" target="_blank">Code base and Results</a></h3>
<b>Abstract:</b>
Vector representations of sentences, trained on massive text corpora, are widely used as generic sentence embeddings across a variety of NLP problems. The learned representations are generally assumed to be continuous and real-valued, giving rise to a large memory footprint and slow retrieval speed, which hinders their applicability to low-resource (memory and computation) platforms, such as mobile devices. In this paper, we propose four different strategies to transform continuous and generic sentence embeddings into a binarized form, while preserving their rich semantic information. The introduced methods are evaluated across a wide range of downstream tasks, where the binarized sentence embeddings are demonstrated to degrade performance by only about 2% relative to their continuous counterparts, while reducing the storage requirement by over 98%. Moreover, with the learned binary representations, the semantic relatedness of two sentences can be evaluated by simply calculating their Hamming distance, which is more computational efficient compared with the inner product operation between continuous embeddings. Detailed analysis and case study further validate the effectiveness of proposed methods.<br>
<br>
<br>


<h1>Twigraph: Discovering and Visualizing Influential Words between Twitter Profiles</h1>
<h2><a href="http://socinfo2017.oii.ox.ac.uk/" target="_blank">Social Informatics 2017</a> ,<a href="http://www.ox.ac.uk/" target="_blank">University of Oxford</a></h2>

<h3> Dhanasekar Sundararaman, Sudharshan Srinivasan </h3>
<h4>Appeared in the <b>Springer</b> Proceedings for SocInfo 2017, Oxford, UK</h4>
<h3><a href="https://link.springer.com/chapter/10.1007/978-3-319-67256-4_26" target="_blank">Pdf</a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://gitlab.com/Dhanasekar-S/Twigraph" target="_blank">Code base and Results</a></h3>
<b>Abstract:</b>
The social media craze is on an ever increasing spree, and people are connected with each other like never before, but these vast connections are visually unexplored. We propose a methodology Twigraph to explore the connections between persons using their Twitter profiles. First, we propose a hybrid approach of recommending social media profiles, articles, and advertisements to a user.
The profiles are recommended based on the similarity score between the user profile, and profile under evaluation. The similarity between a set of profiles is investigated by finding the top influential words thus causing a high similarity through an Influence Term Metric for each word. Then, we group profiles of various domains such as politics, sports, and entertainment based on the similarity
score through a novel clustering algorithm. The connectivity between profiles is envisaged using word graphs that help in finding the words that connect a set of profiles and the profiles that are connected to a word. Finally, we analyze the top influential words over a set of profiles through clustering by finding the similarity of that profiles enabling to break down a Twitter profile with a lot of followers to fine level word connections using word graphs. The proposed method was implemented on datasets comprising 1.1 M Tweets obtained from Twitter. Experimental results show that the resultant influential words were highly representative of the relationship between two profiles or a set of profiles.<br>
<br>
<br>


<h1>Bus Tracking and Intelligent Arrival Prediction System</h1>
<h2><a href="http://dms.iitd.ac.in/IFIP-I3E_2017/homepage.html" target="_blank">The 16th IFIP Conference on e-Business, e-Services and e-Society</a> ,<a href="http://www.iitd.ac.in/" target="_blank">IIT Delhi</a></h2>

<h3>Dhanasekar Sundararaman, Gowtham R, Jagadeesh R, Sasirekha S, Joe Louis Paul I</h3>
<h4>Appeared in the <b>Springer</b> Proceedings for IFIP Conference on e-Business, e-Services and e-Society</h4>

<i> Acceptance rate < 40%. One among the very few undergrads</i>
<h3><a href="https://link.springer.com/chapter/10.1007/978-3-319-68557-1_27" target="_blank">Pdf</a> </h3>
  <b>Abstract:</b>
In this work, an efficient vehicle tracking system is designed and implemented for tracking the movement of any vehicle from any location and time. The proposed system uses popular technology that combines a smartphone application with a microcontroller that is inexpensive compared to others. The users will be able to continuously monitor a moving vehicle on demand using the Smartphone application and determine the estimated distance and time for the vehicle to arrive at a given destination. Apart from this, the system is designed further to account for the case of failing to catch one’s vehicle by dynamically suggesting a new vehicle within one’s reach with an estimated time and a route. The data collected is effectively used to predict the estimated arrival time of the vehicles using sophisticated machine learning technique Artificial Neural Networks (ANN). While there are other systems on vehicle tracking, we present a vehicle tracking, dynamic route suggestion on failing to catch one’s vehicle and intelligent arrival time prediction system together making it a comprehensive system for users. The feasibility and effectiveness of the system are presented through experimental results of the vehicle tracking system and some experiences on practical implementations.<br>
<br>
<br>
