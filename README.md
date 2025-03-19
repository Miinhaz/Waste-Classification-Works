# Towards Sustainable Solutions: Effective Waste Classification Framework via Enhanced Deep Convolutional Neural Networks

## Repository Overview
This repository contains datasets, models, and research materials related to our study on waste classification using deep learning. The research employs **DenseNet201**, combined with a **parallel CNN architecture** and a **squeeze-and-excitation (SE) attention mechanism**, to enhance feature extraction and optimize classification accuracy.

This study explores a **multi-dataset approach**, improving the model's generalizability across different waste compositions. Additionally, **energy consumption and CO2 emission tracking** are incorporated to evaluate the sustainability of our methodology. **A rigorous evaluation was conducted to analyze the model's performance when subjected to additional adversarial noises and image inconsistencies** such as variations in contrast, brightness, and blurriness. I have also developed a **user-friendly web system** for real-world waste classification applications, which is currently hosted locally.

## Folder Structure

### **1. Datasets and Rigorous Evaluation Using Different Models**
- **`Dataset1-10classes/`** - Waste classification dataset with 10 categories.
- **`Dataset2-12classes/`** - Expanded dataset containing 12 waste classes.
- **`Dataset3-6classes/`** - Smaller dataset with 6 waste categories.
- **`Dataset4-7classes/`** - Dataset containing 7 waste categories.
- **`Recyclable Waste Images (9 classes)/`** - Dataset focusing on recyclable waste classification.
- **`realwaste (9 classes)/`** - Real-world waste dataset with 9 classes.
- **`waste image dataset (9 classes)/`** - Additional dataset with 9 waste classes.
- **`Tiff files/`** - TIFF format images for showcasing the outcome of the analysis.

*Overall, a comprehensive dataset analysis was performed to evaluate waste classification under different conditions. These datasets were utilized to ensure the robustness and adaptability of our model across diverse waste compositions, contributing to the success of this research.*

### **2. Energy and Sustainability Analysis**
- **`Energy Consumption and CO2 Emission Tracking/`** - Data and analysis related to the environmental impact of the computational processes.

### **3. Different Models, Adversarial Noise, and Image Randomness Analysis**
- **`Additional Models with Different Parameter Sizes/`** - Variants of our deep learning models with different parameter configurations.
- **`Training by Adding Noises/`** - Models trained with artificially introduced adversarial noise to test model robustness.
- **`Training by Employing Randomness in Images/`** - Models trained with image inconsistencies such as blur, contrast, brightness variations, and other distortions to analyze how classification performance is affected and whether accuracy remains stable.

### 4. Research Documents

- **Revised_Manuscript_UnderReview.pdf** - Our latest research manuscript currently under review.
- **README.md** - This file, providing an overview of the project.


## **Key Contributions of Our Research**
- **Enhanced Waste Classification Model**: Utilized **DenseNet201** with a **Parallel CNN architecture** and **SE attention mechanism**, significantly improving classification accuracy and efficiency.
- **Multi-Dataset Evaluation**: Unlike conventional single-dataset studies, we assessed our model on four primary datasets and three additional datasets, increasing generalization and applicability.
- **Web-Based Implementation**: Developed a **Gradio-based web system** for real-time waste classification, currently deployed on a local server with potential for large-scale use in waste management.
- **Energy and Sustainability Monitoring**: Tracked **energy consumption and CO2 emissions** during model training and inference to assess environmental impact and sustainability.
- **Adversarial and Image Variability Testing**: Analyzed model performance by introducing adversarial noise and image inconsistencies to evaluate classification robustness under challenging conditions.


## **Future Directions**
- Expanding dataset diversity to improve model robustness.
- Exploring lightweight models for deployment on **edge devices**.
- Enhancing interpretability using **Explainable AI (XAI) techniques**.

For any inquiries or collaboration opportunities, feel free to contact us!

