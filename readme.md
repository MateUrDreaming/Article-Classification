# Article Classification using Supervised Learning Approaches

This project investigates supervised learning algorithms for classifying BBC news articles into two classes: *tech news* and *entertainment news*. We use **Naïve Bayes (NB)**, **k-Nearest Neighbors (kNN)**, **Support Vector Machines (SVM)**, and **Neural Networks (NNs)** to perform classification and compare model performance. The project is implemented in a Jupyter Notebook using the Scikit-learn library.

## Disclaimer

This project was completed as part of an assignment for a course at the University between 4 people. It is intended for educational purposes only.

### Contributors 

- Parin Kasabia
- Jack Choi
- Edward Lim 
- Benjamin De Wet

## Requirements

Before running the notebook, ensure you have the following installed:

1. **Python 3.x**
2. **Jupyter Notebook** or an equivalent IDE
3. The following Python libraries:
   - `numpy`
   - `pandas`
   - `scikit-learn`
   - `matplotlib`
   - `seaborn`

You can install missing dependencies using pip:

```bash
pip install -r requirements.txt
```
## How to Run the Notebook

1. **Download the Project Files**  
   Ensure you have the Jupyter Notebook (`article_classification.ipynb`) and the dataset files (`train.csv` and `test.csv`) in the same directory.

2. **Open the Notebook**  
   Launch Jupyter Notebook, navigate to the directory containing the notebook, and open `article_classification.ipynb`.

3. **Execute the Notebook**  
   - Run each cell sequentially by clicking **Cell** > **Run Cell** or pressing `Shift + Enter`. 
   - Follow any instructions provided in the notebook to input parameters, if required.

4. **View Results**  
   The notebook will output:
   - Exploratory Data Analytics (EDA) visualizations and summaries.
   - Classification model performance metrics, including F1 scores.
   - A comparison of hyperparameter impacts across models.
   - Insights and recommendations based on the analysis.
  
## Notes

- **Dataset Format**: Ensure the dataset (`train.csv`) is formatted correctly with three columns:
  - `news_id` (unique identifier)
  - `processed_news_body` (preprocessed text data)
  - `news_class` (label: `tech` or `entertainment`).

- **Reproducibility**: For consistent results, the notebook includes random seed settings for splitting data and training models.

- **Output**: All plots, tables, and summaries will be displayed directly within the notebook cells.

## Troubleshooting

- If you encounter import errors, verify that all required libraries are installed.
- Ensure the dataset file is in the same directory as the notebook.
- Restart the notebook kernel if any unexpected issues occur: **Kernel** > **Restart & Run All**.

## Acknowledgments

This project is based on concepts covered in supervised learning, including Naïve Bayes, kNN, SVM, and Neural Networks, as applied to text classification tasks.