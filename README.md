# Resume Classifier

This is a Flask-based web application that classifies resumes into various job categories using a machine learning model.

## Features
- Upload resume files (PDF or text format)
- Extract text from resumes and preprocess them
- Predict job categories using a trained classifier
- Display the classification results

## Project Structure
```
├── __pycache__
├── static/
├── templates/
├── app.py
├── clf.pkl
├── tfidf.pkl
├── requirements.txt
├── Resume Classifier.ipynb
├── README.md
├── .gitattributes
```

## Installation
### Prerequisites
- Python 3.x
- Flask
- NLTK
- PyPDF2
- scikit-learn

### Setup
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Flask app:
   ```sh
   python app.py
   ```
4. Open your browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

## Model Details
The classifier uses a machine learning model trained on resume data. The model (`clf.pkl`) and TF-IDF vectorizer (`tfidf.pkl`) are loaded to process input resumes and predict their job categories.

## Usage
1. Upload a resume file (PDF or text format).
2. The system extracts and cleans the text from the file.
3. The cleaned text is passed to the model for prediction.
4. The predicted job category is displayed.

## Job Categories
The model can classify resumes into the following job categories:
- Advocate
- Arts
- Automation Testing
- Blockchain
- Business Analyst
- Civil Engineer
- Data Science
- Database
- DevOps Engineer
- DotNet Developer
- ETL Developer
- Electrical Engineering
- HR
- Hadoop
- Health and Fitness
- Java Developer
- Mechanical Engineer
- Network Security Engineer
- Operations Manager
- PMO
- Python Developer
- SAP Developer
- Sales
- Testing
- Web Designing


## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request.

## Author
AdhilAbu9072


 
