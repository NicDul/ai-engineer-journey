# AI Engineer Journey

Learning AI engineering in public, from first principles to deployed, evaluated LLM systems.

I'm a railway simulation engineer (MATSim / railsim, capacity and timetabling). This repo documents the path from building a neural network by hand to shipping retrieval and agent systems for the rail domain, with every project measured by an evaluation, not by a demo alone.

## Principles

- **Ship, don't collect.** Every step ends with code pushed or a write-up written.
- **Understand before abstracting.** Start from scratch (autograd, language models) before using frameworks.
- **Measure everything.** Each project has a test set and a score, with before/after results.
- **Public data only.** Every dataset and document used here is publicly available.

## Roadmap

| Phase | Focus | Output | Status |
| --- | --- | --- | --- |
| 0 · Fundamentals | Andrej Karpathy's [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html): micrograd, makemore | Autograd engine and bigram language model, built from scratch | 🟡 In progress |
| 1 · Retrieval (RAG) | "Ask the rulebook": question answering over public Swiss railway regulations, with citations | Live demo, eval set, write-up | ⚪ Planned |
| 2 · Agents | An agent that turns a plain-language scenario into a railsim run and explains the capacity result, via an MCP server | Repo, demo video, write-up | ⚪ Planned |
| 3 · Evals & ops | Golden sets, LLM-as-judge vs human labels, cost/latency tracking, regression tests on every change | Evaluation harness and write-up | ⚪ Planned |

## Repository layout

Each phase gets its own folder as it starts:

```
00-micrograd/      autograd engine + tiny neural net
01-makemore/       character-level language models
10-rag-rulebook/   Phase 1
20-railsim-agent/  Phase 2
30-evals/          Phase 3
```

## Log

| Date | What | Link |
| --- | --- | --- |
| 2026-11-09 | Repo created | — |

## Resources

- [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) · [micrograd](https://github.com/karpathy/micrograd) · [nanoGPT](https://github.com/karpathy/nanoGPT)
- [Hugging Face LLM course](https://huggingface.co/learn/llm-course)
- [DeepLearning.AI: Retrieval Augmented Generation](https://www.deeplearning.ai/courses/retrieval-augmented-generation-rag/)
- [Hugging Face Agents course](https://huggingface.co/learn/agents-course) · [MCP course](https://huggingface.co/learn/mcp-course)
- [Hamel Husain: Your AI product needs evals](https://hamel.dev/blog/posts/evals/)

## About

More on [nicodulex.com](https://nicodulex.com).
