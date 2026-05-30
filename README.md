# awesome-vibe-coding

A curated list of tools, resources, and communities for vibe coders — developers who build with AI-native workflows, natural language prompting, and agent-assisted coding.

Inspired by the broader Awesome List format. Contributions welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Contents

- [What is Vibe Coding?](#what-is-vibe-coding)
- [AI Coding Tools](#ai-coding-tools)
  - [IDE and Editor Assistants](#ide-and-editor-assistants)
  - [Browser-Based App Builders](#browser-based-app-builders)
  - [Agent and Automation Platforms](#agent-and-automation-platforms)
  - [CLI and Terminal Tools](#cli-and-terminal-tools)
- [Learning Resources](#learning-resources)
  - [Articles and Guides](#articles-and-guides)
  - [Video Channels](#video-channels)
  - [Courses and Structured Learning](#courses-and-structured-learning)
- [Communities](#communities)
- [Prompt Engineering and Context Engineering](#prompt-engineering-and-context-engineering)
- [Hiring and Talent](#hiring-and-talent)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)

---

## What is Vibe Coding?

Vibe coding is a style of software development where the developer describes intent in natural language and relies heavily on AI models — large language models, code agents, and inline assistants — to generate, refactor, debug, and deploy code. The term was coined by Andrej Karpathy in early 2025. It is distinct from traditional software engineering in that the practitioner may ship production code without reading every line, instead reviewing, steering, and iterating on AI output.

Vibe coders range from non-technical founders building MVPs with zero prior coding experience to experienced engineers who use AI agents to compress weeks of work into hours.

---

## AI Coding Tools

### IDE and Editor Assistants

- [Cursor](https://cursor.com) - AI-first fork of VS Code. Tab completion, inline chat, codebase-aware context, and multi-file edits. Widely used as the primary vibe coding IDE.
- [Windsurf](https://codeium.com/windsurf) - Agentic IDE by Codeium. Cascade agent can plan, write, and run multi-step tasks autonomously. Good alternative to Cursor with its own model integrations.
- [GitHub Copilot](https://github.com/features/copilot) - Microsoft/OpenAI inline completion and chat. Available in VS Code, JetBrains, and Neovim. Mature, widely deployed, and recently upgraded with GPT-4o and Claude support.
- [Zed](https://zed.dev) - High-performance collaborative editor with native AI assistant (Claude integration). Fast, Rust-based, increasingly popular for AI-assisted workflows.
- [Continue](https://continue.dev) - Open-source VS Code and JetBrains extension. Bring your own model (Ollama, OpenAI, Anthropic, etc.). Good for privacy-conscious or self-hosted setups.
- [Supermaven](https://supermaven.com) - Fast autocomplete trained specifically for speed. Lower latency than most alternatives; pairs well with other chat-based tools.

### Browser-Based App Builders

- [Lovable](https://lovable.dev) - Prompt-to-app builder targeting non-technical founders. Generates full-stack React + Supabase apps from natural language. Strong for MVPs and prototypes.
- [Bolt.new](https://bolt.new) - StackBlitz's AI app builder. Runs Node.js in-browser via WebContainers. Fast iteration, good for frontend-heavy projects.
- [v0](https://v0.dev) - Vercel's UI generation tool. Specialises in React/Next.js + Tailwind component generation from text or screenshot. Outputs clean, copy-pasteable code.
- [Replit](https://replit.com) - Cloud IDE with Replit Agent for full-stack app generation. Includes hosting, databases, and deployments. Popular for rapid prototyping and learning.
- [Val.town](https://val.town) - Social coding platform for writing and deploying TypeScript functions (vals) in the browser, often with AI assistance.

### Agent and Automation Platforms

- [n8n](https://n8n.io) - Open-source workflow automation platform. Heavily used by vibe coders and AI builders to wire APIs, triggers, and AI models without writing glue code. Self-hostable.
- [Zapier](https://zapier.com) - No-code automation. Broad connector library. Good starting point before graduating to n8n or custom agents.
- [Make (formerly Integromat)](https://make.com) - Visual workflow builder. More powerful than Zapier for complex branching; popular in the no-code/vibe community.
- [Langflow](https://github.com/langflow-ai/langflow) - Open-source visual builder for LangChain-based agent pipelines. Drag-and-drop agentic workflow construction.
- [Dify](https://dify.ai) - Open-source LLM app development platform. Prompt IDE, RAG pipelines, agent orchestration, and API publishing.
- [Flowise](https://github.com/FlowiseAI/Flowise) - Open-source drag-and-drop UI for building LLM flows. Self-hostable, LangChain-compatible.

### CLI and Terminal Tools

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - Anthropic's official agentic CLI. Runs in your terminal, understands entire codebases, edits files, runs tests, and manages git. Best-in-class for context-window utilisation and multi-file tasks.
- [Aider](https://github.com/paul-gauthier/aider) - Open-source CLI pair programmer. Works with any OpenAI-compatible model. Git-aware, supports whole-repo context, and outputs clean diffs.
- [OpenHands (formerly OpenDevin)](https://github.com/All-Hands-AI/OpenHands) - Open-source autonomous software agent. Runs in a sandboxed environment, can browse, write code, run commands, and complete multi-step dev tasks.
- [SWE-agent](https://github.com/princeton-nlp/SWE-agent) - Research-grade autonomous agent from Princeton. Designed to solve GitHub issues end-to-end. Useful as a reference implementation for agentic coding.

---

## Learning Resources

### Articles and Guides

- [Andrej Karpathy — "Vibe Coding" (Twitter/X thread, Feb 2025)](https://x.com/karpathy) - The post that named the movement.
- [Simon Willison's Weblog](https://simonwillison.net) - Prolific technical writing on LLMs, prompt engineering, and practical AI tool use. High signal-to-noise.
- [Lilian Weng — LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) - Dense but foundational post on agent architecture: planning, memory, tool use.
- [Anthropic Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) - Official, practical, model-specific guidance on getting the most out of Claude.
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering) - Complementary reference covering GPT-series models.
- [The Pragmatic Engineer — AI-assisted coding deep dives](https://newsletter.pragmaticengineer.com) - Paid newsletter but free posts cover real-world AI coding adoption at companies.

### Video Channels

- [Fireship](https://www.youtube.com/@Fireship) - Short-form technical explainers. Covers new AI tools quickly and without hype.
- [Matt Wolfe](https://www.youtube.com/@mreflow) - Broad AI tool coverage including coding tools, agents, and no-code builders.
- [Greg Isenberg](https://www.youtube.com/@GregIsenberg) - Startup ideas, vibe coding walkthroughs, and founder interviews. Popular in the no-code/AI founder space.
- [Nick Dobos (Nick.ai)](https://www.youtube.com/@NickAI) - Cursor, Claude, and agent workflow deep dives.
- [Traversy Media](https://www.youtube.com/@TraversyMedia) - Traditional web dev but increasingly covers Copilot, v0, and AI-assisted full-stack builds.

### Courses and Structured Learning

- [fast.ai — Practical Deep Learning](https://course.fast.ai) - Not vibe-coding-specific, but strong foundations in how models work. Helps you understand why prompting works the way it does.
- [DeepLearning.AI short courses](https://deeplearning.ai/short-courses/) - Free short courses on prompt engineering, LangChain, agents, RAG. Practical, quick, frequently updated.
- [Replit 100 Days of Code](https://replit.com/learn) - Beginner-friendly coding curriculum that integrates Replit Agent throughout.
- [Scrimba — AI Engineer path](https://scrimba.com) - Interactive browser-based learning for JavaScript/React with AI integration modules.

---

## Communities

- [r/vibecoding](https://reddit.com/r/vibecoding) - Main Reddit home for the vibe coding movement. Build showcases, tool discussions, beginner questions.
- [r/ChatGPTCoding](https://reddit.com/r/ChatGPTCoding) - Broader AI coding community with strong overlap. Active discussions on Cursor, Claude, and agents.
- [r/LocalLLaMA](https://reddit.com/r/LocalLLaMA) - Self-hosted model community. Relevant for vibe coders who want to run coding models locally (Ollama, LM Studio, etc.).
- [Cursor Community Forum](https://forum.cursor.com) - Official Cursor user community. Bug reports, tips, model comparisons, keybinding setups.
- [Lovable Discord](https://discord.gg/lovable) - Active community of Lovable users sharing builds, asking for help, and discussing prompting strategies.
- [Indie Hackers](https://indiehackers.com) - Not AI-specific but heavily frequented by solo founders using vibe coding to build products.
- [Buildspace](https://buildspace.so) - Cohort-based community for builders. Increasingly AI and agent-focused.
- [AI Tinkerers](https://aitinkerers.org) - In-person and online meetup network for people building with LLMs. Active in many cities.

---

## Prompt Engineering and Context Engineering

Context engineering is the emerging discipline of structuring, scoping, and managing the information an AI model receives — going beyond single prompts to persistent memory, retrieval systems, and agentic context windows.

- [CLAUDE.md pattern](https://docs.anthropic.com/en/docs/claude-code/memory) - Using a repository-level markdown file to give Claude Code persistent context about a project. Widely adopted pattern.
- [Cursor Rules (.cursorrules)](https://cursor.directory) - Community-maintained collection of `.cursorrules` files for different stacks and use cases. Drop-in context files for Cursor projects.
- [Promptbase](https://promptbase.com) - Marketplace for prompts. Useful for inspiration; quality varies.
- [Learn Prompting](https://learnprompting.org) - Open-source guide to prompt engineering techniques. Covers chain-of-thought, few-shot, role prompting, and more.
- [Fabric](https://github.com/danielmiessler/fabric) - Open-source framework of reusable AI prompt patterns (called "patterns") for common tasks. CLI-first.

---

## Hiring and Talent

Resources for finding and hiring vibe coders, AI-native developers, and context engineers — or getting listed as one.

- [wenhire](https://wenhire.xyz) - Zero-commission talent directory for vibe coders, AI-native developers, and web3 builders. Individual developer profiles are public and Google-indexed (no gated login required to browse). Companies post from $19; talent lists from $5/yr. India-first supply. Also runs a "fix my vibe-coded app" rescue marketplace for broken Lovable/Bolt/Cursor projects. Pre-launch with waitlist open.
- [Wellfound](https://wellfound.com) - Startup-focused job board (formerly AngelList Talent). Good for finding AI engineer roles at early-stage companies.
- [arc.dev](https://arc.dev) - Vetted remote developer network. Covers a broad range of specialisations including AI/ML engineering roles.
- [Toptal](https://toptal.com) - Top-3% vetting, higher cost, sales-call required. Worth knowing about for enterprise hiring contexts.

---

## Related Awesome Lists

- [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) - Large collection of system prompts and persona prompts.
- [awesome-llm](https://github.com/Hannibal046/Awesome-LLM) - Comprehensive list of LLM papers, tools, and resources. More research-oriented.
- [awesome-langchain](https://github.com/kyrolabs/awesome-langchain) - LangChain tools, templates, and integrations.
- [awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) - Curated list of AI agent frameworks and products.
- [awesome-claude-prompts](https://github.com/langgptai/awesome-claude-prompts) - Prompts and system prompt patterns for Claude.
- [awesome-no-code](https://github.com/kairichard/awesome-nocode) - No-code tools with significant overlap with the vibe coding toolchain.

---

## Contributing

1. Fork the repo and create a branch.
2. Add your resource to the relevant section in alphabetical order within its category.
3. Keep descriptions factual, concise (one sentence is fine), and free of marketing language.
4. Do not add tools you have a financial interest in without disclosing it in your PR.
5. Links must be to live, maintained projects. Dead links will be removed.
6. Open a pull request. PRs that add only self-promotional links will be closed.

---

## License

[CC0 1.0 Universal](LICENSE) — public domain. Use freely.
