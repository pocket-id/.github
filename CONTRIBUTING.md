# Contributing

We are happy that you want to contribute to Pocket ID projects and help to make them better!

## Before you start

Before starting to work on a new feature, please open an issue first, or comment on an existing one, to discuss the implementation details. This saves you time and avoids the disappointment of having a PR closed later because the change doesn't fit the project's direction.

### AI Usage Policy

We have nothing against using AI tools to assist your development. However, AI must not replace the human contribution behind a new feature. **Simply copying a feature request into an AI tool, generating code, and submitting the result as a pull request is not accepted.** Maintainers can already do that themselves, so this workflow provides no meaningful advantage to the project.

This restriction applies to new features, not bug fixes. For feature contributions, we expect meaningful human involvement such as thoughtfully prompting and iterating, making implementation decisions and reviewing and reflecting the output.

#### Guidelines for Using AI Tools

To keep contributions reviewable and high-quality, please follow these guidelines when using AI tools:

1. **Do not submit prompt-only feature implementations.** A new feature must include meaningful human input beyond passing the feature request to an AI tool and submitting its output. This restriction does not apply to bug fixes.
2. **Understand every line.** You must be able to explain what your code does and why, in your own words. "The AI wrote it" is not an acceptable answer to a reviewer's question.
3. **Test before submitting.** Review and test all code manually, as a human, before opening a PR. Don't trust the AI's claim that it works.
4. **Write your own words.** Don't paste AI-generated text into issues, comments, or PR descriptions. Walls of generated text make discussions harder, not easier.

Feature PRs that appear to be low-effort AI output may be closed without a detailed review.

## Getting started

### Submit a Pull Request

Before you submit the pull request for review please ensure that

- The pull request naming follows the [Conventional Commits specification](https://www.conventionalcommits.org):

  `<type>[optional scope]: <description>`

  example:

  ```
  fix: hide global audit log switch for non admin users
  ```

  Where `TYPE` can be:
  - **feat** - is a new feature
  - **doc** - documentation only changes
  - **fix** - a bug fix
  - **refactor** - code change that neither fixes a bug nor adds a feature

- Your pull request has a detailed description
- You format the code using the tools documented by the repository

For setup, formatting, and testing instructions, see the development guide linked from the repository README.
