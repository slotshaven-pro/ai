# Copilot Instructions for This Repository

## Overview
This repository primarily uses Jupyter Notebooks to combine Python code and Markdown documentation. The notebooks are designed to:
- Demonstrate Python code snippets.
- Provide inline documentation and explanations using Markdown.
- Allow interactive execution of code cells.

## Key Concepts
1. **Notebook Structure**:
   - Each notebook consists of cells that can contain either Python code or Markdown.
   - Code cells can be executed independently, but they retain the state of previously executed cells.
   - Markdown cells are used for documentation and cannot be executed.

2. **Execution Flow**:
   - Code cells depend on the execution order. Ensure that any dependencies (e.g., variable definitions) are executed in the correct sequence.
   - Use the "Run All" feature to execute all cells in order, or run cells individually as needed.

3. **Extending the Notebook**:
   - Add new cells for additional code or documentation.
   - Maintain a clear separation between code and Markdown for readability.

## Developer Workflows
- **Testing Code**: Execute code cells interactively to verify functionality.
- **Debugging**: Modify and re-run individual cells to isolate and fix issues.
- **Documentation**: Use Markdown cells to explain the purpose and functionality of code snippets.

## Project-Specific Conventions
- Use descriptive variable names and comments in code cells.
- Keep Markdown cells concise and relevant to the adjacent code.
- Avoid hardcoding values; use variables where possible.

## Example
Here is an example of a typical notebook cell:

### Markdown Cell
```
# Reverse a String
This cell explains the purpose of the code in the next cell.
```

### Code Cell
```python
tekst = 'Dette er python i en workbook'
print(tekst[::-1])
```

## Contribution Guidelines
- Ensure that new notebooks follow the existing structure and conventions.
- Test all code cells before committing changes.
- Update Markdown documentation to reflect any changes in the code.

For further questions, refer to the Jupyter Notebook documentation or consult the project maintainers.