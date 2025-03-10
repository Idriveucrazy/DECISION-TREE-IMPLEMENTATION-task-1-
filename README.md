# DECISION-TREE-IMPLEMENTATION-task-1-
COMPANY : CODETECH IT SOLUTIONS

NAME : VED SUHAS KULKARNI

INTERN ID : CT04WC71

DOMAIN : MACHINE LEARNING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

DESCRIPTION OF THE TASK :

Decision Tree Model for Drug Classification-
The objective of this task was to build and visualize a Decision Tree Classifier using the scikit-learn library to classify or predict outcomes based on a given dataset. The dataset contained information about patients, including Age, Sex, Blood Pressure (BP), Cholesterol levels, Sodium-to-Potassium ratio (Na_to_K), and the corresponding drug type prescribed to them.

Data Preprocessing-
Since the dataset contained categorical features like Sex (M/F), BP (High/Low/Normal), and Cholesterol (High/Normal), they were first converted into numerical form using the LabelEncoder from the sklearn.preprocessing module. This step was essential because Decision Tree models only work with numerical data.

Splitting the Data-
The dataset was then split into training (70%) and testing (30%) sets using the train_test_split() function from sklearn.model_selection. The training data was used to train the model, while the testing data was used to evaluate the model's performance.

Building and Training the Decision Tree-
A DecisionTreeClassifier was created using the entropy criterion (which measures information gain). The model was then fitted on the training data using the fit() function. This step allowed the model to learn patterns from the input features to predict the type of drug prescribed.

Prediction and Accuracy-
The model was tested on the test data using the predict() function, and its accuracy was measured using the accuracy_score() function from sklearn.metrics. The accuracy score provided a measure of how well the model performed on unseen data. Additionally, a confusion matrix was plotted to visualize the model's performance in correctly and incorrectly predicting the drug type.

Visualization of Decision Tree-
The Decision Tree was visualized using the plot_tree() function from sklearn.tree. This provided a clear graphical representation of the decision-making process, showing how the model splits the data based on feature values to classify the drug type. The visualization was enhanced by adding feature names, class names, and filled color nodes to make it more interpretable.

Conclusion-
The Decision Tree model successfully classified the drugs based on patient information with reasonable accuracy. Visualizing the Decision Tree helped understand how different features like Age, BP, Cholesterol, etc. influenced the prediction of a particular drug. This model can be further improved by tuning hyperparameters or deploying it as an interactive web application for real-time predictions.

OUTPUT-
![Image](https://github.com/user-attachments/assets/ea1dc615-4e55-4184-9c14-eec9eefaef24)
