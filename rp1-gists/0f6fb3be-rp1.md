# RP-1 Feedback

**Score: 101/120**

## Overall
This is a solid RP-1 with a clear topic and a meaningful software/requirements engineering angle. The strongest part of the proposal is that it does not treat hallucination only as a model-quality issue, but instead reframes it as a problem that may also reflect **missing or under-specified requirements**. That is a productive direction and a good fit for the course.

At the same time, this draft still feels a bit broader and less settled than some of the strongest proposals in the batch. The topic is promising, but it needs one more round of sharpening so that the final proposal does not become too diffuse. In particular, the project needs to be careful about scope and about whether it is trying to analyze the problem, classify the problem, and propose solutions all at once.

## What is working well

### 1. The RE framing is good
The proposal makes a useful shift away from treating hallucination only as a machine learning problem. The argument that systems integrating LLMs often lack explicit requirements about:
- acceptable output behavior
- uncertainty communication
- validation expectations
- user interaction boundaries

is a strong software/requirements engineering insight. That move gives the proposal a legitimate course-related center.

### 2. The problem statement is understandable and relevant
The draft clearly explains why hallucination matters in software engineering settings. The examples of:
- incorrect code
- nonexistent APIs
- fabricated documentation
- misleading design recommendations

help make the issue concrete. You also explain well why this matters in real workflows rather than only in theory.

### 3. The response to feedback shows meaningful narrowing
The revision from “AI reliability in general” toward “hallucination in software engineering tasks” is a good improvement. The shift toward missing or under-specified requirements also helps sharpen the project. The RP-1 clearly has more focus than a broad AI-risk discussion would have had.

## What to strengthen

### 1. The project is still somewhat broad
This is the biggest issue to address next. Right now the proposal is trying to cover:
- types of hallucinations
- missing requirements
- candidate requirements to mitigate risk
- prioritization by scenario

That is a lot for a 3–5 page final paper. Each of those could become a project on its own. The result is that the current proposal still feels a little spread out, even though it is improved from RP-0.

### 2. RQ3 moves quickly into solution design
The question asking **what requirements can be defined to mitigate the risks** is reasonable, but it also shifts the project from analyzing the problem to proposing a design framework. That is not necessarily wrong, but it may be too ambitious if the project is also trying to classify hallucinations and identify under-specified requirements at the same time.

For the next version, consider whether the project is primarily about:
- identifying the requirements gap, or
- proposing a requirements framework

It will be easier to produce a strong final paper if one of those clearly comes first.

### 3. The context could be narrowed further
“Software engineering tasks” is a good improvement over “LLMs in general,” but it is still a large space. It includes:
- code generation
- debugging
- API use
- documentation
- design guidance
- possibly review and testing as well

That may be too much unless you are using “software engineering tasks” very selectively. The final version may benefit from narrowing to one or two task categories or one particularly important risk setting.

## Suggestions for the next iteration

### 1. Choose a clearer center of gravity
I think the strongest version of this project would likely focus on one of these:
- the requirements gap around uncertainty and validation in LLM-supported SE tools
- the difference between acceptable and unacceptable hallucination across different SE tasks
- the boundaries of trust and verification for LLM-supported engineering work

Any of those could work, but the next draft should feel more clearly organized around one.

### 2. Narrow the task context
For the full proposal, consider whether you want to emphasize:
- code generation/code assistance
- API/documentation guidance
- design recommendations
- or software engineering support tools more broadly but with one primary example

The project will be easier to support if the context is not too expansive.

### 3. Distinguish between “requirements to specify” and “requirements currently missing”
That difference matters. One is more descriptive/analytic, and the other is more prescriptive/design-oriented. The proposal would become stronger if it made that distinction more clearly. Right now it gestures toward both.

## Bottom line
This is a promising RP-1 with a good underlying problem and a legitimate requirements engineering lens. The main task for the next iteration is to reduce the remaining breadth, sharpen the central contribution, and decide whether the full proposal is primarily about analyzing missing requirements or proposing what those requirements should be.
