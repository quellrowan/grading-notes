# Smith, Caleb — RP-0 Gist

## Quick Read
A strong and timely proposal with a clear requirements angle. The topic overlaps somewhat with other LLM-focused submissions, but this one has a clean center around hallucination as a requirements problem.

## Topic
AI hallucinations in large language models and whether they should be understood as a requirements engineering problem rather than only as a technical or model-training issue.

## Why It Works
- The proposal identifies a concrete and important problem.
- It frames hallucination as a requirements issue, which gives the topic a real conceptual center.
- The connection to course ideas such as validation, misuse, tradeoffs, and prioritization is clear.
- The early research questions are usable and already point toward a stronger project.

## Risks / Watchouts
- The topic overlaps with other LLM proposals, so what matters here is keeping a distinct angle.
- It could become too broad if it tries to explain hallucinations from every possible perspective at once.
- The strongest version of the project will need to stay centered on requirements questions, not drift into general commentary on AI reliability.

## Coaching Direction
The best next step would be to keep the focus on hallucination as a requirements problem and decide where that problem is most interesting: specification, validation, misuse analysis, or system boundary-setting.

## Rough Score Impression
54/60

## One-Line Summary
A strong proposal with a clear center; the main task now is to narrow the question so it stays focused on requirements rather than AI problems in general.

## Research Guidance Packet

### Instructor Comment
This is a strong proposal because it takes a familiar AI problem and gives it a real requirements engineering lens. The most useful move here is not simply pointing out that hallucinations are bad. It is asking whether some of what we call hallucination is actually a failure to specify acceptable system behavior, define boundaries, anticipate misuse, or validate outputs appropriately.

That gives the topic a clear conceptual center. It also helps distinguish this proposal from more general “AI safety” or “AI trust” discussions. The most important next step is to keep that center in view and not let the project drift into a broad overview of everything that can go wrong with LLMs.

If this is narrowed well, it could become a very solid project.

### Directions to Suggest
- focus on hallucination as a specification problem rather than a general model problem
- study what requirements around uncertainty handling, citation, or escalation might reduce risk
- examine whether misuse cases can capture overtrust and fabricated output risks
- compare contexts where hallucinations are tolerable versus contexts where they are especially dangerous

### Scite Search Suggestions
- hallucination requirements engineering large language models
- trustworthy AI requirements uncertainty communication
- misuse cases generative AI hallucinations
- validation of LLM outputs software engineering
- requirements for truthful or grounded AI systems
- source citation and uncertainty handling in large language models

### Useful Kinds of Articles
- papers on hallucinations in LLMs
- software engineering work on specifying trustworthy AI behavior
- papers on grounding, verification, or source attribution
- work on misuse cases, human oversight, and safety requirements in AI systems

### Concrete Next-Step Question
Do you want to argue that hallucination is primarily a specification problem, or do you want to study what kinds of requirements could reduce hallucination risk in practice? Those are related, but they lead to slightly different projects.
