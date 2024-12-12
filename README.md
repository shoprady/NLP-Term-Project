# NLP-Term-Project

## Overview
This repository contains the code for Team 5's NLP Term Project. Our goal is developing the solar-1-mini-chat model to answer MMLU-Pro questions and inquiries about the regulations of Ewha Womans University.

![image](https://github.com/user-attachments/assets/6efc82e1-d054-4f17-b0c4-71edfe661590)

## Project Structure

```bash
NLP-Term-Project/
│
├── KB/
│   ├── business/
│   ├── ewha/
│   ├── history/
│   ├── law/
│   ├── philosophy/
│   └── psychology/
│
├── RAG_final.ipynb
└── testset.csv
```

## APIs used
We used APIs from <a href="https://www.upstage.ai/">Upstage</a>.

- `solar-1-mini-chat`
  - LLM of Upstage
- `embedding-passage`
  - Embedding model of Upstage
