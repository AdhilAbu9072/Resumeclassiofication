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
   git clone https://github.com/AdhilAbu9072/Resumeclassiofication.git
   cd Resumeclassiofication
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

## Deployment on AWS EC2
The project was also deployed on AWS EC2 using Amazon Linux. Below are the basic steps:

1. Launch an EC2 instance with Amazon Linux.
2. Install necessary dependencies:
   ```sh
   sudo dnf update -y
   sudo dnf install python3 python3-pip -y
   pip install -r requirements.txt
   ```
3. Run the Flask app and expose it on port 80:
   ```sh
   sudo python app.py
   ```
4. Configure security groups to allow inbound traffic on port 80.
5. Access the application via the public IP of the EC2 instance.

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

