# 🧠 Awesome LLM Landscape

<p align="center">
  <b>English</b> ・ <a href="README.zh-CN.md">简体中文</a>
</p>

<p align="center">
  <a href="https://github.com/HoobenWang/awesome-llm-landscape/stargazers"><img src="https://img.shields.io/github/stars/HoobenWang/awesome-llm-landscape?style=social" alt="stars"></a>
  <a href="https://github.com/HoobenWang/awesome-llm-landscape/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="license"></a>
  <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome"></a>
  <img src="https://img.shields.io/badge/last_updated-2026--11-orange.svg" alt="last updated">
</p>

<p align="center">
A mind-map style, logo-illustrated guide to today's mainstream Large Language Models — who makes them, what they're good at, and how they relate to each other.
</p>

<p align="center">
  🌐 <a href="https://hoobenwang.github.io/awesome-llm-landscape/"><b>Live interactive mind map (GitHub Pages)</b></a>
</p>

Most "awesome LLM" lists are long, flat bullet dumps. This one is organized as a **mind map** first, so you can see the shape of the landscape at a glance, then drill into tables with **logos** for fast visual recognition, plus links to benchmarks and real-world applications.

> Inspired by [uhub/awesome-llm](https://github.com/uhub/awesome-llm), [hannibal046/Awesome-LLM](https://github.com/hannibal046/Awesome-LLM), [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps), and [Awesome-LLM-Evaluation](https://alopatenko.github.io/LLMEvaluation/).

## Contents

- [🗺️ Mind Map Overview](#️-mind-map-overview)
- [🏢 Proprietary (Closed-Weight) Models](#-proprietary-closed-weight-models)
- [🧩 Open-Weight Models](#-open-weight-models)
- [🇨🇳 Chinese LLM Ecosystem](#-chinese-llm-ecosystem)
- [🖼️ Multimodal Models](#️-multimodal-models)
- [🛠️ Build With LLMs](#️-build-with-llms)
- [📊 Evaluation & Benchmarks](#-evaluation--benchmarks)
- [🔗 Related Awesome Lists](#-related-awesome-lists)
- [🤝 Contributing](#-contributing)

---

## 🗺️ Mind Map Overview

```mermaid
mindmap
  root((LLM Landscape))
    🏢 Proprietary
      🇺🇸 US
        OpenAI
        Anthropic
        Google DeepMind
        xAI
        Amazon
        Microsoft
      🇨🇳 China
        Baidu ERNIE
        Doubao / ByteDance
        Tencent Hunyuan
        SenseTime
        iFlytek Spark
        MiniMax
      🌏 Other Asia
        Naver HyperCLOVA X
    🧩 Open-Weight
      Meta Llama
      Mistral AI
      DeepSeek
      Alibaba Qwen
      Zhipu GLM
      Moonshot Kimi
      01.AI Yi
      Microsoft Phi
      NVIDIA Nemotron
      IBM Granite
      TII Falcon
      AllenAI OLMo
    🖼️ Multimodal
      Vision-Language
      Omni / Any-to-Any
    📊 Evaluation
      Arenas
      Benchmarks
      Leaderboards
    🛠️ Applications
      Agents
      RAG
      Coding
```

> GitHub doesn't always keep its mermaid renderer current — if the mind map above shows as plain text instead of a diagram, open the file directly on [mermaid.live](https://mermaid.live) or view it in VS Code.

Each branch below is a detail table: a logo for quick recognition, the organization, the model family, what it's best known for, and links.

---

## 🏢 Proprietary (Closed-Weight) Models

Flagship models you access only through an API or app — weights are not released.

| | Organization | Model Family | Known For | Link |
|---|---|---|---|---|
| <img src="https://www.google.com/s2/favicons?domain=openai.com&sz=64" width="24"> | **OpenAI** 🇺🇸 | GPT-5 series, o-series reasoning | General intelligence, coding, the ChatGPT ecosystem | [openai.com](https://openai.com) |
| <img src="https://www.google.com/s2/favicons?domain=anthropic.com&sz=64" width="24"> | **Anthropic** 🇺🇸 | Claude 5 (Opus / Sonnet / Haiku) | Long-context reasoning, coding agents, safety-focused alignment | [anthropic.com](https://anthropic.com) |
| <img src="https://www.google.com/s2/favicons?domain=deepmind.google&sz=64" width="24"> | **Google DeepMind** 🇺🇸 | Gemini series | Native multimodality, 1M+ token context, deep Google ecosystem integration | [deepmind.google](https://deepmind.google) |
| <img src="https://www.google.com/s2/favicons?domain=x.ai&sz=64" width="24"> | **xAI** 🇺🇸 | Grok series | Real-time X/Twitter data access, fast iteration cadence | [x.ai](https://x.ai) |
| <img src="https://www.google.com/s2/favicons?domain=aws.amazon.com&sz=64" width="24"> | **Amazon** 🇺🇸 | Nova series | Low-cost, high-throughput models tied to AWS Bedrock | [aws.amazon.com/bedrock](https://aws.amazon.com/bedrock) |
| <img src="https://www.google.com/s2/favicons?domain=microsoft.com&sz=64" width="24"> | **Microsoft** 🇺🇸 | Copilot (Orchestrated OpenAI + in-house) | Enterprise/Office integration | [microsoft.com/ai](https://www.microsoft.com/ai) |
| <img src="https://www.google.com/s2/favicons?domain=cohere.com&sz=64" width="24"> | **Cohere** 🇨🇦 | Command R series | Enterprise RAG & retrieval-tuned models | [cohere.com](https://cohere.com) |
| <img src="https://www.google.com/s2/favicons?domain=baidu.com&sz=64" width="24"> | **Baidu** 🇨🇳 | ERNIE series | Chinese-language search & knowledge grounding | [yiyan.baidu.com](https://yiyan.baidu.com) |
| <img src="https://www.google.com/s2/favicons?domain=doubao.com&sz=64" width="24"> | **ByteDance** 🇨🇳 | Doubao | Consumer apps, TikTok/Douyin ecosystem | [doubao.com](https://www.doubao.com) |
| <img src="https://www.google.com/s2/favicons?domain=hunyuan.tencent.com&sz=64" width="24"> | **Tencent** 🇨🇳 | Hunyuan (混元) series | WeChat/gaming/cloud ecosystem integration | [hunyuan.tencent.com](https://hunyuan.tencent.com) |
| <img src="https://www.google.com/s2/favicons?domain=sensetime.com&sz=64" width="24"> | **SenseTime** 🇨🇳 | SenseChat (日日新) | Vision-heritage lab, strong multimodal perception + LLM | [sensetime.com](https://www.sensetime.com) |
| <img src="https://www.google.com/s2/favicons?domain=xfyun.cn&sz=64" width="24"> | **iFlytek** 🇨🇳 | Spark (讯飞星火) | Speech + language, education & government sectors | [xfyun.cn](https://www.xfyun.cn) |
| <img src="https://www.google.com/s2/favicons?domain=minimax.io&sz=64" width="24"> | **MiniMax** 🇨🇳 | abab series | Long-context chat, multimodal agents | [minimax.io](https://www.minimax.io) |
| <img src="https://www.google.com/s2/favicons?domain=clova.ai&sz=64" width="24"> | **Naver** 🇰🇷 | HyperCLOVA X | Korean-language flagship, regional alternative to US/China giants | [clova.ai](https://clova.ai) |

## 🧩 Open-Weight Models

Weights you can download, fine-tune, and self-host.

| | Organization | Model Family | Known For | License Note | Link |
|---|---|---|---|---|---|
| <img src="https://www.google.com/s2/favicons?domain=meta.com&sz=64" width="24"> | **Meta** 🇺🇸 | Llama 4 (Scout / Maverick / Behemoth) | The reference open-weight baseline, huge ecosystem/tooling | Custom community license | [llama.com](https://www.llama.com) |
| <img src="https://www.google.com/s2/favicons?domain=mistral.ai&sz=64" width="24"> | **Mistral AI** 🇫🇷 | Mistral Large / Small, Mixtral | Efficient MoE architectures, strong multilingual (EU) performance | Apache 2.0 (most variants) | [mistral.ai](https://mistral.ai) |
| <img src="https://www.google.com/s2/favicons?domain=deepseek.com&sz=64" width="24"> | **DeepSeek** 🇨🇳 | DeepSeek-V3 / R1 | Frontier-level reasoning at a fraction of training/inference cost | MIT / open weights | [deepseek.com](https://www.deepseek.com) |
| <img src="https://www.google.com/s2/favicons?domain=qwen.ai&sz=64" width="24"> | **Alibaba** 🇨🇳 | Qwen series | Broad size range (0.5B–235B+), strong coding & multilingual | Apache 2.0 (most sizes) | [qwen.ai](https://qwen.ai) |
| <img src="https://www.google.com/s2/favicons?domain=zhipuai.cn&sz=64" width="24"> | **Zhipu AI** 🇨🇳 | GLM series | Agentic tool-use, bilingual EN/ZH training focus | Apache 2.0 (most variants) | [zhipuai.cn](https://www.zhipuai.cn) |
| <img src="https://www.google.com/s2/favicons?domain=moonshot.ai&sz=64" width="24"> | **Moonshot AI** 🇨🇳 | Kimi (K2) | Ultra-long context, agentic/tool-use benchmarks | Modified MIT | [moonshot.ai](https://www.moonshot.ai) |
| <img src="https://www.google.com/s2/favicons?domain=01.ai&sz=64" width="24"> | **01.AI** 🇨🇳 | Yi series | Bilingual efficiency-focused models | Apache 2.0 | [01.ai](https://www.01.ai) |
| <img src="https://www.google.com/s2/favicons?domain=microsoft.com&sz=64" width="24"> | **Microsoft** 🇺🇸 | Phi series | Small, high-quality "data-optimal" models for edge/on-device | MIT | [azure.microsoft.com/phi](https://azure.microsoft.com/en-us/products/phi) |
| <img src="https://www.google.com/s2/favicons?domain=ai.google.dev&sz=64" width="24"> | **Google** 🇺🇸 | Gemma series | Lightweight open models derived from Gemini research | Gemma license | [ai.google.dev/gemma](https://ai.google.dev/gemma) |
| <img src="https://www.google.com/s2/favicons?domain=nvidia.com&sz=64" width="24"> | **NVIDIA** 🇺🇸 | Nemotron series | Distilled/optimized for NVIDIA GPU inference, strong post-training tooling | NVIDIA Open Model License | [nvidia.com/nemotron](https://www.nvidia.com/en-us/ai/nemotron/) |
| <img src="https://www.google.com/s2/favicons?domain=ibm.com&sz=64" width="24"> | **IBM** 🇺🇸 | Granite series | Enterprise-focused, documented training-data provenance | Apache 2.0 | [ibm.com/granite](https://www.ibm.com/granite) |
| <img src="https://www.google.com/s2/favicons?domain=falconllm.tii.ae&sz=64" width="24"> | **TII** 🇦🇪 | Falcon series | Leading open model from the Middle East, strong Arabic + multilingual support | Apache 2.0 (Falcon 2+) | [falconllm.tii.ae](https://falconllm.tii.ae) |
| <img src="https://www.google.com/s2/favicons?domain=allenai.org&sz=64" width="24"> | **Allen Institute for AI** 🇺🇸 | OLMo series | "Fully open" — training data, code, and weights all released | Apache 2.0 | [allenai.org/olmo](https://allenai.org/olmo) |

## 🇨🇳 Chinese LLM Ecosystem

A closer look at the fast-moving Chinese market, since it spans both of the categories above.

```mermaid
mindmap
  root((中国大模型))
    开源 Open
      DeepSeek
      通义千问 Qwen
      智谱 GLM
      Kimi K2
      Yi
    闭源 Closed
      文心一言 ERNIE
      豆包 Doubao
      腾讯混元 Hunyuan
      商汤 SenseChat
      讯飞星火 Spark
      MiniMax abab
    应用场景
      长文本 Long-context
      编程 Coding
      智能体 Agents
      多模态 Multimodal
```

| Strength | Recommended Model(s) |
|---|---|
| Ultra-long context (1M+ tokens) | DeepSeek, Qwen |
| Long context (200K+ tokens) | Kimi K2 |
| Lowest-cost open weights | DeepSeek-V3 |
| Consumer/C-end products | Doubao |
| Chinese writing & creative tasks | ERNIE, Qwen |
| Agentic tool-use | GLM, Kimi |

## 🖼️ Multimodal Models

Models that go beyond text — vision, audio, and "omni" any-to-any models.

| | Model | Organization | Modalities |
|---|---|---|---|
| <img src="https://www.google.com/s2/favicons?domain=openai.com&sz=64" width="24"> | GPT-5 (multimodal) | OpenAI | Text, image, audio, video |
| <img src="https://www.google.com/s2/favicons?domain=deepmind.google&sz=64" width="24"> | Gemini (native multimodal) | Google DeepMind | Text, image, audio, video, code execution |
| <img src="https://www.google.com/s2/favicons?domain=anthropic.com&sz=64" width="24"> | Claude 5 (vision) | Anthropic | Text, image, PDFs/documents |
| <img src="https://www.google.com/s2/favicons?domain=qwen.ai&sz=64" width="24"> | Qwen-VL / Qwen-Omni | Alibaba | Text, image, video, audio |
| <img src="https://www.google.com/s2/favicons?domain=opengvlab.com&sz=64" width="24"> | InternVL | Shanghai AI Lab | Text, image (open weights) |

## 🛠️ Build With LLMs

Want to *use* these models instead of just reading about them? See **[Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)** for 50+ real, runnable projects: RAG pipelines, autonomous agents, MCP servers, voice agents, and more.

## 📊 Evaluation & Benchmarks

Picking a model means knowing how it's measured. Start here:

- **[Awesome LLM Evaluation](https://alopatenko.github.io/LLMEvaluation/)** — the most comprehensive single reference for evaluation methodology, benchmarks, and papers.
- **[LMArena (formerly Chatbot Arena)](https://lmarena.ai/)** — crowdsourced human head-to-head preference ranking.
- **MMLU / MMLU-Pro** — broad academic knowledge benchmark.
- **GPQA Diamond** — graduate-level reasoning questions.
- **SWE-bench** — real-world GitHub issue resolution for coding agents.
- **LiveCodeBench** — contamination-resistant, continuously-refreshed coding benchmark.

## 🔗 Related Awesome Lists

- [uhub/awesome-llm](https://github.com/uhub/awesome-llm)
- [hannibal046/Awesome-LLM](https://github.com/hannibal046/Awesome-LLM)
- [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)
- [Awesome-LLM-Evaluation](https://alopatenko.github.io/LLMEvaluation/)

## 🤝 Contributing

New model, wrong logo, outdated version number? PRs are very welcome — see [CONTRIBUTING.md](CONTRIBUTING.md). This landscape moves fast; this list is only useful if it stays current.

## License

[MIT](LICENSE)
