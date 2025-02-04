Deep Learning for Early Disease Detection in Medical Imaging

📌 Project Overview

This project leverages Deep Learning and Convolutional Neural Networks (CNNs) for the early detection of diseases using medical imaging. By analyzing medical images (such as lung scans), the model aims to assist healthcare professionals in detecting diseases at an early stage, improving diagnostic accuracy and patient outcomes.

📂 Dataset

Dataset Name: IQ-OTHNCCD Lung Cancer Dataset

Source: Kaggle

Data Collection:

The Iraq-Oncology Teaching Hospital/National Center for Cancer Diseases (IQ-OTH/NCCD) lung cancer dataset was collected over a period of three months in fall 2019.

It includes CT scans of patients diagnosed with lung cancer in different stages, as well as healthy subjects.

The dataset contains a total of 1190 images representing CT scan slices of 110 cases.

These cases are grouped into three categories:

Normal Cases: 55 cases

Benign Cases: 15 cases

Malignant Cases: 40 cases

The CT scans were originally collected in DICOM format using a SOMATOM scanner from Siemens.

CT protocol: 120 kV, 1 mm slice thickness, window width 350-1200 HU, window center 50-600 HU, breath hold at full inspiration.

The dataset was marked by oncologists and radiologists, and all images were de-identified before analysis.

The 110 cases vary in gender, age, educational attainment, area of residence, and living status.

Participants included employees from Iraqi ministries, farmers, and residents from Baghdad, Wasit, Diyala, Salahuddin, and Babylon.

⚙️ Project Components

1️⃣ Data Preprocessing

Standardized pixel values

Handled noise and image resizing

Used data augmentation techniques

2️⃣ Deep Learning Model (CNN)

Designed a Convolutional Neural Network (CNN) model for classification

Utilized transfer learning with pre-trained models like ResNet or VGG

3️⃣ Model Training & Validation

Trained the CNN model on labeled medical images

Evaluated performance on a test set

4️⃣ Explainability (XAI)

Implemented Grad-CAM (Gradient-weighted Class Activation Mapping) for interpretability

5️⃣ Clinical Integration

Explored integration with the clinical workflow for healthcare professionals

6️⃣ Performance Metrics

Accuracy

Sensitivity

Specificity

ROC Curve (AUC Score)

7️⃣ Business & Ethical Considerations

Discussed AI ethics in healthcare, including bias, patient privacy, and regulatory compliance

Assessed business impact on patient care and healthcare efficiency

🚀 How to Run the Project

1️⃣ Clone the Repository

git clone https://github.com/Kartik97660/Medical-Image-Processing.git
cd Deep-Learning-Medical-Imaging

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Model Training

python train_model.py

4️⃣ Test the Model

python test_model.py

5️⃣ View Predictions

python predict.py --image path/to/test_image.jpg

📊 Model Performance

Accuracy - 90.2
Sensitivity -92.5%
Specificity-88.7%
AUC-ROC -94.3%

📌 Future Enhancements

✅ Implement Federated Learning for privacy-preserving model training across hospitals.✅ Address imbalanced datasets using advanced augmentation and weighting techniques.✅ Improve clinical integration by developing a web-based UI for doctors and radiologists.

📝 Authors
Kartik Pathak

📌 GitHub Repository: Deep-Learning-Medical-Imaging

📜 License
This project is open-source 