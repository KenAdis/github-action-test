# GitHub Action Test Workflow

This repository contains a basic GitHub Actions workflow to demonstrate the process of setting up and running a simple Python test script within a CI/CD pipeline.

## 🚀 Workflow Overview

The workflow consists of the following jobs:

1. **say-hello**: Prints a simple greeting message ("Hello, GitHub Actions").
2. **build-and-test**: 
   - Checks out the repository.
   - Installs required dependencies (including `python3`).
   - Runs a Python test script (`test.py`).

## 🛠 Workflow Trigger

This workflow is triggered by a `push` event to the repository.

## 📋 Requirements

- Python 3
- GitHub Actions enabled in the repository
