# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## IMPORTANT

- ALWAYS read [IDEA.md](./IDEA.md) to stay on point what we build
- USE Emojis in [README.md](./README.md) or **docs/*.md** with care. NOT MUCH.
- ALWAYS read [GOTCHA.md](./GOTCHA.md) before make changes
- PREFER British English over American English spelling and grammar
- Files and Directories MUST NOT have **dashes** in names/paths (Use **underscore** instead)
- NEVER USE Git LFS
- ALL files MUST have final new line (i.e. consistent with **insert_final_newline = true** Editor Config config)

## Project Overview

<!-- AI-TODO -->

## Commit Messages

Follow conventional commit format with detailed explanations and proper sign-off. Use British Spelling.

### Format

```
<type>(<scope>): <subject>

<detailed body explaining what and why in bullet points>

BREAKING CHANGE: <description if applicable>

🤖 Generated with [Claude Code](https://claude.ai/code)

Co-Authored-By: Claude <noreply@anthropic.com>
Signed-Off-By: Paal Øye-Strømme <paal.o.eye@gmail.com>
```

### Best Practices

  - **Type**: Use `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`
  - **Scope**: Specify affected module/component (e.g., `supabase`, `components`, `hooks`)
  - **Subject**: Imperative mood, no period, max 50 characters
  - **Body**: Explain the what and why, not how. Include context and reasoning in bullet points using "-" as for item mark
  - **Breaking Changes**: Always document with `BREAKING CHANGE:` footer
  - **Sign-off**: Include Claude Code attribution for AI-generated commits in `Co-Authored-By` and the main committer in `Signed-Off-By`

### Examples

```bash
feat(supabase): add verify-email function

- added verify-email Edge function to confirm users's email
- added tests

fix(components): add toaster

- toaster is used for notification
- no testes yet

docs:: update module usage examples and references

- for consistency
- improved readability

refactor(hooks): change useToast

- fixes #1
- added extra options
```
