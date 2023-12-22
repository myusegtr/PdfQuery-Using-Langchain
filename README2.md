## Question Answering using Langchain & AstraDB

### Overview
To get this demo running, you'll need to have a Serverless Cassandra database with Vector Search enabled, set up on Astra DB. Obtain a DB token with Database Administrator permissions, and grab your Database ID - you'll need these to connect.

Link to Astra DB:-https://www.datastax.com/products/datastax-astra

Additionally, an OpenAI API key is required for the natural language features.

With those prerequisites met, you can then import the code dependencies, configure your credentials, initialize the LangChain vector indexer, and start the question-answering loop. This will retrieve relevant headlines from the database using vector search, and leverage the LLM to generate answers in natural language.

The key steps are establishing the database connection, providing API keys, setting up LangChain, and implementing the QA loop to find pertinent passages and produce responses.

### Aim of the project
To create a natural language question answering system powered by a vector search database and large language model. The system will ingest text data, index it for semantic search, and generate answers to user questions by retrieving relevant passages from the database and contextualizing them into coherent responses. The goal is seamless question answering with personalized answers constructed leveraging AI.

### Libraries

Libraries used are:-

Langchain
openAI
datasets
cassio
pdfminer

### Steps
1. Importing the libraries.
2. Connect with AstraDB database
3. Building llm & embeddings
4. Creating the vector storage db
5. Loading the dataset in the vector store
6. Asking querires

### Files used

The pdf file I have used here is 'Global Air pollution report(soga_report_2019.pdf)".