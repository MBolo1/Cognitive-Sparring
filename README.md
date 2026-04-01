# Cognitive Sparring Protocol

A skill for Claude that turns AI from an answer machine into a thinking partner.

## The Problem

When people receive polished AI-generated analysis, they cognitively offload — they absorb the conclusion without building the reasoning muscles that produced it. The research confirms this:

- **Wu et al. (2025, n=3,562)**: Passive AI consumption degrades intrinsic motivation. Active collaboration preserves it.
- **Lee et al. (2026, n=539)**: Passive AI reliance destroys self-efficacy. Active collaboration preserves it.
- **Gerlich (2025)**: Significant negative correlation between frequent AI tool usage and critical thinking abilities.
- **Doshi & Hauser (2024, Science Advances)**: AI increases individual creativity but decreases collective diversity.
- **Mollick et al. (BCG/Wharton, n=758)**: The "cyborg" model — deep interweaving of human and AI reasoning — outperforms pure delegation.

## How It Works

The Cognitive Sparring Protocol forces you through a 5-phase reasoning process every time you'd normally get a packaged answer:

1. **Hypothesis Extraction** — State your position before the AI does any research
2. **Raw Findings** — Receive evidence without synthesis, including contradictions
3. **User Engagement** — Interpret the findings yourself before the AI weighs in
4. **Challenge Round** — Get your reasoning stress-tested with steelman counterarguments
5. **Synthesis** — Only after you've done the cognitive work, receive the AI's full analysis

The friction is the point.

## Installation

This is a [Claude skill](https://docs.claude.com). To use it:

1. Copy the `cognitive-sparring/SKILL.md` file into your `.claude/skills/cognitive-sparring/` directory
2. The skill triggers automatically for research requests, strategic questions, decision-making, recommendations, and any request where Claude would normally deliver a packaged answer

## When It Triggers

The skill activates for prompts like:
- "What should I do about..."
- "Help me think through..."
- "What's the best approach for..."
- "Look into..." / "Dig into..."
- "What do you think about..."
- Any complex question where you'd normally get a pre-synthesized answer

It stays out of the way for simple factual lookups, task execution (drafting, coding, formatting), and when you explicitly invoke other skills.

## Teaching Mode

If you're exploring a topic where you have no prior knowledge, the protocol shifts into Teaching Mode — it builds your mental model first, explains the "why" behind findings, and uses analogies from domains you already understand. The 5 phases still run, but the information becomes accessible without becoming easy.

## License

MIT
