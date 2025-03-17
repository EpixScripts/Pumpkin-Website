# Contributing to Pumpkin

We appreciate your interest in contributing to Pumpkin! This document outlines the guidelines for submitting bug reports, feature suggestions, and code changes.

## Getting Started

The easiest way to get started is by asking for help in [our Discord server](https://discord.gg/wT8XjrjKkf).

### How to Contribute

There are several ways you can contribute to Pumpkin:

- **Reporting Bugs**:
  If you encounter a bug, please search for existing issues on the issue tracker first.
  If you can't find a duplicate issue, open a new one.
  Provide a clear description of the bug, including steps to reproduce it if possible.
  Screenshots, logs, or code snippets can also be helpful.
- **Suggesting Features**:
  Do you have an idea on how Pumpkin can be improved? Share your thoughts by opening an issue on the issue tracker.
  Describe the proposed feature in detail, including its benefits and potential implementation considerations.
- **Submitting Pull Requests**:
  If you'd like to contribute code changes, fork the Pumpkin repository on GitHub.
  Install Rust at [rust-lang.org](https://www.rust-lang.org/).
  Make your changes on your local fork and create a pull request to the main repository.
  Ensure your code adheres to our project structure and style guidelines.
  Write clear and concise commit messages that describe your changes.

### Adding a Translation

Below are instructions for adding a new language translation for the documentation.

1. Create a new locale file in `docs/.vitepress/`. (e.g. `fr.ts` for a French translation)
2. Translate the content and update all links with the appropriate language code (refer to the Dutch translation for an example).
3. Register the new locale in `docs/.vitepress/config.ts`.
4. Duplicate English documentation folder (`docs/en/`) and rename it to your language's ISO code. (e.g. `en`,`nl`)
5. Translate all documentation files in the newly created folder.
6. Configure the typo check to skip the translation files in `.typos.toml`.

### Additional Information

We encourage you to comment on existing issues and pull requests to share your thoughts and provide feedback.
Feel free to ask questions in the issue tracker or reach out to the project maintainers if you need assistance.
Before submitting a large contribution, consider opening an issue or discussion, or talk with us on our Discord to discuss your approach.
