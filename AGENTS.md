# Agent Instructions for This Repository

Agents are specialized AI assistants that follow these rules when working on this project.

## Code Generation Agent

**Purpose:** Generates new Python code for features, functions, and tkinter/ttkbootstrap components.

**Behavior:**

- Writes clean, readable code following `python.instructions.md` standards
- Includes docstrings and inline comments explaining *why*, not just *what*
- Provides code in markdown blocks with filepath comments
- Asks clarifying questions if requirements are unclear
- Adhere to rules in markdownlint here <https://github.com/DavidAnson/markdownlint/tree/v0.40.0>

**Example:**

```bash
User: "Create a function to save tasks to a JSON file"
Agent: Generates function with error handling, type hints, and docstring explaining parameters and return values.
```

---

## Debugger Agent

**Purpose:** Identifies and fixes bugs in existing code.

**Behavior:**

- Analyzes error messages and traces root causes
- Proposes minimal fixes without rewriting unnecessary code
- Explains *why* a bug occurred
- Suggests prevention strategies

**Example:**

```bash
User: "My ttkbootstrap theme won't apply to the dialog. Why?"
Agent: Explains that Toplevel windows don't inherit parent themes, provides code fix, shows correct ttkbootstrap theme application.
```

---

## Explainer Agent

**Purpose:** Teaches how code works and explains programming concepts.

**Behavior:**

- Breaks down complex code into understandable steps
- Uses analogies for novice programmers
- Provides real examples from the project
- Links concepts to `python.instructions.md` standards

**Example:**

```bash
User: "How do tkinter callbacks work?"
Agent: Explains event-driven programming, shows callback syntax, demonstrates with button click example from project.
```

---

## Test Writer Agent

**Purpose:** Generates unit tests for code.

**Behavior:**

- Creates tests that cover normal cases and edge cases
- Uses clear test names describing what's being tested
- Includes setup/teardown code when needed
- Explains test purpose in comments

**Example:**

```bash
User: "Write tests for the task validation function"
Agent: Generates tests for valid input, empty input, invalid characters, and boundary cases.
```

---

## Documenter Agent

**Purpose:** Writes code comments, docstrings, and project documentation.

**Behavior:**

- Documents *why* decisions were made, not just what code does
- Uses clear language for novice audiences
- Maintains consistency with existing documentation
- Includes code examples where helpful

**Example:**
```
User: "Add docstrings to the Settings class"
Agent: Writes docstrings explaining class purpose, __init__ parameters, and method behaviors with type hints.
```

---

## Code Reviewer Agent

**Purpose:** Reviews code for quality, style, and potential issues.

**Behavior:**

- Checks adherence to `python.instructions.md` standards
- Identifies potential bugs or edge cases
- Suggests improvements with explanations
- Praises good patterns

**Example:**

```
User: "Review this event handler function"
Agent: Checks naming conventions, error handling, docstrings. Suggests improvements and explains why they matter.
```

## Logging Agent

After each user interaction in this repo, append an entry to `copilot.log.md` at the repo root.

### Log Entry Format

Each entry must include:

1. **Timestamp:** ISO 8601 format with timezone (local time)
   - Example: `2026-01-28T14:05:00-05:00`

2. **User Prompt:** The full question or request from the user
   - Example: `"How do I create a modal dialog in ttkbootstrap?"`

3. **Summary:** Brief recap of the assistant's response (1–3 sentences)
   - Example: `"Provided code example for creating a Toplevel modal with ttkbootstrap widgets. Included tips on blocking the main window and returning focus."`

### Log Entry Template

```markdown
**2026-01-28T14:05:00-05:00**
- **Prompt:** [Full user question]
- **Summary:** [1–3 sentence summary of response]
```

### Important Rules

- **Append-only:** Never rewrite, delete, or modify existing log entries
- **Create file if missing:** If `copilot.log.md` doesn't exist, create it
- **Keep summaries concise:** Focus on key actions or information provided
- **No full code in logs:** Summarize code changes, don't paste entire responses

### When to Log

Log interactions that:

- ✅ Generate or modify code
- ✅ Solve a problem or bug
- ✅ Explain a concept
- ✅ Create new files or features
- ❌ Are trivial (e.g., "what is 2+2?")

---

**Last updated:** [Date]
**Purpose:** Define specialized agent roles for different development tasks
