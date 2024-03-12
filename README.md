# Ask your PDF

A single-page web application built using Streamlit library in Python that allows the user to upload documents and chat with Google Gemini AI about the contents of the documents.

# Installation

To run this project, please follow the steps below:

1. Clone the repository:

```shell
git clone https://github.com/VigneshP-03/ask-your-pdf.git
cd ask-your-pdf
```

2. Create and activate a virtual environment (optional but recommended):

```shell
python3 -m venv venv
cd venv
Scripts\activate
cd ..
```

3. Install the dependencies from the `requirements.txt` file:

```shell
pip install -r requirements.txt
```

4. Create your unique Gemini API key from here: https://aistudio.google.com/app/apikey
5. Copy your API key and add it to GOOGLE_API_KEY in `.env` file

# Running the Project

Once you have installed the required libraries, you can run the project using Streamlit. Streamlit provides an easy way to create interactive web applications in Python.

To start the application, run the following command:

```shell
streamlit run app.py
```

This will start the Streamlit server and open the application in your default web browser.
