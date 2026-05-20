<h1 align="center">Slavko Mihajlovic</h1>
<h3 align="center">Senior AI Engineer & Software Architect</h3>
<p align="center"><em>Building production-grade AI infrastructure across C++, Python, and TypeScript.</em></p>

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-20-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
</p>

---

> C++ AI infrastructure engineer. Most work proprietary; two pieces public below.

### Featured Open-Source Projects

#### [omnidyon-raptor](https://github.com/omnidyon/omnidyon-raptor) — Hierarchical RAG · C++20

Standalone C++20 library implementing the [RAPTOR paper](https://arxiv.org/abs/2401.18059) — *Recursive Abstractive Processing for Tree-Organized Retrieval*. Traditional RAG retrieves isolated text chunks, limiting holistic understanding. RAPTOR recursively embeds, clusters, and summarizes chunks into a multi-level tree, then retrieves across all abstraction levels in a single query — granular detail and high-level summaries together.

Built on FAISS, libcurl, SQLite, and `std::`. Zero custom-utility dependencies.

#### [omnidyon-ralph](https://github.com/omnidyon/omnidyon-ralph) — Autonomous Agent Loops · C++20

Standalone C++20 library implementing RALPH — an autonomous development loop controller for AI agents. Three-state circuit breaker (Closed / HalfOpen / Open) prevents runaway loops. Intelligent exit detection requires both completion indicators and an explicit exit signal before stopping. Response classification across completion, questions, errors, and progress.

Agent-agnostic via consumer-implemented `ITaskRunner` — no dependencies on any specific agent harness. Reusable across any agent stack.

---

### Beyond the public work

These two libraries are pieces of a larger, proprietary AI infrastructure stack I've built in C++20 — covering orchestration, observability, evaluation, and supporting tooling. Architecture deep-dives available in technical interviews.

### Stack

`C++20` `Python` `TypeScript` · `CMake` `FAISS` `SQLite` · `FastAPI` `Pydantic` · `clang-tidy` `cppcheck` `Semgrep` · `GoogleTest` · `GCP/GKE`

---

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR-HANDLE">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>
