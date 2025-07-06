<p align="center">
  <img src="https://media.giphy.com/media/S3Pe5NZqgmE8Tl3niZ/giphy.gif" width="300" />
</p>
# 🌲 Forest Cover Type Prediction

This repository contains a machine learning project that predicts forest cover types based on cartographic variables. It uses classification algorithms to classify each observation into one of the forest cover types.

## 📂 Dataset

- **Name**: `covtype.csv` (not included in this repo, please download separately from UCI ML Repository)
- **Attributes**: 54 features including Elevation, Slope, Distance metrics, Hillshade indices, and Wilderness/Soil type indicators
- **Target**: `Cover_Type` (Integer 1-7 representing forest cover classes)

## 🔍 Project Overview

### 📈 Objective
Build a classification model to predict the type of forest cover using various environmental and geographic features.

### 🔧 Workflow

1. **Data Loading and Cleaning**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Selection**
4. **Model Building**
5. **Model Evaluation**

### 💻 Model Used

- **Feature Selector**: `ExtraTreesClassifier` from sklearn
- **Classifier**: `RandomForestClassifier`
- **Metric**: Accuracy and Confusion Matrix

### 🔬 Evaluation

- Uses accuracy as the primary metric.
- Visualizes confusion matrix for performance analysis.

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## 🚀 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/<your-username>/forest-cover-prediction.git
    cd forest-cover-prediction
    ```

2. Add the dataset `covtype.csv` to the root folder.

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Launch the notebook:
    ```bash
    jupyter notebook forest-fire-prediction.ipynb
    ```

## 📋 Requirements

You can install the required libraries with:
```bash
pip install -r requirements.txt
```

Example `requirements.txt`:
```
pandas
numpy
matplotlib
seaborn
scikit-learn
```
- **Accuracy**: 93.12% (Random Forest)
- 
## 🤖 Author

**Prashant Joshi**  
Bachelor of Engineering – Computer Science & Engineering  
Prof Ram Meghe College of Engineering and Management, Amravati

## 📬 Contact

For any inquiries or collaboration ideas, feel free to reach out!

---

> “Forests are not just a resource, they are the lungs of our planet.” 🌍

