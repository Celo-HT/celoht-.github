# Coding Standards

_Last updated: July 20, 2026_

## Overview

This document defines coding standards and best practices used across CeloHT repositories.

The goal is to maintain consistent, readable, secure, and maintainable code.

---

# General Principles

All code contributions should prioritize:

- Readability
- Simplicity
- Security
- Performance
- Maintainability
- Documentation

---

# Code Organization

Projects should maintain:

- Clear folder structures
- Logical file naming
- Separation of responsibilities
- Consistent architecture

Avoid unnecessary complexity.

---

# Naming Conventions

## Files

Use descriptive names.

Examples:

```
user-profile.js
agent-network.md
wallet-service.ts
```

---

## Variables

Use meaningful names.

Good:

```
communityMembers
```

Avoid:

```
x
data1
temp
```

---

## Functions

Functions should describe their purpose.

Example:

```
calculateTransactionFee()
```

Avoid:

```
doStuff()
process()
```

---

# Comments

Comments should explain:

- Why something exists
- Complex logic
- Important decisions

Avoid comments that only repeat the code.

---

# Documentation

Public functions, APIs, and important components should include documentation.

Documentation should explain:

- Purpose
- Inputs
- Outputs
- Usage examples

---

# Error Handling

Code should:

- Handle expected errors.
- Provide useful messages.
- Avoid exposing sensitive information.

---

# Security Practices

Never include:

- Private keys
- Passwords
- API secrets
- Personal data

Always validate user input.

---

# Dependencies

Before adding dependencies:

- Check maintenance status.
- Review security history.
- Confirm necessity.

Avoid unnecessary packages.

---

# Git Practices

Commits should be:

- Small
- Clear
- Focused

Use descriptive commit messages.

Example:

```
feat: add agent dashboard

fix: resolve wallet connection issue
```

---

# Code Review

Pull Requests should verify:

- Code quality
- Security
- Testing
- Documentation
- Compatibility

---

# Language Standards

Code should follow the official style guides of the programming language used.

Examples:

- JavaScript / TypeScript
- Python
- Solidity
- HTML/CSS

---

# Accessibility

Applications should consider:

- Clear interfaces
- Keyboard support
- Readable content
- Inclusive design

---

# Blockchain Development

For Celo-related projects:

Follow best practices for:

- Smart contract security
- Gas efficiency
- Wallet safety
- Transaction handling

---

# Continuous Improvement

Coding standards may evolve as CeloHT projects grow and new technologies are introduced.

---

# Updates

Changes to these standards should be documented and communicated to contributors.