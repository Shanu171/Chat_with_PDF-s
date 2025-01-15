# CHAT with PDFs

CHAT with PDFs is an innovative application that allows users to upload multiple PDF documents and ask questions related to the content of those PDFs. The app leverages the power of Google Gemini and Streamlit to provide accurate and fast responses, making it a great tool for research, education, and professional use.

## Features

Multiple PDF Uploads: Upload and manage multiple PDF files.

Interactive Q&A: Ask questions related to the content of the uploaded PDFs and get precise answers.

Seamless User Experience: Built using Streamlit for an intuitive and responsive interface.

Advanced Language Understanding: Powered by Google Gemini for state-of-the-art natural language processing.

Getting Started

Prerequisites

Ensure you have the following installed on your system:

Python 3.10 

pip (Python package installer)

Streamlit

Required API keys for Google Gemini

Installation

Clone the repository:

git clone https://github.com/yourusername/chat-with-pdfs.git
cd chat-with-pdfs

Create a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

Install dependencies:

pip install -r requirements.txt

Set up environment variables:
Create a .env file in the root directory with the following:

GOOGLE_GEMINI_API_KEY=your_api_key

Running the Application

Start the Streamlit app:

streamlit run app.py

Open your browser and go to http://localhost:8501 to use the app.

Usage

Upload one or more PDF files using the file uploader in the app.

Enter your questions in the provided text box.

View the answers generated based on the uploaded PDFs.

File Structure

chat-with-pdfs/
├── app.py              # Main application file
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
├── .env                # Environment variables
└── assets/             # Optional folder for additional resources (e.g., images)

Dependencies

Streamlit: For building the web application interface

Google Gemini API: For natural language processing and question answering

PyPDF2 or similar library: For handling PDF files

Contributing

Contributions are welcome! If you'd like to contribute, please:

Fork the repository.

Create a feature branch:

git checkout -b feature-name

Commit your changes:

git commit -m 'Add some feature'

Push to the branch:

git push origin feature-name

Open a pull request.

