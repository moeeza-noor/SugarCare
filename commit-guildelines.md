# Commit Guidelines

This section outlines the guidelines for making commits in the Healthcare Connect project. Adhering to these guidelines ensures a clear and navigable project history.

## 1. Concise and Specific Subject Line:
- Begin with a concise summary title, under 50 characters.
- Capitalize the first letter and avoid ending with a period.
- Use imperative mood, e.g., "Add", "Fix", "Update".
- Prefix with a relevant area or component, e.g., `[Login Feature] Add password validation`.

## 2. Descriptive Body:
- Follow the subject line with a blank line.
- Explain the context and reason for the change.
- Keep lines under 72 characters for readability.
- Include relevant links to issues or documents.

## 3. Bullet Points for Multiple Changes:
- List multiple changes as bullet points.
- Use dashes or asterisks for each point.

## 4. Reference Related Issues and Tickets:
- Reference related issues or tickets, e.g., `Fixes #123`, `Related to issue #456`.

## 5. Avoid Ambiguous Messages:
- Avoid vague messages like "fixed bug" or "updates".

## 6. Testing or Deployment Notes:
- Include any notes on required additional actions like database migrations.

## 7. Use Present Tense:
- Use present tense for consistency.

## 8. Language and Style:
- Write in English, ensuring correct spelling and grammar.

## 9. Sample Commit Message:

```markdown
[Patient Dashboard] Implement appointment scheduling feature

- Add functionality for patients to schedule appointments
- Integrate date picker component
- Ensure form validation for inputs
- Fixes #321, relates to user story #30

Note: Requires updating the user interface library.
