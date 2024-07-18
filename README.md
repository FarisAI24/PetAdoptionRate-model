# Pet Adoption Prediction Project

## Overview
This project aims to predict the likelihood of pet adoption using machine learning techniques. We use a dataset containing various features of pets in shelters to train a Random Forest Classifier that predicts whether a pet is likely to be adopted. The entire analysis, from data preprocessing to model training and evaluation, is contained in a single Jupyter notebook.

## Dataset
The dataset (`pet_adoption_data.csv`) contains information about pets in shelters, including:
- Pet type (e.g., Dog, Cat, Rabbit, Bird)
- Breed
- Age
- Color
- Size
- Weight
- Vaccination status
- Health condition
- Time spent in the shelter
- Adoption fee
- Previous owner status
- Adoption likelihood (target variable)

## Project Structure
The project is structured as follows:

```
pet_adoption_prediction/
│
├── pet_adoption_analysis.ipynb
├── pet_adoption_data.csv
├── requirements.txt
└── README.md
```

## Setup and Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/pet-adoption-prediction.git
   cd pet-adoption-prediction
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Ensure you have Jupyter Notebook or Jupyter Lab installed.

2. Open the Jupyter notebook:
   ```
   jupyter notebook pet_adoption_analysis.ipynb
   ```
   or
   ```
   jupyter lab
   ```

3. Run the cells in the notebook sequentially to perform the analysis.

## Contents of the Notebook

The `pet_adoption_analysis.ipynb` notebook contains the following sections:

1. Data Loading and Initial Exploration
2. Data Preprocessing
3. Exploratory Data Analysis and Visualization
4. Model Training (Random Forest Classifier)
5. Model Evaluation

## Results
The Random Forest Classifier achieves an accuracy of 92% on the test set. 

## Future Work
- Experiment with other machine learning algorithms
- Perform hyperparameter tuning to improve model performance
- Collect more data to potentially improve prediction accuracy
- Develop a web application for easy use by shelter staff

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.