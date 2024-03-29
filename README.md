
# Summary
This project examines the relationship between learning mentality and network strength for developer career satisfaction. Basic statistics, OLS regression, and k-means clustering are used to answer the following questions: 
- To what extent do full time developers have a learning mentality? 
- To what extent do full time developers have a strong social network with other developers? 
- How do individual learning mentality and social network strength relate to career satisfaction? 

# Prerequisites
- Anaconda 3 https://www.anaconda.com/distribution/

# Files  
- Learning_or_Networking.ipynb - Notebook with analyses and findings
- survey_results_public.csv.zip – csv to reconstruct (and improve on) analyses

# Main findings:
- Full time developers have fairly high career satisfaction. 
- Learning mentality variables are relatively left skewed with more full time employed developer respondents favoring a learning mentality.
- NetworkStrength variables are relatively normally distributed when compared to LearningMentality variables, indicating less existence of strong networks than existence of learning mentality amongst respondents.
- LearningMentality variables are relatively more correlated with one another than NetworkStrength variables.
- With OLS regression, we observe that LearningMentality and NetworkStrength variables are both important for CareerSatisfaction.
- If we create a more parsimonious model by creating aggregate variables for LearningMentality and NetworkStrength, we observe that LearningMentality has a more substantial relationship with CareerSatisfaction than NetworkStrength.
- Using k-means clustering, we find that networking learners appear to have the highest career satisfaction, followed by recluse learners, networking moderate-learners, then erratic networking anti-learners.

See blog post for more storytelling https://medium.com/@ncnakamine/to-learn-or-to-network-880c2504dbbf

# Citations
- Udacity Data Science Nanodegree Program https://www.udacity.com/course/data-scientist-nanodegree--nd025
- General Assembly Data Science https://generalassemb.ly/san-francisco/data-science https://github.com/ncnakamine/DS-SF-34
- Stack overflow data https://www.kaggle.com/stackoverflow/so-survey-2017



