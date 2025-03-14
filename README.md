# Resume Ranking System

## Project Overview
The Resume Ranking System is a machine learning-based project that scores resumes based on a given job description. It leverages Natural Language Processing (NLP) techniques and a Random Forest Regressor to predict the relevance of resumes to the job description, helping recruiters streamline the hiring process.

## Features
- Processes resumes and job descriptions using NLP techniques.
- Computes similarity scores between resumes and job descriptions.
- Predicts resume relevance using a Random Forest Regressor.
- Provides a ranked list of resumes based on predicted scores.

## Tech Stack
- Python
- Natural Language Processing (NLP)
- Scikit-Learn
- Pandas, NumPy
- NLTK / SpaCy (for text processing)
- Random Forest Regressor

## Installation
1. Clone the repository:
```bash
https://colab.research.google.com/drive/1_4CkJxQeAjofrzDWU0qRzC3xv8tfRxYP?usp=sharing
```
2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Prepare your dataset with resumes and job descriptions.
2. Run the main script:
```bash
python main.py
```
3. The system will output ranked resumes with their corresponding scores.

## Project Structure
```
resume-ranking-system/
├── data/
│   ├── resumes/               # Directory containing resume files
│   └── job_descriptions/      # Directory containing job descriptions
├── models/                    # Saved machine learning models
├── main.py                    # Entry point for the project
├── utils.py                   # Helper functions
├── requirements.txt           # Project dependencies
└── README.md                  # Project documentation
```

## Evaluation Metrics
- Mean Squared Error (MSE)
- R-squared Score

## Results
- Achieved an R-squared score of **X.XX** on the validation set.

## Google Colab Link
You can run this project in Google Colab: [Open in Colab](https://colab.research.google.com/)

## Future Enhancements
- Integrate other ML algorithms for comparison.
- Implement a web interface for easier use.
- Expand dataset for improved accuracy.

## Contributing
Contributions are welcome! Please open an issue or create a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any questions or suggestions, feel free to contact [Your Name](mailto:mmanikandan281@gmail.com).

---
**Note:** Replace placeholders like "X.XX" and "yourusername" with actual values before publishing.

