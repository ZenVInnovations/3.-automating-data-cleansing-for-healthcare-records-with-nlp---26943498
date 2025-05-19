The Healthcare Data Cleansing Tool is an automated solution designed to preprocess and standardize healthcare records, ensuring data quality for clinical, research, and operational use. Given the highly unstructured nature of medical data, this tool leverages Natural Language Processing (NLP) and machine learning techniques to clean, validate, and structure key fields such as diagnoses, medications, and blood pressure readings.
This project addresses common challenges in healthcare data management, including inconsistent terminology, duplicate records, and anomalous values. By offering both batch processing and manual entry through a user-friendly Streamlit interface, the tool is accessible to technical and non-technical users alike.

🔎Key Features:

Text Standardization: Cleans and normalizes diagnoses and medication names using NLP.

Duplicate Detection: Removes duplicate records based on Name and DOB.

Blood Pressure Validation: Checks format and clinical validity of BP readings.

Anomaly Detection: Identifies outliers using the Isolation Forest algorithm.

Streamlit Interface: Intuitive web UI for CSV uploads and manual data entry.

Data Export: Allows downloading of cleaned data in CSV format.

Technologies Used:

•	Python 3.8+

•	Streamlit – for the web-based user interface

•	scikit-learn – for anomaly detection

•	pandas – for data manipulation

•	NLP techniques – for text processing and standardization

Use Cases

•	Preprocessing Electronic Medical Records (EMRs)

•	Cleaning clinical research data

•	Standardizing patient survey responses

•	Preparing datasets for machine learning models in healthcare
