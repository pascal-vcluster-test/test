# Contributing to test

Thank you for your interest in contributing! This document provides guidelines and steps for contributing to this project.

## Table of Contents

- [Getting Started](#getting-started)
- [Development Setup](#development-setup)
- [How to Contribute](#how-to-contribute)
- [Pull Request Process](#pull-request-process)
- [Code Style](#code-style)
- [Reporting Issues](#reporting-issues)
- [Maintainers](#maintainers)

## Getting Started

1. Fork the repository on GitHub
2. Clone your fork locally:
   ```bash
   git clone https://github.com/<your-username>/test.git
   cd test
   ```

## Development Setup

This project uses Python. Make sure you have Python 3 installed on your system.

We recommend using [uv](https://docs.astral.sh/uv/) as the Python package manager and project tool. To get started:

1. Install uv (if not already installed):
   ```bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```

2. Run the project:
   ```bash
   uv run test.py
   ```

Alternatively, you can run the project directly with Python:
```bash
python3 test.py
```

## How to Contribute

1. Create a new branch from `main` for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. Make your changes
3. Test your changes locally
4. Commit your changes with a clear and descriptive commit message:
   ```bash
   git commit -m "Add a brief description of your change"
   ```
5. Push your branch to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
6. Open a Pull Request against the `main` branch of this repository

## Pull Request Process

1. Ensure your PR description clearly explains the changes and the motivation behind them
2. Link any related issues in the PR description
3. Make sure your code follows the project's code style guidelines
4. A maintainer will review your PR and may request changes before merging
5. Once approved, a maintainer will merge your PR

## Code Style

- Follow [PEP 8](https://peps.python.org/pep-0008/) conventions for Python code
- Use clear, descriptive variable and function names
- Keep functions focused and concise
- Add comments where the intent of the code is not immediately obvious

## Reporting Issues

If you find a bug or have a feature request, please [open an issue](https://github.com/pascal-vcluster-test/test/issues/new) on GitHub. When reporting a bug, include:

- A clear description of the problem
- Steps to reproduce the issue
- Expected vs actual behavior
- Your Python version and operating system

## Maintainers

- [@pascalbreuninger](https://github.com/pascalbreuninger)
