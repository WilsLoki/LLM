## 大模型探索

### Fine_Tuning_LoRA.ipynb
结合stanfordnlp/imdb数据集，采用 LoRA 对 DistilBERT 模型进行微调，推动电影评论情感分类任务的准确率从 50%（基本随机）提升至 89.5%，并将优化后的模型部署到Hugging Face Hub；
微调后的模型：https://huggingface.co/WillLoki/distilbert-base-uncased-lora-text-classification

### RAG.ipynb
基于LangChain框架和文心一言大模型（ERNIE-Speed-128K）构建RAG智能问答系统，实现对自定义知识库的高效语义理解与精准问答；
