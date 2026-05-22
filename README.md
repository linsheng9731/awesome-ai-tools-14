# Awesome AI Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A meticulously curated, community-driven list of the best Artificial Intelligence tools, frameworks, models, and resources — updated for 2025.

**Why this list?** Unlike other AI tool directories, every entry here is hand-picked for quality, actively maintained, and organized by how developers, creators, and businesses actually use AI. We include pricing tiers, open-source status, and brief descriptions so you can make informed decisions fast.

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Last Updated](https://img.shields.io/badge/Updated-May%202025-blue.svg)]()
[![Tools Count](https://img.shields.io/badge/Tools-300%2B-orange.svg)]()

---

## Contents

- [Foundation Models & LLMs](#-foundation-models--llms)
- [AI Chatbots & Assistants](#-ai-chatbots--assistants)
- [AI Coding Tools](#-ai-coding-tools)
- [AI Writing & Content](#-ai-writing--content)
- [AI Image Generation](#-ai-image-generation)
- [AI Video Generation](#-ai-video-generation)
- [AI Audio, Voice & Music](#-ai-audio-voice--music)
- [AI Agents & Automation](#-ai-agents--automation)
- [Developer Infrastructure](#-developer-infrastructure)
  - [LLM APIs & Inference](#llm-apis--inference)
  - [Vector Databases](#vector-databases)
  - [LLM Frameworks & Orchestration](#llm-frameworks--orchestration)
  - [LLMOps & Observability](#llmops--observability)
  - [Model Deployment & Local Inference](#model-deployment--local-inference)
  - [Evaluation & Testing](#evaluation--testing)
- [AI Search & Research](#-ai-search--research)
- [AI Productivity & Workspace](#-ai-productivity--workspace)
- [AI Design & Creative](#-ai-design--creative)
- [AI Marketing & Sales](#-ai-marketing--sales)
- [AI Customer Service](#-ai-customer-service)
- [Domain-Specific AI](#-domain-specific-ai)
  - [Healthcare](#healthcare)
  - [Legal](#legal)
  - [Finance](#finance)
  - [Education](#education)
  - [Cybersecurity](#cybersecurity)
- [AI Safety, Ethics & Governance](#-ai-safety-ethics--governance)
- [Prompt Engineering](#-prompt-engineering)
- [Learning Resources](#-learning-resources)
- [Benchmarks & Leaderboards](#-benchmarks--leaderboards)
- [Communities & Newsletters](#-communities--newsletters)
- [Related Awesome Lists](#-related-awesome-lists)
- [Contributing](#contributing)

---

## Legend

| Badge | Meaning |
|---|---|
| `#opensource` | Source code is publicly available |
| `#free` | Has a meaningful free tier |
| `#selfhost` | Can be self-hosted |
| `⭐ Editor's Pick` | Exceptional quality, widely recommended |
| `🔥 Trending` | Rapidly growing in popularity |

---

## 🧠 Foundation Models & LLMs

The core large language models powering the AI ecosystem. Organized by access type.

### Proprietary Frontier Models

| Model | Provider | Context Window | Key Strengths |
|---|---|---|---|
| [GPT-4o](https://platform.openai.com/docs/models) | OpenAI | 128K tokens | Multimodal (text/image/audio/video), fastest response |
| [GPT-4.1](https://platform.openai.com/docs/models) | OpenAI | 1M tokens | Long context, coding, instruction following |
| [o3 / o4-mini](https://openai.com/o3) | OpenAI | 200K tokens | Advanced reasoning, math, science |
| [Claude 3.7 Sonnet](https://www.anthropic.com/claude) | Anthropic | 200K tokens | Best for coding, writing, nuanced reasoning |
| [Claude Opus 4](https://www.anthropic.com/claude) | Anthropic | 200K tokens | Highest capability, constitutional AI safety |
| [Gemini 2.5 Pro](https://deepmind.google/technologies/gemini/) | Google | 2M tokens | Largest context window, video/audio analysis |
| [Gemini 2.5 Flash](https://deepmind.google/technologies/gemini/) | Google | 1M tokens | Fast, cost-efficient multimodal |
| [Grok 3](https://x.ai/grok) | xAI | 131K tokens | Real-time X/Twitter data, STEM reasoning |
| [DeepSeek-V3](https://www.deepseek.com/) | DeepSeek | 128K tokens | Open weights, frontier performance, cost-efficient |
| [DeepSeek-R1](https://www.deepseek.com/) | DeepSeek | 128K tokens | Chain-of-thought reasoning, math & coding `#opensource` |
| [Mistral Large 2](https://mistral.ai/) | Mistral AI | 128K tokens | European, multilingual, function calling |

### Open-Weight Models

These models have publicly available weights, enabling local deployment, fine-tuning, and research.

| Model | Parameters | License | Highlights |
|---|---|---|---|
| [Llama 4 Scout / Maverick](https://llama.meta.com/) | 17B–400B+ | Llama 4 Community | Meta's latest, MoE architecture, multimodal `#opensource` |
| [Qwen3](https://qwenlm.github.io/) | 0.6B–235B | Apache 2.0 | Alibaba, strong multilingual & coding `#opensource` |
| [Mistral / Mixtral 8x22B](https://mistral.ai/) | 7B–141B | Apache 2.0 | MoE, efficient, strong instruction following `#opensource` |
| [Phi-4](https://azure.microsoft.com/en-us/products/phi) | 14B | MIT | Microsoft, small but highly capable `#opensource` |
| [Gemma 3](https://ai.google.dev/gemma) | 1B–27B | Gemma ToS | Google, efficient, multimodal `#opensource` |
| [Command R+](https://cohere.com/command) | 104B | CC-BY-NC | Cohere, RAG-optimized `#opensource` |
| [Falcon 180B](https://falconllm.tii.ae/) | 180B | Falcon License | TII, strong general purpose `#opensource` |
| [DBRX](https://www.databricks.com/blog/introducing-dbrx-new-state-art-open-llm) | 132B | Databricks Open | MoE, strong coding `#opensource` |

---

## 💬 AI Chatbots & Assistants

Consumer-facing AI assistants for everyday tasks, research, and conversation.

- ⭐ [ChatGPT](https://chat.openai.com) — The world's most popular AI assistant by OpenAI. Supports GPT-4o with multimodal inputs, web browsing, code execution, image generation, and memory. `#free`
- ⭐ [Claude](https://claude.ai) — Anthropic's assistant, praised for thoughtful long-form writing, nuanced reasoning, and safety. Excellent for document analysis and coding. `#free`
- ⭐ [Gemini](https://gemini.google.com) — Google's multimodal assistant with deep integration into Google Workspace, YouTube, and Search. Gemini Advanced uses the 2M-token Pro model. `#free`
- [Microsoft Copilot](https://copilot.microsoft.com) — Powered by GPT-4o, integrated across Windows, Office, Bing, and Edge. `#free`
- [Grok](https://grok.x.ai) — xAI's assistant with real-time access to X (Twitter) data and strong STEM capabilities. `#free`
- [Meta AI](https://ai.meta.com) — Available across WhatsApp, Instagram, Facebook, and Messenger. Powered by Llama 4. `#free`
- [Perplexity AI](https://www.perplexity.ai) — Search-first AI that cites sources inline. Excellent for research and fact-checking. `#free`
- [You.com](https://you.com) — Privacy-focused AI search and assistant with multiple model options. `#free`
- [Poe](https://poe.com) — Quora's multi-model platform: access Claude, GPT-4o, Gemini, Llama, and more in one interface. `#free`
- [HuggingChat](https://huggingface.co/chat) — Open-source chatbot powered by community models (Llama, Mistral, etc.). `#opensource` `#free`
- [DeepSeek Chat](https://chat.deepseek.com) — DeepSeek's assistant, exceptional for coding and math. `#free`
- [Kagi Assistant](https://kagi.com/assistant) — Privacy-first AI assistant with no ads, integrated with Kagi search.
- [Character.AI](https://character.ai) — Create and chat with custom AI personas. Popular for entertainment and roleplay. `#free`
- [Pi](https://pi.ai) — Inflection AI's empathetic conversational assistant. `#free`

---

## 👩‍💻 AI Coding Tools

### AI-Powered IDEs & Editors

- ⭐ [Cursor](https://cursor.sh) — AI-first fork of VS Code. Best-in-class autocomplete, multi-file edits, and codebase understanding. Supports all major LLMs. `#free`
- ⭐ [Windsurf](https://codeium.com/windsurf) — Codeium's agentic IDE with "Cascade" flow that understands your entire codebase. `#free`
- [GitHub Copilot](https://github.com/features/copilot) — The most widely adopted AI coding assistant. Integrates with VS Code, JetBrains, Neovim, and more.
- [JetBrains AI Assistant](https://www.jetbrains.com/ai/) — Native AI in IntelliJ IDEA, PyCharm, WebStorm, and all JetBrains IDEs.
- [Replit Agent](https://replit.com/ai) — Build and deploy full-stack apps from natural language in the browser. `#free`
- [Amazon Q Developer](https://aws.amazon.com/q/developer/) — AWS's AI coding assistant with deep AWS integration. `#free`
- [Zed](https://zed.dev) — High-performance editor with built-in AI collaboration. `#opensource` `#free`

### Autonomous Coding Agents

- ⭐ [Claude Code](https://docs.anthropic.com/en/docs/claude-code) — Anthropic's terminal-based agentic coding tool. Highly configurable, can run autonomously. `#free`
- [Devin](https://cognition.ai/devin) — The first "AI software engineer" by Cognition. Handles entire engineering tasks end-to-end.
- [SWE-agent](https://swe-agent.com) — Princeton's open-source agent that solves GitHub issues autonomously. `#opensource` `#free`
- [Aider](https://aider.chat) — Terminal-based AI pair programmer that edits code in your local git repo. `#opensource` `#free`
- [Plandex](https://plandex.ai) — Open-source terminal AI engine for complex, multi-file coding tasks. `#opensource` `#free`
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) — Open-source Devin alternative. `#opensource` `#free` `#selfhost`

### AI App Builders (Vibe Coding)

- ⭐ [v0](https://v0.dev) — Vercel's AI that generates production-ready React/Next.js UI from text. `#free`
- ⭐ [Bolt.new](https://bolt.new) — StackBlitz's full-stack AI builder. Generates, runs, and deploys apps in the browser. `#free`
- [Lovable](https://lovable.dev) — Build full-stack web apps from a description. Integrates with Supabase and GitHub. `#free`
- [Tempo Labs](https://tempolabs.ai) — AI-powered React app builder with visual editing.
- [Webcrumbs Frontend AI](https://webcrumbs.org) — Generate React components from screenshots or descriptions. `#free`

### Code Review & Quality

- [CodeRabbit](https://coderabbit.ai) — AI-powered PR reviews with line-by-line feedback, summaries, and security checks. `#free`
- [PR-Agent](https://github.com/Codium-ai/pr-agent) — Open-source automated PR analysis and review. `#opensource` `#free`
- [Qodo](https://qodo.ai) — Generates meaningful tests and reviews code logic (formerly CodiumAI). `#free`
- [Sourcery](https://sourcery.ai) — Automated Python refactoring and code quality. `#free`
- [Gito](https://gito.dev) — AI code reviewer for GitHub Actions, compatible with any LLM. `#free`

### Code Documentation

- [Mintlify](https://mintlify.com) — AI-powered documentation writer and hosting platform. `#free`
- [Swimm](https://swimm.io) — Keeps code documentation in sync with your codebase automatically.
- [Stenography](https://stenography.dev) — Automatic inline code documentation generation.

---

## 📝 AI Writing & Content

### General Writing Assistants

- ⭐ [Grammarly](https://grammarly.com) — Grammar, tone, clarity, and plagiarism checking. Integrates with 500K+ apps. `#free`
- ⭐ [Jasper](https://jasper.ai) — Enterprise-grade content platform with brand voice, 50+ templates, and team collaboration.
- [Copy.ai](https://copy.ai) — Specializes in marketing copy, ad content, and automated workflows. `#free`
- [Rytr](https://rytr.me) — Affordable AI writer with 20+ tones and 40+ use cases. `#free`
- [Anyword](https://anyword.com) — Brand-consistent content with predictive performance scoring.
- [Writesonic](https://writesonic.com) — Long-form articles, ads, and landing pages with SEO integration. `#free`
- [DeepL Write](https://www.deepl.com/write) — AI writing tool focused on improving clarity and style. `#free`
- [Wordtune](https://wordtune.com) — Rewrite and rephrase sentences with context awareness. `#free`
- [QuillBot](https://quillbot.com) — Paraphrasing, summarization, grammar checking, and citation tools. `#free`

### SEO & Long-Form Content

- [Surfer SEO](https://surferseo.com) — Data-driven content optimization with real-time SERP analysis.
- [MarketMuse](https://marketmuse.com) — AI content strategy and topic authority platform.
- [Frase](https://frase.io) — Research, write, and optimize SEO content in one workflow.
- [Clearscope](https://clearscope.io) — Content optimization graded against top-ranking pages.
- [Moonbeam](https://moonbeam.ai) — Long-form AI writing assistant for blogs and essays.

### Summarization & Document AI

- [NotebookLM](https://notebooklm.google.com) — Google's AI that chats with your documents, PDFs, and notes. Creates audio overviews. `#free`
- [Recall](https://www.recall.ai) — Summarize anything you read online and build a connected knowledge base. `#free`
- [Gist AI](https://www.gistai.tech) — Summarize websites, YouTube videos, and PDFs with ChatGPT. `#free`
- [ChatPDF](https://www.chatpdf.com) — Chat with any PDF document. `#free`
- [SciSpace](https://typeset.io) — AI chat for scientific papers, with explanations of math and tables. `#free`

### Email Writing

- [Lavender](https://lavender.ai) — AI email coach that improves reply rates for sales teams.
- [Superhuman](https://superhuman.com) — AI-powered email client with instant triage and reply drafting.
- [Shortwave](https://shortwave.com) — AI email assistant that summarizes threads and drafts replies. `#free`

---

## 🖼️ AI Image Generation

### Text-to-Image Models

- ⭐ [Midjourney](https://midjourney.com) — Industry standard for artistic, high-quality image generation. v6 offers photorealism and style consistency.
- ⭐ [DALL-E 3](https://openai.com/dall-e-3) — OpenAI's image model, accessible via ChatGPT. Excellent prompt adherence and text rendering.
- ⭐ [Stable Diffusion 3.5](https://stability.ai) — Stability AI's open-source flagship. Run locally or via API. `#opensource`
- [Adobe Firefly](https://firefly.adobe.com) — Commercially safe image generation trained on licensed content. Integrated with Creative Cloud. `#free`
- [Ideogram 2.0](https://ideogram.ai) — Best-in-class text rendering within images. `#free`
- [Flux (Black Forest Labs)](https://blackforestlabs.ai) — State-of-the-art open-weight image generation models (Flux.1 Pro/Dev/Schnell). `#opensource`
- [Leonardo AI](https://leonardo.ai) — Fine-tuned models for game assets, concept art, and consistent characters. `#free`
- [Playground AI](https://playground.ai) — Free AI image creator with multiple model options. `#free`
- [Reve Image](https://reve.art) — Strong prompt adherence and photorealism. `#free`
- [Krea AI](https://krea.ai) — Real-time AI generation and enhancement. `#free`

### Image Editing & Enhancement

- [Adobe Photoshop (AI)](https://adobe.com/photoshop) — Generative Fill, Remove, and Expand powered by Firefly.
- [Canva AI](https://canva.com) — Magic Edit, Magic Eraser, and AI image generation in a design platform. `#free`
- [ClipDrop](https://clipdrop.co) — Remove backgrounds, upscale, relight, and generate images. Powered by Stability AI. `#free`
- [Remove.bg](https://remove.bg) — Instant background removal. `#free`
- [Photoroom](https://photoroom.com) — Professional product and portrait photos from your phone. `#free`
- [Lensa](https://prisma-ai.com/lensa) — AI avatar and portrait enhancement app.
- [Magnific AI](https://magnific.ai) — AI upscaling and enhancement with creative hallucination.

### Specialized Image Tools

- [Headshot Pro](https://headshotpro.com) — Generate professional AI headshots from casual photos.
- [StockPhotoAI](https://stockphotoai.net) — Generate royalty-free stock photos on demand.
- [VectorArt.ai](https://vectorart.ai) — Create vector images with AI.
- [Civitai](https://civitai.com) — Community hub for sharing and downloading Stable Diffusion models and LoRAs. `#free`
- [OpenArt](https://openart.ai) — Search 10M+ AI-generated images and prompts. `#free`

---

## 📽️ AI Video Generation

### Text-to-Video & Video Generation

- ⭐ [Sora](https://sora.com) — OpenAI's text-to-video model. Cinematic quality, up to 20 seconds, 1080p.
- ⭐ [Runway Gen-4](https://runwayml.com) — Professional-grade video generation and editing. Industry standard for filmmakers.
- ⭐ [Google Veo 2](https://deepmind.google/technologies/veo/) — Google's high-fidelity video generation with strong physics simulation.
- [Kling AI](https://klingai.com) — Kuaishou's video model. Excellent motion quality and longer clips. `#free`
- [Pika Labs](https://pika.art) — Quick, accessible video generation with style controls. `#free`
- [Luma Dream Machine](https://lumalabs.ai/dream-machine) — Fast, high-quality video from text or images. `#free`
- [Hailuo AI (MiniMax)](https://hailuoai.video) — Strong motion consistency and character animation. `#free`
- [Pixverse](https://pixverse.ai) — Versatile video generation with effects and transitions. `#free`

### AI Video Editing & Production

- [Descript](https://descript.com) — Edit video by editing the transcript. Overdub voice cloning, screen recording, and AI captions. `#free`
- [CapCut](https://capcut.com) — TikTok's AI video editor with auto-captions, effects, and templates. `#free`
- [InVideo AI](https://invideo.io) — Turn text scripts into polished videos with AI voiceovers. `#free`
- [Opus Clip](https://opus.pro) — Automatically repurpose long videos into viral short clips. `#free`
- [Captions](https://captions.ai) — AI video creator with auto-captions, eye contact correction, and translation.

### AI Avatars & Presenters

- [HeyGen](https://heygen.com) — Create AI avatar videos with realistic lip-sync in 175+ languages.
- [Synthesia](https://synthesia.io) — Corporate training and explainer videos with AI presenters.
- [D-ID](https://d-id.com) — Animate photos and create talking avatar videos.
- [Rephrase AI](https://rephrase.ai) — Hyper-personalized video creation at scale.

---

## 🎶 AI Audio, Voice & Music

### Text-to-Speech & Voice Cloning

- ⭐ [ElevenLabs](https://elevenlabs.io) — Ultra-realistic voice synthesis and cloning. Supports 29+ languages with emotion control. `#free`
- [Murf AI](https://murf.ai) — Professional voiceover platform with 120+ AI voices. `#free`
- [Play.ht](https://play.ht) — Realistic text-to-speech with voice cloning. `#free`
- [Resemble AI](https://resemble.ai) — Real-time voice synthesis and custom voice cloning.
- [Cartesia](https://cartesia.ai) — Ultra-low-latency TTS for real-time applications.
- [Microsoft Azure Neural TTS](https://azure.microsoft.com/en-us/products/ai-services/text-to-speech) — Enterprise-grade, 400+ voices, 140+ languages.
- [LMNT](https://lmnt.com) — Fast, expressive voice synthesis API.
- [Kokoro](https://github.com/hexgrad/kokoro) — Lightweight, high-quality open-source TTS model. `#opensource` `#free`

### Speech-to-Text & Transcription

- [Whisper](https://github.com/openai/whisper) — OpenAI's open-source speech recognition model. State-of-the-art accuracy. `#opensource` `#free`
- [AssemblyAI](https://assemblyai.com) — Accurate transcription API with speaker diarization, sentiment analysis, and summarization.
- [Deepgram](https://deepgram.com) — Real-time and batch transcription with low latency.
- [Otter.ai](https://otter.ai) — Meeting transcription with speaker identification and action items. `#free`
- [Rev AI](https://rev.ai) — Automated and human transcription services.

### AI Music Generation

- ⭐ [Suno AI](https://suno.com) — Generate complete songs with vocals, lyrics, and instrumentation from a text prompt. `#free`
- ⭐ [Udio](https://udio.com) — High-quality music generation with fine-grained style control. `#free`
- [AIVA](https://aiva.ai) — AI composer for classical, cinematic, and custom music. `#free`
- [Soundraw](https://soundraw.io) — Royalty-free music customized by mood, genre, and length. `#free`
- [Beatoven.ai](https://beatoven.ai) — AI music tailored for video and podcast content. `#free`
- [Stable Audio](https://stability.ai/stable-audio) — Stability AI's music and sound generation model. `#free`
- [MusicGen](https://audiocraft.metademolab.com/) — Meta's open-source music generation model. `#opensource` `#free`
- [Mubert](https://mubert.com) — Real-time generative music for content creators. `#free`

### Audio Enhancement

- [Adobe Podcast Enhance](https://podcast.adobe.com/enhance) — Remove background noise and enhance voice quality instantly. `#free`
- [Krisp](https://krisp.ai) — Real-time noise cancellation for calls and recordings. `#free`
- [Auphonic](https://auphonic.com) — Automated audio post-production for podcasts. `#free`

---

## 🤖 AI Agents & Automation

### Agent Frameworks & Libraries

- ⭐ [LangChain](https://langchain.com) — The most popular framework for building LLM-powered applications with chains, tools, and memory. `#opensource` `#free`
- ⭐ [LangGraph](https://langchain-ai.github.io/langgraph/) — Build stateful, multi-actor agent workflows as graphs. Built on LangChain. `#opensource` `#free`
- ⭐ [CrewAI](https://crewai.com) — Multi-agent collaboration framework with role-based agent teams. `#opensource` `#free`
- [AutoGen](https://microsoft.github.io/autogen/) — Microsoft's framework for multi-agent conversational AI. `#opensource` `#free`
- [LlamaIndex](https://llamaindex.ai) — Data framework for connecting LLMs to external data sources. `#opensource` `#free`
- [Phidata](https://phidata.app) — Build multimodal agents with memory, knowledge, and tools. `#opensource` `#free`
- [Semantic Kernel](https://learn.microsoft.com/en-us/semantic-kernel/) — Microsoft's SDK for integrating LLMs into .NET, Python, and Java apps. `#opensource` `#free`
- [Haystack](https://haystack.deepset.ai) — End-to-end NLP framework for building RAG pipelines and agents. `#opensource` `#free`
- [DSPy](https://dspy.ai) — Stanford's framework for programming (not prompting) language models. `#opensource` `#free`
- [Mastra](https://mastra.ai) — TypeScript-native agent framework with built-in workflows and memory. `#opensource` `#free`
- [VoltAgent](https://voltagent.dev) — TypeScript framework for building AI agents with tools, memory, and observability. `#opensource` `#free`

### No-Code Agent Builders

- [Flowise](https://flowiseai.com) — Drag-and-drop UI to build LLM apps and agents. Self-hostable. `#opensource` `#free` `#selfhost`
- [Langflow](https://langflow.org) — Visual framework for building multi-agent and RAG applications. `#opensource` `#free`
- [Dify](https://dify.ai) — Open-source LLM app development platform with visual workflow builder. `#opensource` `#free` `#selfhost`
- [Botpress](https://botpress.com) — Enterprise chatbot and agent builder with visual flows. `#free`
- [Voiceflow](https://voiceflow.com) — Design, prototype, and deploy conversational AI agents. `#free`
- [Stack AI](https://stack-ai.com) — No-code AI workflow builder for enterprises. `#free`

### Workflow Automation

- ⭐ [Zapier](https://zapier.com) — Connect 6,000+ apps with AI-powered automation. No-code. `#free`
- ⭐ [n8n](https://n8n.io) — Open-source workflow automation with AI nodes and self-hosting. `#opensource` `#free` `#selfhost`
- [Make](https://make.com) — Visual automation platform with advanced data transformation. `#free`
- [Lindy](https://lindy.ai) — AI-native automation for complex business workflows. `#free`
- [Gumloop](https://gumloop.com) — AI workflow builder with drag-and-drop simplicity. `#free`
- [Relay.app](https://relay.app) — Human-in-the-loop workflow automation with AI steps. `#free`

### Computer Use & Browser Agents

- [Operator](https://openai.com/operator) — OpenAI's agent that uses a computer to complete web tasks.
- [Claude Computer Use](https://www.anthropic.com/news/3-5-models-and-computer-use) — Anthropic's API for controlling computers with Claude.
- [Browser Use](https://github.com/browser-use/browser-use) — Open-source library for AI browser automation. `#opensource` `#free`
- [Hyperbrowser](https://hyperbrowser.ai) — Browser infrastructure for AI agents with proxy and session management.
- [Notte](https://notte.cc) — Fast, reliable browser agent framework. `#opensource`
- [AgentQL](https://agentql.com) — Query language for AI agents to interact with web pages. `#free`

---

## 🛠️ Developer Infrastructure

### LLM APIs & Inference

Platforms for accessing and running language models via API.

| Provider | Models Available | Key Feature |
|---|---|---|
| [OpenAI API](https://platform.openai.com) | GPT-4o, o3, Whisper, DALL-E | Industry standard, richest ecosystem |
| [Anthropic API](https://www.anthropic.com/api) | Claude 3.7, Claude Opus | Best for coding & safety-critical apps |
| [Google AI / Vertex AI](https://ai.google.dev) | Gemini 2.5 Pro/Flash | 2M context, multimodal, Google Cloud |
| [Groq](https://groq.com) | Llama, Mixtral, Gemma | Ultra-fast inference (LPU hardware) `#free` |
| [Together AI](https://together.ai) | 50+ open models | Fast inference for open-weight models |
| [Fireworks AI](https://fireworks.ai) | Llama, Mixtral, Qwen | Low-latency open model hosting |
| [Replicate](https://replicate.com) | 1000s of models | Run any model with one API call `#free` |
| [Hugging Face Inference API](https://huggingface.co/inference-api) | All HF models | Largest model hub `#free` |
| [Cohere API](https://cohere.com) | Command R+, Embed | RAG-optimized, enterprise focus |
| [AI/ML API](https://aimlapi.com) | 100+ models | Single API for 100+ models `#free` |
| [Mistral API](https://mistral.ai/api) | Mistral, Mixtral | European, strong multilingual |
| [Perplexity API](https://www.perplexity.ai/api) | Sonar models | Web-grounded responses |

### Vector Databases

Essential for RAG, semantic search, and long-term AI memory.

| Database | Type | Best For |
|---|---|---|
| [Pinecone](https://pinecone.io) | Managed | Production RAG, serverless scaling `#free` |
| [Weaviate](https://weaviate.io) | Open-source | Hybrid search, GraphQL API `#opensource` `#selfhost` |
| [Qdrant](https://qdrant.tech) | Open-source | High performance, Rust-based `#opensource` `#selfhost` |
| [Milvus](https://milvus.io) | Open-source | Billion-scale vector search `#opensource` `#selfhost` |
| [Chroma](https://trychroma.com) | Open-source | Developer-friendly, easy setup `#opensource` `#selfhost` |
| [pgvector](https://github.com/pgvector/pgvector) | PostgreSQL ext. | Existing Postgres users `#opensource` |
| [LanceDB](https://lancedb.com) | Open-source | Multimodal, embedded `#opensource` `#selfhost` |
| [Turbopuffer](https://turbopuffer.com) | Managed | Fast, cost-efficient at scale |

### LLM Frameworks & Orchestration

- ⭐ [LangChain](https://langchain.com) — Chains, agents, tools, memory, and RAG. The most widely adopted framework. `#opensource`
- ⭐ [LlamaIndex](https://llamaindex.ai) — Data ingestion, indexing, and querying for LLM apps. `#opensource`
- [Haystack](https://haystack.deepset.ai) — Modular NLP pipelines for search and QA. `#opensource`
- [DSPy](https://dspy.ai) — Optimize LLM pipelines programmatically instead of manual prompting. `#opensource`
- [Guidance](https://github.com/guidance-ai/guidance) — Control LLM output structure with templates and constraints. `#opensource`
- [Outlines](https://github.com/dottxt-ai/outlines) — Structured text generation with guaranteed JSON/regex output. `#opensource`
- [Instructor](https://python.useinstructor.com) — Structured LLM outputs using Pydantic. `#opensource`
- [Marvin](https://askmarvin.ai) — AI functions and bots with a clean Python API. `#opensource`

### LLMOps & Observability

Monitor, debug, and improve your LLM applications in production.

| Tool | Key Feature | Open Source |
|---|---|---|
| [LangSmith](https://smith.langchain.com) | Native LangChain tracing & evaluation | No |
| [Langfuse](https://langfuse.com) | Open-source LLM observability `#opensource` | Yes |
| [Weights & Biases](https://wandb.ai) | Experiment tracking, prompts, evals | No |
| [Arize AI](https://arize.com) | Production ML & LLM monitoring | No |
| [Helicone](https://helicone.ai) | LLM proxy with logging & caching `#opensource` | Yes |
| [Portkey](https://portkey.ai) | LLM gateway with fallbacks & routing | No |
| [Braintrust](https://braintrust.dev) | Evals, prompts, and datasets | No |
| [Maxim AI](https://getmaxim.ai) | End-to-end LLM evaluation platform | No |
| [Opik](https://comet.com/opik) | Open-source LLM evaluation `#opensource` | Yes |
| [Phoenix (Arize)](https://phoenix.arize.com) | Open-source ML observability `#opensource` | Yes |

### Model Deployment & Local Inference

Run models locally or deploy them to production infrastructure.

- ⭐ [Ollama](https://ollama.ai) — The easiest way to run LLMs locally. One command to download and run any model. `#opensource` `#free`
- ⭐ [vLLM](https://vllm.ai) — High-throughput LLM serving with PagedAttention. Production-grade. `#opensource` `#free`
- [llama.cpp](https://github.com/ggerganov/llama.cpp) — Run LLMs on CPU (and GPU) with minimal dependencies. `#opensource` `#free`
- [LM Studio](https://lmstudio.ai) — Desktop app to discover, download, and run local LLMs. `#free`
- [Jan](https://jan.ai) — Open-source ChatGPT alternative that runs fully offline. `#opensource` `#free`
- [GPT4All](https://gpt4all.io) — Run LLMs locally on any hardware. `#opensource` `#free`
- [Text Generation WebUI](https://github.com/oobabooga/text-generation-webui) — Gradio-based UI for running LLMs. `#opensource` `#free`
- [TGI (Text Generation Inference)](https://github.com/huggingface/text-generation-inference) — HuggingFace's production inference server. `#opensource`
- [BentoML](https://bentoml.com) — Build and deploy ML services with a Python-native workflow. `#opensource`
- [TensorZero](https://tensorzero.com) — Open-source framework for production LLM apps with optimization. `#opensource`

### Evaluation & Testing

- [RAGAS](https://ragas.io) — RAG evaluation framework measuring faithfulness, relevance, and context recall. `#opensource` `#free`
- [DeepEval](https://deepeval.com) — LLM evaluation framework with 14+ metrics. `#opensource` `#free`
- [Promptfoo](https://promptfoo.dev) — Test and evaluate LLM prompts with automated red-teaming. `#opensource` `#free`
- [Evals (OpenAI)](https://github.com/openai/evals) — OpenAI's framework for evaluating LLMs. `#opensource` `#free`
- [PromptBench](https://github.com/microsoft/promptbench) — Microsoft's adversarial robustness evaluation. `#opensource` `#free`
- [Giskard](https://giskard.ai) — Open-source AI quality testing and vulnerability scanning. `#opensource` `#free`

### Model Context Protocol (MCP)

MCP is an open standard by Anthropic for connecting AI models to external data sources and tools.

- [MCP Specification](https://modelcontextprotocol.io) — Official MCP documentation and specification. `#opensource`
- [MCP Servers (Official)](https://github.com/modelcontextprotocol/servers) — Reference MCP server implementations. `#opensource`
- [ToolHive](https://toolhive.io) — Find and deploy MCP servers with one click. `#free`
- [Smithery](https://smithery.ai) — MCP server registry and marketplace. `#free`
- [mcp-use](https://github.com/mcp-use/mcp-use) — Open-source library to connect any LLM to MCP servers. `#opensource`

---

## 🔍 AI Search & Research

- ⭐ [Perplexity AI](https://perplexity.ai) — AI-powered search with inline citations. Best for research and fact-checking. `#free`
- [You.com](https://you.com) — Privacy-focused AI search with multiple model options. `#free`
- [Exa](https://exa.ai) — Semantic search API designed for AI agents. `#free`
- [Phind](https://phind.com) — AI search engine optimized for developers and technical questions. `#free`
- [Elicit](https://elicit.com) — AI research assistant for literature review and academic papers. `#free`
- [Consensus](https://consensus.app) — Search engine that finds answers in scientific research. `#free`
- [SciSpace](https://typeset.io) — AI chat for scientific PDFs with math and table explanations. `#free`
- [NotebookLM](https://notebooklm.google.com) — Google's AI for chatting with your own documents and generating audio overviews. `#free`
- [Semantic Scholar](https://semanticscholar.org) — AI-powered academic search by Allen Institute for AI. `#free`
- [Connected Papers](https://connectedpapers.com) — Visualize connections between academic papers. `#free`
- [Sourcely](https://sourcely.net) — AI-powered academic citation finder. `#free`
- [MemFree](https://memfree.me) — Open-source hybrid AI search for the internet, bookmarks, and docs. `#opensource` `#free`

---

## 📊 AI Productivity & Workspace

### Note-Taking & Knowledge Management

- ⭐ [Notion AI](https://notion.so/ai) — AI writing, Q&A, and summarization built into the world's most popular workspace. `#free`
- [Obsidian + AI Plugins](https://obsidian.md) — Local-first notes with powerful AI plugins (Smart Connections, Copilot). `#free`
- [Mem AI](https://mem.ai) — AI-powered workspace that automatically organizes your notes.
- [Reflect](https://reflect.app) — AI-powered note-taking with networked thoughts.
- [Rewind AI](https://rewind.ai) — Records everything on your Mac and makes it searchable with AI.
- [Recall](https://www.recall.ai) — Summarize and connect everything you read online. `#free`

### Meeting Assistants

- ⭐ [Otter.ai](https://otter.ai) — Real-time meeting transcription, summaries, and action items. `#free`
- [Fireflies.ai](https://fireflies.ai) — AI notetaker for Zoom, Teams, Meet with search and analytics. `#free`
- [tl;dv](https://tldv.io) — Record, transcribe, and summarize meetings with AI. `#free`
- [Fathom](https://fathom.video) — Free AI meeting recorder and notetaker. `#free`
- [MeetGeek](https://meetgeek.ai) — AI meeting assistant with CRM integration. `#free`
- [Cogram](https://cogram.com) — Automatic meeting notes and action items.

### Email & Calendar

- [Superhuman](https://superhuman.com) — Fastest email client with AI triage and reply drafting.
- [Shortwave](https://shortwave.com) — AI email assistant with thread summarization. `#free`
- [SaneBox](https://sanebox.com) — AI email management that filters and prioritizes your inbox.
- [Reclaim AI](https://reclaim.ai) — AI calendar assistant that protects focus time and schedules meetings. `#free`

### Task & Project Management

- [Taskade](https://taskade.com) — AI-powered task management with autonomous agents. `#free`
- [ClickUp AI](https://clickup.com/ai) — AI writing, summarization, and automation within ClickUp. `#free`
- [Asana AI](https://asana.com/ai) — AI project management with smart workflows and insights.
- [Linear](https://linear.app) — Fast project management with AI-powered issue creation and triage.

### Presentation & Slides

- [Gamma](https://gamma.app) — Create beautiful presentations and documents from a prompt. `#free`
- [Tome](https://tome.app) — AI-powered storytelling and presentation tool. `#free`
- [Beautiful.ai](https://beautiful.ai) — Smart presentation software with AI design suggestions.
- [SlidesAI](https://slidesai.io) — Generate Google Slides from text. `#free`

---

## 🎨 AI Design & Creative

### UI/UX Design

- ⭐ [Figma AI](https://figma.com/ai) — AI-powered design suggestions, auto-layout, and content generation within Figma.
- [Uizard](https://uizard.io) — Turn sketches and screenshots into editable UI designs. `#free`
- [Galileo AI](https://usegalileo.ai) — Generate UI designs from text descriptions.
- [Framer AI](https://framer.com) — Build and publish websites with AI. `#free`
- [Locofy](https://locofy.ai) — Convert Figma designs to production-ready code. `#free`
- [v0](https://v0.dev) — Generate React components and full UIs from text. `#free`

### Graphic Design & Branding

- ⭐ [Canva AI](https://canva.com) — Magic Design, Magic Write, and AI image generation in the world's most popular design tool. `#free`
- [Adobe Express](https://express.adobe.com) — Quick graphic design with Adobe Firefly AI. `#free`
- [Microsoft Designer](https://designer.microsoft.com) — AI-powered graphic design tool. `#free`
- [Looka](https://looka.com) — AI logo and brand identity generator.
- [Brandmark](https://brandmark.io) — AI-based logo design.
- [Napkin](https://napkin.ai) — Turn text into visual diagrams and infographics. `#free`

### 3D Generation

- [Meshy AI](https://meshy.ai) — Text and image to 3D model generation. Game-ready assets. `#free`
- [Spline AI](https://spline.design) — 3D design tool with AI generation and web publishing. `#free`
- [Luma Genie](https://lumalabs.ai/genie) — 3D object generation from text. `#free`
- [Tripo3D](https://tripo3d.ai) — Fast, high-quality 3D model generation. `#free`
- [Rodin (Hyper 3D)](https://hyper3d.ai) — High-fidelity 3D generation for game development.

---

## 📣 AI Marketing & Sales

### Content & Copywriting

- [Jasper AI](https://jasper.ai) — Enterprise content platform with brand voice and 50+ templates.
- [Copy.ai](https://copy.ai) — Ad copy, email sequences, and marketing content. `#free`
- [Anyword](https://anyword.com) — Predictive performance scoring for marketing copy.
- [Phrasee](https://phrasee.co) — AI-optimized email subject lines and marketing copy.
- [AdCreative.ai](https://adcreative.ai) — Generate conversion-optimized ad creatives at scale. `#free`

### SEO & Content Strategy

- [Surfer SEO](https://surferseo.com) — Content optimization with real-time SERP analysis.
- [Semrush AI](https://semrush.com) — AI-powered SEO, content, and competitive research.
- [Clearbit](https://clearbit.com) — B2B data enrichment and lead intelligence.
- [MarketMuse](https://marketmuse.com) — AI content strategy and topic authority.

### Social Media

- [Buffer AI](https://buffer.com) — AI-assisted social media scheduling and content creation. `#free`
- [FeedHive](https://feedhive.io) — AI-powered social media management with performance prediction. `#free`
- [Taplio](https://taplio.com) — AI LinkedIn content creation and scheduling.
- [Postwise](https://postwise.ai) — AI tweet and LinkedIn post writer.

### CRM & Sales Automation

- [HubSpot AI](https://hubspot.com/ai) — AI across CRM, marketing, sales, and service.
- [Salesforce Einstein](https://salesforce.com/einstein) — AI embedded across the Salesforce platform.
- [Clay](https://clay.com) — AI-powered prospecting and outreach automation.
- [Apollo AI](https://apollo.io) — Sales intelligence and engagement platform with AI.

---

## 🎧 AI Customer Service

- ⭐ [Intercom (Fin AI)](https://intercom.com/fin) — AI agent that resolves 50%+ of support queries instantly.
- [Zendesk AI](https://zendesk.com/ai) — AI-powered ticketing, bots, and agent assistance.
- [Freshdesk AI](https://freshdesk.com) — Freddy AI for automated support and agent copilot.
- [Tidio](https://tidio.com) — AI chatbot for e-commerce with live chat. `#free`
- [Ada](https://ada.cx) — No-code AI customer service automation.
- [Drift](https://drift.com) — Conversational marketing and sales AI.
- [Kustomer](https://kustomer.com) — AI-first CRM for customer service teams.
- [Crisp](https://crisp.chat) — Shared inbox with AI chatbot and automation. `#free`
- [Helpshift](https://helpshift.com) — AI-powered mobile customer support.

---

## 🏥 Domain-Specific AI

### Healthcare

- [Suki AI](https://suki.ai) — Voice-powered clinical documentation assistant for physicians.
- [Nabla](https://nabla.com) — Ambient AI scribe that generates clinical notes from conversations.
- [DeepScribe](https://deepscribe.ai) — AI medical scribe for real-time documentation.
- [Ada Health](https://ada.com) — AI-powered symptom checker and health assessment. `#free`
- [Doximity GPT](https://doximity.com) — AI tools for physicians: clinical notes, patient messages, and research.
- [Viz.ai](https://viz.ai) — AI-powered care coordination for stroke and cardiovascular disease.

### Legal

- [Harvey AI](https://harvey.ai) — AI legal research and document drafting for law firms.
- [Casetext (Thomson Reuters)](https://casetext.com) — AI-powered legal research with CoCounsel.
- [Lexis+ AI](https://lexisnexis.com) — LexisNexis's AI for legal research and document analysis.
- [Ironclad AI](https://ironcladapp.com) — AI contract lifecycle management.
- [Spellbook](https://spellbook.legal) — AI contract drafting and review in Microsoft Word.
- [Darrow](https://darrow.ai) — AI for identifying high-value litigation opportunities.

### Finance

- [Bloomberg GPT](https://bloomberg.com/company/press/bloomberggpt-50-billion-parameter-llm-purpose-built-finance/) — LLM trained on Bloomberg's financial data.
- [Kensho (S&P Global)](https://kensho.com) — AI analytics for financial markets.
- [DataSnipper](https://datasnipper.com) — AI-powered audit and financial analysis in Excel.
- [Ramp](https://ramp.com) — AI-powered corporate card and expense management.
- [Trullion](https://trullion.com) — AI accounting and financial reporting automation.
- [FinChat](https://finchat.io) — AI for analyzing public company financials. `#free`

### Education

- ⭐ [Khan Academy Khanmigo](https://khanacademy.org/khan-labs) — AI tutor and teaching assistant powered by GPT-4.
- [Duolingo Max](https://duolingo.com/max) — AI-powered language learning with roleplay and explanations.
- [Coursera AI](https://coursera.org) — AI course recommendations and learning assistance.
- [MagicSchool AI](https://magicschool.ai) — AI tools for teachers: lesson plans, rubrics, and differentiation. `#free`
- [Synthesis](https://synthesis.com) — AI-powered math and problem-solving for students.
- [Socratic (Google)](https://socratic.org) — AI homework helper for students. `#free`
- [Quizlet AI](https://quizlet.com) — AI-powered flashcards, practice tests, and study guides. `#free`

### Cybersecurity

- [CrowdStrike Falcon AI](https://crowdstrike.com) — AI-powered endpoint detection and threat hunting.
- [Darktrace](https://darktrace.com) — Self-learning AI for network threat detection.
- [SentinelOne Singularity](https://sentinelone.com) — AI-driven endpoint protection and response.
- [Snyk](https://snyk.io) — AI-powered code security scanning and vulnerability remediation. `#free`
- [GitHub Advanced Security](https://github.com/features/security) — AI code scanning with CodeQL. `#free`
- [Protect AI](https://protectai.com) — Comprehensive AI/ML security platform.

---

## 🛡️ AI Safety, Ethics & Governance

### Safety Research Organizations

- [Anthropic Safety Research](https://www.anthropic.com/research) — Constitutional AI, interpretability, and alignment research.
- [OpenAI Safety](https://openai.com/safety) — Alignment, red-teaming, and preparedness research.
- [DeepMind Safety](https://deepmind.google/research/safety/) — Technical AI safety and specification research.
- [AI Safety Institute (UK)](https://www.gov.uk/government/organisations/ai-safety-institute) — Government AI safety evaluation.
- [Center for AI Safety](https://safe.ai) — Research and policy for AI risk reduction.
- [Alignment Forum](https://alignmentforum.org) — Community for AI alignment research and discussion. `#free`

### Governance & Compliance Tools

- [Credo AI](https://credo.ai) — AI governance platform for risk assessment and compliance.
- [Holistic AI](https://holisticai.com) — AI risk management and compliance auditing.
- [Arthur AI](https://arthur.ai) — ML monitoring and explainability platform.
- [Fiddler AI](https://fiddler.ai) — Explainable AI and model performance monitoring.
- [Weights & Biases](https://wandb.ai) — Model lineage, experiment tracking, and governance.

### Responsible AI Resources

- [AI Fairness 360 (IBM)](https://aif360.mybluemix.net) — Open-source toolkit for detecting and mitigating bias. `#opensource` `#free`
- [What-If Tool (Google)](https://pair-code.github.io/what-if-tool/) — Visualize ML model behavior without code. `#opensource` `#free`
- [LIME](https://github.com/marcotcr/lime) — Explain predictions of any ML classifier. `#opensource` `#free`
- [SHAP](https://shap.readthedocs.io) — Unified approach to explain ML model output. `#opensource` `#free`

---

## ✍️ Prompt Engineering

### Tools & Platforms

- [PromptHub](https://prompthub.us) — Version control and collaboration for prompts. `#free`
- [Promptfoo](https://promptfoo.dev) — Test, evaluate, and red-team prompts. `#opensource` `#free`
- [LangSmith](https://smith.langchain.com) — Prompt management with A/B testing and tracing. `#free`
- [Vellum](https://vellum.ai) — Prompt engineering, testing, and deployment platform. `#free`
- [PromptBase](https://promptbase.com) — Marketplace for buying and selling quality prompts.
- [FlowGPT](https://flowgpt.com) — Community for sharing and discovering prompts. `#free`

### Guides & Resources

- [Prompt Engineering Guide](https://promptingguide.ai) — Comprehensive guide covering all major prompting techniques. `#free`
- [OpenAI Cookbook](https://cookbook.openai.com) — Practical examples and guides for the OpenAI API. `#free`
- [Anthropic Prompt Library](https://docs.anthropic.com/en/prompt-library) — Curated prompts for Claude. `#free`
- [Learn Prompting](https://learnprompting.org) — Free, open-source course on prompt engineering. `#opensource` `#free`
- [Awesome Prompt Engineering](https://github.com/promptslab/Awesome-Prompt-Engineering) — Curated list of prompt engineering resources. `#free`

---

## 📚 Learning Resources

### Courses & Certifications

| Course | Provider | Level | Cost |
|---|---|---|---|
| [Practical Deep Learning](https://course.fast.ai) | Fast.ai | Intermediate | Free |
| [Deep Learning Specialization](https://deeplearning.ai/courses/deep-learning-specialization/) | DeepLearning.AI | Beginner-Advanced | Paid |
| [Machine Learning Specialization](https://deeplearning.ai/courses/machine-learning-specialization/) | Stanford/DeepLearning.AI | Beginner | Paid |
| [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course) | Hugging Face | Intermediate | Free |
| [LLM Bootcamp](https://fullstackdeeplearning.com/llm-bootcamp/) | Full Stack Deep Learning | Intermediate | Free |
| [Building LLM Apps](https://deeplearning.ai/short-courses/) | DeepLearning.AI | Beginner | Free |
| [CS224N: NLP with Deep Learning](https://web.stanford.edu/class/cs224n/) | Stanford | Advanced | Free |
| [MIT 6.S191: Deep Learning](http://introtodeeplearning.com) | MIT | Intermediate | Free |
| [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course) | Google | Beginner | Free |

### Books

- [Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) — Aurélien Géron. The definitive practical ML textbook.
- [Deep Learning](https://www.deeplearningbook.org) — Goodfellow, Bengio & Courville. Free online. `#free`
- [Natural Language Processing with Transformers](https://www.oreilly.com/library/view/natural-language-processing/9781098136789/) — Lewis Tunstall et al.
- [The Alignment Problem](https://brianchristian.org/the-alignment-problem/) — Brian Christian. AI safety for general audiences.
- [AI Superpowers](https://www.aisuperpowers.com) — Kai-Fu Lee. US-China AI competition.
- [Build a Large Language Model (From Scratch)](https://www.manning.com/books/build-a-large-language-model-from-scratch) — Sebastian Raschka.

### YouTube Channels

- [Andrej Karpathy](https://youtube.com/@AndrejKarpathy) — Deep dives into neural networks and LLMs from the former OpenAI/Tesla AI director.
- [3Blue1Brown](https://youtube.com/@3blue1brown) — Visual explanations of neural networks and math.
- [Two Minute Papers](https://youtube.com/@TwoMinutePapers) — Accessible summaries of AI research papers.
- [Yannic Kilcher](https://youtube.com/@YannicKilcher) — In-depth ML paper reviews.
- [AI Explained](https://youtube.com/@aiexplained-official) — Clear explanations of AI news and research.

---

## 📊 Benchmarks & Leaderboards

Track the state of the art across different AI capabilities.

| Benchmark | What It Measures | Link |
|---|---|---|
| [LMSYS Chatbot Arena](https://chat.lmsys.org) | Human preference rankings via blind A/B tests | [leaderboard](https://chat.lmsys.org/?leaderboard) |
| [MMLU](https://paperswithcode.com/dataset/mmlu) | Multitask language understanding (57 subjects) | [results](https://paperswithcode.com/sota/multi-task-language-understanding-on-mmlu) |
| [HumanEval](https://github.com/openai/human-eval) | Python code generation correctness | [results](https://paperswithcode.com/sota/code-generation-on-humaneval) |
| [MATH](https://github.com/hendrycks/math) | Competition mathematics | [results](https://paperswithcode.com/sota/math-word-problem-solving-on-math) |
| [GPQA](https://github.com/idavidrein/gpqa) | Graduate-level science questions | [results](https://paperswithcode.com/sota/question-answering-on-gpqa) |
| [SWE-bench](https://swe-bench.github.io) | Real-world software engineering tasks | [leaderboard](https://swe-bench.github.io/leaderboard) |
| [HELM](https://crfm.stanford.edu/helm/) | Holistic evaluation across 42 scenarios | [results](https://crfm.stanford.edu/helm/latest/) |
| [Artificial Analysis](https://artificialanalysis.ai) | Quality, speed, price across 100+ models | [leaderboard](https://artificialanalysis.ai/models) |
| [Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) | Open-weight model benchmarks | [leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) |
| [LLM-Stats](https://llm-stats.com) | 300+ models ranked by intelligence, speed, price | [leaderboard](https://llm-stats.com) |

---

## 🌐 Communities & Newsletters

### Online Communities

- [r/MachineLearning](https://reddit.com/r/MachineLearning) — The largest ML community on Reddit.
- [r/LocalLLaMA](https://reddit.com/r/LocalLLaMA) — Running LLMs locally, open-weight models.
- [r/artificial](https://reddit.com/r/artificial) — General AI news and discussion.
- [Hugging Face Community](https://huggingface.co/community) — Model sharing, datasets, and spaces.
- [AI Alignment Forum](https://alignmentforum.org) — Technical AI safety research and discussion.
- [LessWrong](https://lesswrong.com) — Rationality, AI risk, and long-term thinking.
- [Latent Space Discord](https://discord.gg/latent-space) — AI engineers and researchers community.

### Newsletters

| Newsletter | Focus | Frequency |
|---|---|---|
| [The Batch](https://deeplearning.ai/the-batch/) | AI research & industry news | Weekly |
| [Import AI](https://jack-clark.net) | Technical AI research summaries | Weekly |
| [The Rundown AI](https://therundown.ai) | Daily AI news digest | Daily |
| [TLDR AI](https://tldr.tech/ai) | Curated AI news in 5 minutes | Daily |
| [AI Breakfast](https://aibreakfast.beehiiv.com) | Morning AI news | Daily |
| [Ahead of AI](https://magazine.sebastianraschka.com) | Deep dives into ML research | Monthly |
| [The Gradient](https://thegradient.pub) | Long-form AI research analysis | Irregular |

---

## 📋 Related Awesome Lists

- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM) — Papers, tools, and resources for large language models.
- [Awesome LLMOps](https://github.com/tensorchord/Awesome-LLMOps) — LLMOps tools for developers.
- [Awesome AI Agents](https://github.com/e2b-dev/awesome-ai-agents) — AI autonomous agents and frameworks.
- [Awesome Prompt Engineering](https://github.com/promptslab/Awesome-Prompt-Engineering) — Prompt engineering resources.
- [Awesome AI DevTools](https://github.com/jamesmurdza/awesome-ai-devtools) — AI-powered developer tools.
- [Awesome Vector Search](https://github.com/currentslab/awesome-vector-search) — Vector search libraries and databases.
- [Awesome MLOps](https://github.com/visenger/awesome-mlops) — MLOps tools and resources.
- [Awesome Generative AI](https://github.com/steven2358/awesome-generative-ai) — Generative AI tools and resources.
- [Awesome Open Source AI](https://github.com/alvinreal/awesome-opensource-ai) — Open-source AI projects.
- [Awesome Vibe Coding](https://github.com/filipecalegario/awesome-generative-ai) — AI-assisted coding tools.

---

## Contributing

Contributions are welcome! This list thrives on community input.

**Before submitting a PR, please ensure:**

1. The tool is **actively maintained** (last update within 12 months).
2. The tool is **genuinely useful** — not just a thin wrapper around another API.
3. Your entry follows the format: `` `[Tool Name](https://url.com) — Brief description. #tag` ``
4. Place the tool in the **most appropriate category**.
5. Check for **duplicates** before adding.
6. For new categories, ensure there are at least **5 quality tools** to justify it.

**Quality over quantity.** We prefer a curated list of excellent tools over an exhaustive list of mediocre ones.

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

*Maintained with ❤️ by the community. Last updated: May 2025.*

*Found a broken link or outdated entry? [Open an issue](https://github.com/your-username/awesome-ai-tools/issues).*
