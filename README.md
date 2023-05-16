# predicting-gender-based-injuries-soccer
Gender-based injuries in soccer players: Developing machine learning programs to predict the most significant factors.

Abstract:

Injuries, especially in sports, are devastating to pursuing a career in professional sports or even continuing to play at the competitive level. This study aimed to analyze injuries in a public dataset to test the hypothesis that male and female injuries are similar across different injury factors. 

Injury data was extracted from a stats-bomb library database and analyzed using Python libraries and the Jupyter notebook. A two-tailed independent t-test was performed on two variables, with gender as a factor, and linear or logistic regression was conducted to accurately fit a line through the data. 

The results of the independent t-test showed a significant difference between the number of male starters injured vs female starters injured. When performing my own linear or logistic regression, the alpha cutoff value was 0.05, and four significant correlations were found between time interval (5 minutes = 1 interval) and total injuries, female starters, male midfielders, and female defenders, all of which had a positive slope. 

In this study, I concluded that for both genders, the number of injuries increases as time increases, most likely due to player fatigue. There was a significant difference between gender-based injuries, as no factor shared a significant correlation, suggesting the need for further studies into specific factors for injuries in males and females separately. Future research could involve comparing different variables such as age and using a larger dataset to predict the probability of re-injury. These findings could help warn and prevent athletes from factors that contribute to their injuries.
