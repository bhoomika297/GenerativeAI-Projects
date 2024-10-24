##AI-Powered Applications using LLM Models
Welcome to my collection of AI-powered applications, each utilizing different large language models (LLMs) to provide unique and innovative solutions. This repository includes three key projects: a Blog Generation App, a Code Assistant Chatbot, and a Multi-Language Invoice Extractor, each built with FastAPI, Streamlit, and leading LLM models like LLaMA2, CodeLlama, and Google Gemini.

#Table of Contents
Project 1: Blog Generation App
Project 2: Code Assistant Chatbot
Project 3: Multi-Language Invoice Extractor
Tech Stack
How to Run the Projects
##Project 1: Blog Generation App
Overview:
This is an interactive blog generation tool that uses the LLaMA2 LLM model to assist users in generating high-quality blog content. Users can interact with the app through a chatbot interface, allowing them to brainstorm ideas, draft paragraphs, or get suggestions for their blogs.

#Key Features:
Interactive Chatbot: Users can interact with the app to generate blog content in real-time.
LLaMA2 Model: Leveraging the power of the LLaMA2 LLM for natural, coherent blog generation.
FastAPI Backend: The app’s core is powered by FastAPI to handle API requests efficiently.
Streamlit Frontend: A simple and interactive user interface for real-time chatbot interaction and blog generation.
##Project 2: Code Assistant Chatbot
Overview:
The Code Assistant Chatbot helps developers by providing coding solutions, debugging advice, and code snippets. It utilizes the CodeLlama model, which is fine-tuned for understanding and generating code-related queries.

#Key Features:
Code Generation: Generate code snippets based on user queries or programming needs.
Debugging Assistance: Users can get help with debugging errors or improving code efficiency.
FastAPI for Backend: API endpoints built using FastAPI handle code requests and model responses.
Streamlit UI: A user-friendly interface for developers to interact with the assistant chatbot and get real-time coding solutions.
##Project 3: Multi-Language Invoice Extractor
Overview:
The Multi-Language Invoice Extractor App is built using Google Gemini LLM, designed to extract key details (such as total amounts, dates, and invoice numbers) from invoices in various languages. This tool supports businesses by automating the process of invoice data extraction.

#Key Features:
Multi-Language Support: Capable of extracting data from invoices in multiple languages.
Google Gemini LLM: Leveraging Google's Gemini model for handling multi-language invoice text.
FastAPI Backend: Manages API requests to process invoice data.
Streamlit UI: Provides a simple interface for users to upload invoices and retrieve extracted data.
Tech Stack
The following technologies are used across all projects:

#FastAPI: For building high-performance backend APIs to interact with LLM models.
#Streamlit: To create interactive web interfaces where users can interact with the models in real-time.
#LLaMA2 / CodeLlama / Google Gemini: Cutting-edge language models used for natural language processing, code generation, and multi-language text extraction.
#Docker (optional): For containerization and deployment of the applications.
How to Run the Projects
#Prerequisites:
Python 3.8+: Make sure Python is installed.
FastAPI: Install FastAPI for backend APIs.
Streamlit: Install Streamlit for the frontend user interface.
LLM API Access: Ensure you have access to the required LLM models (LLaMA2, CodeLlama, Google Gemini).
Docker (optional): If you wish to containerize and deploy the applications.
Installation:
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
Install required packages:

bash
Copy code
pip install -r requirements.txt
Running the Projects:
For each project, navigate to its folder and start both the FastAPI backend and Streamlit frontend.
Start FastAPI Backend:

bash
Copy code
uvicorn app:app --reload
Start Streamlit Frontend:

bash
Copy code
streamlit run app.py
Access the application at http://localhost:8501 in your browser.

