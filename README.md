# CIND820-Final-Project
Airbnb Host Pricing Strategies: Detecting the Influence of the Superhost Status

Airbnb has created the superhost program which provides benefits to distinguished hosts. Superhosts are experienced hosts who provide a shining example for other hosts1. For non-superhosts, pricing is yet a critical factor in the long-term success or failure of the accommodation.
The purpose of this study is to predict the price that a superhost would apply to an accommodation in the city of Toronto belonging to a non-superhost, and to test if a significant difference exists between superhost predicted prices and non-superhost actual prices, given a set of relevant features from the dataset2. Multiple regression algorithms will be applied to select the best model, followed by a hypothesis testing will help answer that question
We will exploit the “insideAirBnb” dataset, that gathers 15542 listings in Toronto as of April 2021. Along with the numerical features, the dataset includes a key textual attribute which is the guests ‘reviews (410918). Mining these reviews would be of a substantial added value to the regression model.
We will use a dictionary-based technique-the AFINN lexicon- to assign a score to each review and aggregate the scores into a new attribute that will be added to the predictors
The selected model will be trained on the superhost listings and tested on the non-superhost listings to predict the prices that superhosts would apply on non-superhosts listings. Hypothesis testing is the technique that will be used to judge if a significant difference experienced (superhosts) and less experienced (non-superhosts) accommodation suppliers

Themes: Regression-Text Mining-Hypothesis Testing
