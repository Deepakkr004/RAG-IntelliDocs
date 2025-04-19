# RAG-IntelliDocs

**RAG-IntelliDocs** is a cutting-edge, intelligent document analysis tool that leverages Retriever-Augmented Generation (RAG) technology for generating context-driven answers from your PDFs. Using advanced machine learning models (LLaMA, Chroma, and LlamaParse), this tool can analyze any uploaded PDF and provide insightful answers based on the document’s content.


## Colab Link

To run this project in Google Colab, click the link below and get started quickly with the notebook version of **RAG-IntelliDocs**:

🔗 [**Launch in Google Colab**](https://colab.research.google.com/drive/1Thkv5E4iYrnpbxZ6Mw0-wuMIhWp6Kw55?usp=sharing)

> ⚠️ **Note:** To use the LlamaIndex API, sign in and generate your API key at:

🔑 [**LlamaIndex Cloud Portal**](https://cloud.llamaindex.ai/login)


## Features

- **Contextual Querying:** Ask specific questions about your documents and receive precise answers derived from the text.
- **Powered by LLaMA + Chroma + LlamaParse:** Seamlessly integrates powerful language models and vector databases for efficient search and generation.
- **Easy PDF Upload:** Simply upload a PDF and start querying it right away.
- **Smart Answer Generation:** Generate human-like responses based on document context using state-of-the-art RAG techniques.

## Installation

To run the application locally, follow these steps:

### Prerequisites

- Python 3.7+
- Install necessary libraries via `pip`.

### Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/Deepakkr004/RAG-IntelliDocs.git
    cd RAG-IntelliDocs
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate   # For Windows, use `venv\Scripts\activate`
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. (Optional) If using any pre-trained models for LLaMA, Chroma, or LlamaParse, ensure you have the correct access tokens or credentials.

## Usage

1. Run the application:
    ```bash
    python app.py
    ```

2. Open your browser and navigate to the displayed URL (usually `http://localhost:7860`).

3. Upload a PDF and enter your query to start analyzing the document.

## How It Works

- **LLaMA:** A powerful language model that understands and processes natural language.
- **Chroma:** A vector database that stores document embeddings, enabling fast and efficient similarity search.
- **LlamaParse:** A tool for parsing PDFs, converting them into a structured format suitable for question answering.

When you upload a PDF, the tool first extracts text from it. The extracted text is then embedded into vector space using Chroma. When you ask a question, the system retrieves the most relevant chunks and uses LLaMA to generate an accurate, context-driven response.

## Contributing

We welcome contributions to improve **RAG-IntelliDocs**!

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -am 'Add new feature'
    ```
4. Push to your branch:
    ```bash
    git push origin feature-name
    ```
5. Open a Pull Request.

Please ensure to follow best practices for code quality and add tests where applicable.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
