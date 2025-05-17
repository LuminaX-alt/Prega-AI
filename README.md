# Prega-AI
🩺 Prega-AI: Smart AI Assistant for Pregnancy Risk & Health Monitoring
🌟 Project Summary
Prega-AI is an AI-enabled smart pregnancy companion designed to assist expecting mothers and doctors in identifying pregnancy risks, monitoring fetal development, and providing timely insights for maternal care. The system combines machine  learning, computer vision, and tabular data analysis to deliver accurate, personalized support.

✅ Key Features of Prega-AI
1. 🤰 Pregnancy Risk Assessment (Tabular ML)
Upload clinical data (e.g., prevalence %, BP, sugar, age, etc.)

Trained Random Forest or Logistic Regression model

Predict Low-Risk or High-Risk pregnancy

Gradio interface for easy use

2. 🧪 Pregnancy Blood Test Analyzer (Lab Report OCR)
Upload blood test results (PDF or image)

Extract key parameters using OCR (Tesseract or EasyOCR)

Flag abnormalities (anemia, thyroid, infections)

Cross-check with pregnancy guidelines

3. 🧠 Ultrasound Image Analyzer (CNN-based Model)
Upload fetal ultrasound image

Detect anomalies like:

Neural tube defects

Placenta previa

Fetal growth restriction

Optional: segmentation of fetal organs (future scope)

4. 📊 Fetal Health Predictor (CTG Data - Machine Learning)
Input CTG (Cardiotocography) features (dataset available)

Predict fetal state: Normal, Suspect, Pathological

Dataset: UCI CTG Dataset
5. 🗓️ Trimester Tracker & Health Tips (Rule-Based NLP)
Enter weeks of pregnancy

Output:

Current trimester

Important scans/tests due

Nutrition and lifestyle tips

Danger signs to watch for

6. 🤖 Doctor’s Companion Dashboard (for clinics)
View risk levels of patients

Access uploaded records (CSV or image)

Download patient report (PDF generation)

Integrated with Smart Clinic database if needed📋 Future Ideas (Phase 2)
Voice assistant for pregnancy FAQs (using SpeechRecognition + GPT)

Integration with wearable health trackers (heart rate, movement)

Mobile app version

Chatbot for rural language access

Medication safety checker for pregnancy
🚀 Suggested Technologies
Gradio – for AI interfaces

Scikit-learn – tabular models

TensorFlow / PyTorch – CNN for ultrasound

Tesseract / EasyOCR – OCR from reports

Faker / Synthetic Data Generator – to simulate datasets

ReportLab / PDFKit – for generating patient reports

<img width="783" alt="image" src="https://github.com/user-attachments/assets/0df9310f-5023-4b6e-9b0e-baee583b3d7c" />

<img width="1193" alt="image" src="https://github.com/user-attachments/assets/76193810-805f-4c45-99fe-5e1070363900" />

<img width="377" alt="image" src="https://github.com/user-attachments/assets/c79ac70a-3fea-4c1c-941d-f8c3841f61d6" />

<img width="1423" alt="image" src="https://github.com/user-attachments/assets/80c1570e-9d63-4a26-80d9-430b0f7af468" />

<img width="1411" alt="image" src="https://github.com/user-attachments/assets/b07021c5-0f4d-4d60-a996-9be8b67db3e3" />
