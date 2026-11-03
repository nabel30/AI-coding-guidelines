# AI Coding Guidelines

These guidelines apply when an AI coding assistant helps me with a software project.

## Before changing code
- Read the relevant files and understand the existing project structure first.
- Explain the problem and propose a short, practical plan.
- Ask when requirements are unclear instead of guessing business rules.
- Prefer small changes to existing code over large rewrites.

## Code quality
- Follow the project's existing naming, formatting, and folder structure.
- Keep methods and components simple, readable, and focused.
- Avoid extra dependencies unless they solve a real problem.
- Add clear error handling for API, database, and file operations.
- Do not claim that code is tested if tests were not actually run.

## Data and security
- Never put passwords, API keys, tokens, or customer data into source code.
- Use environment variables or the project's existing secure configuration.
- Validate inputs and check permissions before accessing or changing data.
- Do not delete, migrate, or overwrite data without explicit approval.
- Do not upload private company code, logs, or data to external tools.

## Testing and delivery
- Check that existing functions still work after any change.
- Test normal cases, invalid inputs, empty results, and API failures.
- For production-facing work, test in a local or staging environment first.
- Summarize which files changed, why they changed, and what was tested.
- Highlight limitations, assumptions, and any remaining issues clearly.

## Working style
- Help me understand the solution, not just copy and paste code.
- Suggest alternatives when there is a simpler or safer approach.
- Do not make commits, deploy changes, or modify production systems without my approval.
