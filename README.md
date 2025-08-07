# IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies
This repository documents the capstone project completed during the IBM SkillsBuild 4-Weeks Internship on AI & Cloud Technologies. This program is a collaborative initiative by the Edunet Foundation, AICTE, and IBM SkillsBuild.

The internship's primary goal is to provide hands-on experience in emerging technologies, enhancing employability and confidence by solving real-world challenges using the IBM SkillsBuild and IBM Cloud platforms.

# 📝 Table of Contents
Intern Details
About the Internship
Project:Power System Fault Detection and Classification
     Problem Statement
     Solution Overview
⚙️ Technology Stack
🚀 Project Workflow
📊 Results
📁 Repository Contents
# 👨‍💻 Intern Details
Name: VARSHITHA N
Institute: DR AMBEDKAR INSTITUTE OF TECHNOLOGY
Duration: 4 Weeks (15th July 2025 to 10th August 2025)
# 📖 About the Internship
This 4-week program focused on providing practical skills in AI and Cloud Computing. The internship was structured with weekly virtual sessions, mentor guidance, and hands-on labs. The curriculum included:

Week 1: Internship Orientation, IBM Cloud Registration, Artificial Intelligence.
Week 2: Data Analytics concepts, Hands-On Labs, and Cloud EDA.
Week 3 & 4: Building a Chat Bot, AI/ML experiments on the cloud, and a deep dive into AutoAI experiments on IBM Cloud.
Successful completion required active participation, completion of at least two courses on IBM SkillsBuild, and the submission of a final project presentation. This internship was offered with no stipend.

# 💡 Project:  Power System Fault Detection and Classification
Problem Statement
Design a machine learning model to detect and classify different types of faults in a power distribution system. Using electrical measurement data (e.g., voltage and current 
phasors), the model should be able to distinguish between normal operating conditions 
and various fault conditions (such as line-to-ground, line-to-line, or three-phase faults). The objective is to enable rapid and accurate fault identification, which is crucial for maintaining power grid stability and reliability. 

Solution Overview
An end-to-end machine learning solution was developed to automate the detection and classification of power system faults. The system uses voltage and current phasor data to accurately distinguish between normal operating conditions and various types of faults, such as line-to-ground, line-to-line, double line-to-ground, and three-phase faults. The final, trained model was deployed as a real-time web service on the IBM Cloud platform using Watson Studio and IBM Machine Learning services.

# ⚙ Technology Stack
Cloud Platform: IBM Cloud
AI/ML Service: IBM watsonx.ai Studio
Automated ML Tool: IBM AutoAI
Core Language & Libraries:
Python
scikit-learn
pandas
Matplotlib & Seaborn
ibm-watsonx-ai
# 🚀 Project Workflow
Data Ingestion: The  Power System Fault Detection and Classification dataset from the Kaggle dataset link-https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset
Automated Model Building:A machine learning pipeline was built using Scikit-learn. A Random Forest Classifier was selected to classify different types of faults due to its robustness and accuracy in handling multi-class classification problems. The dataset was split into training and testing subsets, and performance was evaluated using accuracy, confusion matrix, and classification metrics.
Model Optimization: Hyperparameters of the Random Forest model were tuned using GridSearchCV to improve predictive performance. Feature importance analysis was performed to understand the most influential electrical parameters in fault classification.
Deployment: The top-performing pipeline was saved as a model asset and deployed as an Online Web Service within a Deployment Space on IBM Watsonx.ai, which provides a REST API for fault detection.
Testing: The deployed API endpoint was successfully tested with sample phasor data inputs to ensure it could accurately classify the type of fault in real-time. The response time and classification accuracy validated its suitability for integration into smart grid applications.
# 📊 Results
The deployed model demonstrated high accuracy in classifying infrastructure projects, proving the effectiveness of using automated AI tools for rapid development and deployment. The project successfully met all requirements for the final evaluation and submission.

<img width="2880" height="1800" alt="Screenshot 2025-08-02 003232" src="https://github.com/user-attachments/assets/43deef25-5721-4870-9987-23fcec8ab2ce" />
<img width="2880" height="1800" alt="Screenshot 2025-08-02 003518" src="https://github.com/user-attachments/assets/ed20d38f-aa7d-428c-824f-66723bd6d500" />
<img width="2880" height="1800" alt="Screenshot 2025-08-02 003540" src="https://github.com/user-attachments/assets/b8926a6a-f76d-4cd8-aa1e-d7df5f950828" />
<img width="2880" height="1800" alt="Screenshot 2025-08-02 010638" src="https://github.com/user-attachments/assets/f109b7fc-7c5c-4d83-99aa-bcaa7a98de01" />
<img width="2880" height="1800" alt="Screenshot 2025-08-02 011159" src="https://github.com/user-attachments/assets/bbd1a9c8-a9b1-4e9c-83e3-41815d4d1fda" />


# 📁 Repository Contents
Power_System_Fault_Classifier.ipynb
A Jupyter Notebook containing the complete machine learning workflow, including data preprocessing, model training using a Random Forest Classifier, performance evaluation, and visualizations of fault classification results.

Power_System_Fault_Classification_Project.pdf
The final project presentation PDF summarizing the problem statement, methodology, model performance, IBM Cloud deployment, and key outcomes of the solution.

README.md
This file. Provides an overview of the project, dataset, technologies used, deployment details, and instructions for reproducing the solution.
