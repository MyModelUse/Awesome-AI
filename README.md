# Awesome AI
[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE)
[![Pull Requests Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

A curated guide to high-quality AI products, open-source projects, and resources.

- [Awesome AI](#awesome-ai)
- [🔥 General AI](#-general-ai)
  - [Major AI Products](#major-ai-products)
  - [Independent Projects](#independent-projects)
  - [Ecosystem \& Infrastructure](#ecosystem--infrastructure)
- [🧩 Agent Skills](#-agent-skills)
  - [General Skills](#general-skills)
  - [Skill Libraries and Marketplaces](#skill-libraries-and-marketplaces)
  - [Build Your Own Skills](#build-your-own-skills)
- [🔌 Model Context Protocol](#-model-context-protocol)
  - [The Protocol Itself](#the-protocol-itself)
  - [Popular Servers](#popular-servers)
  - [Build Your Own Server](#build-your-own-server)
- [✍️ Prompt Engineering](#️-prompt-engineering)
  - [General-Purpose Pattern Libraries](#general-purpose-pattern-libraries)
  - [Optimize and Manage](#optimize-and-manage)
- [🎯 AI Products by Scenario](#-ai-products-by-scenario)
  - [Personal Knowledge Management](#personal-knowledge-management)
  - [Coding](#coding)
    - [Terminal Agents](#terminal-agents)
    - [IDE Extensions](#ide-extensions)
    - [Editors and Platforms](#editors-and-platforms)
    - [Code Review](#code-review)
  - [Media Creation](#media-creation)
    - [Image Generation](#image-generation)
    - [Video Generation](#video-generation)
    - [Speech and Audio](#speech-and-audio)
    - [Music Generation](#music-generation)
    - [3D Generation](#3d-generation)
  - [Writing and Content](#writing-and-content)
  - [Documents and Office](#documents-and-office)
  - [Data Analysis](#data-analysis)
  - [Science and Research](#science-and-research)
  - [Finance](#finance)
- [🔎 AI Search and Browser Agents](#-ai-search-and-browser-agents)
  - [Self-Hosted AI Search](#self-hosted-ai-search)
  - [Browser Control](#browser-control)
- [🏗️ Build Your Own](#️-build-your-own)
  - [Pick an Open-Source Model](#pick-an-open-source-model)
  - [Run the Model](#run-the-model)
  - [Fine-Tune It](#fine-tune-it)
  - [Give It Your Knowledge (RAG)](#give-it-your-knowledge-rag)
  - [Build Applications (you control the flow)](#build-applications-you-control-the-flow)
  - [Build Agents (model controls the flow)](#build-agents-model-controls-the-flow)
  - [Test and Monitor](#test-and-monitor)
  - [Keep It Safe](#keep-it-safe)
- [📚 Learning Resources](#-learning-resources)
  - [Beginner](#beginner)
  - [In-Depth](#in-depth)



---

# 🔥 General AI

The AI landscape at the top level, in three layers: the flagship products most people actually use, the independent open-source projects building the alternatives, and the ecosystem and infrastructure that everything else runs on.

## Major AI Products

Mainstream commercial AI products — general assistants, answer engines, AI agents, and desktop tools that define today's AI experience.

| Project | Badge | Description |
| --- | --- | --- |
| [OpenAI/ChatGPT](https://chatgpt.com) | <img src="https://www.google.com/s2/favicons?domain=chatgpt.com&sz=32" width="16" height="16" alt="favicon"> | Flagship conversational assistant that popularized the category. |
| [Anthropic/Claude](https://claude.ai) | <img src="https://www.google.com/s2/favicons?domain=claude.ai&sz=32" width="16" height="16" alt="favicon"> | Assistant known for long-context reasoning and coding ability. |
| [Google/Gemini](https://gemini.google.com) | <img src="https://www.google.com/s2/favicons?domain=gemini.google.com&sz=32" width="16" height="16" alt="favicon"> | Multimodal assistant integrated across Google's ecosystem. |
| [Microsoft Copilot](https://copilot.microsoft.com) | <img src="https://www.google.com/s2/favicons?domain=microsoft.com&sz=32" width="16" height="16" alt="favicon"> | Microsoft's general-purpose AI assistant integrated with Microsoft products and services. |
| [Perplexity](https://www.perplexity.ai) | <img src="https://www.google.com/s2/favicons?domain=perplexity.ai&sz=32" width="16" height="16" alt="favicon"> | Answer engine that searches the web in real time and cites its sources. |
| [DeepSeek](https://chat.deepseek.com) | <img src="https://www.google.com/s2/favicons?domain=deepseek.com&sz=32" width="16" height="16" alt="favicon"> | Free assistant built on its own open-weight reasoning models. |
| [Grok](https://grok.com) | <img src="https://www.google.com/s2/favicons?domain=grok.com&sz=32" width="16" height="16" alt="favicon"> | xAI's general-purpose AI assistant with web access and real-time information. |
| [Moonshot AI/Kimi](https://www.kimi.com) | <img src="https://www.google.com/s2/favicons?domain=kimi.com&sz=32" width="16" height="16" alt="favicon"> | Long-context assistant for reading, research, and coding. |
| [Le Chat](https://chat.mistral.ai) | <img src="https://www.google.com/s2/favicons?domain=mistral.ai&sz=32" width="16" height="16" alt="favicon"> | Mistral's general-purpose AI assistant for research, writing, coding, and analysis. |
| [Poe](https://poe.com) | <img src="https://www.google.com/s2/favicons?domain=poe.com&sz=32" width="16" height="16" alt="favicon"> | Multi-model AI platform providing access to models and bots from multiple AI providers. |
| [Manus](https://manus.im) | <img src="https://www.google.com/s2/favicons?domain=manus.im&sz=32" width="16" height="16" alt="favicon"> | General-purpose AI agent that performs multi-step research, analysis, coding, and computer tasks. |
| [Genspark](https://www.genspark.ai) | <img src="https://www.google.com/s2/favicons?domain=genspark.ai&sz=32" width="16" height="16" alt="favicon"> | AI workspace combining search, research, content generation, and autonomous agent workflows. |
| [Raycast](https://www.raycast.com) | <img src="https://www.google.com/s2/favicons?domain=raycast.com&sz=32" width="16" height="16" alt="favicon"> | Productivity launcher for macOS and Windows with AI features, commands, extensions, and automation. |
| [Wispr Flow](https://wisprflow.ai) | <img src="https://www.google.com/s2/favicons?domain=wisprflow.ai&sz=32" width="16" height="16" alt="favicon"> | AI-powered voice input tool that turns speech into polished text across desktop applications. |

## Independent Projects

Open-source and community-driven projects — autonomous agents and alternative tools built outside the big platforms.

| Project | Badge | Description |
| --- | --- | --- |
| [OpenManus/OpenManus](https://github.com/OpenManus/OpenManus) | [![stars](https://img.shields.io/github/stars/OpenManus/OpenManus?style=flat-square)](https://github.com/OpenManus/OpenManus/stargazers) | Open-source general-purpose AI agent for executing multi-step tasks. |
| [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | [![stars](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT?style=flat-square)](https://github.com/Significant-Gravitas/AutoGPT/stargazers) | Open-source platform for building and running autonomous AI agents. |
| [bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop) | [![stars](https://img.shields.io/github/stars/bytedance/UI-TARS-desktop?style=flat-square)](https://github.com/bytedance/UI-TARS-desktop/stargazers) | Open-source multimodal GUI agent stack that operates browsers and computer interfaces visually, via desktop app, CLI, or Web UI. |
| [Fosowl/agenticSeek](https://github.com/Fosowl/agenticSeek) | [![stars](https://img.shields.io/github/stars/Fosowl/agenticSeek?style=flat-square)](https://github.com/Fosowl/agenticSeek/stargazers) | Fully local, privacy-focused Manus alternative — an autonomous, voice-enabled agent that browses the web, writes code, and plans complex tasks with no cloud APIs. |
| [HKUDS/nanobot](https://github.com/HKUDS/nanobot) | [![stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=flat-square)](https://github.com/HKUDS/nanobot/stargazers) | Ultra-lightweight, self-hosted personal AI agent with a WebUI, tools, memory, MCP, multi-agent workflows, automation, and chat-app integrations. |
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | [![stars](https://img.shields.io/github/stars/NousResearch/hermes-agent?style=flat-square)](https://github.com/NousResearch/hermes-agent/stargazers) | General-purpose AI agent that executes tasks through tools, skills, and persistent context. |

## Ecosystem & Infrastructure

The layer everything else runs on — model hubs, unified API gateways, inference clouds, and local runtimes. For the developer-focused deep dive into running and serving models yourself, see [Run the Model](#run-the-model).

| Project | Badge | Description |
| --- | --- | --- |
| [Hugging Face](https://huggingface.co) | <img src="https://www.google.com/s2/favicons?domain=huggingface.co&sz=32" width="16" height="16" alt="favicon"> | The hub of open AI — hundreds of thousands of open models, datasets, and demo Spaces, plus libraries like Transformers. |
| [OpenRouter](https://openrouter.ai) | <img src="https://www.google.com/s2/favicons?domain=openrouter.ai&sz=32" width="16" height="16" alt="favicon"> | Unified API to hundreds of LLMs from all major providers with pay-as-you-go pricing. |
| [Replicate](https://replicate.com) | <img src="https://www.google.com/s2/favicons?domain=replicate.com&sz=32" width="16" height="16" alt="favicon"> | Cloud platform for running thousands of open-source models — image, video, text, and more — through a simple API. |
| [Together AI](https://together.ai) | <img src="https://www.google.com/s2/favicons?domain=together.ai&sz=32" width="16" height="16" alt="favicon"> | Cloud platform for running and fine-tuning leading open-source models at production scale. |
| [Fireworks AI](https://fireworks.ai) | <img src="https://www.google.com/s2/favicons?domain=fireworks.ai&sz=32" width="16" height="16" alt="favicon"> | High-speed inference platform serving open-source and custom models for production applications. |
| [BerriAI/litellm](https://github.com/BerriAI/litellm) | [![stars](https://img.shields.io/github/stars/BerriAI/litellm?style=flat-square)](https://github.com/BerriAI/litellm/stargazers) | Unified proxy and SDK for calling 100+ LLM APIs in the OpenAI format, with load balancing and spend tracking. |
| [ollama/ollama](https://github.com/ollama/ollama) | [![stars](https://img.shields.io/github/stars/ollama/ollama?style=flat-square)](https://github.com/ollama/ollama/stargazers) | Tool for downloading, running, and managing large language models locally. |


# 🧩 Agent Skills

Skills are drop-in folders of instructions, scripts, and resources that teach an agent a new ability — like installing an app on your phone. Drop one in, and your agent can suddenly run scientific experiments, follow structured workflows, or self-check its own output. Scenario-specific skills — for coding, writing, office documents, science, and other concrete use cases — are listed under [AI Products by Scenario](#-ai-products-by-scenario).

## General Skills

Skills that don't teach a specific task — they teach the agent how to work: planning, self-checking, and orchestrating its own workflows and other skills.

| Project | Badge | Description |
| --- | --- | --- |
| [obra/superpowers](https://github.com/obra/superpowers) | [![stars](https://img.shields.io/github/stars/obra/superpowers?style=flat-square)](https://github.com/obra/superpowers/stargazers) | Composable skill library and framework that gives coding agents structured workflows for planning, debugging, and shipping. |

## Skill Libraries and Marketplaces

Where skills live — the official repository that launched the pattern, plus catalogs and marketplaces for browsing what's available.

| Project | Badge | Description |
| --- | --- | --- |
| [anthropics/skills](https://github.com/anthropics/skills) | [![stars](https://img.shields.io/github/stars/anthropics/skills?style=flat-square)](https://github.com/anthropics/skills/stargazers) | Official repository of Skills: folders of instructions, scripts, and resources that teach Claude specialized tasks. |
| [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | [![stars](https://img.shields.io/github/stars/anthropics/claude-plugins-official?style=flat-square)](https://github.com/anthropics/claude-plugins-official/stargazers) | Official directory of high-quality Claude Code plugins, which bundle skills, MCP servers, and other components into a single installable package. |
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | [![stars](https://img.shields.io/github/stars/github/awesome-copilot?style=flat-square)](https://github.com/github/awesome-copilot/stargazers) | Community-curated collection of instructions, prompts, agents, and skills for GitHub Copilot. |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | [![stars](https://img.shields.io/github/stars/ComposioHQ/awesome-claude-skills?style=flat-square)](https://github.com/ComposioHQ/awesome-claude-skills/stargazers) | Curated catalog of 1,000+ production-ready skills and plugins that also work across Codex, Cursor, Gemini CLI, and other agents. |
| [wshobson/agents](https://github.com/wshobson/agents) | [![stars](https://img.shields.io/github/stars/wshobson/agents?style=flat-square)](https://github.com/wshobson/agents/stargazers) | Large collection of installable agents, skills, and plugins for Claude Code. |
| [Vercel Skills](https://skills.sh) | <img src="https://www.google.com/s2/favicons?domain=skills.sh&sz=32" width="16" height="16" alt="favicon"> | Marketplace and ecosystem for reusable AI agent skills. |

## Build Your Own Skills

Frameworks and tooling for authoring, testing, and packaging skills yourself.

| Project | Badge | Description |
| --- | --- | --- |
| [agentskills/agentskills](https://github.com/agentskills/agentskills) | [![stars](https://img.shields.io/github/stars/agentskills/agentskills?style=flat-square)](https://github.com/agentskills/agentskills/stargazers) | Open standard and tooling for packaging reusable capabilities that can be installed by AI agents. |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | [![stars](https://img.shields.io/github/stars/vercel-labs/agent-skills?style=flat-square)](https://github.com/vercel-labs/agent-skills/stargazers) | Collection of reusable skills designed for coding agents and AI development workflows. |

# 🔌 Model Context Protocol

MCP is the open protocol that standardizes how models connect to external tools, data sources, and services — think of it as a universal port: any MCP-compatible app can plug into any MCP server. It is fast becoming the standard interface of the agent ecosystem.

## The Protocol Itself

Where the standard lives — specification and official reference implementations.

| Project | Badge | Description |
| --- | --- | --- |
| [modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol) | [![stars](https://img.shields.io/github/stars/modelcontextprotocol/modelcontextprotocol?style=flat-square)](https://github.com/modelcontextprotocol/modelcontextprotocol/stargazers) | Official repository for the Model Context Protocol specification and ecosystem. |
| [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) | [![stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat-square)](https://github.com/modelcontextprotocol/servers/stargazers) | Official reference implementations of Model Context Protocol servers for tools and data. |

## Popular Servers

Ready-to-use servers that connect agents to major platforms — code hosting, browsers, and cloud infrastructure.

| Project | Badge | Description |
| --- | --- | --- |
| [github/github-mcp-server](https://github.com/github/github-mcp-server) | [![stars](https://img.shields.io/github/stars/github/github-mcp-server?style=flat-square)](https://github.com/github/github-mcp-server/stargazers) | Official MCP server for browsing code, managing issues and PRs, monitoring Actions, and automating workflows. |
| [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) | [![stars](https://img.shields.io/github/stars/microsoft/playwright-mcp?style=flat-square)](https://github.com/microsoft/playwright-mcp/stargazers) | Browser automation MCP server based on structured accessibility snapshots rather than screenshots. |
| [awslabs/mcp](https://github.com/awslabs/mcp) | [![stars](https://img.shields.io/github/stars/awslabs/mcp?style=flat-square)](https://github.com/awslabs/mcp/stargazers) | Official suite of specialized MCP servers for AWS services, documentation, and infrastructure workflows. |
| [BrowserMCP/mcp](https://github.com/BrowserMCP/mcp) | [![stars](https://img.shields.io/github/stars/BrowserMCP/mcp?style=flat-square)](https://github.com/BrowserMCP/mcp/stargazers) | MCP server paired with a Chrome extension that automates your real, logged-in browser profile locally and privately. |

## Build Your Own Server

SDKs and scaffolding for developing MCP servers yourself.

| Project | Badge | Description |
| --- | --- | --- |
| [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) | [![stars](https://img.shields.io/github/stars/modelcontextprotocol/python-sdk?style=flat-square)](https://github.com/modelcontextprotocol/python-sdk/stargazers) | Official Python SDK for building MCP clients and servers. |
| [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) | [![stars](https://img.shields.io/github/stars/modelcontextprotocol/typescript-sdk?style=flat-square)](https://github.com/modelcontextprotocol/typescript-sdk/stargazers) | Official TypeScript SDK for building MCP clients and servers. |
| [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) | [![stars](https://img.shields.io/github/stars/modelcontextprotocol/inspector?style=flat-square)](https://github.com/modelcontextprotocol/inspector/stargazers) | Interactive developer tool for testing, debugging, and inspecting MCP servers. |
| [modelcontextprotocol/quickstart-resources](https://github.com/modelcontextprotocol/quickstart-resources) | [![stars](https://img.shields.io/github/stars/modelcontextprotocol/quickstart-resources?style=flat-square)](https://github.com/modelcontextprotocol/quickstart-resources/stargazers) | Example resources and starter material for learning how to build MCP integrations. |

# ✍️ Prompt Engineering

Tools and pattern libraries for working with prompts systematically instead of treating them as throwaway strings — general-purpose pattern collections plus engineering tooling. Scenario-specific prompt libraries live under [AI Products by Scenario](#-ai-products-by-scenario).

## General-Purpose Pattern Libraries

Ready-made prompt collections that work across any task.

| Project | Badge | Description |
| --- | --- | --- |
| [danielmiessler/fabric](https://github.com/danielmiessler/fabric) | [![stars](https://img.shields.io/github/stars/danielmiessler/fabric?style=flat-square)](https://github.com/danielmiessler/fabric/stargazers) | Framework for augmenting humans with composable AI prompt patterns. |
| [f/awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) | [![stars](https://img.shields.io/github/stars/f/awesome-chatgpt-prompts?style=flat-square)](https://github.com/f/awesome-chatgpt-prompts/stargazers) | Large community-curated collection of prompts for ChatGPT and other LLMs. |
| [dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) | [![stars](https://img.shields.io/github/stars/dair-ai/Prompt-Engineering-Guide?style=flat-square)](https://github.com/dair-ai/Prompt-Engineering-Guide/stargazers) | Comprehensive guide and resource collection covering prompt engineering techniques and LLM prompting. |

## Optimize and Manage

For developers who treat prompts as code — optimizing them automatically and managing versions, delivery, and collaboration.

| Project | Badge | Description |
| --- | --- | --- |
| [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy) | [![stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=flat-square)](https://github.com/stanfordnlp/dspy/stargazers) | Framework for programming language models and automatically optimizing prompts and weights. |
| [Humanloop](https://humanloop.com) | <img src="https://www.google.com/s2/favicons?domain=humanloop.com&sz=32" width="16" height="16" alt="favicon"> | Platform for developing, evaluating, and optimizing LLM prompts and applications. |
| [Vellum](https://www.vellum.ai) | <img src="https://www.google.com/s2/favicons?domain=vellum.ai&sz=32" width="16" height="16" alt="favicon"> | Platform for designing, testing, evaluating, and deploying LLM-powered applications. |

# 🎯 AI Products by Scenario

AI products organized by the scenario you are working in — coding, media creation (images, video, speech, music), writing, notes and knowledge, office documents, data analysis, science, and finance. Anything tied to one specific scenario lives here, including scenario-specific agents, skills, and prompt collections; capability sections such as Agent Skills and Prompt Engineering stay general-purpose and cross-scenario.

## Personal Knowledge Management

AI-powered note-taking and second-brain tools — capture, link, and retrieve your personal knowledge with local or cloud models.

| Project | Badge | Description |
| --- | --- | --- |
| [Notion AI](https://www.notion.com/product/ai) | <img src="https://www.google.com/s2/favicons?domain=notion.com&sz=32" width="16" height="16" alt="favicon"> | AI writing assistant and document Q&A built into the Notion workspace. |
| [NotebookLM](https://notebooklm.google.com) | <img src="https://www.google.com/s2/favicons?domain=notebooklm.google.com&sz=32" width="16" height="16" alt="favicon"> | Google's AI research and note-taking tool that works from user-provided sources. |
| [logancyang/obsidian-copilot](https://github.com/logancyang/obsidian-copilot) | [![stars](https://img.shields.io/github/stars/logancyang/obsidian-copilot?style=flat-square)](https://github.com/logancyang/obsidian-copilot/stargazers) | AI copilot plugin for Obsidian — chat with your vault and run private RAG over notes using local or cloud models. |
| [toeverything/AFFiNE](https://github.com/toeverything/AFFiNE) | [![stars](https://img.shields.io/github/stars/toeverything/AFFiNE?style=flat-square)](https://github.com/toeverything/AFFiNE/stargazers) | Open-source workspace combining docs, whiteboards, and kanban with built-in AI writing and drawing features. |
| [khoj-ai/khoj](https://github.com/khoj-ai/khoj) | [![stars](https://img.shields.io/github/stars/khoj-ai/khoj?style=flat-square)](https://github.com/khoj-ai/khoj/stargazers) | Open-source AI second brain — search and chat across your notes, documents, and images, self-hosted or in the cloud. |
| [reorproject/reor](https://github.com/reorproject/reor) | [![stars](https://img.shields.io/github/stars/reorproject/reor?style=flat-square)](https://github.com/reorproject/reor/stargazers) | Local-first AI note-taking app with on-device models, private RAG, semantic search, and automatic note linking. |
| [Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm) | [![stars](https://img.shields.io/github/stars/Mintplex-Labs/anything-llm?style=flat-square)](https://github.com/Mintplex-Labs/anything-llm/stargazers) | All-in-one desktop app for chatting with documents — private RAG, agents, and multi-user workspaces with local or cloud LLMs. |
| [Mem](https://mem.ai) | <img src="https://www.google.com/s2/favicons?domain=mem.ai&sz=32" width="16" height="16" alt="favicon"> | AI-powered workspace for organizing, retrieving, and working with personal knowledge. |
| [Heptabase](https://heptabase.com) | <img src="https://www.google.com/s2/favicons?domain=heptabase.com&sz=32" width="16" height="16" alt="favicon"> | Visual knowledge management and research workspace built around cards, canvases, and structured notes. |
| [Tana](https://tana.inc) | <img src="https://www.google.com/s2/favicons?domain=tana.inc&sz=32" width="16" height="16" alt="favicon"> | Structured knowledge workspace combining notes, databases, AI, and flexible data organization. |

## Coding

AI pair programmers and autonomous software-development agents that write, edit, and review code. The first three groups are organized by where the agent lives — in your terminal, inside your existing editor, or as a full editor or platform of its own — followed by agents that take over one specific job: reviewing pull requests.

### Terminal Agents

Live in the command line — launch, chat, and let them edit your local git repository directly.

| Project | Badge | Description |
| --- | --- | --- |
| [Claude Code](https://claude.com/claude-code) | <img src="https://www.google.com/s2/favicons?domain=claude.com&sz=32" width="16" height="16" alt="favicon"> | Agentic coding tool that works directly with a codebase and terminal to implement software tasks. |
| [openai/codex](https://github.com/openai/codex) | [![stars](https://img.shields.io/github/stars/openai/codex?style=flat-square)](https://github.com/openai/codex/stargazers) | OpenAI's open-source command-line coding agent for working with repositories and software-development tasks. |
| [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | [![stars](https://img.shields.io/github/stars/google-gemini/gemini-cli?style=flat-square)](https://github.com/google-gemini/gemini-cli/stargazers) | Command-line AI agent for coding and working with local development environments. |
| [Aider-AI/aider](https://github.com/Aider-AI/aider) | [![stars](https://img.shields.io/github/stars/Aider-AI/aider?style=flat-square)](https://github.com/Aider-AI/aider/stargazers) | AI pair programming in the terminal that edits code in your local git repository. |
| [sst/opencode](https://github.com/sst/opencode) | [![stars](https://img.shields.io/github/stars/sst/opencode?style=flat-square)](https://github.com/sst/opencode/stargazers) | Terminal-based AI coding agent that works with any LLM provider. |
| [block/goose](https://github.com/block/goose) | [![stars](https://img.shields.io/github/stars/block/goose?style=flat-square)](https://github.com/block/goose/stargazers) | Open-source AI agent for automating software-development and other engineering tasks. |
| [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code) | [![stars](https://img.shields.io/github/stars/QwenLM/qwen-code?style=flat-square)](https://github.com/QwenLM/qwen-code/stargazers) | Open-source terminal coding agent with auto-memory, sub-agents, MCP, and multi-provider support. |
| [1jehuang/jcode](https://github.com/1jehuang/jcode) | [![stars](https://img.shields.io/github/stars/1jehuang/jcode?style=flat-square)](https://github.com/1jehuang/jcode/stargazers) | High-performance, RAM-efficient coding agent harness written in Rust, with MCP support and a TUI. |
| [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) | [![stars](https://img.shields.io/github/stars/PrimeIntellect-ai/prime-agent?style=flat-square)](https://github.com/PrimeIntellect-ai/prime-agent/stargazers) | Self-improving agent built around a Recursive Language Model, for coding workflows and long-running autonomous tasks. |
| [badlogic/pi-mono](https://github.com/badlogic/pi-mono) | [![stars](https://img.shields.io/github/stars/badlogic/pi-mono?style=flat-square)](https://github.com/badlogic/pi-mono/stargazers) | Monorepo containing Pi, a minimal AI coding agent and toolkit for building agentic coding workflows. |

### IDE Extensions

Plug into the editor you already use (VS Code, JetBrains) as a chat, autocomplete, or agent sidebar.

| Project | Badge | Description |
| --- | --- | --- |
| [GitHub Copilot](https://github.com/features/copilot) | <img src="https://www.google.com/s2/favicons?domain=github.com&sz=32" width="16" height="16" alt="favicon"> | AI coding assistant integrated into popular IDEs and GitHub workflows. |
| [cline/cline](https://github.com/cline/cline) | [![stars](https://img.shields.io/github/stars/cline/cline?style=flat-square)](https://github.com/cline/cline/stargazers) | Autonomous coding agent in VS Code that plans and executes multi-step software tasks. |
| [continuedev/continue](https://github.com/continuedev/continue) | [![stars](https://img.shields.io/github/stars/continuedev/continue?style=flat-square)](https://github.com/continuedev/continue/stargazers) | Open-source AI code assistant for VS Code and JetBrains with autocomplete, edit, and chat features. |
| [JetBrains AI Assistant](https://www.jetbrains.com/ai) | <img src="https://www.google.com/s2/favicons?domain=jetbrains.com&sz=32" width="16" height="16" alt="favicon"> | AI assistant integrated into JetBrains IDEs for coding, documentation, refactoring, and development tasks. |
| [Amazon Q Developer](https://aws.amazon.com/q/developer) | <img src="https://www.google.com/s2/favicons?domain=amazon.com&sz=32" width="16" height="16" alt="favicon"> | AI coding assistant for software development and AWS workflows. |
| [Kilo-Org/kilocode](https://github.com/Kilo-Org/kilocode) | [![stars](https://img.shields.io/github/stars/Kilo-Org/kilocode?style=flat-square)](https://github.com/Kilo-Org/kilocode/stargazers) | Open-source AI coding agent and development environment for VS Code and other editors. |
| [PawanOsman/OpenCursor](https://github.com/PawanOsman/OpenCursor) | [![stars](https://img.shields.io/github/stars/PawanOsman/OpenCursor?style=flat-square)](https://github.com/PawanOsman/OpenCursor/stargazers) | Open-source Cursor-like VS Code agent with agentic chat, semantic search, MCP support, and local models via Ollama or llama.cpp. |

### Editors and Platforms

Skip the plugin entirely — AI-first editors and platforms built around agents from the ground up.

| Project | Badge | Description |
| --- | --- | --- |
| [Cursor](https://www.cursor.com) | <img src="https://www.google.com/s2/favicons?domain=cursor.com&sz=32" width="16" height="16" alt="favicon"> | AI-native code editor built around codebase-aware chat, generation, editing, and autonomous coding. |
| [Windsurf](https://windsurf.com) | <img src="https://www.google.com/s2/favicons?domain=windsurf.com&sz=32" width="16" height="16" alt="favicon"> | AI coding editor combining code generation, context awareness, and agentic development workflows. |
| [All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands) | [![stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=flat-square)](https://github.com/All-Hands-AI/OpenHands/stargazers) | Platform for autonomous software-development agents that write code and fix bugs. |
| [Devin](https://devin.ai) | <img src="https://www.google.com/s2/favicons?domain=devin.ai&sz=32" width="16" height="16" alt="favicon"> | AI software engineering agent that can plan, code, debug, and complete development tasks. |
| [Replit](https://replit.com) | <img src="https://www.google.com/s2/favicons?domain=replit.com&sz=32" width="16" height="16" alt="favicon"> | Cloud development platform that uses AI to help users build and deploy applications. |
| [v0](https://v0.dev) | <img src="https://www.google.com/s2/favicons?domain=v0.dev&sz=32" width="16" height="16" alt="favicon"> | AI-powered development platform for generating web interfaces and applications from natural-language prompts. |
| [Bolt.new](https://bolt.new) | <img src="https://www.google.com/s2/favicons?domain=bolt.new&sz=32" width="16" height="16" alt="favicon"> | Browser-based AI development environment for generating and running web applications. |
| [Lovable](https://lovable.dev) | <img src="https://www.google.com/s2/favicons?domain=lovable.dev&sz=32" width="16" height="16" alt="favicon"> | AI-powered application builder for creating full-stack web applications from natural-language descriptions. |
| [zed-industries/zed](https://github.com/zed-industries/zed) | [![stars](https://img.shields.io/github/stars/zed-industries/zed?style=flat-square)](https://github.com/zed-industries/zed/stargazers) | High-performance open-source code editor with integrated AI coding and agent capabilities. |
| [voideditor/void](https://github.com/voideditor/void) | [![stars](https://img.shields.io/github/stars/voideditor/void?style=flat-square)](https://github.com/voideditor/void/stargazers) | Open-source AI code editor forked from VS Code with inline edits and agent mode. |
| [Google Jules](https://jules.google) | <img src="https://www.google.com/s2/favicons?domain=jules.google&sz=32" width="16" height="16" alt="favicon"> | AI coding agent designed to autonomously work on software development tasks. |
| [Firebase Studio](https://firebase.google.com/docs/studio) | <img src="https://www.google.com/s2/favicons?domain=firebase.google.com&sz=32" width="16" height="16" alt="favicon"> | Google's browser-based development environment with AI-assisted application development. |

### Code Review

Self-hostable and hosted agents that review pull requests automatically, so feedback arrives before a human ever looks at the diff.

| Project | Badge | Description |
| --- | --- | --- |
| [CodeRabbit](https://www.coderabbit.ai) | <img src="https://www.google.com/s2/favicons?domain=coderabbit.ai&sz=32" width="16" height="16" alt="favicon"> | AI code review tool that analyzes pull requests and provides contextual review feedback. |
| [Qodo](https://www.qodo.ai) | <img src="https://www.google.com/s2/favicons?domain=qodo.ai&sz=32" width="16" height="16" alt="favicon"> | AI-powered coding platform for code review, testing, and software quality workflows. |
| [Greptile](https://www.greptile.com) | <img src="https://www.google.com/s2/favicons?domain=greptile.com&sz=32" width="16" height="16" alt="favicon"> | AI code review and codebase understanding platform for software development teams. |
| [Graphite](https://graphite.dev) | <img src="https://www.google.com/s2/favicons?domain=graphite.dev&sz=32" width="16" height="16" alt="favicon"> | Developer platform combining stacked pull requests, code review, and AI-assisted development workflows. |
| [qodo-ai/pr-agent](https://github.com/qodo-ai/pr-agent) | [![stars](https://img.shields.io/github/stars/qodo-ai/pr-agent?style=flat-square)](https://github.com/qodo-ai/pr-agent/stargazers) | Open-source AI agent that reviews pull requests, suggests improvements, and assists with code changes. |
| [kodustech/kodus-ai](https://github.com/kodustech/kodus-ai) | [![stars](https://img.shields.io/github/stars/kodustech/kodus-ai?style=flat-square)](https://github.com/kodustech/kodus-ai/stargazers) | Open-source, self-hosted AI code review for GitHub, GitLab, Bitbucket, and Azure DevOps — bring your own LLM. |
| [reviewdog/reviewdog](https://github.com/reviewdog/reviewdog) | [![stars](https://img.shields.io/github/stars/reviewdog/reviewdog?style=flat-square)](https://github.com/reviewdog/reviewdog/stargazers) | Automated code review tool that integrates linters and static-analysis results into pull requests. |


## Media Creation

Models and tools that create media — generating images and video, transcribing and synthesizing speech, and composing music.

### Image Generation

Text-to-image generation and editing — from full-featured web interfaces to the underlying libraries.

| Project | Badge | Description |
| --- | --- | --- |
| [Midjourney](https://www.midjourney.com) | <img src="https://www.google.com/s2/favicons?domain=midjourney.com&sz=32" width="16" height="16" alt="favicon"> | AI image generation platform focused on high-quality visual creation and artistic styles. |
| [comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI) | [![stars](https://img.shields.io/github/stars/comfyanonymous/ComfyUI?style=flat-square)](https://github.com/comfyanonymous/ComfyUI/stargazers) | Node-based graphical interface for building and chaining image-generation pipelines. |
| [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) | [![stars](https://img.shields.io/github/stars/AUTOMATIC1111/stable-diffusion-webui?style=flat-square)](https://github.com/AUTOMATIC1111/stable-diffusion-webui/stargazers) | Web interface for Stable Diffusion — txt2img, img2img, inpainting, upscaling, and a massive extension ecosystem. |
| [Civitai](https://civitai.com) | <img src="https://www.google.com/s2/favicons?domain=civitai.com&sz=32" width="16" height="16" alt="favicon"> | Community hub for image-generation models — checkpoints, LoRAs, and shared creations. |
| [Adobe Firefly](https://www.adobe.com/products/firefly.html) | <img src="https://www.google.com/s2/favicons?domain=adobe.com&sz=32" width="16" height="16" alt="favicon"> | Adobe's generative AI platform for creating and editing images and other creative assets. |
| [huggingface/diffusers](https://github.com/huggingface/diffusers) | [![stars](https://img.shields.io/github/stars/huggingface/diffusers?style=flat-square)](https://github.com/huggingface/diffusers/stargazers) | Modular PyTorch library for state-of-the-art diffusion models, covering image, video, and audio generation. |
| [black-forest-labs/flux](https://github.com/black-forest-labs/flux) | [![stars](https://img.shields.io/github/stars/black-forest-labs/flux?style=flat-square)](https://github.com/black-forest-labs/flux/stargazers) | Repository for FLUX text-to-image generation models and related resources. |
| [lllyasviel/ControlNet](https://github.com/lllyasviel/ControlNet) | [![stars](https://img.shields.io/github/stars/lllyasviel/ControlNet?style=flat-square)](https://github.com/lllyasviel/ControlNet/stargazers) | Framework and models for controlling diffusion-based image generation with additional visual conditions. |
| [Ideogram](https://ideogram.ai) | <img src="https://www.google.com/s2/favicons?domain=ideogram.ai&sz=32" width="16" height="16" alt="favicon"> | AI image generation platform particularly known for typography, posters, and graphic design. |
| [Recraft](https://www.recraft.ai) | <img src="https://www.google.com/s2/favicons?domain=recraft.ai&sz=32" width="16" height="16" alt="favicon"> | AI design platform for generating images, illustrations, vectors, and brand assets. |

### Video Generation

Open models and studios that turn text or images into video.

| Project | Badge | Description |
| --- | --- | --- |
| [Runway](https://runwayml.com) | <img src="https://www.google.com/s2/favicons?domain=runwayml.com&sz=32" width="16" height="16" alt="favicon"> | AI creative platform for generating and editing video and other visual media. |
| [Google Veo](https://deepmind.google/models/veo) | <img src="https://www.google.com/s2/favicons?domain=deepmind.google&sz=32" width="16" height="16" alt="favicon"> | Google's generative video model for creating high-quality video from prompts and other inputs. |
| [Kling AI](https://klingai.com) | <img src="https://www.google.com/s2/favicons?domain=klingai.com&sz=32" width="16" height="16" alt="favicon"> | AI video generation platform for creating and editing videos from text and images. |
| [Luma Dream Machine](https://lumalabs.ai/dream-machine) | <img src="https://www.google.com/s2/favicons?domain=lumalabs.ai&sz=32" width="16" height="16" alt="favicon"> | AI video generation platform for creating cinematic videos from text and images. |
| [Synthesia](https://www.synthesia.io) | <img src="https://www.google.com/s2/favicons?domain=synthesia.io&sz=32" width="16" height="16" alt="favicon"> | AI video platform for creating presenter-led videos with digital avatars and multilingual voiceovers. |
| [HeyGen](https://www.heygen.com) | <img src="https://www.google.com/s2/favicons?domain=heygen.com&sz=32" width="16" height="16" alt="favicon"> | AI video platform for avatars, presenters, translation, and business video creation. |
| [Pika](https://pika.art) | <img src="https://www.google.com/s2/favicons?domain=pika.art&sz=32" width="16" height="16" alt="favicon"> | AI video creation platform for generating and transforming short-form videos. |
| [Tencent-Hunyuan/HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) | [![stars](https://img.shields.io/github/stars/Tencent-Hunyuan/HunyuanVideo?style=flat-square)](https://github.com/Tencent-Hunyuan/HunyuanVideo/stargazers) | Open-source video generation model with over 13B parameters. |
| [Wan-Video/Wan2.1](https://github.com/Wan-Video/Wan2.1) | [![stars](https://img.shields.io/github/stars/Wan-Video/Wan2.1?style=flat-square)](https://github.com/Wan-Video/Wan2.1/stargazers) | Open suite of video foundation models supporting text-to-video and image-to-video. |
| [Lightricks/LTX-Video](https://github.com/Lightricks/LTX-Video) | [![stars](https://img.shields.io/github/stars/Lightricks/LTX-Video?style=flat-square)](https://github.com/Lightricks/LTX-Video/stargazers) | Open-source video generation model designed for efficient text-to-video and image-to-video generation. |

### Speech and Audio

Speech recognition and text-to-speech — transcription, voice cloning, and realtime voice agents.

| Project | Badge | Description |
| --- | --- | --- |
| [ElevenLabs](https://elevenlabs.io) | <img src="https://www.google.com/s2/favicons?domain=elevenlabs.io&sz=32" width="16" height="16" alt="favicon"> | AI platform for text-to-speech, voice cloning, dubbing, and audio generation. |
| [openai/whisper](https://github.com/openai/whisper) | [![stars](https://img.shields.io/github/stars/openai/whisper?style=flat-square)](https://github.com/openai/whisper/stargazers) | Robust multilingual speech recognition and translation model. |
| [SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper) | [![stars](https://img.shields.io/github/stars/SYSTRAN/faster-whisper?style=flat-square)](https://github.com/SYSTRAN/faster-whisper/stargazers) | Faster and more memory-efficient implementation of OpenAI Whisper using CTranslate2. |
| [Descript](https://www.descript.com) | <img src="https://www.google.com/s2/favicons?domain=descript.com&sz=32" width="16" height="16" alt="favicon"> | AI-powered audio and video editor based around transcription and text editing. |
| [Krisp](https://krisp.ai) | <img src="https://www.google.com/s2/favicons?domain=krisp.ai&sz=32" width="16" height="16" alt="favicon"> | AI-powered noise cancellation and meeting audio enhancement software. |
| [fishaudio/fish-speech](https://github.com/fishaudio/fish-speech) | [![stars](https://img.shields.io/github/stars/fishaudio/fish-speech?style=flat-square)](https://github.com/fishaudio/fish-speech/stargazers) | Multilingual text-to-speech system with voice cloning from short reference audio. |
| [FunAudioLLM/CosyVoice](https://github.com/FunAudioLLM/CosyVoice) | [![stars](https://img.shields.io/github/stars/FunAudioLLM/CosyVoice?style=flat-square)](https://github.com/FunAudioLLM/CosyVoice/stargazers) | Multilingual large-scale speech synthesis framework supporting zero-shot voice cloning. |
| [SWivid/F5-TTS](https://github.com/SWivid/F5-TTS) | [![stars](https://img.shields.io/github/stars/SWivid/F5-TTS?style=flat-square)](https://github.com/SWivid/F5-TTS/stargazers) | Flow-matching based text-to-speech system with strong zero-shot voice cloning capabilities. |
| [myshell-ai/OpenVoice](https://github.com/myshell-ai/OpenVoice) | [![stars](https://img.shields.io/github/stars/myshell-ai/OpenVoice?style=flat-square)](https://github.com/myshell-ai/OpenVoice/stargazers) | Open-source instant voice cloning and zero-shot text-to-speech system. |
| [coqui-ai/TTS](https://github.com/coqui-ai/TTS) | [![stars](https://img.shields.io/github/stars/coqui-ai/TTS?style=flat-square)](https://github.com/coqui-ai/TTS/stargazers) | Toolkit for training and running text-to-speech models. |
| [Adobe Podcast](https://podcast.adobe.com) | <img src="https://www.google.com/s2/favicons?domain=adobe.com&sz=32" width="16" height="16" alt="favicon"> | AI audio tools for recording, enhancement, cleanup, and podcast production. |

### Music Generation

Open-source models and interfaces for composing full songs — vocals, lyrics, and instrumentation — from text prompts.

| Project | Badge | Description |
| --- | --- | --- |
| [Suno](https://suno.com) | <img src="https://www.google.com/s2/favicons?domain=suno.com&sz=32" width="16" height="16" alt="favicon"> | AI music generation platform for creating complete songs from natural-language prompts. |
| [Udio](https://udio.com) | <img src="https://www.google.com/s2/favicons?domain=udio.com&sz=32" width="16" height="16" alt="favicon"> | AI music creation platform for generating and editing songs from text prompts. |
| [facebookresearch/audiocraft](https://github.com/facebookresearch/audiocraft) | [![stars](https://img.shields.io/github/stars/facebookresearch/audiocraft?style=flat-square)](https://github.com/facebookresearch/audiocraft/stargazers) | Meta's library for generative audio and music models including MusicGen and AudioGen. |
| [fspecii/ace-step-ui](https://github.com/fspecii/ace-step-ui) | [![stars](https://img.shields.io/github/stars/fspecii/ace-step-ui?style=flat-square)](https://github.com/fspecii/ace-step-ui/stargazers) | Open-source Suno alternative — a local-first professional interface for the ACE-Step AI music generation model. |
| [Stability-AI/stable-audio-tools](https://github.com/Stability-AI/stable-audio-tools) | [![stars](https://img.shields.io/github/stars/Stability-AI/stable-audio-tools?style=flat-square)](https://github.com/Stability-AI/stable-audio-tools/stargazers) | Tools and models for training and generating music and audio with diffusion-based methods. |
| [AIVA](https://www.aiva.ai) | <img src="https://www.google.com/s2/favicons?domain=aiva.ai&sz=32" width="16" height="16" alt="favicon"> | AI music composition platform for generating original music across different styles. |
| [Soundraw](https://soundraw.io) | <img src="https://www.google.com/s2/favicons?domain=soundraw.io&sz=32" width="16" height="16" alt="favicon"> | AI music generation platform for creating customizable royalty-free music. |
| [Beatoven.ai](https://www.beatoven.ai) | <img src="https://www.google.com/s2/favicons?domain=beatoven.ai&sz=32" width="16" height="16" alt="favicon"> | AI music generation platform for creating background and soundtrack music. |

### 3D Generation

Open-source models that turn text or images into 3D assets.

| Project | Badge | Description |
| --- | --- | --- |
| [Tencent-Hunyuan/Hunyuan3D-2](https://github.com/Tencent-Hunyuan/Hunyuan3D-2) | [![stars](https://img.shields.io/github/stars/Tencent-Hunyuan/Hunyuan3D-2?style=flat-square)](https://github.com/Tencent-Hunyuan/Hunyuan3D-2/stargazers) | Open-source framework and models for generating 3D assets from images or text. |

## Writing and Content

Products and tools for drafting, editing, and content-creation workflows.

| Project | Badge | Description |
| --- | --- | --- |
| [Grammarly](https://www.grammarly.com) | <img src="https://www.google.com/s2/favicons?domain=grammarly.com&sz=32" width="16" height="16" alt="favicon"> | AI writing assistant for grammar, rewriting, tone, and content generation. |
| [Jasper](https://www.jasper.ai) | <img src="https://www.google.com/s2/favicons?domain=jasper.ai&sz=32" width="16" height="16" alt="favicon"> | AI content platform focused on marketing, brand content, and business writing. |
| [Copy.ai](https://www.copy.ai) | <img src="https://www.google.com/s2/favicons?domain=copy.ai&sz=32" width="16" height="16" alt="favicon"> | AI platform for marketing content, sales workflows, and business automation. |
| [Writer](https://writer.com) | <img src="https://www.google.com/s2/favicons?domain=writer.com&sz=32" width="16" height="16" alt="favicon"> | Enterprise AI platform for content creation, knowledge assistance, and business workflows. |
| [Sudowrite](https://www.sudowrite.com) | <img src="https://www.google.com/s2/favicons?domain=sudowrite.com&sz=32" width="16" height="16" alt="favicon"> | AI writing assistant designed specifically for fiction and creative writing. |
| [Lex](https://lex.page) | <img src="https://www.google.com/s2/favicons?domain=lex.page&sz=32" width="16" height="16" alt="favicon"> | AI-powered document editor for drafting, rewriting, brainstorming, and collaborative writing. |
| [QuivrHQ/quivr](https://github.com/QuivrHQ/quivr) | [![stars](https://img.shields.io/github/stars/QuivrHQ/quivr?style=flat-square)](https://github.com/QuivrHQ/quivr/stargazers) | Open-source AI-powered knowledge and content assistant for interacting with personal data and documents. |

## Documents and Office

AI tools for working with documents and office files — from full office suites and PDF assistants to open-source parsing, OCR, and document-processing tools.

| Project | Badge | Description |
| --- | --- | --- |
| [Microsoft 365 Copilot](https://www.microsoft.com/microsoft-365/copilot) | <img src="https://www.google.com/s2/favicons?domain=microsoft.com&sz=32" width="16" height="16" alt="favicon"> | AI assistant integrated into Word, Excel, PowerPoint, Outlook, Teams, and Microsoft 365 workflows. |
| [Google Workspace with Gemini](https://workspace.google.com/gemini) | <img src="https://www.google.com/s2/favicons?domain=workspace.google.com&sz=32" width="16" height="16" alt="favicon"> | AI features integrated across Gmail, Docs, Sheets, Meet, and other Google Workspace applications. |
| [Adobe Acrobat AI Assistant](https://www.adobe.com/acrobat/generative-ai-pdf.html) | <img src="https://www.google.com/s2/favicons?domain=adobe.com&sz=32" width="16" height="16" alt="favicon"> | AI assistant for understanding, summarizing, extracting, and working with PDF documents. |
| [Gamma](https://gamma.app) | <img src="https://www.google.com/s2/favicons?domain=gamma.app&sz=32" width="16" height="16" alt="favicon"> | AI-powered platform for creating presentations, documents, and web pages. |
| [microsoft/markitdown](https://github.com/microsoft/markitdown) | [![stars](https://img.shields.io/github/stars/microsoft/markitdown?style=flat-square)](https://github.com/microsoft/markitdown/stargazers) | Python tool for converting files and documents into Markdown for use with LLMs and downstream processing. |
| [Unstructured-IO/unstructured](https://github.com/Unstructured-IO/unstructured) | [![stars](https://img.shields.io/github/stars/Unstructured-IO/unstructured?style=flat-square)](https://github.com/Unstructured-IO/unstructured/stargazers) | Open-source toolkit for preprocessing and extracting structured content from documents. |
| [VikParuchuri/marker](https://github.com/VikParuchuri/marker) | [![stars](https://img.shields.io/github/stars/VikParuchuri/marker?style=flat-square)](https://github.com/VikParuchuri/marker/stargazers) | Fast toolkit for converting PDFs and other documents into clean structured Markdown. |
| [ChatPDF](https://www.chatpdf.com) | <img src="https://www.google.com/s2/favicons?domain=chatpdf.com&sz=32" width="16" height="16" alt="favicon"> | AI tool for asking questions and extracting information from PDF documents. |
| [Humata](https://www.humata.ai) | <img src="https://www.google.com/s2/favicons?domain=humata.ai&sz=32" width="16" height="16" alt="favicon"> | AI document analysis platform for asking questions and extracting insights from uploaded files. |
| [genspark-ai/genoffice](https://github.com/genspark-ai/genoffice) | [![stars](https://img.shields.io/github/stars/genspark-ai/genoffice?style=flat-square)](https://github.com/genspark-ai/genoffice/stargazers) | Open-source AI Office suite for real .docx/.xlsx/.pptx/PDF files, with a built-in agent, CLI, and agent skill for coding agents. |
| [OCRmyPDF/OCRmyPDF](https://github.com/OCRmyPDF/OCRmyPDF) | [![stars](https://img.shields.io/github/stars/OCRmyPDF/OCRmyPDF?style=flat-square)](https://github.com/OCRmyPDF/OCRmyPDF/stargazers) | Adds an OCR text layer to scanned PDF documents while preserving their original appearance. |
| [opendataloader-project/opendataloader-pdf](https://github.com/opendataloader-project/opendataloader-pdf) | [![stars](https://img.shields.io/github/stars/opendataloader-project/opendataloader-pdf?style=flat-square)](https://github.com/opendataloader-project/opendataloader-pdf/stargazers) | Open-source PDF parsing and data-extraction toolkit designed for AI and RAG workflows. |
| [opendatalab/PDF-Extract-Kit](https://github.com/opendatalab/PDF-Extract-Kit) | [![stars](https://img.shields.io/github/stars/opendatalab/PDF-Extract-Kit?style=flat-square)](https://github.com/opendatalab/PDF-Extract-Kit/stargazers) | Toolkit for extracting structured information and elements from complex PDF documents. |
| [snapotter-hq/SnapOtter](https://github.com/snapotter-hq/SnapOtter) | [![stars](https://img.shields.io/github/stars/snapotter-hq/SnapOtter?style=flat-square)](https://github.com/snapotter-hq/SnapOtter/stargazers) | Self-hosted file-processing stack — convert, compress, OCR, transcribe, and run local AI across images, video, audio, PDFs, and documents. |

## Data Analysis

Agents that turn natural-language questions into SQL, charts, hypotheses, and reports — no manual spreadsheeting required.

| Project | Badge | Description |
| --- | --- | --- |
| [Julius AI](https://julius.ai) | <img src="https://www.google.com/s2/favicons?domain=julius.ai&sz=32" width="16" height="16" alt="favicon"> | AI data analyst for exploring datasets, creating visualizations, and performing statistical analysis. |
| [Hex](https://hex.tech) | <img src="https://www.google.com/s2/favicons?domain=hex.tech&sz=32" width="16" height="16" alt="favicon"> | Collaborative analytics platform combining SQL, Python, notebooks, visualization, and AI-assisted analysis. |
| [sinaptik-ai/pandas-ai](https://github.com/sinaptik-ai/pandas-ai) | [![stars](https://img.shields.io/github/stars/sinaptik-ai/pandas-ai?style=flat-square)](https://github.com/sinaptik-ai/pandas-ai/stargazers) | Conversational data-analysis library that lets LLMs interact with pandas DataFrames and other data sources. |
| [marimo-team/marimo](https://github.com/marimo-team/marimo) | [![stars](https://img.shields.io/github/stars/marimo-team/marimo?style=flat-square)](https://github.com/marimo-team/marimo/stargazers) | Reactive Python notebook environment designed for reproducible data analysis and AI-assisted workflows. |
| [DataLab](https://www.datacamp.com/datalab) | <img src="https://www.google.com/s2/favicons?domain=datacamp.com&sz=32" width="16" height="16" alt="favicon"> | AI-powered data analysis environment for working with data, notebooks, and visualizations. |



## Science and Research

Skill collections and tools that turn agents into research collaborators — lab work, literature, and running experiments end-to-end.

| Project | Badge | Description |
| --- | --- | --- |
| [Elicit](https://elicit.com) | <img src="https://www.google.com/s2/favicons?domain=elicit.com&sz=32" width="16" height="16" alt="favicon"> | AI research assistant for finding, screening, extracting, and synthesizing academic papers. |
| [Consensus](https://consensus.app) | <img src="https://www.google.com/s2/favicons?domain=consensus.app&sz=32" width="16" height="16" alt="favicon"> | AI-powered academic search engine that synthesizes findings from scientific research. |
| [Semantic Scholar](https://www.semanticscholar.org) | <img src="https://www.google.com/s2/favicons?domain=semanticscholar.org&sz=32" width="16" height="16" alt="favicon"> | AI-powered academic search engine for discovering and exploring scientific literature. |
| [Scite](https://scite.ai) | <img src="https://www.google.com/s2/favicons?domain=scite.ai&sz=32" width="16" height="16" alt="favicon"> | Research platform that helps users discover and evaluate scientific literature through citation context. |
| [ResearchRabbit](https://www.researchrabbit.ai) | <img src="https://www.google.com/s2/favicons?domain=researchrabbit.ai&sz=32" width="16" height="16" alt="favicon"> | Visual research discovery tool for exploring papers, authors, and citation networks. |
| [Connected Papers](https://www.connectedpapers.com) | <img src="https://www.google.com/s2/favicons?domain=connectedpapers.com&sz=32" width="16" height="16" alt="favicon"> | Visual tool for discovering related academic papers through citation relationships. |
| [SciSpace](https://scispace.com) | <img src="https://www.google.com/s2/favicons?domain=scispace.com&sz=32" width="16" height="16" alt="favicon"> | AI research platform for reading, understanding, and analyzing academic papers. |
| [SakanaAI/AI-Scientist](https://github.com/SakanaAI/AI-Scientist) | [![stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist?style=flat-square)](https://github.com/SakanaAI/AI-Scientist/stargazers) | System that uses AI agents to automate parts of the scientific research process, including idea generation, experimentation, and paper writing. |
| [microsoft/RD-Agent](https://github.com/microsoft/RD-Agent) | [![stars](https://img.shields.io/github/stars/microsoft/RD-Agent?style=flat-square)](https://github.com/microsoft/RD-Agent/stargazers) | AI agent framework for automating research and development workflows. |
| [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | [![stars](https://img.shields.io/github/stars/K-Dense-AI/scientific-agent-skills?style=flat-square)](https://github.com/K-Dense-AI/scientific-agent-skills/stargazers) | 177 validated scientific skills plus 100+ databases for biology, chemistry, medicine, physics, and drug discovery. |
| [Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) | [![stars](https://img.shields.io/github/stars/Orchestra-Research/AI-Research-SKILLs?style=flat-square)](https://github.com/Orchestra-Research/AI-Research-SKILLs/stargazers) | 98 skills across 23 categories for running AI research end-to-end — ideation, training, post-training, inference, and paper writing. |

## Finance

Agents and models for trading research, market analysis, and financial applications.

| Project | Badge | Description |
| --- | --- | --- |
| [Bloomberg Terminal](https://www.bloomberg.com/professional/solutions/bloomberg-terminal) | <img src="https://www.google.com/s2/favicons?domain=bloomberg.com&sz=32" width="16" height="16" alt="favicon"> | Professional financial data and analytics platform used by investors and financial institutions. |
| [AlphaSense](https://www.alpha-sense.com) | <img src="https://www.google.com/s2/favicons?domain=alpha-sense.com&sz=32" width="16" height="16" alt="favicon"> | AI-powered financial and market intelligence platform for research and enterprise decision-making. |
| [Koyfin](https://www.koyfin.com) | <img src="https://www.google.com/s2/favicons?domain=koyfin.com&sz=32" width="16" height="16" alt="favicon"> | Financial analytics platform for market data, charts, screening, and investment research. |
| [FinChat](https://finchat.io) | <img src="https://www.google.com/s2/favicons?domain=finchat.io&sz=32" width="16" height="16" alt="favicon"> | AI financial research platform for analyzing companies, financial data, and investment questions. |
| [Fiscal.ai](https://fiscal.ai) | <img src="https://www.google.com/s2/favicons?domain=fiscal.ai&sz=32" width="16" height="16" alt="favicon"> | AI-powered financial research platform for company analysis, market intelligence, and investment research. |
| [OpenBB-finance/OpenBB](https://github.com/OpenBB-finance/OpenBB) | [![stars](https://img.shields.io/github/stars/OpenBB-finance/OpenBB?style=flat-square)](https://github.com/OpenBB-finance/OpenBB/stargazers) | Open-source investment research platform providing financial data, analytics, and APIs. |
| [microsoft/qlib](https://github.com/microsoft/qlib) | [![stars](https://img.shields.io/github/stars/microsoft/qlib?style=flat-square)](https://github.com/microsoft/qlib/stargazers) | AI-oriented quantitative investment platform for researching and developing quantitative trading strategies. |
| [AI4Finance-Foundation/FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | [![stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinGPT?style=flat-square)](https://github.com/AI4Finance-Foundation/FinGPT/stargazers) | Open-source financial large language models for sentiment analysis, technical analysis, robo-advising, and other fintech applications. |
| [AI4Finance-Foundation/FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) | [![stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRobot?style=flat-square)](https://github.com/AI4Finance-Foundation/FinRobot/stargazers) | Open-source AI agent platform for financial analysis, research, and decision support. |
| [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | [![stars](https://img.shields.io/github/stars/TauricResearch/TradingAgents?style=flat-square)](https://github.com/TauricResearch/TradingAgents/stargazers) | Multi-agent framework for developing and simulating AI-powered trading strategies. |
| [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | [![stars](https://img.shields.io/github/stars/virattt/ai-hedge-fund?style=flat-square)](https://github.com/virattt/ai-hedge-fund/stargazers) | AI-powered hedge fund that makes trading decisions through paper trading and backtesting, for educational and research purposes. |


# 🔎 AI Search and Browser Agents

Open-source answer engines you can self-host, and agents that search the web and drive a browser for you.

## Self-Hosted AI Search

Perplexity popularized the AI answer engine; these open-source projects let you run your own.

| Project | Badge | Description |
| --- | --- | --- |
| [ItzCrazyKns/Perplexica](https://github.com/ItzCrazyKns/Perplexica) | [![stars](https://img.shields.io/github/stars/ItzCrazyKns/Perplexica?style=flat-square)](https://github.com/ItzCrazyKns/Perplexica/stargazers) | Open-source AI-powered search engine that searches the web and cites sources. |
| [zaidmukaddam/scira](https://github.com/zaidmukaddam/scira) | [![stars](https://img.shields.io/github/stars/zaidmukaddam/scira?style=flat-square)](https://github.com/zaidmukaddam/scira/stargazers) | AI-powered search engine that combines web search with LLM-generated answers. |



## Browser Control

From ready-to-use agentic browsers to libraries that let any agent click, fill forms, and run web tasks.

| Project | Badge | Description |
| --- | --- | --- |
| [browser-use/browser-use](https://github.com/browser-use/browser-use) | [![stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square)](https://github.com/browser-use/browser-use/stargazers) | Library that lets AI agents browse websites and automate browser tasks. |
| [browseros-ai/BrowserOS](https://github.com/browseros-ai/BrowserOS) | [![stars](https://img.shields.io/github/stars/browseros-ai/BrowserOS?style=flat-square)](https://github.com/browseros-ai/BrowserOS/stargazers) | Open-source agentic browser — connect Claude Code, Codex, or any MCP agent and hand off web tasks that run in parallel tabs. |
| [Comet](https://www.perplexity.ai/comet) | <img src="https://www.google.com/s2/favicons?domain=perplexity.ai&sz=32" width="16" height="16" alt="favicon"> | AI browser designed to combine web browsing, search, and agentic actions. |
| [Dia](https://diabrowser.com) | <img src="https://www.google.com/s2/favicons?domain=diabrowser.com&sz=32" width="16" height="16" alt="favicon"> | AI-native browser designed for conversational browsing and task assistance. |
| [Browserbase](https://www.browserbase.com) | <img src="https://www.google.com/s2/favicons?domain=browserbase.com&sz=32" width="16" height="16" alt="favicon"> | Infrastructure for running and scaling browser automation and browser-based AI agents. |

# 🏗️ Build Your Own

Everything you need to build your own AI product, in the order you'd actually need it: pick a model, run it, fine-tune it, feed it your data — then build applications or agents on top, and test and protect what you ship.


## Pick an Open-Source Model

The open-weight models themselves — "brains" whose weights you can download and deploy on your own systems, from labs like DeepSeek, Meta, and Alibaba. They are the starting point for everything else in this section.

| Project | Badge | Description |
| --- | --- | --- |
| [deepseek-ai/DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3) | [![stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V3?style=flat-square)](https://github.com/deepseek-ai/DeepSeek-V3/stargazers) | Open-weight Mixture-of-Experts language model with 671B total parameters. |
| [QwenLM/Qwen](https://github.com/QwenLM/Qwen) | [![stars](https://img.shields.io/github/stars/QwenLM/Qwen?style=flat-square)](https://github.com/QwenLM/Qwen/stargazers) | Open-weight language model family covering general, coding, math, and multimodal variants. |
| [meta-llama/llama](https://github.com/meta-llama/llama) | [![stars](https://img.shields.io/github/stars/meta-llama/llama?style=flat-square)](https://github.com/meta-llama/llama/stargazers) | Foundational open-weight large language model family. |
| [moonshotai/Kimi-K2](https://github.com/moonshotai/Kimi-K2) | [![stars](https://img.shields.io/github/stars/moonshotai/Kimi-K2?style=flat-square)](https://github.com/moonshotai/Kimi-K2/stargazers) | Open-weight large language model from Moonshot AI focused on reasoning and agentic capabilities. |
| [THUDM/GLM-4](https://github.com/THUDM/GLM-4) | [![stars](https://img.shields.io/github/stars/THUDM/GLM-4?style=flat-square)](https://github.com/THUDM/GLM-4/stargazers) | Open large language model family developed by the Zhipu AI and Tsinghua GLM team. |

## Run the Model

Tools that make a model actually work — run it on your own laptop (Ollama, llama.cpp), serve thousands of users on a server (vLLM, SGLang), or route between hosted APIs with one unified gateway (LiteLLM, OpenRouter).

| Project | Badge | Description |
| --- | --- | --- |
| [ollama/ollama](https://github.com/ollama/ollama) | [![stars](https://img.shields.io/github/stars/ollama/ollama?style=flat-square)](https://github.com/ollama/ollama/stargazers) | Tool for downloading, running, and managing large language models locally. |
| [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) | [![stars](https://img.shields.io/github/stars/ggml-org/llama.cpp?style=flat-square)](https://github.com/ggml-org/llama.cpp/stargazers) | LLM inference in C/C++ with broad hardware support and the GGUF quantization format. |
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | [![stars](https://img.shields.io/github/stars/vllm-project/vllm?style=flat-square)](https://github.com/vllm-project/vllm/stargazers) | High-throughput, memory-efficient inference and serving engine with PagedAttention. |
| [sgl-project/sglang](https://github.com/sgl-project/sglang) | [![stars](https://img.shields.io/github/stars/sgl-project/sglang?style=flat-square)](https://github.com/sgl-project/sglang/stargazers) | Fast serving engine for LLMs and vision-language models with RadixAttention prefix caching. |
| [huggingface/text-generation-inference](https://github.com/huggingface/text-generation-inference) | [![stars](https://img.shields.io/github/stars/huggingface/text-generation-inference?style=flat-square)](https://github.com/huggingface/text-generation-inference/stargazers) | Production-ready server for deploying and serving Hugging Face language models. |
| [kvcache-ai/ktransformers](https://github.com/kvcache-ai/ktransformers) | [![stars](https://img.shields.io/github/stars/kvcache-ai/ktransformers?style=flat-square)](https://github.com/kvcache-ai/ktransformers/stargazers) | Flexible CPU-GPU heterogeneous inference and fine-tuning framework, optimized for running large MoE models on consumer hardware. |
| [BerriAI/litellm](https://github.com/BerriAI/litellm) | [![stars](https://img.shields.io/github/stars/BerriAI/litellm?style=flat-square)](https://github.com/BerriAI/litellm/stargazers) | Unified proxy and SDK for calling 100+ LLM APIs in the OpenAI format, with load balancing and spend tracking. |
| [OpenRouter](https://openrouter.ai) | <img src="https://www.google.com/s2/favicons?domain=openrouter.ai&sz=32" width="16" height="16" alt="favicon"> | Unified API to hundreds of LLMs from all major providers with pay-as-you-go pricing. |
| [mudler/LocalAI](https://github.com/mudler/LocalAI) | [![stars](https://img.shields.io/github/stars/mudler/LocalAI?style=flat-square)](https://github.com/mudler/LocalAI/stargazers) | Self-hosted OpenAI-compatible API for running local AI models. |

## Fine-Tune It

Make a general model your own — adapt it to your domain, style, or task with efficient methods like LoRA, without retraining from scratch.

| Project | Badge | Description |
| --- | --- | --- |
| [hiyouga/LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) | [![stars](https://img.shields.io/github/stars/hiyouga/LLaMA-Factory?style=flat-square)](https://github.com/hiyouga/LLaMA-Factory/stargazers) | Unified toolkit for efficiently fine-tuning 100+ large language models. |
| [unslothai/unsloth](https://github.com/unslothai/unsloth) | [![stars](https://img.shields.io/github/stars/unslothai/unsloth?style=flat-square)](https://github.com/unslothai/unsloth/stargazers) | Fast, memory-efficient fine-tuning of open LLMs with minimal code. |
| [huggingface/trl](https://github.com/huggingface/trl) | [![stars](https://img.shields.io/github/stars/huggingface/trl?style=flat-square)](https://github.com/huggingface/trl/stargazers) | Transformer Reinforcement Learning library for training and fine-tuning language models. |
| [huggingface/peft](https://github.com/huggingface/peft) | [![stars](https://img.shields.io/github/stars/huggingface/peft?style=flat-square)](https://github.com/huggingface/peft/stargazers) | Parameter-efficient fine-tuning library for adapting large pretrained models with fewer trainable parameters. |
| [axolotl-ai-cloud/axolotl](https://github.com/axolotl-ai-cloud/axolotl) | [![stars](https://img.shields.io/github/stars/axolotl-ai-cloud/axolotl?style=flat-square)](https://github.com/axolotl-ai-cloud/axolotl/stargazers) | Configuration-driven framework for fine-tuning and post-training language models. |
| [h2oai/h2o-llmstudio](https://github.com/h2oai/h2o-llmstudio) | [![stars](https://img.shields.io/github/stars/h2oai/h2o-llmstudio?style=flat-square)](https://github.com/h2oai/h2o-llmstudio/stargazers) | Framework with a no-code GUI for fine-tuning state-of-the-art LLMs — no scripting required. |

## Give It Your Knowledge (RAG)

Not training — just access. Models only know what they were trained on, but these vector databases and retrieval engines look up the right chunks of your own documents at answer time, without touching the model's weights. That's retrieval-augmented generation (RAG).

| Project | Badge | Description |
| --- | --- | --- |
| [run-llama/llama_index](https://github.com/run-llama/llama_index) | [![stars](https://img.shields.io/github/stars/run-llama/llama_index?style=flat-square)](https://github.com/run-llama/llama_index/stargazers) | Data framework for connecting LLMs to external data with indexing and retrieval abstractions. |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | [![stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat-square)](https://github.com/deepset-ai/haystack/stargazers) | Orchestration framework for building retrieval-augmented generation and search pipelines. |
| [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | [![stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=flat-square)](https://github.com/infiniflow/ragflow/stargazers) | Open-source RAG engine with deep document understanding and template-based chunking. |
| [chroma-core/chroma](https://github.com/chroma-core/chroma) | [![stars](https://img.shields.io/github/stars/chroma-core/chroma?style=flat-square)](https://github.com/chroma-core/chroma/stargazers) | AI-native open-source embedding database for storing and querying vector embeddings. |
| [qdrant/qdrant](https://github.com/qdrant/qdrant) | [![stars](https://img.shields.io/github/stars/qdrant/qdrant?style=flat-square)](https://github.com/qdrant/qdrant/stargazers) | High-performance vector database and similarity search engine written in Rust. |
| [milvus-io/milvus](https://github.com/milvus-io/milvus) | [![stars](https://img.shields.io/github/stars/milvus-io/milvus?style=flat-square)](https://github.com/milvus-io/milvus/stargazers) | Cloud-native vector database built for scalable similarity search and embedding retrieval. |
| [weaviate/weaviate](https://github.com/weaviate/weaviate) | [![stars](https://img.shields.io/github/stars/weaviate/weaviate?style=flat-square)](https://github.com/weaviate/weaviate/stargazers) | Cloud-native vector database combining vector similarity search with structured filtering, reranking, and built-in vectorization modules. |
| [pgvector/pgvector](https://github.com/pgvector/pgvector) | [![stars](https://img.shields.io/github/stars/pgvector/pgvector?style=flat-square)](https://github.com/pgvector/pgvector/stargazers) | PostgreSQL extension that adds vector similarity search and embeddings to PostgreSQL. |
| [manticoresoftware/manticoresearch](https://github.com/manticoresoftware/manticoresearch) | [![stars](https://img.shields.io/github/stars/manticoresoftware/manticoresearch?style=flat-square)](https://github.com/manticoresoftware/manticoresearch/stargazers) | Search database for full-text, vector, and hybrid search with real-time indexing and SQL — an Elasticsearch alternative. |

## Build Applications (you control the flow)

One school of building: apps with a flow you design — chatbots, document Q&A, RAG pipelines. You define the steps; the model fills each one in. Ranges from visual, no-code platforms (Dify, n8n) to code libraries (LangChain, Eino, Vercel AI SDK), plus memory layers (Mem0).

| Project | Badge | Description |
| --- | --- | --- |
| [langgenius/dify](https://github.com/langgenius/dify) | [![stars](https://img.shields.io/github/stars/langgenius/dify?style=flat-square)](https://github.com/langgenius/dify/stargazers) | Visual platform for building LLM applications with workflows, agents, and RAG. |
| [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | [![stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat-square)](https://github.com/langchain-ai/langchain/stargazers) | Composable framework for building context-aware reasoning applications. |
| [n8n-io/n8n](https://github.com/n8n-io/n8n) | [![stars](https://img.shields.io/github/stars/n8n-io/n8n?style=flat-square)](https://github.com/n8n-io/n8n/stargazers) | Workflow automation platform with native AI capabilities for chaining models, tools, and services. |
| [vercel/ai](https://github.com/vercel/ai) | [![stars](https://img.shields.io/github/stars/vercel/ai?style=flat-square)](https://github.com/vercel/ai/stargazers) | Provider-agnostic TypeScript toolkit for building AI-powered applications and agents, with UI hooks for React, Vue, Svelte, and Next.js. |
| [FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise) | [![stars](https://img.shields.io/github/stars/FlowiseAI/Flowise?style=flat-square)](https://github.com/FlowiseAI/Flowise/stargazers) | Visual low-code platform for building LLM workflows and AI agents. |
| [langflow-ai/langflow](https://github.com/langflow-ai/langflow) | [![stars](https://img.shields.io/github/stars/langflow-ai/langflow?style=flat-square)](https://github.com/langflow-ai/langflow/stargazers) | Visual framework for building AI applications and agent workflows from reusable components. |
| [mem0ai/mem0](https://github.com/mem0ai/mem0) | [![stars](https://img.shields.io/github/stars/mem0ai/mem0?style=flat-square)](https://github.com/mem0ai/mem0/stargazers) | Memory layer for AI agents that extracts, stores, and retrieves long-term user context. |
| [cloudwego/eino](https://github.com/cloudwego/eino) | [![stars](https://img.shields.io/github/stars/cloudwego/eino?style=flat-square)](https://github.com/cloudwego/eino/stargazers) | The definitive LLM application development framework in Go, with reusable components, an agent development kit, and graph-based composition. |
| [Chainlit/chainlit](https://github.com/Chainlit/chainlit) | [![stars](https://img.shields.io/github/stars/Chainlit/chainlit?style=flat-square)](https://github.com/Chainlit/chainlit/stargazers) | Python framework for building conversational AI applications and LLM interfaces. |

## Build Agents (model controls the flow)

The other school: autonomous loops where the model decides the steps. You give it a goal and a set of tools; it plans, acts, and self-corrects. Mostly frameworks for multi-agent collaboration.

| Project | Badge | Description |
| --- | --- | --- |
| [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) | [![stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=flat-square)](https://github.com/langchain-ai/langgraph/stargazers) | Library for building stateful, multi-actor applications with LLMs as graph-based workflows. |
| [microsoft/autogen](https://github.com/microsoft/autogen) | [![stars](https://img.shields.io/github/stars/microsoft/autogen?style=flat-square)](https://github.com/microsoft/autogen/stargazers) | Framework for building multi-agent systems with conversable agents and tool use. |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | [![stars](https://img.shields.io/github/stars/crewAIInc/crewAI?style=flat-square)](https://github.com/crewAIInc/crewAI/stargazers) | Framework for orchestrating role-playing autonomous agents that collaborate on tasks. |
| [huggingface/smolagents](https://github.com/huggingface/smolagents) | [![stars](https://img.shields.io/github/stars/huggingface/smolagents?style=flat-square)](https://github.com/huggingface/smolagents/stargazers) | Lightweight framework for building AI agents capable of using tools and executing code. |
| [openai/openai-agents-python](https://github.com/openai/openai-agents-python) | [![stars](https://img.shields.io/github/stars/openai/openai-agents-python?style=flat-square)](https://github.com/openai/openai-agents-python/stargazers) | OpenAI's lightweight Python framework for building multi-step AI agents with tools and handoffs. |
| [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | [![stars](https://img.shields.io/github/stars/pydantic/pydantic-ai?style=flat-square)](https://github.com/pydantic/pydantic-ai/stargazers) | Python agent framework built around typed, validated AI application development. |
| [google/adk-python](https://github.com/google/adk-python) | [![stars](https://img.shields.io/github/stars/google/adk-python?style=flat-square)](https://github.com/google/adk-python/stargazers) | Google Agent Development Kit for building, evaluating, and deploying AI agents. |
| [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) | [![stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=flat-square)](https://github.com/microsoft/semantic-kernel/stargazers) | SDK for integrating AI models with tools, memory, plugins, and application workflows. |
| [Microsoft Copilot Studio](https://www.microsoft.com/microsoft-copilot/microsoft-copilot-studio) | <img src="https://www.google.com/s2/favicons?domain=microsoft.com&sz=32" width="16" height="16" alt="favicon"> | Platform for creating custom AI agents and connecting them to business data and applications. |
| [Salesforce Agentforce](https://www.salesforce.com/agentforce) | <img src="https://www.google.com/s2/favicons?domain=salesforce.com&sz=32" width="16" height="16" alt="favicon"> | Enterprise platform for building and deploying AI agents across business workflows. |
| [Amazon Bedrock Agents](https://aws.amazon.com/bedrock/agents) | <img src="https://www.google.com/s2/favicons?domain=amazon.com&sz=32" width="16" height="16" alt="favicon"> | AWS service for building AI agents that use foundation models, tools, and enterprise data. |
| [Google Vertex AI Agent Builder](https://cloud.google.com/products/agent-builder) | <img src="https://www.google.com/s2/favicons?domain=cloud.google.com&sz=32" width="16" height="16" alt="favicon"> | Google Cloud platform for building, deploying, and managing AI agents. |
| [Zapier Agents](https://zapier.com/agents) | <img src="https://www.google.com/s2/favicons?domain=zapier.com&sz=32" width="16" height="16" alt="favicon"> | Platform for creating AI agents that automate tasks across connected applications. |

## Test and Monitor

Check output quality before you ship, then keep watching in production — tracing, metrics, and monitoring platforms for LLM applications.

| Project | Badge | Description |
| --- | --- | --- |
| [langfuse/langfuse](https://github.com/langfuse/langfuse) | [![stars](https://img.shields.io/github/stars/langfuse/langfuse?style=flat-square)](https://github.com/langfuse/langfuse/stargazers) | Open-source observability and analytics platform for LLM applications. |
| [Confident-AI/deepeval](https://github.com/Confident-AI/deepeval) | [![stars](https://img.shields.io/github/stars/Confident-AI/deepeval?style=flat-square)](https://github.com/Confident-AI/deepeval/stargazers) | Evaluation framework for unit-testing LLM outputs and agent pipelines. |
| [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | [![stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=flat-square)](https://github.com/promptfoo/promptfoo/stargazers) | Toolkit for testing, evaluating, red-teaming, and comparing prompts, agents, and RAG systems. |
| [LangSmith](https://www.langchain.com/langsmith) | <img src="https://www.google.com/s2/favicons?domain=langchain.com&sz=32" width="16" height="16" alt="favicon"> | Platform for tracing, evaluating, testing, and monitoring LLM applications and agents. |
| [Braintrust](https://www.braintrust.dev) | <img src="https://www.google.com/s2/favicons?domain=braintrust.dev&sz=32" width="16" height="16" alt="favicon"> | AI evaluation and observability platform for testing and improving LLM applications. |
| [Arize-ai/phoenix](https://github.com/Arize-ai/phoenix) | [![stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=flat-square)](https://github.com/Arize-ai/phoenix/stargazers) | Open-source AI observability and evaluation platform for tracing and analyzing LLM applications. |
| [openai/evals](https://github.com/openai/evals) | [![stars](https://img.shields.io/github/stars/openai/evals?style=flat-square)](https://github.com/openai/evals/stargazers) | Framework for evaluating LLMs and LLM systems, plus an open-source registry of benchmarks. |
| [EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) | [![stars](https://img.shields.io/github/stars/EleutherAI/lm-evaluation-harness?style=flat-square)](https://github.com/EleutherAI/lm-evaluation-harness/stargazers) | Unified framework for evaluating language models across many academic and practical benchmarks. |
| [UKGovernmentBEIS/inspect_ai](https://github.com/UKGovernmentBEIS/inspect_ai) | [![stars](https://img.shields.io/github/stars/UKGovernmentBEIS/inspect_ai?style=flat-square)](https://github.com/UKGovernmentBEIS/inspect_ai/stargazers) | Framework for evaluating AI systems through reproducible benchmark and task-based evaluations. |
| [Weave](https://wandb.ai/site/weave) | <img src="https://www.google.com/s2/favicons?domain=wandb.ai&sz=32" width="16" height="16" alt="favicon"> | AI evaluation and observability platform for tracing and monitoring model applications. |
| [Patronus AI](https://www.patronus.ai) | <img src="https://www.google.com/s2/favicons?domain=patronus.ai&sz=32" width="16" height="16" alt="favicon"> | AI evaluation and safety platform for testing model quality, reliability, and risks. |

## Keep It Safe

Guardrails that constrain what the model can say or do — input/output filtering, policy enforcement, and rails that keep conversational systems safe and on-topic.

| Project | Badge | Description |
| --- | --- | --- |
| [NVIDIA-NeMo/Guardrails](https://github.com/NVIDIA-NeMo/Guardrails) | [![stars](https://img.shields.io/github/stars/NVIDIA-NeMo/Guardrails?style=flat-square)](https://github.com/NVIDIA-NeMo/Guardrails/stargazers) | Toolkit for adding programmable guardrails to conversational LLM systems. |
| [guardrails-ai/guardrails](https://github.com/guardrails-ai/guardrails) | [![stars](https://img.shields.io/github/stars/guardrails-ai/guardrails?style=flat-square)](https://github.com/guardrails-ai/guardrails/stargazers) | Python framework for adding structure, type, and quality validation to LLM outputs. |
| [protectai/llm-guard](https://github.com/protectai/llm-guard) | [![stars](https://img.shields.io/github/stars/protectai/llm-guard?style=flat-square)](https://github.com/protectai/llm-guard/stargazers) | Security toolkit for detecting and preventing common attacks and risks in LLM applications. |
| [Giskard-AI/giskard](https://github.com/Giskard-AI/giskard) | [![stars](https://img.shields.io/github/stars/Giskard-AI/giskard?style=flat-square)](https://github.com/Giskard-AI/giskard/stargazers) | Open-source testing framework for detecting vulnerabilities and performance issues in AI and LLM applications. |
| [Lakera](https://www.lakera.ai) | <img src="https://www.google.com/s2/favicons?domain=lakera.ai&sz=32" width="16" height="16" alt="favicon"> | AI security platform for detecting prompt injection, malicious inputs, and other LLM security threats. |
| [Protect AI](https://protectai.com) | <img src="https://www.google.com/s2/favicons?domain=protectai.com&sz=32" width="16" height="16" alt="favicon"> | AI and machine learning security platform focused on securing models, applications, and supply chains. |
| [HiddenLayer](https://hiddenlayer.com) | <img src="https://www.google.com/s2/favicons?domain=hiddenlayer.com&sz=32" width="16" height="16" alt="favicon"> | AI security platform for protecting machine learning models and AI applications. |

# 📚 Learning Resources

Courses, paper digests, and curated reading paths for learning how modern AI systems work — organized from beginner-friendly introductions to advanced, systems-level practice.

## Beginner

First steps into AI — no deep math or prior ML background required, just basic programming.

| Project | Badge | Description |
| --- | --- | --- |
| [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | [![stars](https://img.shields.io/github/stars/microsoft/AI-For-Beginners?style=flat-square)](https://github.com/microsoft/AI-For-Beginners/stargazers) | 12-week, 24-lesson curriculum covering symbolic AI, neural networks, computer vision, NLP, and AI ethics with PyTorch and TensorFlow notebooks. |
| [microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) | [![stars](https://img.shields.io/github/stars/microsoft/generative-ai-for-beginners?style=flat-square)](https://github.com/microsoft/generative-ai-for-beginners/stargazers) | Beginner-friendly course with 21 lessons on building generative AI applications. |
| [microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners) | [![stars](https://img.shields.io/github/stars/microsoft/ai-agents-for-beginners?style=flat-square)](https://github.com/microsoft/ai-agents-for-beginners/stargazers) | 18-lesson course on building AI agents — agentic frameworks, design patterns, tool use, agentic RAG, planning, multi-agent systems, MCP, and securing agents. |

## In-Depth

For developers comfortable with the basics who want a structured path into LLM engineering, systems internals, and frontier research.

| Project | Badge | Description |
| --- | --- | --- |
| [mlabonne/llm-course](https://github.com/mlabonne/llm-course) | [![stars](https://img.shields.io/github/stars/mlabonne/llm-course?style=flat-square)](https://github.com/mlabonne/llm-course/stargazers) | Structured course roadmap covering LLMs from fundamentals to fine-tuning. |
| [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | [![stars](https://img.shields.io/github/stars/rohitg00/ai-engineering-from-scratch?style=flat-square)](https://github.com/rohitg00/ai-engineering-from-scratch/stargazers) | Massive reference manual with 500+ lessons across 20 phases — deep learning, NLP, agents, MCP, computer vision, and shipping AI products. |
| [datawhalechina/zero-to-sglang](https://github.com/datawhalechina/zero-to-sglang) | [![stars](https://img.shields.io/github/stars/datawhalechina/zero-to-sglang?style=flat-square)](https://github.com/datawhalechina/zero-to-sglang/stargazers) | Hands-on LLM inference course — build a mini-sglang from scratch covering KV cache, continuous batching, and PagedAttention, then read the real source and land a PR. |
