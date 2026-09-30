# DocuSense AI — Changelog

## [1.0.0] — 2026-09-30

### Added
- Full DocuSense AI rebrand across all modules and UI
- Hybrid retrieval pipeline (vector + BM25 + Reciprocal Rank Fusion)
- LangGraph agentic pipeline: validate → retrieve → generate → format
- Built-in web UI with live pipeline view and document upload
- Public-demo cost controls (per-visitor rate limits + global cap)
- Bring-your-own-key (BYOK) support
- Self-seeding GDPR demo corpus on startup
- LangSmith tracing integration (per-node latency + token cost)
- Prometheus `/metrics` endpoint (latency histograms + retrieval quality)
- Evaluation suite: LangSmith dashboard + Ragas offline cross-check
- 25 hermetic tests (no API keys required)
- Dockerized deployment on Google Cloud Run
- Keyless CI/CD via GitHub Actions + Workload Identity Federation
