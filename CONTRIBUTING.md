# Contributing to AI Voice Agent

First off, thank you for considering contributing to AI Voice Agent! It's people like you that make AI Voice Agent such a great tool.

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](./CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check if the bug has already been reported. When you are creating a bug report, please include as many details as possible:

* **Use a clear and descriptive title**
* **Describe the exact steps which reproduce the problem**
* **Provide specific examples to demonstrate the steps**
* **Describe the behavior you observed after following the steps**
* **Explain which behavior you expected to see instead and why**
* **Include screenshots and animated GIFs if possible**
* **Include your environment details**

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

* **Use a clear and descriptive title**
* **Provide a step-by-step description of the suggested enhancement**
* **Provide specific examples to demonstrate the steps**
* **Explain why this enhancement would be useful**

### Pull Requests

* Fill in the required template
* Follow the Python styleguides
* Include appropriate test cases
* Update documentation as needed
* End all files with a newline

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line

### Python Styleguide

* Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/)
* Use [Black](https://github.com/psf/black) for code formatting
* Use [Pylint](https://www.pylint.org/) for linting
* Write docstrings for all public functions

### Documentation Styleguide

* Use [Markdown](https://daringfireball.net/projects/markdown) for all documentation
* Reference other markdown documents with relative links
* Keep line length under 100 characters where possible

## Development Setup

1. Fork and clone the repository
2. Create a virtual environment: `python -m venv venv`
3. Activate the virtual environment: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements-dev.txt`
5. Create a branch for your changes: `git checkout -b my-branch`
6. Make your changes and test thoroughly
7. Commit and push your changes
8. Create a pull request

## Testing

Before submitting a PR, make sure all tests pass:

```bash
# Run all tests
pytest

# Run with coverage
pytest --cov=ai_voice_agent

# Run specific test file
pytest tests/test_specific.py
```

## Code Review Process

1. At least one maintainer review is required
2. All CI checks must pass
3. Code coverage should not decrease
4. All feedback must be addressed before merging

Thank you for contributing! 🎉
