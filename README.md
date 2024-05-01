# Gradient-Descent-for-Logistic-Regression
The provided code demonstrates logistic regression applied to two different scenarios: continuous and categorical data.

1. **Continuous Data:**
     The initial section visualizes a dataset with six data points in a 2D space. It then computes the gradient for logistic regression and performs batch gradient descent to update the model parameters iteratively. The updated parameters are used to plot the decision boundary separating the two classes in the dataset. This process helps in understanding how logistic regression learns to classify data points based on their features.
     
     ![Data-Plot](https://github.com/UMMY87/Gradient-Descent-for-Logistic-Regression/assets/117314436/2c0efc5f-6890-44b7-aad4-21121d6fb5ad)

2. **Categorical Data:**
     Next, the code showcases logistic regression applied to categorical data. It plots a dataset representing tumor classification, where the input features represent tumor sizes, and the output labels indicate the tumor's benign or malignant nature. Logistic regression is used to learn the decision boundary separating benign and malignant tumors. Additionally, a quadratic decision boundary is plotted to show how logistic regression can capture more complex relationships between features and labels.

    ![Plot-Logistic-Regression-Categorical-Data](https://github.com/UMMY87/Gradient-Descent-for-Logistic-Regression/assets/117314436/4e45b8fa-dadd-47f5-8578-4ae29569dd6f)

3. **Decision Boundary:**
The provided code also includes the visualization of the decision boundary learned by logistic regression. After updating the model parameters using batch gradient descent, the decision boundary is computed using the updated weights and bias. The decision boundary is represented as a line separating the two classes in the dataset. This visualization helps to understand how logistic regression distinguishes between different classes based on the input features. Additionally, for the tumor classification dataset, a quadratic decision boundary is plotted, showcasing logistic regression's ability to capture more complex relationships between features and labels. This comprehensive visualization aids in interpreting and evaluating the performance of logistic regression in classifying the data points accurately.

   ![Plot-the-decision-boundary](https://github.com/UMMY87/Gradient-Descent-for-Logistic-Regression/assets/117314436/11affda9-cae0-4753-bc01-1290b43c1a4d)

      Overall, the code provides a comprehensive understanding of logistic regression, demonstrating its versatility in handling both continuous and categorical data and its capability to learn decision boundaries for classification tasks.
