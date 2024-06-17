# DeepRespNet

### A Deep Learning Approach to classify Respiratory Diseases

- DeepRespNet is a deep learning model specifically designed to analyze respiratory sounds and assess the respiratory health of patients. 
- By leveraging deep learning techniques, our model classifies respiratory sounds into categories such as healthy, chronic, and acute conditions.

- The DeepRespNet web application offers an intuitive platform for both individuals and healthcare professionals to evaluate respiratory health through audio recordings. 
- Our primary goal is to facilitate the early detection of respiratory conditions, enabling timely and accurate medical intervention to improve patient outcomes.

## Setup

To set up this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Mohammed-Khubaib/DeepRespNet.git
    ```

2. Navigate to the project directory:
    ```bash
    cd DeepRespNet
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Running the Application

The main application can be launched using `app.py`. This file utilizes `pieChart.py` and `linechart.py` internally.

```bash
streamlit run app.py
```

## Dataset Source

The dataset used in this project is the [Respiratory Sound Database](https://www.kaggle.com/datasets/vbookshelf/respiratory-sound-database) available on Kaggle.

## Web Application User Interface
https://github.com/Mohammed-Khubaib/DeepRespNet-PWCSE20B18/assets/102320167/fd06f6c4-8d19-4acb-ae63-79fd3affebfa
## projet struture

```
.
├── README.MD
├── animations
│   ├── DeepRespNet Architecture.png
│   ├── Lungs.json
│   ├── SoundRecordingAnimation.json
│   ├── Stethoscope.json
│   └── dashboard animation.json
├── app.py
├── diagnosis_GRU_CNN_5.keras
├── linechart.py
├── model5accuracy.yaml
├── pieChart.py
└── requirements.txt
```

## Team
1. Mohammed Khubaib
2. Ashish Kumar Pandia
3. Airla Snehith