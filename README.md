# Machine Learning Course Project – Phase 1 & 2  
**Author:** Keerthana R  

## Overview  
This project demonstrates the implementation of **Transfer Learning** and **Fine-Tuning** using advanced **Convolutional Neural Network (CNN)** architectures. It applies multiple pretrained models to a dataset and evaluates their performance using standard classification metrics.  

---

## Project Files  

| File Name | Description |
|------------|-------------|
| `Keerthana_R_ML_CourseProject_Phase1_Code.ipynb` | Phase 1 notebook – data preprocessing, model setup, and initial training experiments |
| `Keerthana_R_ML_CourseProject_Phase2_Code.ipynb` | Phase 2 notebook – fine-tuning, model optimization, and evaluation |
| `Data_for_UCI_named.csv` | Dataset used for model training and testing |

---

## Models Used  
The project employs **Transfer Learning** with the following pretrained CNN architectures:  
- **ResNet101V2**  
- **InceptionResNetV2**  
- **DenseNet201**

Each model was fine-tuned with:  
- **Batch Normalization**  
- **Dropout Layers**  
- **Layer-Specific Trainability Rules**

---

## Evaluation Metrics  
Performance of each model was assessed using:  
- Confusion Matrix  
- Precision  
- Recall  
- F1 Score  

These metrics provide a holistic view of model accuracy and reliability.

---

## Technologies Used  
- **Python 3.x**  
- **TensorFlow / Keras**  
- **NumPy, Pandas, Matplotlib, Seaborn**  
- **scikit-learn**

---

## How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt

  2. Open Jupyter Notebook:
   ```bash
   jupyter notebook

