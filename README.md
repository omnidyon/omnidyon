<h1 align="center">Slavko Mihajlovic</h1>
<h3 align="center">Senior AI Engineer & Software Architect</h3>
<p align="center"><em>Building production-grade AI infrastructure across C++, Python, and TypeScript.</em></p>

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-20-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
</p>

---

> I work at the layer most AI engineers don't touch: the orchestration, retrieval, and execution machinery that LLM APIs sit on top of. Not consuming AI tools — designing the platforms that run them.

### The omnidyon stack

```mermaid
graph TB
    subgraph apps["Applications"]
        Studio["OmniStudio<br/>Qt6 visual IDE for AI workflows"]
        Vantage["omnidyon-vantage<br/>Offline-first AI-native dev env"]
        Platform["omnidyon-platform<br/>TypeScript orchestration"]
    end

    subgraph chain["omnidyon-chain · LLM orchestration framework · C++20"]
        OmniChain["OmniChain<br/>140+ models · embeddings · RAG · agents"]
        OmniFlow["OmniFlow<br/>BSP/Pregel graphs · HITL · checkpointing"]
        OmniTrace["OmniTrace<br/>run trees · datasets · evaluation"]
        OmniCore["OmniCore · foundation<br/>Composable&lt;I,O&gt; · messages · HTTP · JSON"]
    end

    subgraph standalone["Standalone libraries · C++20"]
        Raptor["omnidyon-raptor<br/>Hierarchical RAG (RAPTOR paper)"]
        Ralph["omnidyon-ralph<br/>Autonomous agent loops"]
    end

    Studio --> OmniChain
    Studio --> OmniFlow
    Studio --> OmniTrace
    Platform --> OmniChain
    Vantage --> Raptor
    Vantage --> Ralph
    OmniChain --> OmniCore
    OmniFlow --> OmniCore
    OmniTrace --> OmniCore
