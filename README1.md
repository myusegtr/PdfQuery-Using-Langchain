## PDF query using Langchain

### Overview
This is a small Generative AI project to extract text from pdf & answer questions based on that.
Here LLM is being used & the system is able to understand unstructured document(pdfs) & generates natural language responses.

### Aim of the project
The end goal is a human-like conversational experience by creating a virtual assistant which can read & understand pdfs to answer user's query.

### Libraries

Libraries used are:-

Langchain
openAI
FAISS
PdfMiner

### Steps

The whole project is implemented using Google Colab.
Steps involved:-

1. Importing relevant libraries
2. Setting up environment for OpenAI api key.
3. Loading the pdf file.
4. Next is to split the whole text into various chunks to overcome the OpenAI's token limit issue.
5. Using embeddings from openAI to store the vector representation of those chunks into some kind of vectorstores such as FAISS(index) in this project.
6. Then importing the load_qa_chain to create chains for the user query to run.

### Files used

The pdf file I have used here is 'Global Air pollution report(soga_report_2019.pdf)".
