### AI Infrastructure & Distributed Systems Engineer

Building low-latency local/distributed LLM inference pipelines, eBPF kernel telemetry engines, and self-healing JVM & Python backends.

#### Featured Systems & Benchmarks

- **[Sentinel Ops](https://github.com/sium-java-developer/sentinel-ops-benchmarks)** — Air-gapped edge telemetry FinOps & runtime threat defense platform (`Java 25 Virtual Threads`, `eBPF`, `Spring AI`, `Ollama / vLLM`, `OpenTelemetry`, `Redis`).
  - **Cost & Egress Reduction:** Cut cloud log ingestion payloads by **~70%** (from ~120 MB/min to ~36 MB/min at 1,000 traces/sec) via Redis semantic caching.
  - **Inference Optimization:** Achieved **3.5x faster local Qwen-2.5-3B inference** (~240ms TTFT, 38.8 tok/s) and **67.6% lower RAM footprint** using GGUF `Q4_K_M` quantization and CPU thread pinning.
  - **Cloud-Native Packaging:** Published as a multi-service OCI Helm chart (`oci://registry-1.docker.io/siumsentinelops/sentinel-ops`).

- **[Sentinel Thread](https://github.com/sium-java-developer/sentinel-thread-spec)** — Event-driven autonomous observability and self-healing architecture (`Java 25/26`, `Spring Modulith`, `LangChain4j`, `PostgreSQL / pgvector`) designed for deterministic root-cause triage and automated remediation.

#### Technical Stack

| Domain | Technologies |
| :--- | :--- |
| **AI Inference & GPU Compute** | Python, PyTorch, CUDA, vLLM, llama.cpp, Ollama, GGUF/AWQ Quantization, Spring AI, LangChain4j, RAG (`pgvector`) |
| **Systems & Observability** | Linux eBPF, OpenTelemetry, Prometheus, Grafana, Hazelcast, Redis Semantic Caching |
| **Backend & Frontend** | Java 21/25/26 (Virtual Threads, Project Panama), Spring Boot, Spring Modulith, Apache Kafka, PostgreSQL, TypeScript, React |
| **Cloud & Orchestration** | Kubernetes, Helm (OCI), Docker, Terraform, AWS, GCP |

---
📫 **Connect:** [LinkedIn](https://www.linkedin.com/in/samiul-alom-sium-47123b331) • [X (@samiul_sium)](https://x.com/samiul_sium) • **Open to Remote US AI Infrastructure / AI Systems Engineering Roles**
