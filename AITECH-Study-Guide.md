# 📚 Study Guide: Cisco AI Technical Practitioner (AITECH 810-110)
**Cisco Certified Support Technician - AI (CCST-AI)**

## 1.0 Generative AI Models (20%)
*   **Model Families:** LLMs (Text), Diffusion Models (Images/Video), Audio Models.
*   **Common Use Cases:** Text summarization, content creation, code generation, translation.
*   **Hosting Trade-offs:**
    *   **Cloud-hosted:** Fast deployment, scalable, but higher cost (per-token) and privacy concerns.
    *   **Locally hosted:** Privacy, lower long-term cost, but high hardware requirement and maintenance.
*   **Key Concepts:**
    *   **Context Window:** The limit of tokens a model can process at once.
    *   **Token Limits:** How text is broken down (1000 tokens ≈ 750 words).
    *   **RAG (Retrieval Augmented Generation):** Connecting a model to external data via embeddings and vector databases to reduce hallucinations.

## 2.0 Prompt Engineering (15%)
*   **Principles:** Clear roles, specific instructions, and constraints.
*   **Techniques:**
    *   **Few-shot:** Providing examples in the prompt.
    *   **Chaining:** Breaking complex tasks into smaller, sequential steps.
    *   **Iterative/Sequential:** Refining prompts based on model output.
*   **Mitigation:** Defensive prompting to prevent hallucinations and model "drift."

## 3.0 Ethics and Security (15%)
*   **Responsible AI Principles:** Fairness, transparency, accountability, and bias mitigation.
*   **Security Threats:**
    *   **Prompt Injection:** Tricking the model into ignoring system instructions.
    *   **Data Privacy:** Protecting corporate IP from being used in public training sets.
*   **Governance:** Risk management, compliance with AI policies, and monitoring for misinformation.

## 4.0 Data Research and Analysis (10%)
*   **EDA (Exploratory Data Analysis):** Using AI to find patterns in datasets.
*   **Automated Data Prep:** Formatting, cleaning, and transforming data for AI models.
*   **Ethics in Analysis:** Ensuring AI-assisted data analysis doesn't expose PII (Personally Identifiable Information).

## 5.0 Development and Workflow Automation (20%)
*   **AI for Code:** Debugging assistance, error handling, and automated documentation.
*   **Software Lifecycle:** AI role in requirements, prototyping, and testing.
*   **Workflow Design:** Monitoring AI-driven tasks and managing token usage costs.

## 6.0 Agentic AI (20%)
*   **GenAI vs. Agentic AI:** GenAI *creates content*; Agentic AI *performs tasks* autonomously.
*   **Agent Design:** Orchestration of multiple tools and autonomous capabilities.
*   **MCP (Model Context Protocol):** Primitives for giving agents access to local tools and context.
*   **HITL (Human-in-the-Loop):** Strategies to ensure human oversight in automated agent workflows.
