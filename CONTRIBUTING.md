# Contributing Guide

Thank you for your interest in contributing to this project!

## Development Lifecycle

This project uses a Makefile to streamline common development tasks. Below are the main targets you should use during development:

- **make install**: Set up the Python virtual environment and install all dependencies.
- **make format**: Automatically format Python code using Black.
- **make lint**: Run code quality checks on Python and Markdown files.
- **make test**: Run the test suite to ensure your changes do not break anything.
- **make build**: Build the application (if applicable).
- **make serve**: Start the development server locally.
- **make clean**: Remove the virtual environment, caches, build artifacts, and other generated files. Use this if you encounter strange issues or want to reset your environment. This is especially helpful before reinstalling dependencies or when switching branches.
- **make precommit**: Run all checks and formatting steps required before committing code. This target is designed to help you catch issues early and ensure code quality before pushing changes.

## Workflow

1. Fork and clone the repository.
2. Run `make install` to set up your environment.
3. Use `make format`, `make lint`, and `make test` regularly as you work.
4. Before committing, always run `make precommit` to ensure your code meets all quality standards.
5. If you encounter issues, try `make clean` and then `make install` to reset your environment.
6. Submit a pull request with a clear description of your changes.

For any questions, please open an issue or reach out to the maintainers.
