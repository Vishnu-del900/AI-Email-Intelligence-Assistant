# AI Email Intelligence Assistant

## About the Project
The AI Email Intelligence Assistant is a web application that uses Generative AI to analyze emails and help users understand important information quickly.

## Features
- **Email Summary:** Generates a short summary of the email.
- **Priority Detection:** Identifies whether an email has High, Medium, or Low priority.
- **Action Items:** Extracts tasks and deadlines mentioned in the email.
- **Suggested Reply:** Generates a polite, professional email response.
- **Download Analysis:** Allows users to download the results as a text file.
- **Input Validation:** Displays a warning when the email field is empty.

## Technologies Used
- Python
- Streamlit
- Google Gemini API
- VS Code

## How to Run the Project

1. Install Python.
2. Install the required packages:

   `python -m pip install streamlit google-genai`

3. Configure your Gemini API key in `.streamlit/secrets.toml`:

   `GEMINI_API_KEY = "YOUR_API_KEY"`

4. Start the application:

   `python -m streamlit run app.py`

5. Open the local URL shown in the terminal.

## Security
Never upload your API key or `.streamlit/secrets.toml` file to GitHub.

## Project Status
Core functionality implemented and tested.
