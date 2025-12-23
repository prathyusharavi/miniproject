# ENDOSCAN-VLM: VISION–LANGUAGE MODEL FOR MULTIMODAL DETECTION OF ENDOMETRIOSIS USING MEDICAL IMAGES AND SYMPTOM DATA

## ABOUT:
EndoScan-VLM is an AI-driven system designed for multimodal detection of endometriosis using medical imaging (MRI/Ultrasound) and patient symptom data. The system leverages a Vision–Language Model (VLM) to integrate visual and textual information, providing highly accurate and interpretable diagnostic predictions. By combining image features with clinical notes and symptom history, EndoScan-VLM aims to reduce diagnostic delays, support clinical decision-making, and improve patient outcomes in gynecology.

## FEATURES:

* Multimodal Input: Processes both medical images and patient symptom data.

* Vision Encoder: CNN-based extraction of lesion-specific image features.

* Language Encoder: Transformer-based NLP model (e.g., ClinicalBERT) for processing symptom and clinical text data.

* Multimodal Fusion: Cross-attention mechanism to combine visual and textual features.

* Interpretable Outputs: Provides lesion localization maps, confidence scores, and textual explanations.

* Real-time Processing: Optimized for timely analysis to support clinical workflows.

* Privacy-Preserving: Designed with HIPAA/GDPR-compliant handling of sensitive patient data.

* Evaluation Metrics: Sensitivity, specificity, AUC, and lesion localization accuracy.

* Extensible Framework: Can be adapted for other medical conditions and multimodal diagnostic tasks.

## REQUIREMENTS:

Operating System:64-bit Windows 10 or Ubuntu (for deep learning framework compatibility)

Development Environment:Python 3.6 or later

Machine Learning & Deep Learning Frameworks:TensorFlow / Keras,PyTorch,Transformers (HuggingFace)

Federated Learning (Optional):TensorFlow Federated (if collaborative privacy-preserving training is implemented)

Data & Processing Libraries:Numpy, Pandas, Matplotlib, Seaborn

Version Control:Git

IDE / Notebook:Google Colab, Jupyter Notebook

Additional Dependencies:OpenCV (for visualization or UI extensions),SHAP (optional, for model explainability)

## SYSTEM ARCHITECTURE:

The EndoScan-VLM system consists of the following components:

1.Vision Encoder:

CNN-based feature extraction from medical images (MRI, Ultrasound)

Captures lesion-specific patterns

2.Language Encoder:

Transformer-based NLP model (e.g., ClinicalBERT)

Processes patient symptoms, clinical notes, and medical history

3.Multimodal Fusion Module:

Combines image and text embeddings using cross-attention

Learns cross-modal dependencies

4.Prediction Module:

Classifies data into “Endometriosis Detected” or “No Endometriosis”

Outputs confidence scores and interpretable visualizations

5.Evaluation & Visualization:

Generates metrics: Accuracy, Sensitivity, Specificity, AUC

Produces lesion localization maps and graphs comparing actual vs predicted outcomes
<img width="864" height="531" alt="Screenshot 2025-12-01 170748" src="https://github.com/user-attachments/assets/cb9c67a8-2f24-43cd-b501-55bc08a708de" />

<img width="1255" height="682" alt="Screenshot 2025-12-01 145013" src="https://github.com/user-attachments/assets/26fe7999-cfe7-44aa-b1da-4a098588a313" />

## OUTPUT:
<img width="1345" height="251" alt="image" src="https://github.com/user-attachments/assets/097434cb-9acf-4b6c-9e03-568af876d043" />
<img width="915" height="519" alt="image" src="https://github.com/user-attachments/assets/8a52978f-c800-4ca6-8440-37acdfc589c8" />

<img width="782" height="550" alt="image" src="https://github.com/user-attachments/assets/0f7bdef7-098c-47fa-b08b-5b5f8736e40b" />
<img width="700" height="339" alt="image" src="https://github.com/user-attachments/assets/a20703e3-602e-466e-a035-d316ec8f543b" />
<img width="777" height="653" alt="image" src="https://github.com/user-attachments/assets/c113156d-6cfc-4660-8fdd-9a17bea5830d" />
<img width="786" height="646" alt="image" src="https://github.com/user-attachments/assets/7f2f67b1-2f6b-4ab1-9647-9d68a0eb46f2" />

<img width="853" height="173" alt="image" src="https://github.com/user-attachments/assets/bf08dd0c-a7a0-448a-beb7-4f5a05e56516" />
<img width="733" height="711" alt="image" src="https://github.com/user-attachments/assets/e1d9c680-4b22-4f15-bf6f-e82a7907460c" />







## RESULTS AND IMPACT:
*Detection Accuracy: Achieves high diagnostic precision (e.g., 95.47% in testing)

*Clinical Benefits:

Reduces diagnostic delays in endometriosis

Provides interpretable outputs for clinicians

Supports informed decision-making and treatment planning

*Operational Impact:

Enhances reliability and efficiency in clinical workflows

Facilitates early detection and better patient outcomes

*Innovation:

Multimodal approach improves upon unimodal detection systems

Integrates cross-modal invariants and attention-based feature extraction

## ARTICLE PUBLISHED/REFERENCES:
1.Ning Zhang, P. Wang, and J. Li, “Deep Learning Models for Short-Term Load Forecasting,” IEEE Transactions on Smart Grid, 2022.

2.Y. Ahmad and H. Zhang, “Load Forecasting in Smart Grids: A Review of Deep Learning Techniques,” Energy Reports, 2021.

3.S. Mohan, A. Singh, “Hybrid Machine Learning for Electricity Demand Prediction in India,” Elsevier Energy, 2023.

4.M. Králíčková, K. Vetvicka, and P. Vetvicka, “Endometriosis: Current understanding and future perspectives,” Int. J. Mol. Sci., 2020.

5.Y. Chen, Z. Lu, and J. Wang, “Vision-language models for medical image analysis: A survey,” Artificial Intelligence in Medicine, 2023.

6.A. Becker, P. Zondervan, and C. Missmer, “Endometriosis: Epidemiology, diagnosis and clinical management,” BMJ, 2018.

7.L. Wang, J. Zhang, and M. Li, “Multimodal medical data fusion for disease diagnosis: A deep learning perspective,” Information Fusion, 2022.
