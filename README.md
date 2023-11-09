# ConversationalAI - CTCxPenseum

This repository contains code for processing a PDF document, splitting it into chunks, embedding the content into vectors, and performing question-answering tasks using ChatGPT and vector similarity search. It's designed to help you efficiently extract information from large PDF documents and answer questions about their contents.

Created for Hack the Change 2023 Hosted by [Code the Change YYC](https://www.codethechangeyyc.ca/).
## Overview

In today's data-rich world, extracting valuable information from lengthy documents can be a time-consuming task. This project streamlines the process by using state-of-the-art tools and libraries to:

1. **Load PDF Documents**: The code starts by loading a PDF document, making it accessible for further processing.

2. **Text Chunking**: The document is divided into smaller text chunks, making it more manageable for analysis and embedding.

3. **Embedding Content**: The content is embedded into high-dimensional vectors, allowing for efficient similarity-based searches, and stored in FAISS.

4. **Vector Store Similarity Search**: You can perform similarity searches on the document's content using a vector store, enabling quick retrieval of relevant information based on queries.

5. **Question-Answering with ChatGPT**: The system utilizes ChatGPT, a powerful language model, to answer questions about the document's content. It combines the strengths of natural language understanding and vector similarity search to provide accurate responses.

6. **Building Sophisticated Prompts**: You can create custom prompts to elicit specific information from the document. This feature enhances the precision of the question-answering process.

7. **Conversational Retrieval**: The code also supports conversational retrieval, allowing you to have back-and-forth conversations with the system to explore document content further.

## Getting Started

To get started with this code, follow these steps:

1. Go to `starer_code/hack_the_change.ipynb` and click on open in Colab.

2. Go to File -> Save a copy in Drive, and open that.

3. Ensure you have the necessary API keys in you are using this code after Nov. 13/2023, as we will be deactivating the provided API Key.

4. Load your PDF document by replacing `"data/react-beginners-handbook.pdf"` with the path to your PDF file.
   - Go to files in the left sidebar and create your own folder and upload your document there.

6. Customize your prompts and questions to extract the information you need.

7. Run the code and explore the responses and information extracted from the document.

## Presentation

For a detailed presentation on how this code works and more information about GenAI and RAG (Retrieval Augmentation Generation), please refer to our [Slide Deck](link-to-slide-deck) that provides a comprehensive overview.

## Acknowledgments

This project leverages several libraries and APIs to make PDF document processing and question-answering efficient and accessible. We would like to acknowledge the contributions of the open-source community and the creators of the tools used in this project.
