# GenAI-experiments
## Exploring LLMs, RAG systems, Fine Tuning and more ....

## 🔍 Evaluating LLM and RAG Systems
As LLMs and Retrieval-Augmented Generation (RAG) systems gain traction in real-world applications, robust evaluation is essential to ensure generated outputs are  relevant, faithful, and correct .

I explored comprehensive evaluation approaches for LLM + RAG systems

✅ Automated Metrics for Answer Quality
BERTScore, ROUGE, BLEU

🧑⚖️ LLM as a Judge: G-Eval
the idea is to use another LLM ( usually a smaller model ) to evaluate correctness and relevance of outputs. 

📚 Retrieval Component Metrics for RAG
Precision@k ( the fraction of top-k results that are actually relevant. Focuses on accuracy of top-ranked dos, not coverage)
Recall@k (Measures if the correct/relevant document appears in the top-k retrieved results)

🧪 Benchmark Datasets
MS MARCO is one of the most widely used datasets as a benchmark to provide ground-truth answers for evaluating the performance of question answering system.

