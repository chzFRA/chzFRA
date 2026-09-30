# Hi, I'm Huazhe Cheng

Exploring **reliable AI agents**, **document intelligence**, and **multimodal systems**.

I’m interested in how AI systems find evidence, use tools, and recover when something goes wrong. I’m building small tools and reproducible experiments that help me understand those systems and give others something useful to inspect and try.

## Selected projects

| Project | What to explore | Status |
| --- | --- | --- |
| [AgentTrace Lab](https://github.com/chzFRA/agent-trace-lab) | Trace Python tools, catch call/error regressions, and diagnose MCP tool failures | v0.3 · real MCP example · reproducible checks |
| [Real Estate Legal QA](https://github.com/chzFRA/real-estate-qa-clean) | New Zealand legal PDF processing, question generation, and retrieval experiments | Research prototype · reproducibility improvements needed |

AgentTrace Lab records tool timing, exceptions, and nested calls without requiring a model key. Its real MCP example demonstrates a subtle failure: a request can return normally while the tool reports an error. Its checks evaluate recorded execution behavior; they do not measure answer quality or stop tools while they run. [中文上手教程](https://github.com/chzFRA/agent-trace-lab/blob/main/docs/QUICKSTART.zh-CN.md) · [Validation evidence](https://github.com/chzFRA/agent-trace-lab/blob/main/docs/VALIDATION.md) · [Learning path](https://github.com/chzFRA/agent-trace-lab/blob/main/docs/LEARNING_PATH.zh-CN.md).

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

你好，我是 Huazhe Cheng。目前围绕 Agent 可靠性积累可运行、可检查、可复现的小型作品。AgentTrace Lab 用来记录真实 Python 工具调用、查看报告和比较修改前后的运行；我也在学习上面的四个社区项目，并把学习拆成具体实验。文档问答项目仍是研究原型，多模态是后续方向。欢迎通过项目 Issues 交流可复现的问题和使用反馈。
