<h1>Student Attrition Risk Prediction</h1>

<h2>Overview</h2>
<p>This project predicts the risk of student attrition by analyzing various features, such as academic performance, attendance, and extracurricular involvement. By using machine learning models, it identifies students at potential risk of dropping out and provides insights for timely intervention.</p>

<h2>Dataset</h2>
<p>The dataset used is synthetic and randomly generated, aiming to simulate real-world student data with features such as academic scores, attendance percentage, part-time job status, extracurricular activities, and weekly study hours.</p>

<h2>Project Structure</h2>
<p>This project includes two main files:</p>
<ul>
    <li><strong>student_dropout_risk.ipynb:</strong> This file includes the final workflow for the selected models based on performance, handling the primary predictions and evaluations.</li>
    <li><strong>model_selection.ipynb:</strong> This file trains multiple models (Random Forest, Gradient Boosting, Linear Regression, SVC, etc.) on the dataset. The best models for classification and regression are selected from this file and then used in <code>student_dropout_risk.ipynb</code> for further tuning and evaluation.</li>
</ul>

<h2>Methodology</h2>
<p>The methodology followed in this project includes:</p>
<ul>
    <li>Data Preprocessing: Cleaning and preparing synthetic data for model training.</li>
    <li>Feature Engineering: Creating additional features to enhance model effectiveness.</li>
    <li>Model Training: Testing various machine learning models for optimal performance.</li>
    <li>Hyperparameter Tuning: Fine-tuning model parameters to improve accuracy and minimize overfitting.</li>
</ul>

<h2>Models Used and Performance</h2>
<p>Several models were tested and evaluated, including:</p>
<ul>
    <li><strong>Random Forest Regressor:</strong> Achieved an R² score of 0.9934 with Mean Squared Error (MSE) of 0.0007, making it the best-performing regression model.</li>
    <li><strong>Gradient Boosting Classifier:</strong> Provided high classification accuracy with a cross-validation score near 99%, and selected as the best classifier.</li>
</ul>

<h3>Model Performance Summary</h3>
<p>The selected models—Random Forest Regressor for regression tasks and Gradient Boosting Classifier for classification tasks—demonstrated strong predictive performance. Random Forest obtained an R² of 0.9934, and Gradient Boosting achieved high accuracy and stability in classification tasks.</p>

<h2>Execution Steps</h2>
<ol>
    <li>Clone the repository or download the code and open in Google Colab</li>
    <li>Install required dependencies</li>
    <li>To run, execute the cells step by step</li>
    <li>Input user queries for the subjects and other features. Get the results.</li>
</ol>

example:
![image](https://github.com/user-attachments/assets/f0a93c65-f3aa-4dba-b7c3-ac39431f55df)
![image](https://github.com/user-attachments/assets/18dc0e0d-51ea-4ff3-8d2e-b992d1fb58fd)
on the right the chart is for min conditions a user should have. The pie chart is helpful for GAP anlysis.
