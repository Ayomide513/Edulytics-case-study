# Edulytics-case-study
Clustering High School Students Based on Social Media Interests

📊 Unsupervised Learning | KMeans, DBSCAN, Agglomerative | PCA Visualization

This project applies unsupervised machine learning to cluster high school students into meaningful personas based on their social media interests and demographics. The dataset comes from Kaggle
 and includes 15,000 profiles (2006–2009).

The analysis was done as part of an Edulytics case study, exploring how clustering can help schools and ed-tech companies better understand student communities.

🚀 Project Overview

Objective: Identify distinct groups of students using their demographics and interest terms.

Techniques:

Data cleaning & preprocessing (missing value imputation, encoding, scaling, log transforms)

Clustering with KMeans, DBSCAN, and Agglomerative Clustering

Evaluation with Elbow Method & Silhouette Score

Visualization using PCA (2D & 3D scatter plots)

Output: 7 interpretable student personas with demographics + top interests.

🔍 Key Findings: Student Personas

Cluster 0 – Romantic Group → Teens focused on relationships.

Cluster 1 – Sports-Oriented Students → Active in basketball, football, softball, plus music.

Cluster 2 – Quieter Music/Religion Group → Older, less connected, into music + god.

Cluster 3 – Highly Social Lifestyle-Oriented Girls → Dance, music, shopping, fashion.

Cluster 4 – Younger Religious/Appearance Group → Faith + music + early lifestyle interests.

Cluster 5 – Religious and Musical Group → Strong alignment with church, god, music.

Cluster 6 – Outlier/Edgy Subgroup → Explicit/edgy interests (likely niche/noise).

Cluster 7 – Fashion & Brand-Driven → Hollister, Abercrombie, shopping, socially active.

📊 Visuals

Top 10 Most Frequent Interests

Silhouette & Elbow Method Charts

3D PCA Scatter Plot of Clusters

Top 5 Interests per Cluster

(See visuals/ folder for saved charts)

🛠️ Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn)

Scikit-learn (KMeans, DBSCAN, Agglomerative, PCA)

Scipy (hierarchical clustering tools)

📂 Repository Structure
student-clustering/
├── notebooks/
│   └── Unsupervised_learning_assignment.ipynb   # main notebook
├── visuals/                                     # exported plots
├── requirements.txt                             # dependencies
└── README.md                                    # project summary

📌 Business Implications

Sports Cluster → Support athletics programs and mentoring.

Religious/Music Clusters → Faith-based clubs, choir, and band activities.

Lifestyle/Fashion Clusters → Talent shows, fashion clubs, leadership opportunities.

Romantic Cluster → Counseling tailored to relationships and social growth.

Outlier Cluster → Digital literacy & mental health awareness programs.

📖 Medium Article

I wrote a full walkthrough of the project here:
👉 Read on Medium: https://medium.com/@ayorindeolamilekan2003/clustering-high-school-students-uncovering-hidden-personas-through-social-media-interests-3baea7815283

📧 Email: [Your Email]

🔥 This project shows how machine learning + behavioral data can be combined to uncover actionable insights in education.
