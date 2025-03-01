## Features

* **PDF Contextual Question Answering:** Upload a PDF document and ask questions related to its content.
* **Gemini API Integration:** Uses the powerful Google Gemini API for natural language understanding and generation.
* **LangChain Framework:** Leverages LangChain for seamless integration of language models and data sources.
* **Vector Store (FAISS):** Efficiently stores and retrieves document embeddings for fast and accurate information retrieval.
* **Streamlit UI:** Provides a user-friendly web interface for interacting with the chatbot.
* **Environment Variable Management:** Uses `.env` for secure storage of API keys.

## Technologies Used

* **Streamlit:** For building the interactive web application.
* **Google Generative AI (Gemini API):** For language model capabilities.
* **LangChain:** For orchestrating language model interactions and data retrieval.
* **PyPDF2:** For extracting text from PDF documents.
* **FAISS (Facebook AI Similarity Search):** For efficient vector similarity search.
* **python-dotenv:** For managing environment variables.
* **langchain\_google\_genai:** For Langchain integration with Google Generative AI.
* **langchain-community:** For Langchain community tools.

## Prerequisites

* Python 3.8 or higher.
* Google Gemini API key.


## Installation

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/DevanshuSinghai/ContextualPDFChat.git](https://github.com/DevanshuSinghai/ContextualPDFChat.git)
    cd ContextualPDFChat
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python -m venv venv
    venv\Scripts\activate  # On Windows
    ```

3.  **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Set up your Google Gemini API key:**

    * Create a file named `.env` in the root directory of the project.
    * Add your Gemini API key to the `.env` file in the following format:

        ```
        GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY
        ```

    * Replace `YOUR_GOOGLE_API_KEY` with your actual API key.

## Usage

1.  **Run the Streamlit application:**

    ```bash
    streamlit run app.py
    ```

2.  **Interact with the chatbot:**

    * Open the Streamlit application in your web browser.
    * Upload a PDF document using the file uploader.
    * Ask questions related to the content of the PDF in the text input area.
    * The chatbot will provide answers based on the PDF context.
