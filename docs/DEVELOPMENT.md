# Development Guide

## Overview

This document describes the development workflow used across CeloHT repositories.

CeloHT is a community-driven open-source initiative. Contributions from developers, designers, educators, writers, researchers, and community members are welcome.

---

# Development Principles

Development should prioritize:

- Simplicity
- Security
- Accessibility
- Sustainability
- Transparency
- Maintainability
- Community collaboration

---

# Repository Workflow

The recommended workflow is:

1. Fork the repository.
2. Create a feature branch.
3. Implement changes.
4. Test your work.
5. Commit using clear messages.
6. Open a Pull Request.
7. Address review feedback.
8. Merge after community approval.

---

# Branch Strategy

The default branch is:

```
main
```

Feature branches should follow this format:

```
feature/add-wallet-support
feature/update-documentation
feature/improve-agent-guide
```

Bug fixes:

```
fix/navigation-links
fix/typos
fix/build-errors
```

Documentation:

```
docs/update-roadmap
docs/new-faq
```

---

# Commit Messages

Recommended examples:

```
feat: add education resources

fix: correct broken links

docs: improve governance guide

refactor: simplify project structure

chore: update dependencies
```

---

# Code Quality

Every contribution should:

- Follow project conventions.
- Be easy to read.
- Avoid unnecessary complexity.
- Include documentation when appropriate.
- Avoid duplicated code.

---

# Documentation

Documentation should:

- Use Markdown.
- Be written in clear English.
- Follow consistent formatting.
- Keep headings organized.

---

# Dependencies

Only trusted and actively maintained dependencies should be added.

Unused dependencies should be removed.

---

# Security

Never commit:

- Private keys
- API keys
- Passwords
- Secrets
- Personal information

Review SECURITY.md before contributing.

---

# Testing

Before submitting a Pull Request:

- Verify builds succeed.
- Check links.
- Review formatting.
- Validate documentation.
- Resolve warnings when possible.

---

# Pull Requests

Pull Requests should:

- Focus on one topic.
- Include a clear description.
- Reference related Issues when applicable.
- Pass automated checks.

---

# Community Review

Community feedback is encouraged before major changes are merged.

Large proposals should be discussed through GitHub Discussions.

---

# Code of Conduct

All contributors are expected to follow the Code of Conduct.

Respectful collaboration is essential to the CeloHT community.

---

# License

By contributing to CeloHT, you agree that your contributions are distributed under the project's license.