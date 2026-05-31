# AI Workforce with xAI and OpenAI — A Living, Self-Documenting Task Loop

A self-documenting recurring-task system built on two consumer AI apps — Grok (xAI) and ChatGPT (OpenAI) — working the same job as co-workers. It runs scheduled tasks on a timer, reads live signals, produces and advances work, surfaces ways it could generate value, checks itself, restyles its own public surface daily, and writes everything to an open record on a live website. This document is the system specification.

> ## ⚠️ READ THIS FIRST — WHAT THESE OUTPUTS ARE, AND ARE NOT
> 
> **The outputs of this system are a mirror of what these specific AI models read the operator to intend.** Grok and ChatGPT, working inside the operator’s own accounts and reading the operator’s own public signals, produce suggestions, posts, sparks, and styling that reflect *their reading of this particular person*. They are not a universal output that anyone would reproduce.
> 
> **If you build your own version, expect completely different results.** A different person, with different public signals, talked to by a different AI — or even the same AI reading a different person — will produce different sparks, different suggestions, different tone, and different choices. That is not a flaw; it is the entire nature of the thing. This system is *live-referenced to its operator*, which is exactly why its specific behavior cannot be copied, only its structure.
> 
> **What transfers is the architecture, not the behavior.** Take the principles, the layers, the protected set, the staging — those are reusable. Do not take any specific output, suggestion, or post from this system as advice, instruction, or a model of what *your* AI should say. Yours will read you, not the operator here.

## How this was built

This system was designed primarily in conversation with Claude (Anthropic), which served as the reasoning and architecture partner across its development, with smaller contributions from the two in-system models, Grok (xAI) and ChatGPT (OpenAI). This distinction matters for anyone building their own version: the two models that run inside the system are not the ones that designed it. Designing a system like this benefits from a tool that can hold the full, evolving context and reason across it; running it benefits from tools that can schedule tasks and send email autonomously. Those turned out to be different strengths in different tools. If you assume the in-system models also did the design work, you may find they lack the context-depth to carry it — which is itself a useful thing to know before you start.

-----

**Creator / origin:** Jaron Kyler Bragg — Fort Wayne, IN (place of origin; not an exact address).

For the full specification, see [SPEC.md](SPEC.md).