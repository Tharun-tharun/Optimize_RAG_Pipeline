# Using Evaluations to Optimize a RAG Pipeline: from Chunkings and Embeddings to LLMs

Retrieval Augmented Generation (RAG) is a useful technique for using your own data in an AI-powered Chatbot. In this blog post, I’ll walk through three key strategies to get the most out of RAG and evaluate each strategy to find the best combinations.

* 89% Improvement by changing the Chunking Strategy 📦
* 20% Improvement by changing the Embedding Model 🤖
* 6% Improvement by changing the LLM Model 🧪

## Let’s dive into each strategy and find the best-performers for a real-world RAG application using RAG component evaluations! 🚀📚

1. Text Chunking Strategies
2. Embedding Models
3. LLM (Generative) Models

`1. Text Chunking Strategies` 📦

Text chunking is like cutting a long story into smaller, bite-sized pieces so a computer can easily find and use the most important parts when answering questions or helping with tasks.

Chunking helps your Vector Database retrieve the most relevant information quickly and accurately.

Below, I’ll try a few different chunking techniques which are explained in-depth in this original article by Greg Kamradt.

    * Recursive Character Text Splitting
    * Small-to-Big Text Splitting
    * Semantic Text Splitting

`2. Different Embedding Models` 🤖

All the chunking methods above used the Embedding model available on HuggingFace BAAI/bge-large-en-v1.5 (with embedding-dim = 1024).

`3. Different LLMs (or Generative Models)` 🧪

Next, I tried six different LLM API endpoints and evaluated the same way as before.

## Evaluate

Iterating on these RAG components can help optimize your RAG pipeline! RAG pipeline evaluation results will vary depending on your particular data and use case. 🛠️
