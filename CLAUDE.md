# Project Guidelines

## Stack

- Modern JavaScript/TypeScript frontend application
- Component-based UI framework
- Node.js and npm tooling
- AI services accessed through environment-configured APIs

## Project Conventions

- Keep reusable UI components small and focused; compose screens from them rather than duplicating markup.
- Place feature-specific code near the feature and shared UI, hooks, and utilities in clearly named common locations.
- Keep API calls, prompt construction, and response parsing out of presentational components where practical.
- Use environment variables for credentials and configuration; never expose secrets in client code, commits, logs, or prompts.
- Prefer existing dependencies and patterns before adding new libraries or architecture.

## Coding Standards

- Use clear, descriptive names and early returns to keep control flow readable.
- Prefer explicit TypeScript types at public boundaries; avoid `any` and unsafe type assertions.
- Keep functions and components focused on one responsibility. Extract repeated or complex logic into a utility or hook.
- Use semantic HTML, accessible labels, keyboard support, and sufficient visual contrast.
- Handle loading, empty, error, and success states for every user-facing async operation.
- Follow the existing formatter and linter configuration. Avoid unrelated formatting changes.

## Quality Checks

- Run the relevant lint, test, and build commands before considering a change complete.
- Verify responsive behavior and basic keyboard navigation for UI changes.
- Validate AI outputs and failures gracefully; do not assume responses are complete, safe, or correctly formatted.

## Git Commits

Use Conventional Commits with an imperative, concise subject:

- `feat: add AI prompt input`
- `fix: handle empty API response`
- `docs: update setup instructions`
- `refactor: simplify result rendering`

## AI-Assisted Development

- Treat generated code as a draft: review, understand, and test it before merging.
- Keep changes scoped and explain assumptions when requirements are unclear.
- Do not send credentials, private data, or proprietary content to AI tools.
- Record meaningful technical decisions and known limitations in project documentation.
