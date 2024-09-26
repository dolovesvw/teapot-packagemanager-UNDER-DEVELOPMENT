
# Contributing to Teapot

Thank you for considering contributing to Teapot! We welcome contributions from everyone, whether you're a seasoned developer or a newcomer to open-source. This guide outlines the process for contributing and the standards for maintaining a healthy, respectful project environment.

## How to Contribute

1. Fork the Repository
Fork the repository to your GitHub account by clicking the "Fork" button at the top of the repository page. This creates a copy of the project under your GitHub username.

2. Clone Your Fork
Once you’ve forked the repository, clone your fork locally:

```bash
git clone https://github.com/your-username/teapot.git
```
Move into the cloned directory:

```bash
cd teapot
```

3. Create a New Branch
Create a new branch for your feature or bug fix:

```bash
git checkout -b my-feature-branch
```
Branch names should be descriptive, ideally using lowercase and hyphens to separate words (e.g., `fix-package-install-bug` or `add-logging-feature`).

4. Make Your Changes
Make your changes or add your new feature. Ensure you write clear, concise code and follow any project conventions. If you're introducing a new feature or fixing a bug, please make sure your code includes:

- Tests: Add or update unit tests to cover your changes.
- Documentation: Update the documentation if your contribution affects how the project works (e.g., user commands or features).

5. Commit Your Changes
Once your changes are made, commit them:

```bash
git add .
git commit -m "Describe the feature or fix"
```
Follow these best practices for commit messages:

- Use the present tense ("Add feature" not "Added feature").
- Keep messages concise, ideally under 50 characters in the first line.

6. Push to Your Fork
Push your changes to your forked repository:

```bash
git push origin my-feature-branch
```

7. Open a Pull Request
Go to the original Teapot repository on GitHub. You should see a button that prompts you to open a Pull Request. Click it and provide a description of your changes.

Ensure the pull request includes:

- A clear description of what you did and why.
- References to related issues (if any).
- Testing steps if applicable.

Once submitted, one of the project maintainers will review your PR. Please be responsive to feedback, and we may request some revisions before merging.

### Guidelines
- Respect the Coding Standards: Follow the existing code conventions in the project. Ensure your changes align with the style used in the codebase.
- Write Tests: Include tests to verify that your code works as intended and does not introduce bugs.
- Keep Commits Focused: Try to keep your changes small and focused on a single issue or feature. This makes it easier to review.
- Be Descriptive: When opening pull requests, provide a detailed explanation of what you’re adding or fixing. It helps maintainers understand the context and test the changes.


---

### `SECURITY.md` (optional)

```markdown
# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark:  |
| < 1.0   | :x:                |

## Reporting a Vulnerability

Please report any security vulnerabilities via email to [your.email@example.com]. 
We will do our best to address the issue as soon as possible.
