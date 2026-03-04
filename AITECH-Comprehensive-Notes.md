# 📖 Comprehensive Study Notes: Cisco AITECH (810-110)
**AI Technical Practitioner Certification**

---

## 🟢 Domain 1.0: Generative AI Models
*   **Model Families:**
    *   **LLMs (Large Language Models):** Transformers (GPT, Llama, Claude). Predict the next token based on probability.
    *   **Diffusion Models:** Stable Diffusion, DALL-E. Use a noise-reduction process to create images or video.
*   **Key Architecture:**
    *   **Self-Attention:** The mechanism allowing models to focus on relevant parts of input text.
    *   **Transformer:** The backbone architecture of modern GenAI models.
*   **Model Deployment:**
    *   **Inference:** The process of using a trained model to generate an output.
    *   **Quantization:** Reducing a model's precision (e.g., from 16-bit to 4-bit) to run on smaller hardware with minimal quality loss.
*   **RAG (Retrieval-Augmented Generation):**
    *   **Process:** Query ➔ Search Vector Database ➔ Feed retrieved info + prompt to LLM ➔ Generate Fact-Based Answer.
    *   **Benefit:** Reduces hallucinations and provides a "source" for information.

---

## 🔵 Domain 2.0: Prompt Engineering
*   **The Anatomy of a Prompt:**
    *   **Role:** Who the AI should act as (e.g., "Senior Developer").
    *   **Context:** Background information about the task.
    *   **Task:** The specific action to perform.
    *   **Output Format:** How the result should look (e.g., "Format as a table").
    *   **Constraint:** What the AI must *not* do (e.g., "Don't use jargon").
*   **Advanced Techniques:**
    *   **Zero-shot:** No examples given.
    *   **One-shot / Few-shot:** 1 or more examples given to guide the AI.
    *   **Chain of Thought (CoT):** Asking the model to "think step-by-step" to improve reasoning in complex problems.
    *   **System Prompt:** A permanent instruction set given to the AI (e.g., "You are a helpful, secure coding assistant").

---

## 🟡 Domain 3.0: Ethics and Security
*   **Responsible AI Principles (Cisco):**
    *   **Fairness:** Models shouldn't discriminate.
    *   **Transparency:** Users should know they are interacting with an AI.
    *   **Safety:** Models shouldn't generate harmful content.
*   **Security Attacks:**
    *   **Prompt Injection:** Direct (user input) vs Indirect (web data) attacks that override system instructions.
    *   **Data Poisoning:** Corrupting the training data to influence model output.
    *   **Model Inversion:** Attempting to extract sensitive data from the model's weights.
*   **AI Policy:** Corporate rules on what data can be sent to external APIs (e.g., forbidding PII or internal IP).

---

## 🟠 Domain 4.0: Data Research and Analysis
*   **The AI Data Lifecycle:** Collection ➔ Cleaning ➔ Formatting ➔ Augmentation ➔ Analysis.
*   **EDA (Exploratory Data Analysis):** Using AI to summarize datasets, generate visualizations, and find outliers.
*   **Synthetic Data:** AI-generated data used to train models when real data is scarce or sensitive (privacy-preserving).

---

## 🔴 Domain 5.0: Development and Workflow Automation
*   **AI for the SDLC:**
    *   **Requirements:** Using AI to draft user stories and PRDs.
    *   **Coding:** Copilots for boilerplate and repetitive tasks.
    *   **Testing:** Automatically generating unit and integration tests.
    *   **Ops:** Log analysis and incident reporting.
*   **Performance Metrics:**
    *   **Perplexity:** How well the model predicts a sample (lower is better).
    *   **Latency:** Time taken to generate the first token (Time to First Token - TTFT).
    *   **Throughput:** Total tokens generated per second.

---

## 🟣 Domain 6.0: Agentic AI
*   **Defining Agents:**
    *   An LLM with a "Loop" that can plan, reason, and use tools (e.g., "Search Google," "Save File").
*   **Architecture Components:**
    *   **Planning:** Task decomposition (breaking one big goal into smaller ones).
    *   **Memory:** Short-term (context window) vs Long-term (vector DB).
    *   **Tool Use (Action):** The ability to call external APIs or execute code.
*   **MCP (Model Context Protocol):**
    *   Developed by Anthropic. A standardized way for LLMs to safely read your local files, browse your DBs, or use your CLI tools without custom coding for every model.
*   **HITL (Human-in-the-Loop):** A security pattern where a human must approve an agent's critical actions (e.g., "Should I send this email?").
