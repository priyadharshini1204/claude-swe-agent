
# OpenLibrary Hackathon - Automated Agent Workflow (Runs on Push)

This repository contains the automated workflow for the SWE-Task Hackathon.

## Structure

- `.github/workflows/swebench-eval.yml`: The main GitHub Actions workflow.
- `run_claude.py`: The AI agent script using Claude Sonnet.
- `extract_metrics.py`: Script to parse logs and generate `result.json`.
- `task.yaml`: Configuration file for the specific task (bug).

## Setup

1.  **API Key**: Ensure the `ANTHROPIC_API_KEY` secret is set in your GitHub repository settings.
2.  **Task Definition**: Update `task.yaml` with the specific bug details provided in the hackathon resources.

## Running

Push to the `main` branch to trigger the workflow.

