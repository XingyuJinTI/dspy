# dspy RAG

RAG experiments with [DSPy](https://github.com/stanfordnlp/dspy), using the RAG-QA Arena "Tech" dataset.

## Setup

```bash
python -m venv dspy-venv
source dspy-venv/bin/activate  # or `dspy-venv\Scripts\activate` on Windows
pip install dspy-ai orjson requests
```

## Run

Open `rag.ipynb` and run the cells. The notebook downloads the dataset to `ragqa_arena_tech_examples.jsonl` in this directory if missing.
