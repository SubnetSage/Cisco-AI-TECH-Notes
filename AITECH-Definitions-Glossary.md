# 📖 Key Terms & Definitions: Cisco AITECH (810-110)

This glossary provides definitions for the generative AI and agentic automation terms covered in the Cisco AITECH certification.

---

## 🏗 Model & Data Concepts
*   **LLM (Large Language Model):** A transformer-based model trained on massive text datasets to predict and generate human-like language.
*   **Diffusion Model:** A model family that generates images by reversing a "noise" process (e.g., Stable Diffusion, DALL-E).
*   **Token:** The smallest unit of text processed by a model (can be a word, part of a word, or even a punctuation mark).
*   **Context Window:** The maximum number of tokens a model can keep in memory at one time during a conversation.
*   **RAG (Retrieval-Augmented Generation):** A method that retrieves data from a local knowledge base (Vector DB) and includes it in the prompt to improve a model's accuracy.
*   **Embedding:** A numerical (vector) representation of data (like words or sentences) that allows models to understand similarity and context.
*   **Vector Database:** A specialized database that stores and searches embeddings (e.g., ChromaDB, Pinecone).
*   **Hallucination:** When an AI model generates factually incorrect information that sounds confident and plausible.

---

## 📡 Prompting & Reasoning
*   **Prompt Engineering:** The art and science of crafting inputs to get the most accurate and useful outputs from an AI model.
*   **Zero-Shot:** Asking a model to perform a task without giving it any examples.
*   **Few-Shot:** Providing one or more examples within a prompt to guide the model's output format or reasoning.
*   **Chain of Thought (CoT):** A technique where the model is asked to "think step-by-step," improving its performance on complex logical or mathematical tasks.
*   **System Prompt:** A high-level instruction that sets the personality, role, and persistent constraints of the AI.

---

## 🛡 Security & Ethics
*   **Prompt Injection:** A security vulnerability where a user or data source tricks a model into ignoring its system instructions to perform unauthorized actions.
*   **PII (Personally Identifiable Information):** Sensitive data (like names, addresses, or SSNs) that must be redacted before sending to public AI models for privacy reasons.
*   **Bias:** Systematic errors in a model's output that reflect societal prejudices present in its training data.
*   **Transparency:** The principle that users should be clearly informed when they are interacting with or consuming content from an AI.

---

## 🤖 Agentic AI & Automation
*   **Agentic AI:** A system where an AI model can autonomously plan, reason, and use tools to achieve a specific goal.
*   **MCP (Model Context Protocol):** An open standard for giving LLMs secure access to local tools, databases, and file systems.
*   **Orchestration:** The management of multiple AI models, agents, and tools to work together on a complex task.
*   **HITL (Human-in-the-Loop):** A design pattern where a human provides feedback or approval at critical points in an automated AI workflow.
*   **Tool Use (Function Calling):** The capability of a model to generate structured output that tells a computer to run a specific function (e.g., "Search the web" or "Save to DB").
