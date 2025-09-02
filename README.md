
# Metal_OCR Project


This project is built using the **Streamlit** framework for the frontend and uses the **Gemini 2.5 Flash API** along with **LangChain** libraries to detect bike frame numbers from images.
---
---------------------------------
   Steps to Set Up and Run the Project
---------------------------------

Step 1 — Download and Extract the Project
---------------------------------
- Download the Metal_OCR project files.
- Extract the ZIP file to any folder on your computer.

Step 2 — Create and Activate a Virtual Environment
---------------------------------
Open **Command Prompt** or **Terminal** inside the project folder and run:

    python -m venv venv

Activate the virtual environment:

    On Windows:
        venv\Scripts\activate

    On Mac/Linux:
        source venv/bin/activate

Step 3 — Install Project Dependencies
---------------------------------
    pip install -r requirements.txt

Step 4 — Generate Your Own Gemini API Key
---------------------------------
1. Go to: https://aistudio.google.com/app/apikey
2. Sign in with your Google account.
3. Click **Create API Key**.
4. Copy the generated API key.

Step 5 — Create a `.env` File
---------------------------------
Inside the project folder, create a file named **.env** and add:

    GOOGLE_API_KEY=your_generated_api_key_here

*(Replace `your_generated_api_key_here` with the key you generated.)*

Step 6 — Run the Project
---------------------------------
Since this is a **Streamlit** app, run:

    streamlit run app.py

*(If your main file has a different name, replace `app.py` with your main file name, e.g., `detection_code.py`.)*

Step 7 — Open the App
---------------------------------
- After running the above command, Streamlit will give you a **local URL**.
- Open that link in your browser to use the app.

---------------------------------
   Project Dependencies
---------------------------------
- Python 3.10+
- Streamlit
- LangChain
- Google Generative AI (Gemini 2.5 Flash)
- dotenv
- Pydantic
- Base64
- OS libraries

---------------------------------
   Author
---------------------------------
Developed during internship at **Atlas Honda**
