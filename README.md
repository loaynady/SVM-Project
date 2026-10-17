# SVM-Project
AI &amp; Machin learning project
# SVM Spam Message Classification

## Project Overview
This project uses a Support Vector Machine (SVM) model to classify text messages as spam or ham (normal messages).

The project demonstrates basic Natural Language Processing (NLP) techniques and machine learning classification.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Machine Learning Techniques
- Text preprocessing with TF-IDF Vectorization
- Label encoding for spam and ham messages
- Train-test split
- Support Vector Machine (SVM) classification
- Model evaluation using accuracy score

## Models
Two SVM kernels are tested:
- Linear Kernel
- Polynomial (Poly) Kernel

## Dataset
The notebook uses a small, manually created dataset containing 20 text messages:
- Spam messages
- Ham (normal) messages

## Results
The current notebook reports the following accuracy scores:

| Model | Accuracy |
|---|---:|
| SVM with Linear Kernel | 25% |
| SVM with Polynomial Kernel | 25% |

These results are from the current implementation and should not be considered reliable performance estimates because the dataset is very small and the text feature selection needs improvement.

## How to Run
1. Install Python.
2. Install the required libraries:
   `pip install pandas numpy matplotlib scikit-learn`
3. Open `SVM Model.ipynb` in Jupyter Notebook.
4. Run the notebook cells.

## Future Improvements
- Use a larger and more realistic dataset.
- Improve text feature extraction.
- Evaluate the models using additional metrics.
- Improve model performance through experimentation.

## Author
Loay Nady

