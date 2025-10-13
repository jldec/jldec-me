---
title: It's early days for Agents
splash:
  image: /images/fall.webp
date: 2025-10-13
layout: BlogPostLayout
excerpt: We're not there yet
---

# It's early days for Agents
[Reasoning](https://openai.com/index/introducing-openai-o1-preview/) and [function calling](https://openai.com/index/function-calling-and-other-api-updates/) both marked significant breakthroughs in the road to making agents more capable.

Coding agents like [Amp](https://ampcode.com/home) and [Claude Code](https://www.claude.com/product/claude-code) now leverage those capabilities to generate real value, for which developers are willing to pay.

But coding agents are not general purpose. Depending on hand-coded agentic apps with pre-selected tools for specialized domains means that we haven't fully grokked the [bitter lesson](https://web.archive.org/web/20251006184925/http://www.incompleteideas.net/IncIdeas/BitterLesson.html).

> To deliver value at scale, Agents need to learn on the job.

Agents should get smarter over time, constantly refining their knowledge, based on what they learn from their interactions at inference-time.

## The two approaches
1. AI researchers tend to approach the problem from the perspective of [reinforcement learning](https://deeprlcourse.github.io/guests/richard_sutton/).
2. AI engineers are trying to get better behavior out of LLMs with [context engineering](https://x.com/karpathy/status/1937902205765607626).

A combination of both approaches will be required eventually, but in the short term there is a lot of room for agent framework providers to innovate without pushing the problem back into the labs

# Low hanging fruit
- Remember all conversations.
- Provide decent search interfaces to map new tasks onto existing knowledge.
- Refine existing knowledge by subjecting it to feedback from new interactions or from user input.
- Apply the strategies used by coding agents to plan and delegate tasks to subagents.
- Facilitate sharing and learning amongst teams of agents and humans via active experimentation.
- Keep learning from related projects across the industry.
