# 🗄️ AI Vector DB

AI向量数据库工具，支持向量存储、检索、索引。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🏗️ 向量数据库设计
- 🔵 ChromaDB配置生成
- 🌲 Pinecone配置生成
- 🔀 混合搜索设计
- 🔎 RAG管道生成
- ⚡ 向量搜索优化

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_vector_db import create_tools

tools = create_tools()

# 向量数据库设计
db = tools.design_vector_db("RAG应用", "中型")

# ChromaDB配置
chroma = tools.generate_chroma_config("知识库", documents)

# Pinecone配置
pinecone = tools.generate_pinecone_config("索引", 1536)

# 混合搜索
hybrid = tools.design_hybrid_search("电商")

# RAG管道
rag = tools.generate_rag_pipeline("知识库", "GPT-4")

# 搜索优化
optimized = tools.optimize_vector_search(config, metrics)

# 数据库比较
comparison = tools.compare_vector_databases(["高性能", "低成本"])
```

## 📁 项目结构

```
ai-vector-db/
├── tools.py       # 向量数据库工具核心
└── README.md
```

## 📄 许可证

MIT License
