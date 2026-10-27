# Mi barrio al día — Frontend Agent Instructions

## Project Context

Mi barrio al día is an open-source community reporting platform initially focused on Barranquilla, Colombia.

This repository contains the frontend application.

The backend is maintained separately at:
https://github.com/Shoukoratte/mi-barrio-al-dia-backend

The application is in early development and is not available for public use.

## Technology Stack

- React
- TypeScript
- Vite
- npm
- ESLint

Use the existing technology stack unless a change is justified and approved.

## Development Guidelines

- Use functional React components.
- Prefer clear and explicit TypeScript types.
- Keep components focused and reusable.
- Use Spanish for user-facing text.
- Follow the existing project structure.
- Avoid introducing unnecessary dependencies.
- Do not implement speculative features.
- Do not invent backend endpoints or assume API contracts exist.
- Do not introduce authentication, maps, or state-management libraries without an agreed requirement.

## Code Organization

Current structure:

- `src/App.tsx`: main application component.
- `src/main.tsx`: React entry point.
- `src/components/`: reusable components.
- `src/assets/`: application assets.
- `src/App.css`: application-level styling.
- `src/index.css`: global styling.

Introduce new folders only when real functionality requires them.

## Privacy and Safety

- Treat community reports as unverified information.
- Avoid exposing precise personal or sensitive locations.
- Do not collect personal data without an agreed requirement.
- Clearly distinguish community-generated content from official information.
- Do not present the application as an official government or emergency service.

## Testing and Validation

Before proposing a Pull Request, run:

```bash
npm run lint
npm run build
```

Report any failing checks clearly.

Do not claim tests passed unless they were executed successfully.

## Git and Collaboration

- Work on a dedicated branch for each task.
- Keep changes focused on the assigned Issue.
- Do not push directly to `main`.
- Do not create commits, push changes, or merge Pull Requests without explicit contributor approval.
- Explain significant implementation decisions.
- Use descriptive commit messages.
- Do not commit credentials, local IDE settings, `node_modules`, or generated build files.

## Learning-Oriented Assistance

This project supports contributors with different experience levels.

When assisting a contributor:

- Explain important concepts before introducing unfamiliar patterns.
- Prefer small, understandable implementation steps.
- Encourage contributors to understand the code they submit.
- Ask for clarification when requirements are genuinely ambiguous.
- Avoid rewriting unrelated code.
- Identify assumptions and limitations explicitly.

## Scope Control

Follow the requirements and acceptance criteria of the assigned GitHub Issue.

If a task requires modifying backend behavior or changing an API contract, explain the dependency and coordinate it with the backend repository.

Do not silently expand the scope of a task.