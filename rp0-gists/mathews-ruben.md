# Mathews, Ruben — RP-0 Gist

## Quick Read
Very strong proposal. Thoughtful, mature, and clearly grounded in a real requirements engineering tension around LLM behavior, trust, and acceptable performance.

## Topic
How requirements should be written for LLM-based systems that are useful but not fully predictable.

## Why It Works
- Strong articulation of the core curiosity: what does “correct enough” mean for variable-output systems?
- Treats hallucination, trust, and boundaries as requirements issues rather than purely model defects.
- Good awareness of stakeholder needs, human review, safety, and validation.
- Course connection feels natural, not forced.
- Research direction is broad enough to explore but specific enough to refine.

## Risks / Watchouts
- Topic could sprawl if it tries to address every quality attribute at once.
- May need help selecting a narrower slice of LLM systems or one specific trust-related requirement dimension.

## Coaching Direction
Encourage the student to keep the topic and narrow by context, such as:
- one application domain
- one trust-related quality attribute
- one contrast between low-risk and high-risk systems

## Rough Score Impression
56/60

## One-Line Summary
A strong, well-reasoned pitch with clear relevance to modern requirements engineering and good potential for refinement.

## Research Guidance Packet

### Stronger Instructor Comment
This is a thoughtful and promising pitch because it takes seriously the mismatch between traditional software expectations and LLM behavior. The proposal is strongest when it asks what “correct enough” means for systems whose outputs are variable, persuasive, and not fully predictable. The main challenge now is narrowing the project so it does not become a broad meditation on “AI trust” in general. To become a strong research project, it needs one sharper lens: a particular quality attribute, risk context, or class of failures.

### Promising Directions to Suggest
- Focus on one requirement dimension such as grounding, transparency, confidence signaling, or human override.
- Compare low-risk versus high-risk LLM use contexts.
- Study how misuse cases for LLM systems differ from misuse cases in traditional software.
- Explore how acceptable behavior should be specified when outputs vary.

### Scite Search Suggestions
- requirements engineering for large language models
- trust requirements AI assistants
- human oversight requirements generative AI
- hallucination risk requirements engineering
- specification of acceptable behavior in AI systems
- misuse cases LLM systems

### Useful Kinds of Articles
- software engineering papers on trustworthy AI requirements
- human-AI interaction papers on trust and overreliance
- work on safety cases, human-in-the-loop, or confidence calibration
- empirical studies on failure modes in generative systems

### Concrete Next-Step Question
Which matters more to you: **how to specify trustworthy behavior**, or **how to validate that a variable-output system meets those expectations**? That distinction could sharpen the whole project.
