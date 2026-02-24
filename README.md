<div align="center">
# Touchless WM

Touchless Window Management for Windows using OpenCV and MediaPipe
</div>

## Overview

### Goals

The goal of this project is to provide alternative means of manipulating the desktop state on Windows using hand gestures and eye tracking.

### Software Stack

- Language: Python
- Frameworks: OpenCV, MediaPipe

## Quickstart

### Development

Clone the repository:

```sh
git clone https://github.com/BlackHat-Magic/CSE-155-Touchless-WM
```

Install [`uv`](https://docs.astral.sh/uv/) and sync dependencies:

```sh
curl -LsSf https://astral.sh/uv/install.sh | sh # if you don't already have uv installed
uv sync
```

Run the script:

```sh
uv run main.py
```

## Collaboration Conventions

- Use semantic commit messages.
- Open an Issue for every distinct unit of work.
- Create branches from `main` named after the issue (e.g., `feat/pose-estimateion`).
- Open a Pull Request early (draft) and link the Issue.
- Request peer review before merging.

