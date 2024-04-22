# Medical Appointment No-Show Analysis
==============================


![image](OIG3.2avc.jpeg)
## Introduction

This project aims to analyze a dataset of 100,000 medical appointments in Brazil, focusing on whether or not patients show up for their appointments. The dataset includes several characteristics about the patient in each row.

## Data
the dataset include the following fields :
| Field                   |Description |
|-------------------------|------------|
| **PatientId**         | Identification of a patient. |
| **AppointmentID**     | Identification of each appointment. |
| **Gender**            | Male or Female. Female is the greater proportion, women take way more care of their health in comparison to men. |
| **DataMarcacaoConsulta** | The day of the actual appointment, when they have to visit the doctor. |
| **DataAgendamento**   | The day someone called or registered the appointment, this is before the appointment of course. |
| **Age**               | How old is the patient. |
| **Neighbourhood**     | Where the appointment takes place. |
| **Scholarship**       | True or False. |
| **Hipertension**      | True or False. |
| **Diabetes**          | True or False. |
| **Alcoholism**        | True or False. |
| **Handcap**           | True or False. |
| **SMS_received**      | 1 or more messages sent to the patient. |
| **No-show**           | True or False. |

## Methodology
The project will involve exploratory data analysis, data cleaning, and feature engineering, followed by the application of machine learning models to predict whether a patient will show up for their appointment.

### Prerequisites
The project requires the following Python libraries:
- pandas
- numpy
- seaborn
- klib
- plotly-express
- Scikit-learn

```bash
- pip install pandas
- pip install numpy 
- pip install seaborn 
- pip install klib 
-pip install plotly-express 
- pip install Scikit-learn
```
### Installing
1. Clone the repository


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
