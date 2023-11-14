# Salary Prediction Project

This project focuses on predicting salaries based on the Stack Overflow Developer Survey dataset. It includes a machine learning model to predict salaries and a web application for easy interaction with the model, built using Streamlit.

## Dataset

The dataset used for this project is the Stack Overflow Developer Survey dataset. It includes information about developers, their skills, job preferences, and, most importantly, their salary.

## Project Structure

- **notebooks**: Jupyter notebooks containing the exploratory data analysis (EDA) and machine learning model development.
- **src**: Python scripts for data preprocessing, model training, and evaluation.
- **app**: Streamlit web application files.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/salary-prediction-project.git
    cd salary-prediction-project
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:

    ```bash
    streamlit run app/app.py
    ```

    This will open the app in your default web browser.

## Model Training

If you want to retrain the model with your own dataset or parameters, you can use the provided Jupyter notebooks in the `notebooks` directory.

```bash
cd notebooks
jupyter notebook

## Streamlit App
The Streamlit web application is located in the app directory. You can customize the app by modifying the app.py file.

## Contributing
Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback and suggestions are highly appreciated.

## License
This project is licensed under the MIT License.
