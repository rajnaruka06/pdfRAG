- This is a RAG system to answer user queries based on the context using MultiQuery and Rag Fusion architecture with LangChain.
- It Loads a book from PDF, splits it into chunks, hierarchically summarisez and stores it in Pinecone vectorstore.
- Utilizing multiquery to retrieve relevant documents and Rank Fusion to build the final context.
- The generation part uses custom memory, aiming to get accurate results from past (Query, Response) pairs along with the context from vectorstore.

TO-DO:
- Can use Contextual RAG