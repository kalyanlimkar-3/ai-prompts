### Creating Agents.md
**Chat Mode - Agent**

Using the repository discovery you just performed, create an AGENTS.md file at the root of the current repository.

Before writing the file, separate verified repository facts from assumptions.

AGENTS.md must contain:

1. Project overview
2. Technology stack
3. Repository structure
4. How to run the project
5. How to run tests
6. Important architectural conventions
7. Important coding conventions that are actually evidenced by the repository
8. Configuration/environment requirements
9. Important directories and their responsibilities
10. Agent working rules
11. Validation expectations
12. Known constraints
13. Explicit unknowns that must not be guessed

For the agent working rules:

- Do not invent requirements.
- Do not assume architecture that is not established.
- Inspect existing code before modifying it.
- Prefer the smallest change necessary.
- Preserve existing conventions.
- Run appropriate validation after changes.
- Clearly report what was changed and how it was validated.
- Ask for clarification when a business decision is required.

Do not add generic framework instructions that are not relevant to this repository.

Do not implement Smart Fare Alert.

After creating AGENTS.md, show me the complete file contents and explain how each major section was derived from repository evidence.
