# **Automated Customer Complaints Classification Leveraging NLP and Machine Learning**

## **Objective**

The aim of this project is to leverage **Natural Language Processing (NLP)** and **Machine Learning** techniques to automate the classification of customer complaints. This automation enables businesses to efficiently categorize and address customer grievances, thereby improving response times, service quality, and the resolution process.

---

## **Table of Contents**

1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Models Used](#models-used)
4. [Key Insights](#key-insights)
5. [Business Recommendations](#business-recommendations)
6. [Results](#results)
7. [Technologies Used](#technologies-used)
8. [How to Run the Project](#how-to-run-the-project)
9. [Author](#author)

---

## **Project Overview**

In the current competitive landscape, efficient customer service is a key differentiator for businesses. This project focuses on automating the process of classifying customer complaints using advanced **NLP** and **Machine Learning** techniques. By analyzing historical complaint data, the system can predict categories for new complaints, enabling faster and more targeted responses.

### Key Highlights:
- **Exploratory Data Analysis (EDA)** to uncover patterns and trends in customer complaints.
- **Topic Modeling** to identify themes in complaints.
- **Supervised Classification** to assign complaints to predefined categories.
- **Actionable Insights** for business improvements.

---

## **Dataset Description**

The dataset used contains **78,313 customer complaints** from a financial institution, stored in JSON format. Each record represents a single complaint with multiple attributes.

### **Key Attributes:**
- **Complaint Details**: Text of the customer complaint.
- **Issue**: A brief description of the problem.
- **Product/Service**: The product or service related to the complaint.
- **State**: Geographic origin of the complaint.
- **Response**: The company's response to the complaint.

### **Use Cases:**
1. **Customer Service Improvement**: Identifying common themes to enhance service quality.
2. **Product Development**: Refining offerings based on complaint patterns.
3. **Fraud Detection**: Highlighting issues related to theft or disputes.
4. **Regional Analysis**: Pinpointing geographic trends in complaints.

---

## **Models Used**

A variety of models were implemented to classify complaints and extract insights:

1. **Random Forest Classifier**
2. **Logistic Regression**
3. **XGBoost**
4. **Non-Negative Matrix Factorization (NMF)** for Topic Modeling

### **Evaluation Metrics**:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

---

## **Key Insights**

1. **Top Issues**:
   - Common complaints include account issues, credit card disputes, and payment problems.
   - Regional variations in complaint types were identified, indicating localized issues.
2. **Timeliness**:
   - Majority of complaints received timely responses, though improvement areas were highlighted.
3. **Topic Clustering**:
   - Six key clusters were identified:
     - Bank account services
     - Credit card/prepaid card issues
     - Payment services
     - Mortgage/loan problems
     - Theft/dispute resolutions
     - Miscellaneous others

---

## **Business Recommendations**

1. **Focus on High-Complaint Products**:
   - Prioritize resolving issues related to credit cards and payment services.
2. **Enhance Fraud Prevention**:
   - Strengthen systems to handle disputes and theft-related complaints.
3. **Regional Customization**:
   - Tailor services to address regional variations in complaints.
4. **Proactive Customer Engagement**:
   - Implement systems to proactively address recurring issues.

---

## **Results**

The **best-performing models** for classification were:
- **Logistic Regression**:
  - Accuracy: 92%
  - Precision: 92%
  - Recall: 91%
- **XGBoost**:
  - Accuracy: 90%
  - Precision: 90%
  - Recall: 89%
- **Random Forest**:
  - Accuracy: 86%
  - Precision: 86%
  - Recall: 85%

---

## **Technologies Used**

- **Python**: Core programming language.
- **Pandas/Numpy**: Data manipulation.
- **Spacy/NLTK**: NLP tasks.
- **Scikit-learn/XGBoost**: Machine Learning models.
- **Matplotlib/Seaborn**: Data visualization.
- **Jupyter Notebook**: Interactive development environment.

---

## **How to Run the Project**

1. Clone the repository:
   ```bash
   git clone https://github.com/bhutto17/Automated-Customer-Complaints-Classification-Leveraging-NLP-and-Machine-Learning.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

---

## **Author**
**Faizan Bhutto**  
[LinkedIn](https://www.linkedin.com/in/faizanbhutto) | [GitHub](https://github.com/bhutto17)

Feel free to reach out if you have any questions or feedback regarding this project.