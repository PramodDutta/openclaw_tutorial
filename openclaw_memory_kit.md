# OpenClaw Memory Kit — Simply Explained

Think of this as a **"starter kit" for giving an AI agent a brain, personality, and rules** — so it behaves consistently across conversations. It's like setting up a new employee with a handbook, ID card, and memory notebook.

Here's each file broken down:

**AGENTS.md** — The **rulebook**. It defines how the AI operates: can it spawn sub-agents? What are the security boundaries? How should it behave in group chats? Think of it as the company policy document.

**SOUL.md** — The **personality guide**. Should the AI be formal or casual? Friendly or professional? Funny or serious? This file shapes *how* the AI talks and behaves — its "soul."

**USER.md** — A **template to store info about the user**. Name, preferences, goals — like a CRM card. Each user gets their own filled-in version so the AI remembers who it's talking to.

**MEMORY.md** — An **example of long-term memory**. This shows how the AI should remember things across conversations — like a diary or notebook it can refer back to later.

**HEARTBEAT.md** — **Scheduled/recurring tasks**. Like a cron job for the AI. Every X minutes or messages, it checks: "Do I need to summarize the conversation? Save something to memory? Run a cleanup?" It keeps the AI's memory fresh.

**TOOLS.md** — A **template for listing available tools**. What APIs, databases, or functions can the AI access? It's like telling a new employee "here's your software access list."

**IDENTITY.md** — The AI's **ID card**. What's the AI's name? What version is it? What's its purpose? This is the core identity configuration.

**BOOTSTRAP.md** — The **first-run setup guide**. When the AI starts for the very first time, this file tells it what to do: load memory, read the rules, introduce itself. Like a "Day 1 onboarding checklist."

**memory/ folder** — A **folder structure for storing memories** — past conversations, learned facts, user preferences. Think of it as the AI's filing cabinet.

**businesses/ folder** — A **folder structure for business-specific data**. If the AI works with multiple businesses/clients, each gets its own folder with relevant context.

---

**The big picture analogy for your students:**

> Imagine hiring a new assistant. You'd give them a **rulebook** (AGENTS), describe the **personality** you want (SOUL), hand them a **notebook** about each client (USER + MEMORY), give them a **to-do list that repeats** (HEARTBEAT), list the **tools they can use** (TOOLS), make them an **ID badge** (IDENTITY), and walk them through **Day 1 setup** (BOOTSTRAP). That's exactly what OpenClaw Memory Kit does — but for an AI agent.
