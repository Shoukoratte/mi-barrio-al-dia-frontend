# Mi barrio al día — Frontend

**The web interface for a community-driven neighborhood reporting platform, initially focused on Barranquilla, Colombia.**

## Project Status

The frontend is in its initial development stage.

The project currently includes a React application, a reusable header component, and a demonstration counter.

Community reporting, interactive maps, authentication, and backend integration are not implemented yet.

The application is not available for public use.

## Technology Stack

- React
- TypeScript
- Vite
- ESLint
- npm

Additional technologies will be introduced when justified by project requirements.

## Getting Started

### Prerequisites

- Node.js compatible with the project's Vite version
- npm
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/Shoukoratte/mi-barrio-al-dia-frontend.git
cd mi-barrio-al-dia-frontend
```

Install dependencies:

```bash
npm ci
```

Start the development server:

```bash
npm run dev
```

Open the local URL shown in the terminal, typically `http://localhost:5173`.

### Code Quality

Run ESLint:

```bash
npm run lint
```

Create a production build:

```bash
npm run build
```

These commands should complete successfully before submitting a Pull Request.

## Project Structure

```text
src/
├── assets/          # Images and other application assets
├── components/      # Reusable React components
│   └── Header.tsx
├── App.tsx          # Main application component
├── App.css          # Application-level styles
├── index.css        # Global styles
└── main.tsx         # React entry point
```

The structure will evolve as new features are implemented.

Avoid introducing unnecessary dependencies or architectural layers before they are needed.

## Backend Integration

The backend is maintained in a separate repository:

[Mi barrio al día — Backend](https://github.com/Shoukoratte/mi-barrio-al-dia-backend)

The applications will communicate through documented HTTP APIs using JSON.

Backend integration is not implemented yet.

## Contributing

We welcome contributions that improve the application and help the team learn.

For each contribution:

1. Start from an updated `main` branch.
2. Create a descriptive feature, fix, or documentation branch.
3. Implement a focused change.
4. Run `npm run lint` and `npm run build`.
5. Open a Pull Request explaining the changes and how they were tested.

Use GitHub Issues to coordinate tasks and discuss implementation details.

Do not commit `node_modules`, local IDE settings, credentials, or build output.

Detailed contributor guidelines will be added incrementally.

## Project Principles

- **Community first:** address real neighborhood needs.
- **Privacy by design:** avoid unnecessary exposure of personal information or precise locations.
- **Accessibility:** prioritize inclusive, usable interfaces.
- **Spanish first:** design the user experience for Spanish-speaking residents, with future internationalization support.
- **Continuous learning:** document decisions and encourage constructive code reviews.
- **Zero-cost development:** prioritize free and open-source tools.

## Important Disclaimer

Mi barrio al día is an independent community initiative.

It is not an official government reporting system, does not replace emergency services, and does not automatically submit formal complaints or petitions.

Community-submitted information must not be presented as officially verified.

## License

A software license has not yet been selected. Public repository visibility does not automatically grant permission to reuse or redistribute the code.