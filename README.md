# Advanced-Negative-Behaviour-Detection


Humans have built extensive models of expressing their thoughts via numerous means. The internet has not only become a credible method for expressing one's thoughts, but is also rapidly becoming the single largest means of doing so. In this context, the increasing levels of threat and abuse from certain sections of the online community renders a fair degree of inadequacy to facilitate proper conversations. Quite naturally, one area that requires attention is the identification of negative online behaviour and consequentially, restricting their scope. This can be done by developing a classification module for the various types of toxic comments that we may be interested in finding.

Machine Learning is one of the most progressing fields in the world right now. We using the same including some other python libraries have developed a model which will dynamically fetch the recent tweets from the twitter about the two popular celebrities in American politics Donald Trump and Joe Biden. We will be classifying the tweets on the basis of negative, positive and neutral tweets and will further compare them and graphically visualize them.
Further the main part of our project  i.e. toxicity classifier (classification of negative comments) runs where we classify the created dataset into six categories using machine learning algorithms

Libraries imported and their uses:
•	tweepy, a python library used for accessing Twitter API
•	textblob, a textual data processing python library for sentiment analysis. 
•	numpy, a library to perform high-level mathematical operations.
•	pandas, a data structure and data analysis library for python.
•	matplotlib, a python library to create interactive plots and visualizations.
•	seaborn, a library which provides a high-level interface for drawing attractive and informative statistical graphics.
•	scikit-learn, a) to choose an appropriate ML model- logistic regression in our case for solving a classification problem.
             b) CountVectorizer- to count the number of times a word occurs
             

NB-SVM
•	Naive Bayes (NB) and Support Vector Machine (SVM) are widely used as baselines in text-related tasks but their performance varies significantly across variants, features and datasets.
•	Word bigrams are useful for sentiment analysis, but not so much for topical text classification tasks
•	NB does better than SVM for short snippet sentiment tasks, while SVM outperforms NB for longer documents
•	A SVM variant using NB log-count ratios as feature values consistently performs well across tasks and datasets

•	MNB is better at snippets while SVM is better at full-length reviews
•	NBSVM performs well on snippets and longer documents for for sentiment, topic and subjectivity classification. NBSVM is a very strong baseline for sophisticated methods aiming to beat a bag of features.
•	In sentiment classification there are gains from adding bigrams because they can capture modified verbs and nouns.


Future work & Conclusion

Our future work as planned is to further add a new class to classify negative comments and we can try to further predict the personality and reputation of the person. We can further suggest the changes in personality and behaviour required to make a good reputation among the public. 
To conclude this paper, we will do a quick review of all the work we have done so far since the beginning of this project. Originally, we first started to fetch live tweets from twitter and use our model to analyse and predict the toxicity in those tweets to make our project dynamic in nature. It was for all of us an interesting first step into the world of research, and it provided us a hands-on experience of what can be done with machine learning techniques in general.


        References

1.	(PDF) SVM Approach to Forum and Comment Moderation
2.	"Anatomy of online hate: Developing a taxonomy and machine learning mod" by Joni SALMINEN, Hind ALMEREKHI et al.
3.	Stack Overflow - Where Developers Learn, Share, & Build Careers
4.	https://monkeylearn.com/blog/introduction-to-support-vector-machines-svm/#:~:text=A%20support%20vector%20machine%20
5.	http://docs.tweepy.org/en/latest/
6.	https://numpy.org/doc/stable/
7.	https://pandas.pydata.org/docs/
8.	https://scikit-learn.org/stable/user_guide.html



