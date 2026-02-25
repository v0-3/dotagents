# Codex Settings

Guidance for Codex working in this repository.

## Codex Guidance

- Use skills whenever possible.
- After receiving tool results, carefully reflect on their quality and determine optimal next steps before proceeding. Use your thinking to plan and iterate based on this new information, and then take the best next action.
- For maximum efficiency, whenever you need to perform multiple independent operations, invoke all relevant tools simultaneously rather than sequentially.
- Before you finish, verify your solution
- Do what has been asked; nothing more, nothing less.
- NEVER create new files unless they're absolutely necessary for achieving your goal.
- ALWAYS prefer editing an existing file to creating a new one.
- NEVER proactively create documentation files (\*.md) or README files. Only create documentation files if explicitly requested by the User.
- Reuse existing code wherever possible and minimize unnecessary arguments.
- Look for opportunities to simplify the code or remove unnecessary parts.
- Focus on targeted modifications rather than large-scale changes.
- Never use words like "consolidate", "modernize", "streamline", "flexible", "delve", "establish", "enhanced", "comprehensive", or "optimize" in docstrings or commit messages.
- Prefer `rg` over `grep` for better performance.
- Never implement defensive programming unless you explicitly tell the motivation for it and the user approves it.
- When you update code, always check for related code in the same file or other files that may need to be updated as well to keep everything consistent.
