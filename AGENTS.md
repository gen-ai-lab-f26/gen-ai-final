# AGENTS.md: rules for your coding agent

Your agent reads this file first. Keep it short and current.

## Project

- **What this builds:** An AI-assisted stage-blocking app that helps dance team leaders and choreographers create and adapt performance formations, including when dancers are missing.
- **Who it's for:** see `INTENT.md`
- **Stack:** Python backend and a responsive HTML/JavaScript canvas. Support iPad touch interaction with Pointer Events and `touch-action: none` on the canvas interaction surface.
- **Product Page:** `docs/index.md`, plain Markdown that GitHub Pages turns into the team's public page. Fill it only with facts from `INTENT.md` and `TEST_LOG.md`, and leave a [bracket] where the team has no answer yet.

## Commands

- **Install:** [Document the verified install command]
- **Run:** [Document the verified run command]
- **Check:** [Document the verified check command]

## Rules

1. **Plan first.** Before changing more than one file, propose a short plan and wait for a yes.
2. **Small changes.** One change at a time, small enough to explain in a sentence.
3. **Explain it.** Say what changed, why, what could break, and how you checked it.
4. **Check your work.** Run the checks and record the results in `TEST_LOG.md`. Never invent a result.
5. **No secrets in code.** Read API keys only from `.env`; never commit `.env` or put key values anywhere else. Add new variable names to `.env.example`, never their values.
6. **Ask before acting on the world.** Don't send messages, spend money or publish anything without a person's OK.
7. **Stop when stuck.** If a fix fails twice, stop, say what failed, and ask before trying a third way.
8. **Enforce geometry in deterministic code.** Validate stage bounds and minimum spacing, and flag sprint distances using deterministic code—not the LLM. Show these checks as visual flags for choreographer review.
