Developed an offline, secure, and embeddable Language Model (LLM) using the Langchain framework. Users have the ability to upload personal documents and inquire about them, all of which takes place locally.

The Langchain framework is utilized in this system. The Sentence Transformers model was employed to create embeddings, and the FAISS vector database was used for storing these. The Mistral 7b instruction LLM model was chosen, as it outperforms Llama2 in various benchmarks.

When a user submits a query, the system performs a similarity search within the vector database. It retrieves relevant chunks, generates an output, and provides context to the documents and the input.
