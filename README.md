# Information-Retrieval-Project

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NLP](https://img.shields.io/badge/NLP-Information%20Retrieval-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A sophisticated document retrieval system that combines traditional lexical search (BM25) with modern semantic search using transformer embeddings.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1_ZJIKqyyXv7vwjh1ywJSQ2P1Lmq49Vv3?usp=sharing#scrollTo=qy-emehWN4ZQ)

## Features

- **Hybrid Search**: Combines BM25 and neural embeddings for optimal retrieval
- **Semantic Understanding**: Uses pre-trained sentence transformers
- **Contextual Results**: Generates snippets with query term highlighting
- **Configurable Pipeline**: Customizable text processing and normalization
- **Scalable**: Designed to work with small to medium document collections

## Architecture

graph TD
    A[Documents] --> B[Preprocessing]
    B --> C[Lexical Index]
    B --> D[Semantic Embeddings]
    E[Query] --> F[Hybrid Retrieval]
    C --> F
    D --> F
    F --> G[Ranked Results]


## Live Demo
CHECK OUT HERE
https://colab.research.google.com/drive/1_ZJIKqyyXv7vwjh1ywJSQ2P1Lmq49Vv3?usp=sharing

Contributing
Contributions are welcome! Please open an issue or submit a pull request.

License
This project is licensed under the MIT License
