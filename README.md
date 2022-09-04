# Underwater Minesweeper : Mine Classification Using SONAR Data

Machine Learning Course Submission

Patrol ships with sonar capabilities are used to survey the seas for possible underwater mines. These boats are usually specialized to do passive countermeasures like mine detection without being detected. And in this study, several rock and metal items were simulated as underwater objects and using sonar, the energy feedback was recorded and used to interpret their corresponding classification.

The dataset consists of 208 samples with a specific pattern represented by its features. Each feature ranges from 0 to 1 and represents the energy within a particular frequency band, over a period of time.

See full report (ipynb) [HERE](https://github.com/mbdelaresma/rock_mine_classification/blob/main/FinalReport.ipynb)

# Highlights

1. Yeo-Johnson transformation was done on the dataset because most of the features are skewed.

2. There is a notable increase in accuracy after the features were scaled for kNN and SVC.

3. Grid search was used to optimize the hyperparameters of chosen machine learning models.

4. It is important to have a holdout data set to test the model’s performance after training and validation.

5. Depending on the problem, precision or recall is more important than the accuracy of the model.

![image](https://user-images.githubusercontent.com/71246479/188295992-fa3da74a-271a-4a1f-94c3-f634616589b2.png)

