# Contributing to GitaPulse-DailyVerse-Browser-Extension

We welcome and appreciate all contributions to the GitaPulse-DailyVerse-Browser-Extension project! Whether it's reporting a bug, suggesting an enhancement, or submitting a new feature, your efforts help us make this a better tool for everyone.

Please take a moment to review this document to ensure a smooth and effective contribution process. Adhering to these guidelines helps us maintain code quality, consistency, and a positive collaborative environment.

## 🤝 Code of Conduct

By participating in this project, you are expected to uphold our [Code of Conduct](https://github.com/chirag127/GitaPulse-DailyVerse-Browser-Extension/blob/main/.github/CODE_OF_CONDUCT.md). Please read it carefully.

## 📝 How Can I Contribute?

### 🐞 Reporting Bugs

If you find a bug, please open an issue on our [GitHub Issue Tracker](https://github.com/chirag127/GitaPulse-DailyVerse-Browser-Extension/issues). Before submitting, please check if a similar issue already exists.

When reporting a bug, provide as much detail as possible:

*   **Clear, concise title:** Summarize the issue.
*   **Steps to reproduce:** Detail the exact steps to trigger the bug.
*   **Expected behavior:** What did you expect to happen?
*   **Actual behavior:** What actually happened?
*   **Browser and Version:** (e.g., Chrome 120, Firefox 121)
*   **Extension Version:** If applicable.
*   **Screenshots/Recordings:** (Optional, but highly recommended).

### ✨ Suggesting Enhancements

Got an idea for a new feature or an improvement to an existing one? We'd love to hear it! Open an issue on the [GitHub Issue Tracker](https://github.com/chirag127/GitaPulse-DailyVerse-Browser-Extension/issues) and describe your suggestion.

When suggesting an enhancement, please include:

*   **Clear, concise title:** Summarize the enhancement.
*   **Detailed description:** Explain the feature or improvement in depth.
*   **Motivation:** Why is this enhancement useful? What problem does it solve?
*   **Use cases:** How would users interact with this new feature?

### 💻 Your First Code Contribution

New to open source or this project? Look for issues tagged with `good first issue` or `help wanted` on our [Issue Tracker](https://github.com/chirag127/GitaPulse-DailyVerse-Browser-Extension/issues).

Feel free to ask questions in the issue comments if you need clarification or guidance. We're here to help!

### 🚀 Pull Requests

When you're ready to contribute code, follow these steps to submit a Pull Request (PR):

1.  **Fork the repository** and clone it to your local machine.
2.  **Create a new branch** from `main` for your feature or bug fix: `git checkout -b feature/your-feature-name` or `git checkout -b bugfix/issue-description`.
3.  **Implement your changes** according to the project's [Architectural Patterns](#-architectural-patterns) and [Development Standards](#-development-standards).
4.  **Write comprehensive tests** for your changes. Ensure all existing tests pass.
5.  **Ensure your code passes linting and formatting checks.** (See [Local Development](#local-development)).
6.  **Commit your changes** using [Conventional Commits](#-conventional-commits) guidelines.
7.  **Push your branch** to your forked repository.
8.  **Open a Pull Request** against the `main` branch of the main repository. Fill out the [Pull Request Template](https://github.com/chirag127/GitaPulse-DailyVerse-Browser-Extension/blob/main/.github/PULL_REQUEST_TEMPLATE.md) completely.

Your PR will be reviewed by a maintainer. We might suggest changes or improvements, which is a normal part of the collaboration process.

## 🛠️ Local Development

### Prerequisites

Before you start, ensure you have the following installed:

*   **Node.js (LTS version):** Required for JavaScript development.
*   **pnpm (recommended):** Or npm/yarn for package management. Install with `npm install -g pnpm`.

### Setup

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/GitaPulse-DailyVerse-Browser-Extension.git
    cd GitaPulse-DailyVerse-Browser-Extension
    

2.  **Install dependencies:**
    bash
    pnpm install
    

### Available Scripts

This project uses `pnpm` (or `npm`/`yarn`) scripts for common development tasks:

*   **`pnpm dev`**: Starts the development server for the browser extension, typically providing hot-reloading.
*   **`pnpm build`**: Builds the production-ready extension package.
*   **`pnpm lint`**: Runs Biome to lint and format your code. This is crucial for maintaining code style and quality.
*   **`pnpm test`**: Executes unit tests using Vitest.
*   **`pnpm test:e2e`**: Runs end-to-end tests using Playwright.

Always run `pnpm lint` and `pnpm test` before submitting a PR.

### Architectural Patterns

This project generally adheres to the following principles to ensure maintainability and scalability:

*   **Feature-Sliced Design (FSD):** For structuring the application, ensuring clear boundaries between features and layers.
*   **SOLID Principles:** For robust and maintainable code design.
*   **DRY (Don't Repeat Yourself):** To avoid redundancy in the codebase.

## 💬 Conventional Commits

We follow the [Conventional Commits specification](https://www.conventionalcommits.org/en/v1.0.0/) for our commit messages. This helps with automatic changelog generation and semantic versioning.

**Commit Message Format:**


<type>(<scope>): <short description>

[optional body]

[optional footer(s)]


**Examples:**

*   `feat(verse): Add daily verse display on new tab`
*   `fix(ui): Correct styling for mobile viewports`
*   `docs(readme): Update contribution guidelines`
*   `chore(deps): Upgrade Biome to v1.5.0`

## 🛡️ Security Vulnerabilities

If you discover a security vulnerability, please report it responsibly. Do NOT open a public issue. Instead, refer to our [Security Policy](https://github.com/chirag127/GitaPulse-DailyVerse-Browser-Extension/blob/main/.github/SECURITY.md) for instructions on how to submit a private report.

## 📜 License

By contributing to GitaPulse-DailyVerse-Browser-Extension, you agree that your contributions will be licensed under its [CC BY-NC 4.0 License](https://github.com/chirag127/GitaPulse-DailyVerse-Browser-Extension/blob/main/LICENSE).

Thank you for making GitaPulse-DailyVerse-Browser-Extension better!