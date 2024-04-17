# Email-Spam-Classifier-with-Visualization

# Summary

*About dataset:The dataset 'emails.csv' contains information on 5172 email files, each represented by a row in the dataset. Each email is characterized by 3000 columns representing the most common words found in the emails, with counts of occurrences for each word. Additionally, the dataset includes a 'Prediction' column indicating whether each email is classified as spam (1) or not spam (0).

*Data Preprocessing: The first observation reveals that the dataset may contain missing values, which can impact model training. Thus, preprocessing steps such as handling missing values is necessary before building the model. After the data preprocessing, the missing values are none in my dataset.

*Data Visualization: Initially in order to understand the distribution and characteristics of spam and not spam emails within the dataset. By analyzing the frequency of the most common words in both spam and not spam emails,I have gained insights into the distinguishing features of each category. Through bar plots showcasing the top 10 words in spam and not spam emails,I observed a pattern in word usage that may serve as discriminative features for classification. Furthermore, I visualized histograms of word counts for specific keywords, such as the first word in the dataset: 'the', to observe differences in distribution between spam and not spam emails. These visualizations provided a comparative view of how frequently certain words appear in both categories, offering valuable clues for feature selection and model training.

*Classifiers: I have taken two classifiers for this project : Logistic regression and Support vector machines classfiers. Logistic regression is a linear model that estimates the probability of a binary outcome, making it suitable for binary classification tasks like spam detection. On the other hand, SVM is a versatile classifier that can handle linear and non-linear decision boundaries, offering flexibility in capturing complex patterns in the data. By visualizing the top words in spam and not spam emails and plotting histograms of word counts, we gained a better understanding of the dataset's characteristics and potential features influencing email classification.

*Conclusion: The comparison between logistic regression and SVM revealed that both classifiers achieved high accuracy and performed well in distinguishing between spam and not spam emails. The Logistic Regression Classifier is the best model with 97% accuracy for this project. The end result of the analysis is a robust and efficient solution for combating email spam, with the help of this well developed logistic regression model. This model can be deployed to automatically categorize incoming emails, providing users with a reliable defense against spam and enhancing overall email security.
