# Hanson, Benjamin — RP-0 Gist

## Quick Read
One of the stronger proposals in the set. The central idea is genuinely interesting, and it has a clearer conceptual hook than most of the other submissions.

## Topic
Prompting as a requirements specification; applying requirements engineering and validation ideas to prompt engineering and LLM reliability.

## Why It Works
- The proposal identifies a real problem rather than just a trendy area.
- It treats prompts as a requirements problem, not just an AI tool problem.
- It connects naturally to course ideas such as ambiguity, validation, incompleteness, and misuse.
- It already gestures toward a plausible empirical direction.

## Risks / Watchouts
- There are several good ideas in here at once, and that creates a scope problem.
- The project could easily become too broad if it tries to cover ambiguity, validation, misuse, prioritization, and output drift all together.
- It needs one central question rather than a cluster of related questions.

## Coaching Direction
The next step is not to broaden the idea further. It is to choose the most interesting slice of it and develop that carefully.

## Rough Score Impression
58/60

## One-Line Summary
A strong proposal with a real conceptual hook, but it will only stay strong if the scope is narrowed early.

## Research Guidance Packet

### Instructor Comment
This is one of the stronger proposals in the set. The central idea is genuinely interesting: treating prompts as a kind of requirements artifact rather than just as ad hoc instructions. That gives the project a real conceptual hook, and it also connects clearly to concerns we have already discussed in requirements engineering—ambiguity, validation, incompleteness, and failure under interpretation.

What works especially well here is that the proposal does not stop at “AI is interesting.” It actually identifies a requirements problem: if prompts increasingly function as both specification and execution, then we need better ways to reason about their quality. That is a worthwhile direction.

The main thing I would push on is scope. Right now there are several good ideas packed together here: ambiguity, validation, misuse, prioritization, output drift, and consistency. Any one of those could support a strong project, but trying to do all of them at once would make the work diffuse. The next step is not to broaden this idea further; it is to choose the most interesting slice of it and develop that well.

If you narrow this carefully, this could become a very strong project.

### Directions to Suggest
- focus on whether requirements-style prompt structure reduces ambiguity or output drift
- compare naive prompts with more explicitly constrained prompts
- define one quality criterion clearly—consistency, correctness, adherence to constraints, or interpretability—and study that
- treat prompt failure as a specification problem rather than only a model-performance problem

### Scite Search Suggestions
- prompt engineering and requirements engineering
- prompt ambiguity in large language models
- structured prompts versus natural prompts
- specifying behavior in generative AI systems
- validation or evaluation of prompt quality
- reproducibility and consistency in LLM outputs

### Useful Kinds of Articles
- empirical studies comparing prompt structures
- papers on prompt quality and reproducibility
- software engineering work on specifying AI behavior
- work on ambiguity, structured natural language, or requirements quality metrics

### Concrete Next-Step Question
Which is more interesting to you: ambiguity reduction, output consistency, or validation of prompt quality? Pick one, because that choice should shape the whole project.
