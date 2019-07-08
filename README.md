
-	This project examines the relationship between learning mentality and network strength for developer career satisfaction. Basic statistics, OLS regression, and k-means clustering are used to answer the following questions: 
o	To what extent do full time developers have a learning mentality? 
o	To what extent do full time developers have a strong social network with other developers? 
o	How do individual learning mentality and social network strength relate to career satisfaction? 
-	Prerequisites/Libraries
o	Anaconda 3 https://www.anaconda.com/distribution/
-	Files  
o	Learning_or_Networking.ipynb - Notebook with analyses and findings
o	survey_results_public.csv.zip – csv to reconstruct (and improve on) analyses
-	Main findings:
o	Full time developers have fairly high career satisfaction. 
o	Learning mentality variables are relatively left skewed with more full time employed developer respondents favoring a learning mentality.
o	NetworkStrength variables are relatively normally distributed when compared to LearningMentality variables, indicating less existence of strong networks than existence of learning mentality amongst respondents.
o	LearningMentality variables are relatively more correlated with one another than NetworkStrength variables.
o	With OLS regression, we observe that LearningMentality AND NetworkStrength variables are important for CareerSatisfaction
o	If we create a more parsimonious model by creating aggregate variables for LearningMentality and NetworkStrength, we observe that LearningMentality has a more substantial relationship with CareerSatisfaction than NetworkStrength.
o	Clustering LearningMentality and NetworkStrength allows use to label users according to these two aggregated dimensions.
o	Networking learners appear to have the highest career satisfaction, followed by recluse learners, networking moderate-learners, then erratic networking anti-learners.
-	 Citations
o	Udacity Data Science Nanodegree Program https://www.udacity.com/course/data-scientist-nanodegree--nd025
o	General Assembly Data Science https://generalassemb.ly/san-francisco/data-science https://github.com/ncnakamine/DS-SF-34
o	Stack overflow data https://www.kaggle.com/stackoverflow/so-survey-2017
o	



