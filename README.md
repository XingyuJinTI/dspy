# dspy RAG

RAG experiments with [DSPy](https://github.com/stanfordnlp/dspy), using the RAG-QA Arena "Tech" dataset.

## Setup

```bash
python -m venv dspy-venv
source dspy-venv/bin/activate  # or `dspy-venv\Scripts\activate` on Windows
pip install dspy-ai orjson requests
```

## Run

- **`dspy-rag.ipynb`** — RAG pipeline; downloads the dataset to `ragqa_arena_tech_examples.jsonl` if missing.
- **`eval.ipynb`** — Evaluation and optimization.

## Next steps

1) Look into STORM pipeline built in DSPy
2) Explore different prompt optimiser
3) Cut cost by distilling to a smaller LM
4) other useful links [RAG](https://dspy.ai/tutorials/rag/), [RAG-Agent](https://dspy.ai/tutorials/agents/), [DSPy-Agent](https://dspy.ai/tutorials/customer_service_agent/) 