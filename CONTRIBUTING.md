# Contributing to AetherPlan

Thank you for your interest in contributing to AetherPlan! We want to make contributing to this project as easy and transparent as possible, whether it's:

- Reporting a bug API
- Discussing the current state of the code
- Submitting a fix
- Proposing new features

## We Develop with Github

We use github to host code, to track issues and feature requests, and to accept pull requests.

## Development Workflow

1.  **Fork the repo** and create your branch from `main`.
2.  **Clone the project** to your local machine.
3.  **Install dependencies** with `npm install`.
4.  **Create a branch** for your feature or bug fix: `git checkout -b my-new-feature`.
5.  **Make your changes** and commit them.
6.  **Push** to your fork and submit a **Pull Request**.

## Coding Standards

### Style Guide

-   We use **Prettier** for code formatting. Please ensure your editor is configured to format on save, or run `npm run format` (if script exists) before committing.
-   We use **ESLint** to catch errors and enforce code quality. Run `npm run lint` to check your code.

### TypeScript

-   This project uses **TypeScript**. Please maintain strong typing and avoid using `any` whenever possible.
-   Define interfaces/types for your components and data structures in the `src/types` directory or collocated with the component if specific to it.

### Component Structure

-   Keep components small and focused.
-   Use **Functional Components** with hooks.
-   Place feature-specific components in `src/features/[feature-name]`.
-   Place generic, reusable components in `src/components`.

### Styling

-   Use **Tailwind CSS** for styling components.
-   For complex visual effects (like the glass indicators), you may use custom CSS classes defined in `src/index.css` or `src/App.css`.
-   Ensure the "Dark Mode" aesthetic is maintained.

## Commit Messages

-   Use clear and descriptive commit messages.
-   Start with a verb (e.g., "Add", "Fix", "Update", "Refactor").
-   Example: `Add fluid animation to progress bar`

## Reporting Bugs

-   Check the issue tracker to see if the bug has already been reported.
-   If not, create a new issue.
-   Provide a clear title and description.
-   Include steps to reproduce the issue.

## License

By contributing, you agree that your contributions will be licensed under its MIT License.
