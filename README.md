# Question_Answering_OpenAI


This repository contains a Python script that demonstrates a process of web scraping, text processing, and question answering using OpenAI's API. The script is designed to crawl a given website, extract text content, tokenize it, and then use OpenAI's language model to answer questions based on the extracted content.
How to Use

  #### Follow these steps to use the provided Python script for web scraping and question answering:

  ###### Install Dependencies: Make sure you have Python 3.x installed on your system. Install the required Python packages by running the following command:
     pip install requests beautifulsoup4 pandas tiktoken openai numpy
  ###### Configure Parameters: In the script, update the domain and full_url variables to specify the website domain you want to scrape and its starting URL. You can also adjust other parameters, such as max_tokens for text chunking and tokenization.
  ###### Run the Script: Execute the script by running the following command:
     python web_qa.py
  This will start the web scraping process, where the script will crawl through the specified domain, extract text content from web pages, and save the content to text files.
  ###### Question Answering: After the scraping is complete, the script will perform question answering based on the extracted text. Modify the question variable in the script to ask your desired question. The script will provide an answer based on the context it has extracted.
  ###### Review Results: The script will output the answer to the question you asked. You can also enable debugging to view raw model responses and perform further analysis.
