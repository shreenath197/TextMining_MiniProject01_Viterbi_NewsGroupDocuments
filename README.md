# TextMining_MiniProject01_Viterbi_NewsGroupDocuments

1) ALL  THE QUESTIONS ARE MANDATORY

2) You can use the Library and Frameworks wherever required except for TF-IDF as you have to implement TF-IDF from scratch.

3) Merge all your problems into a single python Notebook and Upload a Single Python notebook for all your problems.

4) Solution to the problems should be separate and placed one after the other in the final submission Notebook.

5) Do not submit Zip files.

6) Explicitly mention the questions as a Markdown cell in your notebook to segregate the different parts that you are attempting.

7) No deadline extension would be entertained. We are very strict on this from now. We really appreciate you to start working on the miniproject from Day - 1 so as to prevent any last minute occlusions ( Health / office work or any other )

You can use the following references for completing the assignment.

1) https://medium.com/analytics-vidhya/part-of-speech-and-viterbi-algorithm-11138ef0c63d (Links to an external site.)

2) https://towardsdatascience.com/end-to-end-topic-modeling-in-python-latent-dirichlet-allocation-lda-35ce4ed6b3e0 (Links to an external site.)

3) https://towardsdatascience.com/from-dataframe-to-n-grams-e34e29df3460 (Links to an external site.)

 

Dataset:  https://www.kaggle.com/datasets/crawford/20-newsgroups/data

The dataset have 20 newsgroup. Consider each news as separate document.

 

Term - Frequency Inverse Document Frequency  

 

1) Remove Stopwords (1 Mark)

2) Remove the punctuations. the special characters and convert the text to lower case.        (2 Mark)

3) create bigrams for the entire dataset and list down 10 least frequent bigrams. ( 1 Marks )

4) create bigrams for the entire dataset and list down 10 most frequent bigrams. ( 1 Marks )

5) Differentiate between stemming and lemmetization by running algorithm on few words. You can choose the words by your own. ( 1 Mark )

5) Implement the TF-IDF from scratch to use it for step 6. ( 3 Mark )

6) plot the scatter graph of 5 random words from a document such  that - ( 3 Marks )

x - axis frequency of word in the document
y - axis Tf-IDF value
Make sure to assign label to the scatter point which represent the word.
 

Refer to the following link to create POS labeled data: https://www.geeksforgeeks.org/part-speech-tagging-stop-words-using-nltk-python/

 

Perform Part of Speech Tagging using the Viterbi Algorithm, 

7) Label the cleaned Tf-IDF dataset ( obtained after performing step 1 and step 2 )   ( 2 Mark )

8) Split the Train and the Test Dataset                      (1 Mark)

9) Implement the Viterbi Algorithm ( you can use Library) to get the Part of Speech Tagging.        ( 3 Marks)

10) Calculate the Accuracy and F1 score. ( Number of Predicted Correct Tag in the test set / Total number of Data points in the test set)   (2 Marks)

   Topic Modelling        

Use cleaned Tf-IDF dataset ( obtained after performing step 1 and step 2 ) 

11) Using the LDA algorithm create the Topics (10) for the Corpus             (2 Marks)

12) List down the 10 words in each of the Topics Extracted.           (2 Marks)

Note: You may ignore if you find the words in the topic are not highly related. Marks would be deducted if you submit very very long notebooks. ( avoid printing irrelevant cells )

Deadline Extension will not be considered. Do not submit zip files. Do not upload dataset as part of submission

 

For any doubts and queries, you can write me on: chinesh.doshi@wilp.bits-pilani.ac.in
