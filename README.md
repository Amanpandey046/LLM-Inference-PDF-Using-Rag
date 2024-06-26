# LLM-Inference-PDF-Using-Rag

# Description
This Python script enables users to query financial statements using a combination of Large Language Models (LLM) and Retrieval Models. It processes PDF files containing financial data and generates responses based on user queries.

# Installation
1. Clone the repository:
```
bash
Copy code
https://github.com/Amanpandey046/LLM-Inference-PDF-Using-Rag.git
```
2. Install dependencies:
```
bash
Copy code
pip install -r requirements.txt
```
3. Download pre-trained models:
* Mistral-7B-Instruct  model from https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.1-GGUF/blob/main/mistral-7b-instruct-v0.1.Q8_0.gguf
* Sentence Transformer model: sentence-transformers/all-mpnet-base-v2
  

# Code Structure
* query_financial_statements.py: Main script for querying financial statements.
* llama_cpp.py: Wrapper for LLM model using llama_cpp library.
* utils.py: Utility functions for text chunking, prompt generation, and answer generation.
  
# Configuration
* pdf_dir_path: Directory path containing PDF files with financial statements.
* retriever_model_name: Name of the Sentence Transformer model used for text retrieval.
* max_tokens: Maximum tokens allowed per chunk for LLM processing.
  
# Examples
* Query: "Show me the table of FIXED ASSETS as at 31 March 2022."
* Output: Displays the relevant information from the financial statement.
  
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any inquiries or issues, please contact https://www.linkedin.com/in/aman-pandey-60128520a/.
