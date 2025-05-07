## Frameworks
- CrewAI — Orchestrates multiple agents working together. Ideal for tasks that need coordination and role-based behavior.
- Agno — Focuses on memory, tool use, and long-term interactions. Great for assistants that need to remember and adapt.
- Camel — Designed for multi-agent collaboration, simulation, and task specialization.
- AutoGPT — Automates complex workflows with a loop of planning and execution. Best for agents that need to run independently.
- AutoGen—Lets agents communicate with each other to solve complex problems.
- SuperAGI — Streamlined setup for building and shipping autonomous agents fast.
- Superagent — A flexible open-source toolkit to create custom AI assistants.
- LangChain & LlamaIndex — The go-to tools for managing memory, retrieval, and toolchains.

## Computer & Browser
- Open Interpreter — Translates natural language into executable code on your machine. Want to move files or run a script? Just describe it.
- Self-Operating Computer — Gives agents full control of your desktop environment, allowing them to interact with your OS like a person would.
- Agent-S — A flexible framework that lets AI agents use apps, tools, and interfaces like a real user.
- LaVague — Enables web agents to navigate sites, fill forms, and make decisions in real time — ideal for automating browser tasks.
- Playwright — Automates web actions across browsers. Handy for testing or simulating user flows.
- Puppeteer — A reliable tool for controlling Chrome or Firefox. Great for scraping and automating front-end behavior.

## Voice
- Ultravox — A top-tier speech-to-speech model that handles real-time voice conversations smoothly. Fast and responsive. (speech2speech)
- Moshi — Another strong option for speech-to-speech tasks. Reliable for live voice interaction, though Ultravox has the edge on performance. (speech2speech)
- Pipecat — A full-stack framework for building voice-enabled agents. Includes support for speech-to-text, text-to-speech, and even video-based interactions. (speech2speech)
- Whisper — OpenAI’s speech-to-text model — great for transcription and speech recognition across multiple languages. (speech2text)
- Stable-ts — A more developer-friendly wrapper around Whisper. Adds timestamps and real-time support, making it great for conversational agents. (speech2text)
- Speaker Diarization 3.1 — Pyannote’s model for detecting who’s speaking when. Crucial for multi-speaker conversations and meeting-style audio. (speech2text)
- ChatTTS — The best model I’ve found so far. It’s fast, stable, and production-ready for most use cases. (text2speech)
- ElevenLabs (Commercial)— When quality matters more than open source, this is the go-to. It delivers highly natural-sounding voices and supports multiple styles. (text2speech)
- Cartesia (Commercial) — Another strong commercial option if you’re looking for expressive, high-fidelity voice synthesis beyond what open models can offer. (text2speech)
- Vocode — A toolkit for building voice-powered LLM agents. Makes it easy to connect speech input/output with language models. (tooling)
- Voice Lab — A framework for testing and evaluating voice agents. Useful for dialing in the right prompt, voice persona, or model setup. (tooling)

## Document Understanding
- Qwen2-VL — A powerful vision-language model from Alibaba. Outperforms GPT-4 and Claude 3.5 Sonnet on document tasks that mix images and text — great for handling complex, real-world formats.
- DocOwl2 — A lightweight multimodal model built for document understanding without OCR. Fast, efficient, and surprisingly accurate for extracting structure and meaning from messy inputs.

## Memory
- Mem0 — A self-improving memory layer that lets your agent adapt to previous interactions. Great for building more personalized and persistent AI experiences.
- Letta (formerly MemGPT) — Adds long-term memory and tool use to LLM agents. Think of it as scaffolding for agents that need to remember, reason, and evolve.
- LangChain — Includes plug-and-play memory components for tracking conversation history and user context — handy when building agents that need to stay grounded across multiple turns.

## Testing n Evaluation
- eeVoice Lab — A comprehensive framework for testing voice agents, ensuring your agent’s speech recognition and responses are accurate and natural.
- AgentOps — A set of tools for tracking and benchmarking AI agents, helping you spot any issues and optimize performance before they impact users.
- AgentBench — A benchmark tool for evaluating LLM agents across various tasks and environments, from web browsing to gaming, ensuring versatility and effectiveness.

## Monitoring
- openllmetry — Provides end-to-end observability for LLM applications using OpenTelemetry, giving you a clear view of agent performance and helping you troubleshoot and optimize quickly.
- AgentOps — A comprehensive monitoring tool that tracks agent performance, cost, and benchmarking, helping you ensure your agents are efficient and within budget.

## Simulation
- AgentVerse — Supports deploying multiple LLM-based agents across diverse applications and simulations, ensuring effective functioning in various environments.
- Tau-Bench — A benchmarking tool that evaluates agent-user interactions in specific industries like retail or airlines, ensuring smooth handling of domain-specific tasks.
- ChatArena — A multi-agent language game environment where agents interact, ideal for studying agent behavior and refining communication patterns in a safe, controlled space.
- AI Town — A virtual environment where AI characters interact socially, test decision-making, and simulate real-world scenarios, helping to fine-tune agent behavior.
- [Generative Agents](https://github.com/joonspk-research/generative_agents) — A Stanford project focused on creating human-like agents that simulate complex behaviors, perfect for testing memory and decision-making in social contexts.

## Vertical Agents
- Gurubase - Gurubase lets you add an "Ask AI" button to your technical docs, turning your content into an AI assistant.
- OpenHands — A platform for software development agents powered by AI, designed to automate coding tasks and speed up the development process.
- aider— A pair programming tool that integrates directly with your terminal, offering an AI co-pilot to assist right in your coding environment.
- GPT Engineer— Build applications using natural language; simply describe what you want, and the AI will clarify and generate the necessary code.
- screenshot-to-code — Converts screenshots into fully functional websites with HTML, Tailwind, React, or Vue, great for turning design ideas into live code quickly.
- GPT Researcher—An autonomous agent that conducts comprehensive research, analyzes data, and writes reports, streamlining the research process.
- Vanna — Interact with your SQL database using natural language queries; no more complicated SQL commands, just ask questions, and Vanna retrieves the data.
