Classification of X-ray images

Shahram works in the archives of an inter-road medical center. He is obliged to classify the patient's medical files (which are collected from different departments of the center, their number is very large and may contain unrelated data) into predefined categories. In April and also in the summer season, due to the increase in trips and accidents, the number of referrals to this medical center increases sharply, while Shahram does not have the opportunity to sort the cases on his own. Considering this issue, the treatment center has decided to make the classification of cases smarter. In this matter, we intend to do a part of this classification.

Explanation about the data: The data of this problem includes 5 labeled categories of x-ray images (teeth(1), skull(2), chest(3), hand(4), foot(5)). In each category, a small percentage of the data during training is incorrect compared to the label attributed to them. The purpose of this problem is to classify test data into 6 categories (teeth (1), skull (2), chest (3), hand (4), foot (5), and outlier data (6)). The data on this problem can be accessed from this link.

How to evaluate:
To evaluate the models, several test images (from the categories of x-ray images of teeth (1), skull (2), chest (3), hand (4), foot (5), and data outside these categories) 6)) is given to the model and the accuracy of the extracted label is evaluated compared to the real data label. (Each assessment step includes two images and you get the score for that step if the labels of both images are correctly estimated). In this issue, in addition to accuracy, the speed of program execution as well as the amount of memory consumed during execution and the number of lines of code are also evaluated (80% of the evaluation points are for accuracy, 10% for execution speed, 5% for memory amount consumed and 5% of the number of required code lines is allocated).

steps
(1) Detection and removal of out-of-range data (2) Normalization (3) Modeling (4) Optimization (5) Open set learning

Step one:
Preliminary machine vision
Preliminary gate
Preliminary preprocessing
Introductory Feature Engineering

Second step:
Average machine vision
Preliminary gate
Preliminary preprocessing
Introductory Feature Engineering
