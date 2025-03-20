# Vision-based Detection of Household Furniture for Assisting Visually Impaired People

## AIM

The objective of this project is to alternate the visual world into an audio world by notifying visually impaired individuals about indoor objects such as chairs, sofas, and wardrobes. By not only detecting but also recognizing these objects, the system helps users better understand their surroundings and identify places to rest or sit. This work addresses the significant challenges faced by millions of visually impaired people who often struggle to recognize indoor objects independently.

## Procedure

1. **Data Collection and Preparation:**
   - **Dataset:** Collect a comprehensive set of household furniture images.
   - **Organization:** Arrange images into categories (e.g., chair, sofa, wardrobe) to facilitate training.
   - **Preprocessing:** Standardize image sizes and normalize pixel values.
   - **Splitting:** Divide the dataset into training and testing sets to validate model performance.

2. **Feature Extraction:**
   - **SIFT:** Utilize the Scale-Invariant Feature Transform (SIFT) algorithm to extract robust features from the images. SIFT captures keypoints that remain invariant under changes in scale, rotation, and illumination.

3. **Classification:**
   - **Algorithms:** Implement and train multiple machine learning classifiers using the SIFT features:
     - Support Vector Machine (SVM)
     - Decision Tree
     - Random Forest
     - K-Nearest Neighbor (KNN)
   - **Evaluation Metrics:** Assess each classifier based on accuracy, recall, precision, f1-score, sensitivity, and specificity.

4. **Evaluation and Analysis:**
   - Compare classifier performances on the test dataset.
   - Analyze results through metrics and confusion matrices to identify the best performing model for recognizing household furniture.

## Result

- **Performance Overview:**  
  The system effectively detects and recognizes household furniture, enabling it to provide audio notifications to assist visually impaired users.

- **Evaluation Metrics:**  
  The models were evaluated using several key metrics. The accuracy results for the classifiers were as follows:
  - **Decision Tree:** 77.64%
  - **Random Forest:** 75.2%
  - **SVM:** 72.31%
  
  In addition to accuracy, metrics like recall, precision, f1-score, sensitivity, and specificity were computed to ensure a comprehensive evaluation.

- **Insights:**  
  - The decision tree classifier achieved the highest accuracy, indicating its strong potential for this application.
  - The use of SIFT for feature extraction proved essential in capturing the necessary details for effective object recognition.

- **Publication Details:**  
  This work was presented at the International Conference on Intelligent Computing on May 3, 2022.
