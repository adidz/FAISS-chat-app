# FAISS-chat-app


This project is a Streamlit-based application that allows users to interact with multiple PDF documents through a conversational interface. By leveraging the power of PyPDF2, Langchain, FAISS, and Google Generative AI, users can upload PDFs, ask questions, and receive contextually accurate answers.

Features
Extracts text from multiple PDF documents.
Splits large texts into manageable chunks for processing.
Generates vector embeddings for efficient similarity searches.
Utilizes Google Generative AI for natural language question-answering.
Installation
Clone the repository:

bash
Copy code
git clone 
cd chat-with-pdfs
Create a virtual environment:

bash
Copy code
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Set up environment variables:
Create a .env file in the root directory of the project and add your Google API key:

env
Copy code
GOOGLE_API_KEY=your_google_api_key_here
Usage
Run the Streamlit application:

bash
Copy code
streamlit run app.py
Upload PDFs and ask questions:

Use the sidebar to upload multiple PDF documents.
Type your question in the input box provided.
Click "Submit and Process" to process the PDFs.
Ask your question and get responses based on the content of the uploaded PDFs.
