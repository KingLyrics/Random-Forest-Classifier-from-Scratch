# Implementing a Random Forest Classifier from Scratch

## Objective
In this project, students will implement a Random Forest Classifier from scratch. You will gain hands-on experience building classifiers without relying on existing libraries, understand key concepts of a random forest, and learn how to evaluate a trained classifier model.

---

## Project Requirements

### Dataset
Select and download a classification dataset from popular repositories such as [Kaggle](https://www.kaggle.com/) or [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php).

Ensure the dataset has:
- At least **5000 samples**
- At least **10 features**

---

## Steps to Complete the Project

### Step 1: Dataset Selection and Preprocessing
- Choose a suitable dataset that meets the above criteria.
- Download and load the dataset into your Python environment.
- Perform necessary preprocessing:
  - Handle missing values
  - Encode categorical features
  - Normalize/scale numerical features
  - Train-test split

### Step 2: Implementing the Random Forest Classifier
- Implement a **Random Forest classification algorithm** entirely from scratch, without using pre-built libraries like Scikit-learn.
- Your implementation should allow specifying parameters, including:
  - Number of trees
  - Depth threshold
  - Number of samples per split
  - Number of samples per leaf node
  - Criterion for determining the best feature split (**Gini impurity** or **Entropy**)
  - (Optional) Any other parameter that you think could be interesting to add

### Step 3: Model Training, Evaluation, and Comparison
- Train your implemented classifier using your training dataset.
- Evaluate your model's performance on the test dataset using metrics such as:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-score**
  - **Confusion matrix**
- Train a **Random Forest classifier using Scikit-learn** (`sklearn.ensemble.RandomForestClassifier`) on the same training dataset.
- Evaluate the Scikit-learn model's performance using the same metrics.
- Compare the performance of your implemented classifier with the Scikit-learn model and discuss any observed differences and insights.

### Step 4: Documentation
- Clearly document your code with **comments** explaining each part of the implementation.
- Provide a **README file** including:
  - Dataset details
  - Methodology
  - Parameters used
  - Evaluation results
  - Comparative analysis with Scikit-learn's Random Forest

### Step 5: Submission via GitHub
- **Create a private GitHub repository** to store and manage your project.
- Upload your entire project, including:
  - The dataset (or instructions on how to download it)
  - Source code
  - Documentation
  - Results
- Provide me access to review your project by adding me as a collaborator with this ID: `Majid1292`.

#### Important:
- **Weekly commits are required** in your private GitHub repository.
- This project requires **ongoing effort** and cannot be completed in just a few days or a week.
- **At least 5 commits** demonstrating real progress are required.
- You are **not allowed** to make your repository public or invite any other collaborator by the end of this semester.
- Submit your **private GitHub repository link** through **Canvas** by the due date.

---

## Submission Checklist
✅ Dataset meets criteria (**5000+ samples, 10+ features**).  
✅ Random Forest classifier fully implemented from scratch.  
✅ Evaluation metrics clearly calculated and reported.  
✅ Comparative analysis with Scikit-learn Random Forest provided.  
✅ Comprehensive documentation (**README and code comments/explanations**).  
✅ **Weekly commits** to a private GitHub repository.  

---
