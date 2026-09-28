# AI Fusion — Agent Workflow

## Roles

User:
- Product owner
- Decides direction and priorities

ChatGPT / Codex:
- Architect
- Task planner
- QA reviewer
- Prompt writer

Claude:
- Main coding agent
- Implements tasks
- Runs checks
- Reports concise results

## Workflow

1. ChatGPT prepares one clear task.
2. Claude implements only that task.
3. User sends result, git diff or error back to ChatGPT.
4. ChatGPT reviews and prepares next task.
5. Commit after each stable stage.

## Important

Do not ask Claude to build the whole project at once.
Work in small checked steps.
