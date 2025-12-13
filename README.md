# AI Automation & AI Agents Roadmap

**(n8n + Python** [You already know] **+ LangChain + LangGraph + LangSmith + LLMOps)**

> Goal: **Build real AI agents that think, decide, call tools, automate workflows, and are production-ready**

## Fundamentals

### 1. What is AI Agent?

* Difference between:
  * Chatbots
  * AI Automation
  * AI Agents

### 2. How AI Agents Actually Work?

* Process: Think → Decide → Act
* Components: LLM, Memory, Tools
* Why prompts alone don’t scale

### 3. LLM Fundamentals (No Math)

* Tokens, Temperature, top-p, top k, Stop Sequence
* System vs user prompts
* Function / Tool calling

### 4. Intro to Automation Thinking

* Event-driven automation
* Stateless vs Stateful workflows
* Idempotency (important)

### 5. Multi-Agent Systems (Most important)

* Single agent vs Multi-agent
* Roles:
  * Planner
  * Executor
  * Validator
* Swarm vs Supervisor pattern
* When NOT to use multi-agent systems

### 6. Memory & Context

* Short-term vs long-term memory
* Context window & Context Rot
* Vector DB basics (PgVector, Supabase, Pinecone, Qdrant)
* When memory is harmful

## Practice Session (Faster) No-Code / Low-Code

### 1. n8n Fundamentals**

**Learn**

* Node and it's type,
* Workflows
* Webhooks
* Auth
* Session
* Credentials
* Execution modes
* Request & Response

**Build**

* Webhook → Gemini (Free) → Response
* Slack / Telegram / Email ChatBot

### 2. AI Inside n8n

**Learn**

* Anthropic, Gemini, OpenAI, Ollama, Guardrails nodes
* AI Agent node
* Basic LLM Chain
* Information Extractor
* Q & A Chain
* Sentiment Analysis
* Summarization Chain
* Text Classifier
* JSON responses/Output Parser

### 3. Tool Calling via n8n

**Learn**

* Treat workflows as tools
* Planner → Executor pattern
* Validation before execution
* Retry & fallback logic

**Build**

* Automate any of the platform for response, guide, work etc. Automate every task of yours from slack/whatsapp/instagram/discord like
  * Meeting schedule on google meet,
  * Todo plan on Google docs or Notion,
  * Research,
  * To get Latest breakthrough in AI/Tech on every friday at 4pm.

### 4. Include additionl Data

**Learn**

* Documents Loader
* Embeddings
* Chunking strategies
* Retrievers/RAG
* RAG vs Finetunning vs Embedding vs Vectorize vs Context (know the difference)

**Build**

* Automate any of the platform for response, by checking your docs and other relavent data. Get information of yours faster by connecting your slack/whatsapp/instagram/discord to google docs, sheets, additional pdf/jpg/mp3 upload, notion, and other application to get information faster.

## Practice Session (Production) Code-First

### 1. LangChain Core

**Learn**

* Chains vs Agents
* Tools abstraction
* Prompt templates
* Deterministic vs non-deterministic agents
* When to freeze vs loop agent state

**Build**

* Tool-calling agent in Python [here](https://github.com/shraysalvi/Agentic-Ai/edit/main/README.md#1-n8n-fundamentals)
* Same logic as n8n but in code

### 2. Memory & Retrieval (RAG)

**Learn**

* Embeddings deeply
* Chunking strategies
* Retrieval failures

**Build**

* PDF / Docs → Agent Q&A
* Memory-aware agent

### 3. LangGraph (IMPORTANT)

**Learn**

* State machines
* Cycles & loops
* Human-in-the-loop
* Agent as a state machine (mental model)
* Failure paths

**Build**

* Graph-based agent
* Same as [here](https://github.com/shraysalvi/Agentic-Ai/edit/main/README.md#3-tool-calling-via-n8n) & [here](https://github.com/shraysalvi/Agentic-Ai/edit/main/README.md#4-include-additionl-data) also try to include human in loop for confirmation.

### 4. Langsmith (Logs and Observation)

**Learn**

* Why traditional logs fail for AI agents
* Traces vs Runs
* Step-by-step agent execution
* Tool call inspection
* Prompt comparison
* Latency + token breakdown

**Build**

* Connect LangChain agent to LangSmith
* Track:
  * Planner decisions
  * Tool calls
  * Final output
* Compare 2 prompts → see which performs better

### 5. Production Automation (Do research on what would be good for your usecase)

**Learn**

* Logging
* Error notifications
* Rate limits
* Secrets management

**Build**

* Monitoring workflow
* Failure alert system


## LLMOps & Production [Advanced / Optional but Career-Defining]

### 1. LLMOps Fundamentals

**Learn**

* Prompt versioning
* Model routing
* Cost tracking
* Eval strategies

### 2. Observability

**Learn**

* Logs vs traces
* Prompt failures
* Hallucination detection

**Build**

* Simple evaluation pipeline
* Output scoring agent

### 3. Safety & Guardrails

**Learn**

* Tool misuse prevention
* Role-based permissions
* Data leakage risks

**Build**

* Policy agent
* Approval workflow

### 4. Performance & Scaling

**Learn**

* Async execution
* Queues (Redis, SQS)
* Caching

**Build**

* High-throughput agent
* Cached tool calls

### 5. Packaging & Deployment

**Learn**

* Docker
* API exposure
* Environment configs
* CI/CD (Not much required)
* Kubernetes/Teraform (Not required much)

**Build**

* Deploy agent
* Share endpoint

# If it helps to you Follow me on [Instagram](https://instagram.com/shraysalvi) ❤️
