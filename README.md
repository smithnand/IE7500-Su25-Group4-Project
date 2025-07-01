# IE7500-Su25-Group4-Project
Group 4's repository for IE7500: Applied Natural Language Processing in Engineering course 

Project: AI for Symptom and Diagnosis Summarization  
Project Description:

This project aims to develop a Natural Language Processing (NLP) system that can consume the raw and unstructured symptom descriptions and reports from the patients. The system will provide a concise summary while maintaining the standard medical terminology and details. 
From here, medical professionals are able to review, filter, and validate the suggestions as a preliminary list of possible diagnoses to consider given the patient’s provided details. The primary objective of this system is to help support medical professionals in their diagnosis to streamline for a more efficient and structured process. This will not replace a medical professional's judgement or provide a diagnosis but instead be a complimentary resource to a medical professional.


Problem Statement:

Medical professionals often receive lengthy or unorganized patient reports which can be time-consuming and inefficient to interpret one-by-one. An example of this can be found in a doctor’s messaging inbox with patients describing their conditions through descriptors of pain, appearance, sensations, or sentiments. These messages may contain vague or nonclinical language that does not allow for fast diagnoses. There is a need for a system that can summarize key concerns a patient has, and then look through a library of potential conditions to identify a diagnosis based on the patient’s medical history, family history, and symptoms or simply categorize the condition in terms of degree of concern and then department to be addressed by using familiar clinical terminology. This would streamline the workflow for doctors, nurses, and limit the necessity of scribes or massive amounts of click throughs and scouring, allowing them to more efficiently identify critical issues, prioritize cases, and communicate with accuracy and consistency. It would also allow patients to receive feedback at a later point. Uses natural language processing (NLP) to analyze patient input. To solve the current inefficiency in this space, we need an nlp system that summarizes and categorizes symptoms into relevant diagnostic possibilities and presents them using standardized medical terms and codes that are universally recognized industry wide. These medical professionals could then review the system's conclusions and derive a medically sound, ultimate diagnosis.

Data Sources:

The project’s primary dataset, which comprises the names of diseases and their associated symptoms, will be obtained from Kaggle dataset.
Kaggle for Symptom and Diagnosis Summarization 
Further information for the project shall be obtained from reports published by the World Health Organization (WHO) and the Centers for Disease Control and Prevention (CDC). Each dataset will be duly cited and utilized ethically.
Data Description:
The Kaggle dataset comprises information about features such as label and text, consisting of 1,200 datapoints with two columns, representing 24 different diseases, with each disease having 50 symptom descriptions. The following 24 diseases have been covered in the dataset.
Psoriasis, Varicose Veins, Typhoid, Chicken pox, Impetigo, Dengue, Fungal infection, Common Cold, Pneumonia, Dimorphic Hemorrhoids, Arthritis, Acne, Bronchial Asthma, Hypertension, Migraine, Cervical spondylosis, Jaundice, Malaria, urinary tract infection, allergy, gastroesophageal reflux disease, drug reaction, peptic ulcer disease, diabetes
Columns	Description
Label	Contains the disease labels
Text	Contains the natural language symptom descriptions.
 
Expected Outcomes:

Our Natural Language Processing (NLP) model for medical diagnostics focuses on extracting valuable information from unstructured medical text data, such as clinical notes and/or datasets. This technology assists in diagnosis and treatment planning by identifying key information, including symptoms, diagnoses, and treatment plans, and converting unstructured data into structured formats for analysis.

NLP helps summarize medical information, making it easier for patients to understand their health conditions. It can analyze various patient data, including medical records and family medical history, to identify early signs of conditions and predict patient outcomes; for instance, it can be utilized to assess the risk of diabetes.

Moreover, we hope to build an NLP model that automates the extraction of information from medical documents and datasets, significantly reducing the time and effort required to document patient information. It may also analyze large datasets from clinical trials, enabling researchers to identify trends and patterns that might otherwise go unnoticed.

With this in mind, we anticipate the following outcomes from our project model:
●	Extraction of Key Information from Medical Documents and Datasets
●	Predicted Diagnosis Output/Patient Outcome
●	Recognition of Medical Context Phrases/Words
●	Recognition of Negated Terms (i.e. certain symptoms or conditions not likely)


