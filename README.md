# Flight Fare Prediction Web App

This web application provides a user-friendly interface for predicting flight fares based on user inputs such as origin and destination airports, departure date, departure time, and cabin type. Users can select from four machine learning models, enabling comparison and flexibility in fare prediction.

## Features

- **Flight Fare Prediction**: Provides fare predictions based on user inputs.
- **Model Selection**: Allows users to choose between four different models for fare prediction.
- **Easy-to-Use Interface**: Dropdowns and date/time pickers ensure an intuitive user experience.

## Getting Started

Follow the instructions below to set up and run the application on your local machine.

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Required Python packages (install via `requirements.txt`)

### Installation

1. Clone the repository or download the code files.

2. Navigate to the project directory:
   ```app_at3```

3. Install the necessary dependencies:
    pip install -r requirements.txt

4. Ensure the trained model files are in the same directory as streamlit_app.py or update the file paths as needed.

## Running the APP

1. From the project directory, run the following command to start the Streamlit app:
    ```streamlit run app.py```

2. Open your browser and go to http://localhost:8501 to access the application.

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
