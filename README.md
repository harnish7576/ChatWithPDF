# ChatWithPDF - LLM Chat App

LLM Chat App is a chatbot application powered by the LangChain library and the OpenAI LLM (Language Model) model. It allows users to interact with a chatbot and ask questions about the content of a PDF file.

## Functionality

- Upload a PDF file and extract the text content from each page.
- Split the text into smaller chunks for efficient processing.
- Generate embeddings for the text chunks using OpenAIEmbeddings from LangChain.
- Create a vector store using FAISS for similarity search based on the embeddings.
- Enter questions or queries about the PDF content.
- Perform a similarity search in the vector store to find the most relevant text chunks.
- Utilize the OpenAI LLM model to run a question-answering chain on the selected documents and the user query.
- Display the response from the question-answering chain, containing answers to the user's questions based on the PDF content.
- Save and load functionality for the vector store to improve performance.

## PDF Architecture

![PDF Architecture](path/to/pdf/architecture/image.png)

## Flowchart

![Flowchart](path/to/flowchart/image.png)

## Getting Started

To run the LLM Chat App locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/llm-chat-app.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the app: `streamlit run app.py`

Make sure to replace `your-username` with your GitHub username in the repository URL.

## About

This app is built using Streamlit, a web application framework for Python, along with the LangChain library and the OpenAI LLM model. It demonstrates the capabilities of chatbots in understanding and answering questions based on the content of a PDF file.

For more information on Streamlit, LangChain, and OpenAI, refer to the following resources:

- Streamlit: [https://streamlit.io/](https://streamlit.io/)
- LangChain: [https://python.langchain.com/](https://python.langchain.com/)
- OpenAI: [https://platform.openai.com/docs/models](https://platform.openai.com/docs/models)

