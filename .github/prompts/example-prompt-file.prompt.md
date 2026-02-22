---
agent: agent
---
# Example Prompt Template

This file shows how to structure AI prompts for this project. Copy and modify for your needs.

## Template

### Context
[Describe what you're working on and why]

Example: "I'm building the settings dialog for the to-do app using ttkbootstrap."

### Current State
[What exists now? What's the current code doing?]

Example: "I have a main window with a task list. Now I need to add a preferences dialog."

### Goal
[What specific outcome do you want?]

Example: "Create a settings dialog that lets users change the app theme and default task priority."

### Constraints
[Any limitations or requirements?]

Example: "Must use ttkbootstrap themes. Dialog should be modal and apply changes immediately."

### Questions for the AI
[What specific help do you need?]

Example: "How do I create a modal dialog? How do I persist user preferences?"

---

## Example Full Prompt

```
Context: Building a to-do app with tkinter and ttkbootstrap

Current State: I have a main window displaying tasks from a list. The app needs user preferences.

Goal: Create a settings window where users can:
- Select a ttkbootstrap theme
- Set default task priority (Low/Medium/High)
- Enable/disable notifications

Constraints:
- Must be modal (blocks main window until closed)
- Settings should save to a JSON file
- Use ttkbootstrap widgets only

Question: What's the best way to structure this dialog and save settings?
```

---

**Refer to this template when asking Copilot for help.**
