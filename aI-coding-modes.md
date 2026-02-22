# AI Coding Modes

This guide explains the three main modes available when working with GitHub Copilot in this repository.

## Ask Mode

**What it is:** Direct Q&A assistance for coding problems.

**When to use it:**

- You need to understand how something works
- You want to debug a specific issue
- You need code examples or explanations
- You have a quick question

**What happens:**

- You ask a question
- I research your codebase and provide an answer
- The response is immediate and actionable

**Example:** "How do I add error handling to this function?"

---

## Plan Mode

**What it is:** Collaborative planning before you start coding.

**When to use it:**

- You're starting a new feature or major change
- You want to think through the approach first
- You need to identify potential issues upfront
- You want feedback on your strategy

**What happens:**

1. I research your codebase to understand context
2. I ask clarifying questions if needed
3. I create a detailed, step-by-step plan
4. You review and refine the plan
5. Once approved, someone can execute it

**Example:** "I want to refactor the data processing pipeline"

---

## Agent Mode

**What it is:** Autonomous multi-step task execution.

**When to use it:**

- You need complex research across your codebase
- The task requires multiple steps or file reads
- You want me to find and gather information independently
- You need thorough investigation before planning

**What happens:**

- I work independently using read-only tools
- I gather all necessary context
- I return a comprehensive summary
- Used within Plan and Ask modes for deep research

**Example:** Used to discover how a feature is currently implemented across multiple files

---

## Choosing a Mode

| Need | Mode |
|------|------|
| Quick answer or code fix | **Ask** |
| Plan a feature or refactor | **Plan** |
| Deep research required | **Agent** (within Ask/Plan) |
