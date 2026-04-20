# RP-2 Feedback

**Score: 135/140**

## Overall
This is a very strong RP-2. The proposal has a clear and disciplined center: prompts in software-development workflows often function like lightweight requirements artifacts, but they are usually not designed or evaluated with requirements-quality concepts in mind. That is a sharp idea, well matched to the course, and narrow enough to be workable.

The draft is especially effective because it does not wander into “all prompt engineering” or “all LLM problems.” Instead, it stays focused on ambiguity, constraints, and consistency in software tasks. That gives the project a real center and a plausible contribution.

## What is working well

### 1. The framing is excellent
The core move here is strong: treat prompts as operational specifications rather than casual text. That creates a direct bridge to requirements engineering and gives the proposal both relevance and originality.

### 2. The problem statement is precise and well motivated
You clearly explain why this matters in practice. In software tasks, users care about boundaries, constraints, format, and adherence. If prompts are ambiguous, the model may produce outputs that are broadly on-topic but still unusable. That is a convincing problem statement.

### 3. The research questions are focused and coherent
These are some of the better research questions in the set. They are specific, aligned, and purposeful. In particular:
- RQ2 gives you a concrete comparison
- RQ3 identifies likely ambiguity-reducing features
- RQ4 keeps the causal interpretation intellectually honest

That is a strong structure.

### 4. The proposed approach is plausible and appropriately scaled
The comparative case-study design is a very good fit here. It is manageable, it matches the questions, and it avoids overclaiming. Comparing informal prompts with more requirements-structured prompts across a small number of software tasks is exactly the kind of bounded study this assignment needs.

### 5. The background/context section is doing real work
The related work is not just present; it supports the argument. You successfully connect prompt engineering, prompt programming, and requirements ambiguity rather than treating them as separate conversations.

## What to strengthen

### 1. Make the evaluation criteria slightly more explicit
The approach is already good, but the next version would benefit from a somewhat sharper definition of “consistent adherence.” For example, will consistency mean:
- repeated satisfaction of explicit constraints?
- similarity across runs?
- fewer violations of prohibited behaviors?
- more reliable output formatting?

Probably yes to several of these, but stating that more directly would make the study design even tighter.

### 2. Be careful with the scope of causal claims
RQ4 is interesting, but it can become slippery if it turns into “prove that failures come from prompts rather than models.” I would keep the wording careful in the next round. The proposal is strongest when it says ambiguity and underspecification may explain part of the failure pattern, not all of it.

### 3. Consider naming the likely contribution a little more directly
The contribution seems to be something like a small analytical framework for reasoning about prompt ambiguity in software tasks using requirements-quality concepts. I would begin stating that very explicitly in the next version.

## Suggestions for the next iteration

### 1. Define the comparison dimensions up front
It may help to say exactly which features the structured prompts will introduce, such as:
- explicit task boundaries
- required output format
- prohibited actions
- acceptance constraints

### 2. Keep the study small and disciplined
Three or four tasks is probably enough. Resist the temptation to widen it.

### 3. Preserve the requirements lens
This is the strongest thing about the proposal. Keep using requirements terms carefully rather than drifting back into generic prompt-engineering language.

## Bottom line
This is an excellent RP-2. It is focused, clearly grounded in requirements engineering, and already has the shape of a strong final proposal. The main work left is refinement: tighten the evaluation language, keep the causal claims appropriately modest, and state the contribution even more directly.
