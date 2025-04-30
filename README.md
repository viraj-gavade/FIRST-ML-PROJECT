# Student Placement Predictor

🎓 **Placement Prediction ML Model**

This is my **first machine learning model** that predicts student placement outcomes using logistic regression. Built with ❤️ using Python, pandas, and scikit-learn.

## 📂 Project Structure
```
├── first-project.ipynb  # Jupyter notebook with full ML workflow
├── placement.csv        # Dataset used for training and testing
├── model.pkl           # Saved logistic regression model
└── README.md           # You're reading it 😄
```

## 📈 Model Summary
* **Model Type**: Logistic Regression
* **Features Used**: Based on the `placement.csv` dataset (e.g. CGPA, specialization, etc.)
* **Target Variable**: Placement status (placed or not placed)
* **Libraries**: `pandas`, `scikit-learn`, `matplotlib`, `mlxtend`

## 📊 Dataset
The dataset (`placement.csv`) includes:
* Academic details
* Stream/specialization
* Placement status *(Feel free to peek inside the CSV for column names and details)*

## 🧠 How the model was trained
1. Preprocessed the data (label encoding, normalization)
2. Split into training and test sets
3. Trained a logistic regression classifier
4. Evaluated using accuracy and decision region plots

## 🚀 How to Use
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/placement-predictor.git
   cd placement-predictor
   ```

2. Run the notebook:
   ```bash
   jupyter notebook first-project.ipynb
   ```

3. Load the model in any Python script:
   ```python
   import pickle
   model = pickle.load(open('model.pkl', 'rb'))
   ```

## 📉 Output Example
* Accuracy: `xx%` (fill in your model's score here)
* Decision boundary plot showing classified regions.

## 📌 Requirements
Install dependencies with:
```bash
pip install -r requirements.txt
```

Minimal `requirements.txt`:
```
pandas
numpy
matplotlib
scikit-learn
mlxtend
```

## ✍️ Author
Viraj Gavade – GitHub
