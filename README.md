# Sentimental-Analysis-Project

## Introduction

Climate change is a growing issue that requires everyone's immediate attention. 
In recent years, we have witnessed rising temperatures and sea-levels, eruptions of wildfires in various regions and unstable storm conditions.
With most businesses adopting sustainable and eco-friendly services and products, it is critical to understand people's perception of 
this ongoing crisis to formulate better strategies for businesses.

To achieve this, we analyzed tweets from Twitter to gain valuable insights towards people's sentiments. The data is sourced from Kaggle and the Twitter Standard API.

## Research Questions

### How has the trend in climate change awareness shifted over time?
We assess two datasets belonging to two different time periods to answer this.

### What is the ruling sentiment amongst people towards climate change?
By labeling climate change tweets as either positive, negative, or neutral, we aim to better understand the general sentiment towards climate change.

## Models used
### Models selected:
    i. Forest model
    ii. KNN model
    iii. Linear SVC model
  
### Performance of each model
    i. F1-Score 0.36 (weighted average)
    ii. F1-Score 0.53 (weighted average)
    iii. F1-Score 0.59 (weighted average) and 0.67 after tuning
 
## Conclusion

### Old tweets: Pro-climate change or news (2015-2018)

Strong political influence of the label of the tweets with Donald Trump being mentioned many times in anti-climate tweets

 Bernie Sanders being mentioned many times in pro climate change tweets

The Linear SVC model performed the best:
 f1 score of 0.59
After tuning the hyperparameters, there was an increase in the performance by 2%

### Recommendations

Based on the exploratory analysis there could have been a change in the general sentiment of climate change on Twitter moving towards being more neutral.

However, Neural Network still remains a promising model. It would be interesting to explore this further by gathering more data, doing more feature engineering, 
and training more models.


