# Customer Loan Classification

This Jupyter Notebook is dedicated to classifying customers into two categories: those whose loans are already paid off and those who defaulted on their loans. We will apply a range of classification algorithms to determine the best-performing one for this specific dataset using accuracy evaluation methods.

**Note:** This notebook is a part of a Cousera course - [Machine Learning with Python IBM]([https://www.coursera.org/learn/introduction-to-deep-learning-boulder](https://www.coursera.org/learn/machine-learning-with-python))


## Dataset Description

The dataset, "Loan_train.csv," contains information about past loans. It includes details of 346 customers, along with their loan status (paid off or defaulted).

## Notebook Contents

In this notebook, we will go through the following steps:

1. **Data Loading**: We'll load the dataset using the Pandas library and explore its structure.

2. **Data Visualization**: We'll perform data visualization to gain insights into the dataset's characteristics and distributions.

3. **Data Pre-processing**: This step involves feature selection, handling categorical variables, and normalizing data to prepare it for classification.

4. **Classification Algorithms**: We'll implement and evaluate several classification algorithms, including:
   - K Nearest Neighbor (KNN)
   - Decision Tree
   - Support Vector Machine
   - Logistic Regression

5. **Model Evaluation**: We'll evaluate the performance of each classification model using the following metrics:
   - Jaccard Score
   - F1 Score
   - Log Loss

6. **Conclusion**: Based on the evaluation metrics, we'll identify the best-performing classification algorithm for this dataset.

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone [https://github.com/yourusername/Customer-Loan-Classification.git](https://github.com/MaitreeVaria/machine_learning_ibm_final_lab.git)
   ```

2. Navigate to the project folder:

   ```bash
   cd Customer-Loan-Classification
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the "ML0101EN-Proj-Loan-py-v1.ipynb" notebook in your browser and run the cells to explore the classification of customer loans.

## Contributing

Contributions are welcome! If you have improvements, bug fixes, or new ideas for this project, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Thank you for exploring customer loan classification! If you have any questions or need assistance, please don't hesitate to reach out. Enjoy working with classification algorithms and data analysis! 📊📈
