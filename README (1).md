# AI Engineering Reference

A single-page reference for LLM and agent engineering — foundations through production.

**Live:** enable GitHub Pages on this repo (Settings → Pages → deploy from `main`, root) and it will serve `index.html` automatically.

## Contents

**Foundations**
- Transformers — self-attention, scaled dot-product, multi-head, positional encoding, masking, the three architectures
- Context length and why it isn't n-grams
- LLM fundamentals — tokens, context windows, sampling, hallucination

**Training**
- Fine-tuning and PEFT — SFT, LoRA, QLoRA, adapters, prefix/prompt tuning, BitFit, DPO vs RLHF
- Training mechanics — mixed precision, gradient accumulation, LR scheduling, FSDP, DeepSpeed ZeRO
- Quantization and inference — GGUF, GPTQ, AWQ, KV cache, PagedAttention, Ollama vs vLLM

**Retrieval**
- RAG — parsing, chunking, embeddings, ANN search, reranking, hybrid search, HyDE, evaluation
- Vector databases — FAISS, Chroma, Qdrant, Pinecone, Weaviate, pgvector; indexing and filtering

**Agents**
- Agentic AI — the agent loop, tool calling, ReAct, planning patterns, context engineering, guardrails, evaluation
- MCP — the Model Context Protocol, including the 2026-07-28 stateless revision
- LangChain and LangGraph — chains, tools, memory, state graphs, checkpointers

**Production**
- System design — where latency goes, TTFT vs TPOT, reducing latency, quality trade-offs, failure handling, cost control, scaling, observability

**Applied**
- Computer vision and edge deployment — detection metrics, hard negatives, small-object detection, augmentation, TensorRT, ONNX
- Python and APIs
- Quick reference table

## Notes

Single self-contained HTML file. No build step, no dependencies beyond Google Fonts. Works offline apart from the font request.

Specifications and library APIs move quickly — verify version-specific details against current documentation before relying on them.
