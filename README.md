# README

## Getting Started

Follow these steps to set up your development environment:

### 1. Clone the repository

```sh
git clone <repository-url>
cd post-service
```

### 2. Install markdownlint (for Markdown linting)

You need to install `markdownlint` globally to enable linting for Markdown files:

```sh
sudo apt update && sudo apt install nodejs npm
npm install -g markdownlint-cli
```

### 3. Install Python dependencies

Before using any other make target, run:

```sh
make install
```

This will create a virtual environment (if it doesn't exist) and install all Python dependencies listed in `requirements.txt`.
