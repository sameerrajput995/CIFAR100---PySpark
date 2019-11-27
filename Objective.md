Data preparation
D1) Work on one of the 7 superclass pairs listed here.

D2) Combine both the testing and training data into one dataset after you load the cifar100 data

D3) Filter to select images belonging to your assigned superclasses.

D4) Validate you have selected the right data matching your assigned classes by printing 4 randomly selected images from each sub-class on your Colab notebook. Show the verbal (not numeric) superclass and class labels of each randomly printed image on top of the image.

Prediction on randomly selected testing images

Randomly select 80% of the data as training data and the rest as testing data. Use your machine learning (ML) algorithm to train the model with the training data and subsequently use it to predict the testing data. Disregard the sub-class label and focus on the superclass label only in this binary classification problem.

PR1) Describe your ML algorithm(s) with workflow/architecture diagram(s).

PR2) Show your prediction scores with train-test-split (80/20).

PR3) List 36 random images with original and predicted labels with your algorithm.

PR4) Use confusion matrix and classification report to analyze your binary classification result. Explain what you observed from the result and comment on if they are consistent.

PR5) Compare, for the same ML algorithm used, the speed and accuracy of Spark vs. Scitkit-learn.  Comment on why one is performing better than the rest.

Prediction on one testing subclass images from each of the two superclasses

Select one sub-class from each of your two assigned super-classes. Use these two selected sub-classes as your testing data. Use all the data minus the two selected test sub-classes as your training data. Repeat for all 5 x 5 =25 pairs of subclass images. Your algorithm should be initialized before it is being trained on new training dataset in each of these 25 trials. All results should be based on the SAME algorithm you designed.

PS1) Summarize your overall prediction results in a 5 by 5 chart, with 5 subclasses from one superclass as the row index and the other 5 subclasses from the other superclass as the column index.  Color the worst 5 and the best 5 with different colors for ease of reference in the chart.

PS2) Show, in a table, the following summary among these 25 trials - Data preparation
D1) Work on one of the 7 superclass pairs listed here.

D2) Combine both the testing and training data into one dataset after you load the cifar100 data

D3) Filter to select images belonging to your assigned superclasses.

D4) Validate you have selected the right data matching your assigned classes by printing 4 randomly selected images from each sub-class on your Colab notebook. Show the verbal (not numeric) superclass and class labels of each randomly printed image on top of the image.

Prediction on randomly selected testing images

Randomly select 80% of the data as training data and the rest as testing data. Use your machine learning (ML) algorithm to train the model with the training data and subsequently use it to predict the testing data. Disregard the sub-class label and focus on the superclass label only in this binary classification problem.

PR1) Describe your ML algorithm(s) with workflow/architecture diagram(s).

PR2) Show your prediction scores with train-test-split (80/20).

PR3) List 36 random images with original and predicted labels with your algorithm.

PR4) Use confusion matrix and classification report to analyze your binary classification result. Explain what you observed from the result and comment on if they are consistent.

PR5) Compare, for the same ML algorithm used, the speed and accuracy of Spark vs. Scitkit-learn.  Comment on why one is performing better than the rest.

Prediction on one testing subclass images from each of the two superclasses

Select one sub-class from each of your two assigned super-classes. Use these two selected sub-classes as your testing data. Use all the data minus the two selected test sub-classes as your training data. Repeat for all 5 x 5 =25 pairs of subclass images. Your algorithm should be initialized before it is being trained on new training dataset in each of these 25 trials. All results should be based on the SAME algorithm you designed.

PS1) Summarize your overall prediction results in a 5 by 5 chart, with 5 subclasses from one superclass as the row index and the other 5 subclasses from the other superclass as the column index.  Color the worst 5 and the best 5 with different colors for ease of reference in the chart.

PS2) Show, in a table, the following summary among these 25 trials - mean, std, min, 25%-50%-75%, max


PS3) Explain your observed result

PS4) Compare, for the same ML algorithm used, the speed and accuracy of Spark vs. Scitkit-learn.  Comment on why one is performing better than the rest.


PS3) Explain your observed result

PS4) Compare, for the same ML algorithm used, the speed and accuracy of Spark vs. Scitkit-learn.  Comment on why one is performing better than the rest.

Your report should contain at least the following:
R1. A table of content with hyperlinkable page to each relevant section (Hint: Use Word->Reference->Table of content and make each chapter/section description as Heading 1 or 2 under Styles first)

R2. Describe in your report the major difference between using Spark and that of Scikit-learn. Elaborate on the performance comparison in terms of the speed and the prediction accuracy between Scikit-learn and Spark in this project.

R3. List your team members and team name on the first page of both your report

R4. Provide all online links on example code you used/extended in the report.

R.5 Show a clear list on who collaborated with who to accomplish any bonus feature, if any.

R6. Add comments on each major step inside your scripts. Show references to any algorithm or reused code.

R7. Your report should contain at least the following in the order shown.
