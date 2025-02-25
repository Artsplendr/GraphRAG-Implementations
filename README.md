# GraphRAG Implementations

The concept of **GraphRAG** was first introduced in the research paper titled **“From Local to Global: A Graph RAG Approach to Query-Focused Summarization”** by Darren Edge, Ha Trinh, Newman Cheng, Joshua Bradley, Alex Chao, Apurva Mody, Steven Truitt, Jonathan Larson, published in April 2024. The research paper is available at this [link](https://arxiv.org/abs/2404.16130?utm_source=chatgpt.com).

This paper addresses the limitations of traditional Retrieval-Augmented Generation (RAG) systems when handling global queries over extensive text corpora. The authors propose a novel approach that integrates large language models (LLMs) with graph-based text indexing to construct an entity knowledge graph from source documents. By generating community summaries for groups of related entities, the system can produce comprehensive and diverse responses to broad, sensemaking questions. Evaluations demonstrate that this Graph RAG method significantly outperforms baseline RAG models in both comprehensiveness and diversity of answers, particularly for large datasets.

This repository contains two notebooks:
**1-GraphRAG-with-LlamaIndex.ipynb**
The goal of this project is to reproduce tutorial "GraphRAG Implementation with LlamaIndex", which is available at at LlamaIndex.a at this [link.](https://docs.llamaindex.ai/en/stable/examples/cookbooks/GraphRAG_v1/)⭐

**2-GraphRAG-with-OpenAI-ScientificDataset**
The goal of this project is to experiment with a **Graph-based Retrieval-Augmented Generation (GraphRAG)** pipeline to analyze and query **scientific documents** from the dataset **GSAP-NER**, which consists of 100 manually annotated full-text scientific publications, focusing on machine learning models and datasets. This resource is valuable for extracting scholarly entities related to machine learning and available at [this link](https://arxiv.org/abs/2311.09860).

If you find this repository useful, light the star ⭐:)! 
