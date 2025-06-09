# Contributing to Korepi

First off, thank you for considering contributing to Korepi! We're thrilled you're here. Every contribution, no matter how small, is valuable and helps make this project better for everyone.

This document provides a set of guidelines for contributing to the Korepi documentation. Following them helps us keep the project maintainable and makes the contribution process smoother for everyone involved.

## Code of Conduct

Before you start, please take a moment to read our **[Code of Conduct](./CODE_OF_CONDUCT.md)**. We expect all contributors to adhere to it to ensure our community remains a welcoming and inclusive environment.

## How Can I Contribute?

There are many ways to contribute, from improving the documentation to reporting bugs and suggesting new features.

### Reporting Bugs

If you find a bug in the documentation (e.g., a broken link, a typo, or inaccurate information), please open an issue on GitHub. A good bug report is one that can be easily reproduced.

Please include the following in your bug report:
-   **A clear and descriptive title:** e.g., "Broken link on the Custom Teleport page."
-   **The URL of the page** where you found the bug.
-   **A detailed description** of what is wrong.
-   **A suggestion for how to fix it** (if you have one).

### Suggesting Enhancements or New Features

If you have an idea for a new feature or an improvement to the documentation structure:
1.  **Check if the feature already exists** or if an issue for it has already been created.
2.  If not, **open a new issue** on GitHub.
3.  Clearly describe the proposed enhancement, including:
    -   **The problem it solves:** Why is this enhancement needed?
    -   **A detailed description of the proposed solution:** How would it work? How would it look?

### Pull Requests for Documentation Changes

We welcome pull requests to fix typos, improve clarity, or add new content.

**1. Getting Started**
-   Fork the repository.
-   Clone your forked repository to your local machine.
-   Follow the [**Local Development & Testing**](./README.md#local-development-&-testing) instructions in the main README to set up the project.

**2. Create a New Branch**
Create a new branch for your changes. Use a descriptive name like `fix/typo-in-teleport-guide` or `docs/add-echo-modifier-page`.
```bash
git checkout -b your-branch-name
```

**3. Make Your Changes**
Make your edits to the relevant markdown files. Please adhere to the **Style Guide** below.

**4. Commit Your Changes**
Commit your changes with a clear and descriptive commit message. We follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.

**Commit Message Format:**
```
<type>: <subject>

[optional body]
```
-   **`type`**: Must be one of `fix`, `feat`, `docs`, `style`, `refactor`, `test`, `chore`.
-   **`subject`**: A short, imperative-tense description of the change.

**Examples:**
-   `docs: update contributing guide with style information`
-   `fix: correct broken link on the download page`

**5. Push and Open a Pull Request**
-   Push your branch to your forked repository: `git push origin your-branch-name`
-   Open a pull request from your fork to the main Korepi repository.
-   In the pull request description, clearly explain the changes you've made and link to any relevant issues (e.g., "Closes #123").

---

## Style Guide for Documentation

To maintain consistency across the documentation, please follow these style guidelines.

### Writing Tone
-   **Clear and Concise:** Use simple, direct language. Avoid jargon where possible.
-   **Friendly and Welcoming:** Write in a way that is helpful and encouraging to users of all experience levels.
-   **Use English:** All documentation should be written in English or the Language that you working on.

### Formatting
-   Use standard Markdown for all formatting (headings, lists, bold, italics, etc.).
-   Use code blocks for commands, file names, and configuration settings.

### Icon Usage
We use [FontAwesome](https://fontawesome.com/search) icons to visually enhance our documentation pages.
-   To add an icon to a page, use the `icon:` key in the frontmatter at the top of the markdown file.
-   Find the desired icon on FontAwesome and use its name.
