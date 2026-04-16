# AI Onboarding Guide
A practical introduction to AI-assisted development for engineers new to agentic workflows.

This guide provides a structured set of exercises designed to help engineers build confidence with AI-assisted development. Each exercise focuses on a different skill: prompting, scripting, refactoring, rapid prototyping, and agentic reasoning. The examples are intentionally general so they can be applied in any engineering environment.

---

## Overview

Modern engineering teams increasingly rely on AI tools to accelerate development, reduce manual effort, and improve clarity in complex workflows. This guide introduces foundational skills through hands-on practice, with an emphasis on practical, real-world tasks.

The goal is to help engineers move from occasional experimentation to consistent, confident use of AI in their daily work.

---

## Exercise 1: Prompting for Signal, Not Syntax

Purpose: Learn how to frame problems so the AI understands context, constraints, and intent.

### What You Will Learn
- How to provide meaningful context
- How assumptions and constraints shape responses
- How to refine prompts for clarity and usefulness

### Steps
1. Open your preferred AI chat tool.
2. Provide a short engineering scenario. Example:
   "Automated tests intermittently fail in CI but pass locally. Failures involve timeouts and inconsistent logs."
3. Ask the AI to:
   - Clarify assumptions
   - Identify likely root causes
   - Suggest next investigation steps
4. Refine your prompt by adding:
   - Environment details
   - Constraints (time, tools, scope)
   - Desired output format (summary, table, bullet list)

### Outcome
You see how prompt quality directly affects the usefulness of the response, even without writing code.

---

## Exercise 2: Generate a One-Off Utility Script

Purpose: Use AI as a coding assistant to automate small, repetitive tasks.

### What You Will Learn
- How to turn a manual task into a quick script
- How to iterate using the generate → run → fix → rerun loop
- How to use AI as a debugging partner

### Steps
1. Identify a small manual task (log parsing, file comparison, data cleanup).
2. Ask the AI to generate a script in your preferred language.
3. Paste the script into your IDE and run it locally.
4. If it fails or needs improvement:
   - Paste the error or output back into the AI
   - Ask for a fix or enhancement
5. Re-run and validate.

### Outcome
You experience the iterative workflow that defines AI-assisted coding.

---

## Exercise 3: Explain and Refactor Code

Purpose: Use AI to understand unfamiliar code and improve maintainability.

### What You Will Learn
- How to use AI as a code reviewer
- How to identify risks, smells, and improvement opportunities
- How to request refactored versions with specific goals

### Steps
1. Select a small piece of code (a test, helper function, or script).
2. Paste it into the AI chat.
3. Ask the AI to:
   - Explain what the code does
   - Identify risks or smells
   - Suggest improvements
4. Request a refactored version that improves:
   - Readability
   - Error handling
   - Logging or assertions
5. Review the differences in your IDE.

### Outcome
You learn to use AI as a reviewer and mentor, not just a generator.

---

## Exercise 4: Build a Simple Functional UI

Purpose: See how quickly AI can generate lightweight UIs for internal tools or demos.

### What You Will Learn
- How to prototype small utilities with minimal effort
- How to iterate on layout, validation, and clarity
- How AI can accelerate internal tooling

### Steps
1. Ask the AI to generate a simple UI that:
   - Accepts input (text, file, numbers)
   - Performs a small action (validation, transformation, summary)
   - Displays output
2. Paste the generated file into your IDE and run it.
3. Interact with the UI to see how it behaves.
4. Ask the AI to:
   - Improve layout or clarity
   - Add basic validation
   - Make the output easier to interpret
5. Iterate once or twice with new functionality.

### Outcome
You see how quickly internal tools can be prototyped with AI assistance.

---

## Exercise 5: Turn a Thought Into an Agent Task

Purpose: Learn how to frame work so the AI can reason, plan, and execute steps, not just answer questions.

### What You Will Learn
- How to express goals in a way that enables multi-step reasoning
- How to break down tasks into subtasks
- How to identify what can be automated

### Steps
1. Write a short goal statement. Example:
   "When tests fail, I want a quick way to understand what went wrong without digging through large logs."
2. Ask the AI to:
   - Break the goal into subtasks
   - Identify inputs and outputs
   - Suggest what could be automated
3. Pick one subtask and ask the AI to implement it.
4. Validate the result in your IDE.
5. Ask the AI what the next logical automation step would be.

### Outcome
You begin thinking in terms of agentic workflows rather than one-off prompts.

---

## Intended Audience

This guide is designed for:
- Quality engineers
- Developers new to AI-assisted workflows
- Teams adopting AI tools for the first time
- Anyone looking to build confidence with agentic reasoning

No prior AI experience is required.

---

## Approach

The exercises emphasize clarity, iteration, and practical value. The goal is not to master AI tools immediately, but to build a foundation for consistent, confident use.

