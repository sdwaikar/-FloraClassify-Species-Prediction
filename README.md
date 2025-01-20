### Iris Dataset Classification Project 🏵️

This project involves classifying the Iris dataset using five different machine learning models: Multinomial Logistic Regression, KNN, Decision Trees, Random Forests, and SVM, implemented in R. The project highlights comparative analysis, accuracy evaluation, and error rates for each model.

#### Features:
- **Multinomial Logistic Regression:** Achieved 96.38% cross-validation accuracy with a 3.65% error rate.
- **KNN Model:** Achieved 92.67% accuracy with a cross-validation error rate of 7.33%.
- **Decision Tree:** Achieved 95.56% cross-validation accuracy, with an error rate of 4.44%.
- **Random Forest:** The best-performing model with 99.17% cross-validation accuracy and an error rate of 0.83%.
- **SVM Model:** Delivered 97.33% cross-validation accuracy with a 2.67% error rate.

#### Installation:
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/IrisDatasetClassification.git
   ```
2. Navigate to the directory:
   ```bash
   cd IrisDatasetClassification
   ```
3. Install required R libraries:
   ```R
   install.packages(c("caret", "class", "nnet", "party", "rpart", "rpart.plot", "randomForest", "e1071"))
   ```

#### Usage:
1. Open the R project file or R Markdown file.
2. Load the dataset using:
   ```R
   iris <- read.csv("iris.data", header = FALSE)
   ```
3. Run the models and compare their performance metrics.

#### Dataset:
The Iris dataset includes 150 records of three flower species:
- **Setosa**
- **Versicolor**
- **Virginica**

Features include:
1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

#### Results:
- **Best Model:** Random Forest with 99.17% accuracy.
- **Comparison:** Models were evaluated using confusion matrices, misclassification rates, and k-fold cross-validation.

#### Skills Demonstrated:
- Multinomial Logistic Regression
- K-Nearest Neighbors
- Decision Trees and Random Forests
- Support Vector Machines
- R Programming and Visualization

#### License:
This project is licensed under the MIT License. See the LICENSE file for details.
