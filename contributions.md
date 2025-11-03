---
title: Contribution Guide
description: Contribution Guide
github: https://github.com/zaimea/open-source-docs/edit/main/
---

# Contribution Guide

[[TOC]]

Thank you for your interest in contributing to Zaimea!
We welcome contributions of all kinds — bug fixes, new features, documentation improvements, or ideas for future development.
This guide explains how to contribute effectively and consistently across the Zaimea ecosystem.

## 📦 Repositories

Zaimea consists of multiple components:

Core Platform:

 - groups.zaimea.com — main focus of the platform
 - accounts.zaimea.com — authentication and user management
 - zaimea.com — main website and documentation

Open-source Laravel packages:
 - Tools and extensions built for public use (e.g., Sluggable, Charts, Metrics, Calendar, OAuth tooling, etc.)

Each repository may contain its own detailed instructions, but this guide applies globally.

## ✅ How to Contribute

### 1. Reporting Bugs

If you find a bug, please open an issue that includes:

 - Clear title
 - Detailed description of the problem
 - Steps to reproduce
 - Expected behavior
 - Actual behavior
 - Screenshots or logs if useful
 - Version information (PHP, Laravel, package version, browser, OS, etc.)
 - Use the Bug Report template if provided.

### 2. Requesting Features

We welcome new feature ideas.
When opening a feature request, include:

 - What problem the feature solves
 - Why it’s valuable
 - How you imagine the feature working
 - (Optional) Any examples or references to similar tools
 - We may accept it immediately, discuss it, or schedule it for a future release.

### 3. Submitting Pull Requests
Step 1 — Fork the repository

Create your own copy and clone it locally.

Step 2 — Create a feature branch
git checkout -b feature/your-feature-name

Step 3 — Write clean, tested code

Follow Laravel’s coding standards

Write unit tests or feature tests when appropriate

Keep commits small and meaningful

Update documentation if your change affects usage

Step 4 — Run tests locally

Most Zaimea packages use PestPHP:

composer install
php artisan test

Step 5 — Submit a Pull Request

Make sure your PR includes:

A clear title (ex: “Add slug suffix configuration”)

A short description of the change

Reference to any related issue

What was changed and why

Screenshots if UI-related

Notes for reviewers (if needed)

We will review as soon as possible.

## 🧪 Testing Standards

For all Laravel packages and internal services:

 - Tests must pass before a PR can be merged
 - Use Pest for simplicity and readability
 - Follow Given/When/Then structure where reasonable
 - Avoid mocking unnecessarily — test real behavior when possible

## 📄 Code Style

Zaimea follows:

 - PSR-12 coding standards
 - Laravel's naming conventions
 - Clean, understandable architecture
 - Avoiding over-complex abstractions
 - Static analysis tools (like Pint or PHPStan) may be used depending on repo.

##📘 Documentation

If you add or modify functionality, update:

 - README
 - Usage examples
 - Any related docs under resources/docs (if applicable)
 - Good documentation is part of the contribution.

## 🛡 Security

If you discover a security vulnerability, do not open a public issue.
Instead, contact at security@zaimea.com

We will respond as quickly as possible.

##💬 Communication

You can discuss ideas or ask for clarification through:

 - GitHub Issues
 - GitHub Discussions (if enabled)
 - Email (mail@zaimea.com)

We encourage open, friendly communication and constructive feedback.

## 💙 Code of Conduct

By contributing to Zaimea, you agree to follow our Code of Conduct:

 - Be respectful and welcoming
 - Provide constructive criticism
 - Avoid aggressive or abusive behavior
 - Keep discussions focused and technical
