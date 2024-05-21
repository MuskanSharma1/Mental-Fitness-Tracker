# Overview:
The Mental Fitness Tracker represents a groundbreaking approach to monitoring and managing mental health by harnessing the power of machine learning algorithms. This innovative system is  designed to assess the well-being of a particular country in a particular year based on specified symptoms, providing a comprehensive evaluation of their psychological state. By leveraging advanced machine learning techniques, the Mental Fitness Tracker offers a proactive means of monitoring and analyzing mental health data, enabling early intervention and support.

Utilizing data-driven insights, the Mental Fitness Tracker employs sophisticated algorithms to accurately predict mental health outcomes. Through the analysis of specified symptoms, the system generates personalized assessments, empowering individuals and healthcare professionals with actionable insights into mental well-being. Unlike traditional methods, which rely on subjective assessments or infrequent evaluations, the Mental Fitness Tracker provides continuous monitoring and analysis, enabling timely interventions to prevent adverse outcomes and promote mental resilience.

# Algorithms Used:
The Mental Fitness Tracker employs two machine learning algorithms, namely Linear Regression and Random Forest, to predict the mental fitness of a country based on user inputs related to symptoms associated with mental health issues.

# Libraries Used:
In the development of the Mental Fitness Tracker, several Python libraries were utilized to handle data manipulation, visualization, and model building. These libraries include NumPy, Pandas, Seaborn, Matplotlib, and Plotly Express.

# Result:
This application predicts the mental fitness of a country based on user-provided mental health statistics. Users input their country, year, and rates of schizophrenia, bipolar disorder, eating disorder, anxiety, drug usage, depression, and alcohol consumption. The country name is encoded using LabelEncoder for numerical representation. The prediction is made using a pre-trained Random Forest model (rf.predict). The resulting mental fitness score is displayed as a percentage. To use the tracker, run the code, fill in the required details, and receive an estimated mental fitness score.
