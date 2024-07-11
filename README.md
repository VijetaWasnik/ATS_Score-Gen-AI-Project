# Smart ATS (Application Tracking System) using Generative AI and Streamlit

This project implements a Smart ATS application using Streamlit and Google's Generative AI to evaluate resumes against job descriptions. It integrates PyPDF2 for PDF handling and dotenv for managing environment variables.

## Features

- **Resume Evaluation:** Upload resumes in PDF format to evaluate against a provided job description.
- **Generative AI Integration:** Utilizes Google's Generative AI to analyze resumes and provide feedback based on job requirements.
- **Keyword Matching:** Evaluates keyword matches between resumes and job descriptions, highlighting missing keywords.
- **Profile Completeness:** Assesses the completeness of resume profiles based on job market competitiveness.

## Technologies Used

- **Streamlit:** Python framework for building interactive web applications.
- **Google Generative AI:** Utilized for natural language processing and content generation.
- **PyPDF2:** Python library for PDF file manipulation.
- **dotenv:** Python library for managing environment variables.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/VijetaWasnik/ATS_Score-Gen-AI-Project/
   cd smart-ats
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:

   Create a `.env` file in the project root and add your environment variables:

   ```dotenv
   GOOGLE_API_KEY=<your_google_api_key>
   ```

4. Run the application:

   ```bash
   streamlit run app.py
   ```

5. Access the application in your browser at `http://localhost:8501`.

## Contributing

Contributions are welcome! If you find any issues or have suggestions, please feel free to open an issue or submit a pull request.

