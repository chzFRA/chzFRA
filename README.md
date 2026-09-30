# Hi, I'm Huazhe Cheng

Building practical tools for **everyday work with AI**, while exploring **agent reliability** and **document intelligence**.

I’m interested in making AI work easier to organize, inspect, and reuse. My projects focus on a clear task, a runnable example, and honest limits. The browser tools below process selected files locally, without an account or model API key.

## Selected projects

| Project | What to explore | Status |
| --- | --- | --- |
| [ChatShelf · 对话书架](https://github.com/chzFRA/chat-shelf) | Search known AI chat exports, inspect conversation branches, and save Markdown notes | [Try in your browser](https://chzfra.github.io/chat-shelf/) · v0.1 |
| [Doc to Context · 文档备料台](https://github.com/chzFRA/doc-to-context) | Turn PDF/text into size-bounded material packets with page references for your AI | [Try in your browser](https://chzfra.github.io/doc-to-context/) · v0.1 |
| [AgentTrace Lab](https://github.com/chzFRA/agent-trace-lab) | Trace Python tools, catch call/error regressions, and diagnose MCP tool failures | v0.3 · real MCP example · reproducible checks |
| [Real Estate Legal QA](https://github.com/chzFRA/real-estate-qa-clean) | New Zealand legal PDF processing, question generation, and retrieval experiments | Research prototype · reproducibility improvements needed |

Start with a browser tool and its built-in example. ChatShelf organizes existing text; Doc to Context prepares materials for the AI you already use. Neither tool generates model answers. Their READMEs explain supported inputs and what is tested.

For developers, AgentTrace Lab records tool timing, exceptions, and nested calls. Its real MCP example demonstrates a request that returns normally while the tool reports an error. [中文上手教程](https://github.com/chzFRA/agent-trace-lab/blob/main/docs/QUICKSTART.zh-CN.md) · [Validation evidence](https://github.com/chzFRA/agent-trace-lab/blob/main/docs/VALIDATION.md) · [Learning path](https://github.com/chzFRA/agent-trace-lab/blob/main/docs/LEARNING_PATH.zh-CN.md).

## Learning from the community

These are upstream projects I’m learning from, maintained by their respective communities. The learning path connects each one to a concrete exercise. A local MCP client/server example is implemented; the other framework integrations remain future work.

| Upstream project | Learning focus |
| --- | --- |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | Agent loops, tool calls, and trace events |
| [LangGraph](https://github.com/langchain-ai/langgraph) | State, checkpoints, and recovery after interruption |
| [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) | Standard tool interfaces and local client/server integration |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) | Evaluation datasets, scoring, and inspectable experiment logs |

## What I'm exploring

- **Agent reliability:** measurable behavior under tool failures and limited execution budgets.
- **Evidence-based QA:** connecting answers to source documents and evaluating retrieval quality.
- **Multimodal document understanding:** extending text pipelines to page images, tables, and visual evidence.

The multimodal work is a direction for future development. Project READMEs distinguish implemented features, synthetic evaluations, and planned extensions.

---

你好，我是 Huazhe Cheng。我在做普通人也能直接使用的 AI 配套工具：用「对话书架」找回并整理聊天记录，用「文档备料台」准备带来源的文档材料；同时用 AgentTrace Lab 学习工具执行与可靠性。文档问答项目仍是研究原型，多模态是后续方向。欢迎通过项目 Issues 告诉我具体使用问题和改进建议，请使用虚构或脱敏样例。
