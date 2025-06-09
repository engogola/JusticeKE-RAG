# JusticeKE-RAG
JusticeKE-RAG Is a specialized AI assistant focused on providing legal information, specifically related to Kenyan law.

The system works by first attempting to find relevant answers within the documents provided, such as the Kenyan Constitution and the Supreme Court Act and rules. This is achieved by extracting text from these documents, dividing it into manageable chunks, and then using embedding models and a vector store (FAISS) to create a searchable database.

If the required information isn't sufficiently found within these local documents, JusticeKE is designed to expand its search to the web, specifically targeting reliable sources like the kenyalaw.org website for constitutional articles.

Finally, the retrieved information, whether from local documents or web searches, is used to construct a prompt for the Gemini language model, which then generates the final answer to the user's legal question. Therefore, JusticeKE represents the complete workflow and infrastructure you've set up in your Colab notebook to power this legal question-answering system.
