# uptm-ai-gpu-server-poc
AI GPU Server PoC documentation for UPTM using Ubuntu Server, GPUStack, Docker/RKE2, Dell XE9680 and NVIDIA H200.
# UPTM AI GPU Server PoC

This repository contains documentation and reference information for the AI GPU Server Proof-of-Concept (PoC).

## Proposed Environment

- Ubuntu Server 24.04 LTS
- Dell PowerEdge XE9680
- NVIDIA H200 GPU
- GPUStack
- Docker / RKE2
- NVIDIA Driver
- NVIDIA Container Toolkit

## PoC Objectives

The PoC aims to validate:

- GPU readiness
- GPUStack model deployment
- LLM inference
- Concurrent user load
- Monitoring and benchmark report
- GPU / VRAM utilization
- Response time
- Throughput
- Error rate
- Recommended server capacity

## Proposed AI Services

- Ollama
- Open WebUI
- FastAPI
- Python
- vLLM
- ChromaDB / FAISS
- Pandas / Polars
- Other tools: LangChain, LlamaIndex, Locust/k6, Prometheus/Grafana

## Dataset Plan

| Dataset | Format | Size | Type |
|---|---|---:|---|
| Synthetic LLM Prompt Dataset | JSON / CSV | <1GB | Synthetic |
| Public QA Dataset | JSON / CSV | <1GB | Public |
| Public Document Dataset for RAG | PDF / TXT / Markdown | 1–5GB | Public |
| Public Image Dataset for Computer Vision | JPG / PNG | 1–10GB | Public / Synthetic |
| Benchmark Logs and Reports | CSV / JSON / HTML | <5GB | Generated |

## Notes

No personally identifiable information (PII), proprietary institutional data or sensitive data will be uploaded to the PoC environment.
