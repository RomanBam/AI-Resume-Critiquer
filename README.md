# AI Resume Critiquer

AI Resume Critiquer is a web application that allows users to upload their resume (PDF or TXT) and receive a detailed, AI-powered critique. The app leverages OpenAI's GPT models to provide feedback on content clarity, skills presentation, experience descriptions, and tailored suggestions for improvement.

## Features
- Upload your resume in PDF or TXT format
- Specify a job role for targeted feedback (optional)
- Receive structured, actionable feedback from an AI trained in HR best practices

## Requirements
- Python 3.13+
- [uv](https://github.com/astral-sh/uv) (for dependency management)
- An OpenAI API key ([get one here](https://platform.openai.com/account/api-keys))

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RomanBam/AI-Resume-Critiquer.git
   cd AI-Resume-Critiquer
   ```

2. **Install dependencies using uv:**
   ```bash
   uv pip install -r pyproject.toml
   ```

3. **Set up environment variables:**
   - Create a `.env` file in the project root with the following content:
     ```env
     OPENAI_API_KEY=your_openai_api_key_here
     ```

## Running the App

Start the Streamlit app with uv:

```bash
uv pip install streamlit  # (if not already installed)
streamlit run main.py
```

The app will open in your browser. Upload your resume and receive instant feedback!
