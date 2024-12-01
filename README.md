# NLP-Term-Project

## Overview
This repository contains the code for Team 5's NLP Term Project. Our goal is developing the solar-1-mini-chat model to answer MMLU-Pro questions and inquiries about the regulations of Ewha Womans University.

![제목 없음](https://github.com/user-attachments/assets/40e8f5fb-f77f-475e-b236-b6114f4f2d29)

## Project Structure

```bash
NLP-Term-Project/
│
├── KB/
│   ├── Business-Introduction_to_Management-33-630.pdf
│   ├── ewha.pdf
│   ├── History-The_Past_in_Perspective.pdf
│   ├── Law-Contracts-Criminal_Procedure-Torts.pdf
│   ├── Philosophy-The_Elements_of_Moral_Philosophy-14-196.pdf
│   └── Psychology-Psychology-77-824.pdf
│
├── RAG_final.ipynb
└── testset.csv
```

## Download Files
You can download files for KB in [here](https://drive.google.com/drive/folders/1T5AQNJeV1h1Nt_Sxra0-m3qmAX9Kuzvh).

## APIs used
Our team used APIs from <a href="https://www.upstage.ai/">Upstage</a>

- `solar-1-mini-chat`
  - LLM of Upstage
- `embedding-passage`
  - Embedding model of Upstage
