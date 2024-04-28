# cs6360-project10

## Dataset
For vector database:
- [SIFT](http://corpus-texmex.irisa.fr/)
- [DEEP](https://research.yandex.com/blog/benchmarks-for-billion-scale-similarity-search)

For RAG Chatbot:
- [Bible text](https://www.kaggle.com/datasets/oswinrh/bible)
- [Quaran text](https://www.kaggle.com/datasets/zusmani/the-holy-quran?select=English.csv)

## Software and Tools
- [Zilliz Cloud](http://cloud.zilliz.com/) for MANU type database management
- [VectorDBBench](https://docs.zilliz.com/docs/perf-benchmark-vectordb#:~:text=Procedures%201%20Set%20up%20testing%20environment%202%20Install,benchmarking%20results.%20Below%20are%20some%20example%20results.%20) for performance metrics
- [LangChain](https://milvus.io/docs/integrate_with_langchain.md) for establishing the connection between chatbot and vector database
- OpenAI for creating text embeddings, which allows the conversion of datasets into vectors
- Run and tested on Google Colab 
