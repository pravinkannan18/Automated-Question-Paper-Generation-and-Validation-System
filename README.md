Automated Question Paper Generation and Validation System
Date: September 2024
Technologies: Python, PyPDF2, Ollama (Mistral), NLP, Text Processing

Project Overview
The Automated Question Paper Generation and Validation System is an AI-powered application designed to streamline the creation, validation, and revision of question papers for educational institutions. Using Python and advanced NLP models, this system automates the extraction, validation, and correction of question papers, ensuring they are grammatically accurate, syllabus-compliant, and suitable based on Bloom's Taxonomy.

Features
AI-Based System:

Automated extraction, validation, and correction of question papers.
Utilizes Python and NLP models (like Ollama's Mistral) for efficient text processing.
Grammatical and Syllabus Check:

Detects and corrects grammatical errors within the questions.
Validates questions to ensure alignment with the given syllabus.
Question Replacement:

Identifies and replaces irrelevant or incorrect questions.
Generates replacement questions aligned with Bloom’s Taxonomy (levels such as Remember, Apply, Evaluate) for improved educational effectiveness.
Real-Time Output:

Streams immediate results for rapid question paper validation.
Enables quick and efficient paper review by generating error-free, syllabus-compliant questions in real time.
Automated Paper Revision:

Generates final, validated question papers ready for academic use.
Ensures papers are free of errors and tailored to curriculum needs.
Technologies Used
Python: Core programming language for automation and logic.
PyPDF2: For reading and processing question papers in PDF format.
Ollama (Mistral): NLP model used to process and validate text data.
NLP (Natural Language Processing): For text analysis, question validation, and error detection.
Text Processing: Handles question extraction, grammar checks, and syllabus alignment.
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/Automated-Question-Paper-Generation.git
cd Automated-Question-Paper-Generation
Install Required Packages: Ensure you have Python installed, then install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Application:

bash
Copy code
python main.py
Usage
Upload Question Paper: Upload a PDF of the question paper.
Validation Process: The system automatically scans and validates questions, checks grammar, and confirms syllabus alignment.
Replacement Suggestions: If any question is found irrelevant or erroneous, the system suggests replacements based on Bloom's Taxonomy.
Output Results: A revised, validated question paper is generated and ready for download.
Contributing
