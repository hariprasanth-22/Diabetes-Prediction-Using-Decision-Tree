# Diabetes-Prediction-Using-Decision-Tree
# Diabetes Prediction using Decision Tree Classifier

This project uses a Decision Tree Classifier to predict whether a person has diabetes, based on health indicators such as glucose level, BMI, insulin, and more. The model is trained on the Pima Indians Diabetes dataset and built entirely in Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hariprasanth-22/Diabetes-Prediction-Using-Decision-Tree/blob/main/Diabetes(DF).ipynb)

---

## Description

The notebook walks through loading the dataset, splitting the data into training and test sets, training a Decision Tree Classifier with Gini impurity and max depth of 3, and evaluating its accuracy. The final tree is also visualized using Graphviz.

---

## Features

- Load and preview the Pima Indians Diabetes dataset
- Check for and confirm no missing values
- Split data into 80% training and 20% test sets
- Train a Decision Tree model using `scikit-learn`
- Evaluate model accuracy (approximately 75.3%)
- Visualize the trained tree structure using `graphviz`

---

## Project Files

.
├── Diabetes(DF).ipynb # Main notebook (Google Colab compatible)
├── diabetes.csv # Dataset (from UCI ML repository)
└── README.md # Project overview

yaml
Copy
Edit

---

## How to Run (Google Colab)

1. Click the **Open in Colab** button above
2. Upload `diabetes.csv` when prompted, or mount your Google Drive if stored there
3. Run all cells in order using `Runtime > Run all`
4. View the model's accuracy score and decision tree visualization

---

## Technologies Used

- Python 3.x
- pandas
- scikit-learn
- graphviz
- Google Colab

---

## Example Results

- Accuracy: ~75.3%
- Criterion: Gini
- Max depth: 3
- Tree visualization rendered using `graphviz.Source`

---

## Contributing

Contributions are welcome. Please follow these steps:

1. Fork this repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a pull request

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Citation

Smith, J. W., et al. *Pima Indians Diabetes Database*, National Institute of Diabetes and Digestive and Kidney Diseases. UCI Machine Learning Repository, 1990.

---

## Acknowledgements

- UCI Machine Learning Repository
- scikit-learn contributors
- Google Colab for providing a cloud-based notebook environment
