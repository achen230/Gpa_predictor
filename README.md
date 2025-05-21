# GPA Predictor

This project is a GPA Predictor web application built with Python. It uses machine learning to predict student GPA based on lifestyle factors and provides an interactive dashboard for exploration.

## Features
- Predicts GPA based on user input for study hours, extracurricular activities, sleep, social, and physical activity.
- Interactive dashboard built with Dash and Plotly.
- Machine learning model built with TensorFlow/Keras and scikit-learn.
- Data visualization of predictions and original data.

## Requirements
- Python 3.8+
- See `requirements.txt` for all dependencies (or install manually):
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - tensorflow
  - joblib
  - dash
  - plotly

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/achen230/Gpa_predictor.git
   cd Gpa_predictor
   ```
2. (Recommended) Create and activate a virtual environment:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   # or manually install as listed above
   ```
4. Run the app (if using Dash):
   ```bash
   python app.py
   # or run the notebook app.py.ipynb in Jupyter/VS Code
   ```

## Data
- The dataset used is `student_lifestyle_dataset.csv`.
- Make sure this file is present in the project directory.

## Notes
- The `.venv/` directory and large installer files are ignored via `.gitignore`.
- Do not commit large binaries or datasets to the repository.

## License
MIT License
