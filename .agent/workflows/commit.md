---
description: Commit staged changes with bilingual, structured messages as per AGENTS.md
---

1. Ensure the changes you want to commit are staged. If not, stage them now using `git add`.
2. Analyze the staged changes to identify major updates and detailed rationale.
3. Compose a commit message following the conventions in `AGENTS.md`:
   - **Structured Body**: Use a short title, then a body with top-level bullets for major changes and indented sub-bullets for details.
   - **Bilingual**: Provide the complete message in English first, followed by the Traditional Chinese translation.
// turbo
4. Commit the changes using the generated message.
   - Example command: `git commit -m "title" -m "body"` or use a temporary file if the message is complex.
5. Provide the user with a summary of the commit.
