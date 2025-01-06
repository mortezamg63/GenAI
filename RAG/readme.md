The first implementation, without openAI API, uses dolly-v2-3b model from huggingface website. This model does not provide a good quality embedding. I tried several queries from the chunks that were used for embedding and query was quiet relevent to the provided documents for chunking.
The faiss library was used to retrieve the relevant chunks, but the library was not able to find the relevant chunks, which shows the embedding is not good. 

For the next implementation, I will use openAI API to check the embedding quality and make the RAG system more accurate.
