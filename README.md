Overview

![Screenshot 2024-09-01 at 11 25 02 PM](https://github.com/user-attachments/assets/01e460c0-0fd9-4ed6-9f7c-70d6af8bc380)


The primary objective of this project is to create a flexible and robust RAG pipeline that can:

Retrieve and Rank Relevant Information: Utilize Pinecone's hybrid search to retrieve relevant documents based on both dense (vector embeddings) and sparse (BM25) representations.
Generate Detailed Responses: Leverage the LLaMA 2 model to generate natural language responses that are accurate, informative, and contextually rich.
Handle Unrelated Queries: Gracefully manage unrelated or out-of-scope queries by providing appropriate responses.
Provide Contextual Explanations: When queried about specific entities (e.g., cities, years), the system offers detailed explanations and relevant historical context.
Key Features

Hybrid Search: Combines dense vector embeddings with sparse BM25 representations to improve search relevance.
Context-Aware Generation: LLaMA 2 model generates detailed answers based on the most relevant retrieved documents.
Flexibility: The prompt function is designed to adapt to various types of questions, including those outside the expected scope.
Entity Explanation: Automatically provides detailed explanations for recognized entities, enhancing the user experience.
