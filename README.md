# CodeMait — UI Component Generator (AI-powered)

CodeMait is a lightweight AI-assisted UI component generator that scaffolds reusable components for web projects. It supports multiple frameworks, configurable styling options, and generates TypeScript-friendly code and tests to speed up development.

Core ideas

- Use AI to suggest component structure, props, and documentation.
- Generate ready-to-use component files (component, styles, tests, storybook).
- Support CLI and config-driven generation for automation and templates.

Key features

- Generate components for React, Vue, or plain HTML/CSS.
- Choose styling strategy: CSS, SCSS, CSS Modules, Styled Components.
- Auto-generate TypeScript types and simple unit tests.
- Optional Storybook story generation.
- Configurable templates and naming conventions.
- CLI and config file support for reproducible outputs.

Quick start (prerequisites)

- Node.js >= 14
- npm or yarn

Installation

1. Clone the repo:
   git clone <repo-url> && cd CompGenerator
2. Install dependencies:
   npm install
   # or
   yarn install

CLI usage (examples)

- Generate a React component named Button with CSS modules and TypeScript:
  npx compgenerator generate Button --framework react --styles css-modules --ts

- Generate a Vue component with SCSS:
  npx compgenerator generate Card --framework vue --styles scss

- Generate a basic HTML component:
  npx compgenerator generate Banner --framework html --styles css


How it helps

- Speeds up repetitive scaffolding tasks.
- Produces consistent component structure and tests.
- Allows teams to enforce style and typing conventions via config.

Extending templates

- Templates are stored in /templates (framework-specific).
- Add or modify templates to match your internal patterns.
- The generator reads templates and fills placeholders via the AI suggestion layer.

Contributing

- Open issues for bugs or feature requests.
- Follow repo conventions and add tests for new templates or features.
- Pull requests should include a brief description and relevant unit tests.

Contact
For questions or help, open an issue in this repository.
