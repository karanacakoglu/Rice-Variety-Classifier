# 🌾 Rice Variety Classification using ResNet50

### Project Overview
This project focuses on the automated classification of rice varieties using deep learning. Accurate identification of rice types is crucial for quality control and supply chain management in the agricultural industry. [cite_start]This implementation uses **ResNet50** to achieve high classification accuracy across five different classes.

---
### 🛠️ Technical Implementation
* [cite_start]**Model Backbone:** **ResNet50**, chosen for its ability to handle deep feature hierarchies via residual connections.
* **Methodology:** * **Preprocessing:** Image resizing and normalization for the ResNet architecture.
    * [cite_start]**Transfer Learning:** Utilizing pre-trained weights to enhance feature detection and reduce training time.
    * [cite_start]**Optimization:** Fine-tuned the fully connected layers to map visual features to the 5 specific rice categories.

---

### 🚀 Key Results
[cite_start]The model effectively distinguishes between similar-looking varieties (e.g., Basmati vs. Jasmine) by identifying subtle morphological features in the grain images[cite: 16].

---

* **Data File Note:** The data file contains images of arborio, basmati, Ipsala, Jasmine, and Karacadag rice. Using these images, the class to which the rice image given as input belongs will be predicted. ResNet50 was selected for the prediction model in this project.

* * **📊 Dataset Source:** [Rice Image Dataset - Kaggle/Murat Koklu](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset)

