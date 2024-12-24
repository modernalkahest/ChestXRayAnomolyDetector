# ChestXRayAnomolyDetector
Chest diseases encompass a wide range of conditions that affect the respiratory system and organs within the chest cavity, including the lungs, heart, and blood vessels. The impact of chest diseases can vary significantly depending on the specific condition, severity, and individual factors.
Chest diseases can have a profound impact on an individual's physical and mental well-being. 

Some of the common consequences include:
* Breathing difficulties: Many chest diseases lead to shortness of breath, coughing, and wheezing, making it difficult to perform everyday activities or exercise.
Reduced lung function: Over time, some chest diseases can cause irreversible damage to the lungs, leading to reduced lung capacity and impaired gas exchange.
Fatigue and weakness: The body's effort to compensate for impaired lung function can result in chronic fatigue and weakness, making it challenging to maintain energy levels.
* Chest pain: Certain chest diseases, such as pleurisy or pericarditis, can cause significant chest pain, leading to discomfort and difficulty breathing deeply.
Psychological distress: Living with a chronic chest disease can lead to anxiety, depression, and social isolation due to the limitations and challenges associated with the condition. In addition to the direct impact on individuals, chest diseases also have broader socioeconomic consequences. 

They can lead to:
* Increased healthcare costs: The diagnosis, treatment, and management of chest diseases require significant healthcare resources, including hospitalizations, medications, and ongoing care.
* Reduced productivity: Individuals with chest diseases may experience decreased work productivity due to missed workdays, reduced working hours, or disability.
Economic burden: The financial costs associated with healthcare, lost productivity, and disability can place a significant economic burden on individuals, families, and society as a whole.

AI and machine learning (ML) are revolutionizing the field of chest disease prediction by enhancing accuracy, speed, and efficiency in diagnosis and treatment.

## Problem Statement
Develop an automated diagnostic system that can accurately detect and classify to class 0, and 1 using chest X-ray images and basic medical records of patients. Your solution should leverage machine learning or deep learning techniques to analyze both types of data and provide a diagnostic prediction.

Structured Data: Basic medical records.

* Image Index - Unique name given to x-ray images in the dataset.
* Finding Labels - Target column (has different classes namely 0,1)
* Follow-up - No of hospital visits
* Patient ID - Unique ID for each patient (can be repeated as per the visits)
* Patient Age - The age of the patient
* Patient Gender - The gender of the patient
* View Position - Position of X-ray image
* OriginalImage_Width - Orginal width of the image
* OriginalImage_Height - Orginal height of the image
* OriginalImagePixelSpacing_x - X spacing between pixels of the image
* OriginalImagePixelSpacing_y - Y spacing between pixels of the image
