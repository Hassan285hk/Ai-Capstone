# Project Guidelines

## Stack

- Modern JavaScript/TypeScript frontend application
- Component-based UI framework
- Node.js and npm tooling
- AI services accessed through environment-configured APIs

## Coding Conventions

- Use clear, descriptive names and small, focused components and functions.
- Prefer TypeScript types where the project supports them; avoid `any`.
- Keep UI components accessible, responsive, and free of avoidable side effects.
- Follow the existing formatter and linter configuration; do not introduce unrelated formatting changes.
- Store secrets only in environment variables—never commit them.

## Git Commits

Use Conventional Commits with an imperative, concise subject:

- `feat: add AI prompt input`
- `fix: handle empty API response`
- `docs: update setup instructions`
- `refactor: simplify result rendering`

## AI-Assisted Development

- Treat generated code as a draft: review, test, and understand it before merging.
- Keep changes scoped; avoid broad rewrites without a clear reason.
- Validate edge cases, errors, accessibility, and loading states.
- Do not expose credentials, private data, or proprietary content in prompts or commits.
- Record meaningful assumptions and technical decisions in project documentation.
