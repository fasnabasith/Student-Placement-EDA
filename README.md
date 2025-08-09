# Student-Placement-EDA
"Exploratory Data Analysis (EDA) on a Student Placement Dataset to uncover key factors influencing placement outcomes using Python, Pandas, Matplotlib, and Seaborn."

# Task 1 – Exploratory Data Analysis on Student Placement Dataset

## 📌 Project Overview
This project involves performing Exploratory Data Analysis (EDA) on a Student Placement Dataset to understand factors influencing student placement outcomes.  
The aim is to clean, analyze, and visualize the dataset to extract meaningful insights that can support decision-making.

---

## 📊 Dataset Description
The dataset contains academic and skill-related information of 10,000 students along with their placement status.  
Key features include:

- **Student_ID**: Unique identifier for each student  
- **CGPA**: Cumulative Grade Point Average  
- **Internships**: Number of internships completed  
- **Projects**: Number of academic or personal projects  
- **Workshops/Certifications**: Number of workshops attended and certifications earned  
- **AptitudeTestScore**: Score obtained in the aptitude test  
- **SoftSkillsRating**: Rating of student’s soft skills  
- **ExtracurricularActivities**: Participation status (Yes/No)  
- **PlacementTraining**: Attendance in placement training (Yes/No)  
- **SSC_Marks**: Secondary school marks  
- **HSC_Marks**: Higher secondary school marks  
- **PlacementStatus**: Whether the student was placed or not  

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔍 EDA Process

### Data Cleaning
- Checked and handled missing values  
- Verified and corrected data types  
- Removed duplicates where necessary  

### Data Visualization
- Created **bar charts** for categorical variables such as Placement Status, Placement Training, and Extracurricular Activities  
- Created **histograms** for numerical variables like CGPA, Aptitude Test Score, and Soft Skills Rating  
- Explored relationships between these variables and Placement Status using comparative histograms  

---

## 📈 Key Insights

- **Placement Status Distribution**: A larger proportion of students were not placed compared to those who were placed.  
- **Placement Training & Extracurricular Activities**: Majority of students attended placement training and participated in extracurricular activities, which might be contributing positively towards placements.  
- **CGPA**: Students with CGPA above 8 show higher chances of placement, indicating academic performance is a significant factor.  
- **Soft Skills Rating**: Higher soft skills ratings are associated with increased placement chances, though the relationship is moderate.  
has a weaker correlation with placement.  
- **Internships, Projects, Certifications**: These factors show minimal or no significant influence on placement status in this dataset.  
