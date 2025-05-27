RAG pipeline using LangChain
A simple retrieval-augmented generation framework using LangChain.

For embeddings, I use the all-mpnet-base-v2 model from HuggingFace. For the knowledge base I use Chromadb, which is a vector management library. It is light weight and an easy alternative for vector databases (for small prototyping or dev projects). For the LLM, I use declare-lab/flan-alpaca-large* from HuggingFace.

To run:

Install requirements using
pip install -r requirements.txt

Create your knoweldge base by adding pdfs to the data folder.

Run the code using
python RAG.py
