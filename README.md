# Langchain PDF ChatBot

This project offers an immersive experience allowing users to engage in insightful conversations with multiple PDF documents. Through natural language queries, users can extract relevant information as the application harnesses a powerful language model, ensuring accurate and tailored responses. It is imperative to note that the project exclusively addresses inquiries related to the loaded PDFs.

## Features:

1. **PDF Loading:** Capability to read and process multiple PDF documents.
2. **Text Chunking:** Efficient division of extracted text into manageable chunks for processing.
3. **Language Model Integration:** Utilization of a language model for generating vector representations of text chunks.
4. **Similarity Matching:** Comparison of user questions with text chunks to identify semantically similar content.
5. **Response Generation:** Selection of relevant text chunks passed to the language model to generate accurate responses based on PDF content.

## Features of  Large Language Models:

Large Language Models (LLMs) are sophisticated natural language processing models known for their ability to handle complex language tasks. Here are the main features of LLMs:

1. **Scale:** LLMs are trained on massive datasets, often containing billions or even trillions of words. This extensive training allows them to capture intricate language patterns and nuances.
2. **Contextual Understanding:** LLMs have a deep understanding of context in language. They can comprehend the meaning of a word based on the words that surround it in a sentence or a document, leading to more accurate and contextually relevant responses.
3. **Pre-trained Representations:** LLMs learn to represent words, phrases, and sentences as high-dimensional vectors. These vector representations capture semantic relationships between words and enable various language-related tasks.
4. **Transfer Learning:** LLMs can be fine-tuned or adapted to specific tasks or domains with comparatively smaller datasets. This makes them versatile and applicable to a wide range of applications without the need for extensive retraining.
5. **Language Generation:** LLMs can generate coherent and contextually relevant text. They can be used to create human-like text, making them valuable for tasks like chatbots, content creation, and dialogue systems.
6. **Multimodal Capabilities:** Some advanced LLMs are designed to handle both textual and visual data, allowing them to understand and generate text based on images or other non-textual inputs.
7. **Handling Ambiguity:** LLMs can deal with ambiguous language constructs, understanding different interpretations based on the context. This ability is essential for tasks like machine translation and question-answering systems.
8. **Broad Applicability:** LLMs are used in a variety of applications, including machine translation, question-answering, sentiment analysis, chatbots, content creation, and more. Their versatility makes them a cornerstone of modern natural language processing.

## Installation:

1. Clone the repository:
    
    ```
    git clone https://github.com/gxutxm/Langchain-PDF-ChatBot
    ```
    
2. Install the required dependencies:
    
    `pip install -r requirements.txt`
    

## Usage:

1. Open the terminal and navigate to the project directory.
2. Run the functionality that you would like to perform. For example,
    
    ```
    streamlit run app.py
    ```
    
3. Click on the IP address from the terminal and feed in PDFs to query about them

project_name/
│
├── .gitignore                  # Git ignore file to specify files/folders to be ignored by Git
├── [README.md](http://readme.md/)                   # Project documentation
├── WALL-E.jpg                  # Image file(s) used in the project
├── [app.py](http://app.py/)                      # Main application file
├── [htmlTemplates.py](http://htmltemplates.py/)            # Module for HTML templates (if your project involves web interfaces)
└── requirements.txt            # Python dependencies required for the project

## Result:

## Project Structure:

```
project_name/
│
├── .gitignore                  # Git ignore file to specify files/folders to be ignored by Git
├── README.md                   # Project documentation
├── WALL-E.jpg                  # Image file(s) used in the project
├── app.py                      # Main application file
├── htmlTemplates.py            # Module for HTML templates (if your project involves web interfaces)
└── requirements.txt            # Python dependencies required for the project
```
