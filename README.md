# Mental Health Analysis

## Introduction
As college students, we believe mental health is a crucial issue that could be addressed in a better manner. This project aims to:
- Understand how certain words/phrases correspond to different mental health conditions
- Develop an emotion text classifier which takes in raw data, preprocesses it and predicts the emotion expressed by the text

---

## Project Structure
- Data/ `mental_heath_unbanlanced.csv` # Dataset used in the analysis
- LICENSE
- `Mental_Health_Analysis.ipynb` # Main Jupyter Notebook
- README.md # Project Documentation
- `requirements.txt` # Contains dependencies/libraries used in analysis


---

## Installation
How to set up the environment:

```bash
# Clone the repository
git clone https://github.com/Ibrahim581/LIN_371_Project.git

# Navigate into the project directory
cd LIN_371_Project

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

```

## Dependencies
- pandas
- nltk
- matplotlib
- seaborn
- wordcloud
- scikit-learn
- xgboost

## Usage
After installing the dependencies, launch Jupyter Notebook and open `Mental_Health_Analysis.ipynb`

## Features
- Data cleaning and preprocessing of text data
- Data Exploration/Visualization of word distributions and emotional trends
- Emotion classification using machine learning techniques

## Results/Insights
- Identified common emotional patterns
- Built multiple classifiers (Logistic Regression, Naive Bayes, XG-Boost)
- Evaluated performance through Accuracy, Precision, Recall and ROC curves

## License

This project is licensed under the MIT License.

See the `LICENSE` file for more details.
