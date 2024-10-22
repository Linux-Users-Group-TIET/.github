# Contributing to LUG Tiet Organisation

Contributions to **LUG Tiet Organisation** are welcomed and encouraged! For contributions to the broader LUG Tiet projects, please see the specific project’s guidelines.

To give clarity of what is expected of our members, **LUG Tiet Organisation** has adopted the code of conduct defined by the [Contributor Covenant](http://contributor-covenant.org/). This document is widely used across many open-source communities and articulates our shared values. Please read the project's [Code of Conduct](https://github.com/Linux-Users-Group-TIET/.github/blob/main/CODE_OF_CONDUCT.md) for more details.

It is highly recommended that you become familiar with using Linux and open-source tools in your own projects before contributing directly to the organisation's projects. We’ve also put together a [Getting Started](https://github.com/Linux-Users-Group-TIET/.github/profile/getting-started.md) guide and tutorials with step-by-step instructions to help you begin.

---

## Reporting Bugs

Reporting bugs is a great way for anyone to help improve the LUG Tiet projects. The open-source projects use GitHub Issues to track bugs.

> **Note**: If a bug can be reproduced only within a particular Linux distribution or external software, please report it to the respective platform’s bug tracker instead.

Since our projects are under active development, we receive many bug reports. Before opening a new issue, please take a moment to [browse our existing issues](https://github.com/Linux-Users-Group-TIET/issues) to reduce the chance of reporting a duplicate.

---

## Good First Issues

**Good first issues** are tasks, bugs, or ideas intended to be accessible for contributors new to working on our projects. These issues are labeled accordingly and can be found in the [Good First Issues](https://github.com/Linux-Users-Group-TIET/) on our Repositories.

They are generally low-priority and relatively modest in scope, without requiring deep research, debugging, or refactoring. Good first issues are great for encouraging newcomers to get involved, learn more about the project, and make meaningful contributions.

Anyone with commit access and insight into a particular area is welcome and encouraged to identify and label **Good First Issues**.

---

## Contributing Code

If you are interested in contributing code to one of our projects:

- **Fork the repository**: Fork the repository you would like to contribute to, using the GitHub `Fork` button.
- **Clone your fork**: Clone the repository to your local environment:
   ```bash
   git clone https://github.com/your-username/project-name.git
   ```

- **Create a feature branch**: Create a dedicated branch for your contribution:
   ```bash
   git checkout -b your-feature-branch
   ```

- **Make your changes**: Develop your contribution—whether it's a new feature, bug fix, or other improvements.

- **Submit a pull request (PR)**: Once you're ready, push your changes to your forked repository and submit a Pull Request to the main project repository. Please provide a clear and concise explanation of your changes.

- **Collaborate on the review process**: Project maintainers will review your PR and may suggest changes. Work with the maintainers until your PR is approved and merged.

For detailed instructions on submitting your first PR, see our [How to Submit Your First Pull Request guide](./docs/HowToGuides/FirstPullRequest.md).

---

## Proposing Changes - Project Evolution

Shaping the future of **LUG Tiet Organisation** projects is a community effort that everyone is encouraged to participate in. If you have an idea for a new feature or a significant change, it’s important to start by discussing it with the community.

The **LUG Tiet** community prefers small, incremental changes over larger changes that are harder to review. Here are some guidelines:

- **Submit small, independent changes**: Try to break larger changes into smaller, standalone changes whenever possible.
- **Gather consensus before starting development**: Open a discussion about your idea in our community forums or GitHub Discussions. This will ensure the community is aligned on the direction of your proposal.

For larger features or changes, it's a good idea to get feedback before writing significant amounts of code.

---

## Incremental Development

The **LUG Tiet Organisation** uses small, incremental changes as its preferred development model. These changes are often small bug fixes or minor improvements, but they can also be steps toward larger goals. Large, monolithic changes make it difficult to review and often lead to merge conflicts.

Here’s why incremental development works better:

- **Merge conflicts**: Large changes can create conflicts, slowing down development.
- **Code reviews**: Large pull requests are harder to review and may be delayed.
- **Continuous integration**: Incremental changes are routinely tested by our CI infrastructure, keeping the codebase stable.

To make large changes easier, break them down into smaller, isolated steps. Some tips:

- **Submit preparatory changes first**: If your larger change depends on refactoring or API adjustments, submit those changes as independent pull requests.
- **Break down interrelated work**: Decompose your larger feature into unrelated sets of changes that can be reviewed and merged individually.

---

## Commit Messages

We don’t enforce a strict format for commit messages, but we prefer that you follow these guidelines, which are common in many open-source projects:

- **Title and body**: Use a single-line title and, if needed, a separate body to describe the changes.
- **Make the title concise**: Keep the title short and meaningful, suitable for reading in a commit log.
- **Use tags for specific areas**: If your change affects a specific part of the project, use a tag in square brackets, e.g., `[UI]`, `[Core]`, etc.
- **Reference issues**: If the commit resolves an issue, include a reference to the GitHub issue.

Good commit messages make it easier for others to understand the context and reasoning behind the changes.

---

## Code Review

The **LUG Tiet Organisation** relies heavily on code reviews to maintain quality. Here’s what to expect during the review process:

- **Submit a PR**: After completing your changes, submit a pull request.
- **Respond to feedback**: Reviewers will leave comments, and you may need to make revisions based on their suggestions.
- **Approval**: Once your changes are approved, they will be merged into the main repository.

Code reviews are an important part of our development process, and we encourage everyone to participate in reviewing others' changes.

---

## Testing

Testing is an integral part of ensuring our projects are stable and reliable. Here’s what’s required:

- **Write tests**: Any new features or bug fixes must be accompanied by test cases to verify their functionality.
- **Test locally**: Run tests locally before submitting your pull request to make sure everything works as expected.

Test coverage is essential for avoiding regressions and ensuring code quality.

---

## Commit Access

Contributors who have demonstrated a strong track record of high-quality contributions may be granted commit access. If you’re interested in commit access, please contact the project maintainers with a list of five significant pull requests you’ve made that were accepted without major modifications.

Once you have commit access, the following rules apply:

- **Commit-after-approval**: You may merge your own pull requests after they have been reviewed and approved.
- **Obvious fixes**: You may commit simple fixes (e.g., typo corrections, comment improvements) directly without prior approval.

---

## Code Attribution

When contributors submit a change, Git automatically tracks the authorship of the commit. We do not add attributions like “This code was written by...” in the source code itself. Instead, rely on Git’s built-in authorship tracking.

Additionally, don’t commit changes authored by others unless they have explicitly given you permission to do so.

---

## Code Templates

All source code files contributed to **LUG Tiet** must include the appropriate license headers. Below are examples for different file types:

For **Bash Scripts**:
```bash
#!/bin/bash
# ===----------------------------------------------------------------------=== #
#
# This script is part of the LUG Tiet Organisation open source project
#
# Licensed under the Apache License, Version 2.0
#
# See https://github.com/Linux-Users-Group-TIET/.github/LICENSE for license information
#
# ===----------------------------------------------------------------------=== #
```

For **Python Files**:
```python
# ===----------------------------------------------------------------------=== #
#
# This file is part of the LUG Tiet Organisation open source project
#
# Licensed under the Apache License, Version 2.0
#
# See https://github.com/Linux-Users-Group-TIET/.github/LICENSE for more information
#
# ===----------------------------------------------------------------------=== #
```

Ensure all new files you contribute include the appropriate header.

---

## Code Quality

We maintain a high bar for code quality to ensure our projects remain stable and reliable. The following are minimum quality standards that must be met before changes are committed to the main branch:

1. **Code must compile without errors** on all supported platforms.
2. **Test coverage**: Bug fixes and new features must include tests to ensure future regressions are avoided.
3. **No regressions**: All code must pass the relevant test suites and must not cause any performance or correctness regressions.

If your change causes issues or regressions, you are responsible for fixing them.
