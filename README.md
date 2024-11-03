# HHA504_assignment_ai

# HHA504 Assignment - Exploring AI and Analytics with Pre-trained Models in Azure and GCP

## Overview

The objective of this assignment is to demonstrate the use of pre-trained AI models for speech and vision analysis on both Google Cloud Platform (GCP) and Microsoft Azure. The main objective is to analyze audio and image files using these platforms, then compare the outputs from each, reflect on their model accuracy and ease of use, and document any challenges faced.


---

## GCP Speech-to-Text

### Steps
1. **Setup and Authentication**: Configured GCP with a Speech-to-Text API enabled. Set up authentication using a service account key.
2. **Processing Audio File**: Uploaded an audio file (`hello01.wav`) to transcribe speech to text.
3. **Execution**: Used GCP's Speech-to-Text API to analyze the audio file.

### Results
- **Output**: The transcription was accurate and aligned well with the speech in the audio file.
- **Screenshot**:
![Screenshot 2024-11-03 105416](https://github.com/user-attachments/assets/0b4bed98-8863-4c5b-8f4d-8bf234f5bae8)
![Screenshot 2024-11-03 112718](https://github.com/user-attachments/assets/19e657a4-b373-4e1a-85f5-578baef38d54)


---

## GCP Vision API

### Steps
1. **Setup and Authentication**: Configured the GCP Vision API and authenticated the session.
2. **Processing Image File**: Uploaded an image file (`dog.jpg`) for object detection.
3. **Execution**: Used the Vision API to analyze the image and detect objects.

### Results
- **Output**: Successfully detected objects with high confidence scores, accurately labeling items in the image.
- **Screenshot**:
  ![Screenshot 2024-11-03 115513](https://github.com/user-attachments/assets/83f690d4-7001-405e-b223-f5be3e5bd294)

---

## Azure Computer Vision

### Steps
1. **Setup and Configuration**: Created an Azure Computer Vision resource, retrieved the API key and endpoint, and set up authentication.
2. **Processing Image File**: Uploaded the same image file (`dog.jpg`) used in GCP to keep the comparison consistent.
3. **Execution**: Used Azure's Computer Vision model to analyze the image for object detection.

### Results
- **Output**: Detected objects with confidence scores, similar to GCP's Vision API but with some variations in labeling confidence.
- **Screenshot**:
  ![Screenshot 2024-11-03 120756](https://github.com/user-attachments/assets/1262132a-06f4-4163-8ece-2f123925b03e)
  ![Screenshot 2024-11-03 125618](https://github.com/user-attachments/assets/3dfbbe78-eee7-4e47-8659-57610bfd9dc3)


---

## Comparison and Reflection

### Accuracy
- **GCP Speech-to-Text**: Provided highly accurate transcription, correctly interpreting the speech.
- **GCP Vision vs. Azure Vision**: Both models were accurate in object detection, with GCP providing slightly higher confidence scores.

### Ease of Use
- **GCP**: The setup process for both Speech-to-Text and Vision APIs was straightforward, with clear documentation and user-friendly configuration steps.
- **Azure**: The setup process required additional steps, such as creating resource groups and retrieving keys and endpoints from specific menus. 

### Challenges and Solutions
1. **Attaching Compute to Azure Notebooks**:
   - **Challenge**: Had trouble attaching compute resources for running Jupyter notebooks in Azure.
   - **Solution**: Created a new compute instance and adjusted the session configuration, which resolved the issue.


---

## Conclusion

Both Google Cloud and Azure provide powerful tools for pre-trained AI models in speech and vision analysis. While **GCP** was slightly more straightforward to configure, **Azure** also delivered accurate results and has an interface with many different features for further customization. 

---





