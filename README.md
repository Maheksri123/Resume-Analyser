Resume Analyser
A Python tool to parse and analyze PDF resumes, extract relevant information, and provide structured output for further processing or insights.

Features
Upload and process PDF resume files

Extract contact information, skills, education, experience, and keywords

Structure and display resume data in a user-friendly format

Easy integration with web apps using Flask and HTML templates

Folder Structure
.env – Environment configuration

analysepdf.py – PDF parsing and analysis logic

main.py – Main application (Flask backend)

templates/ – Contains index.html and other frontend HTML files

Kumaresan-resume.pdf – Example PDF resume

Getting Started
Prerequisites
Python 3.8 or above

pip (Python package installer)

Install required libraries:

text
pip install flask PyPDF2
Running the Project
Clone the repository and navigate to the folder

Place PDF files to be analyzed in the project directory

Start the Flask app:

text
python main.py
Open your browser and go to http://localhost:5000

Usage
Upload a resume PDF through the web interface

View extracted information and suggestions within the app

Customization
Modify analysepdf.py to enhance PDF parsing or add fields

Edit HTML files in templates/ to adjust the frontend

License
This project is for educational purposes.

