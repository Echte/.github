# Copilot Instructions

## Output control
- Code only, no explanation unless asked.
- Bullets over paragraphs.
- No preamble, no summary, no sign-off.
- Omit unchanged code in diffs; use `// ... existing code ...` placeholders.
- Terse commit messages: `type: short description` (50 chars max).
- One-line PR review comments.

## Response format
- Respond in the same language as the question.
- Prefer concise answers; expand only when depth is explicitly requested.
- Skip affirmations ("Sure!", "Great question!").

## Code style
- Match existing conventions in the file being edited.
- Smallest possible change that satisfies the requirement.
- No unrelated refactors or style fixes.
- No new dependencies unless necessary.

## Context usage
- Do not re-read files already in context.
- Ask clarifying questions before long tasks to avoid wrong-direction work.
- Use Ask mode for single questions; Agent mode for multi-step tasks only.