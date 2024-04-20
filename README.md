# Smart ATS

Smart ATS is a Streamlit web application designed to enhance your resume's compatibility with job descriptions. Powered by Google's GenerativeAI, it simulates an Application Tracking System (ATS) to evaluate resumes based on provided job descriptions, offering insights on JD match percentage, missing keywords, and profile summary.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Features

- Upload PDF resumes for analysis.
- Paste job descriptions for comparison.
- Receive detailed feedback including JD match percentage, missing keywords, and profile summary.
- Easy-to-use interface with Streamlit.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/smart-ats.git
   cd smart-ats

2. Install dependencies::

   ```bash
   pip install -r requirements.txt

3. Set up environment variables:Create a .env file in the root directory with the following content:

   ```bash
   GOOGLE_API_KEY=your_google_api_key_here

## Usage

1. Run the app:

   ```bash
   streamlit run smart_ats.py

2. Access the app in your browser:Open your web browser and go to http://localhost:8501.

3. Use the app:
- Paste the job description in the provided text area.
- Upload your resume in PDF format.
- Click the "Submit" button to receive feedback on your resume.


## Technologies
Smart ATS leverages the following technologies:

- Python: The primary programming language used for the backend logic and data processing.
- Streamlit: A Python library used to create interactive web apps for data science and machine learning.
- Google's GenerativeAI: Utilized for simulating an Application Tracking System (ATS) to evaluate resumes.
- PyPDF2: A Python library used for extracting text from PDF files.
- dotenv: Used for managing environment variables securely.

## Contributing

I welcome contributions to enhance Smart ATS. To contribute, please follow these steps:
1. Fork the repository on GitHub.
2. Clone your forked repository to your local machine.
    ```bash
    git clone https://github.com/your-username/smart-ats.git
    cd smart-ats
3. Create a new branch for your feature or bug fix:
    ```bash
    git checkout -b feature/my-feature
4. Make your changes and ensure the code passes all tests.
5. Commit your changes and push to your forked repository:
    ```bash
    git add .
    git commit -m "Add new feature or fix"
    git push origin feature/my-feature
6. Open a pull request on the original repository for review and merging.
Please ensure your contributions align with our code of conduct and contribute positively to the project.
## License
Smart ATS is licensed under the MIT License
