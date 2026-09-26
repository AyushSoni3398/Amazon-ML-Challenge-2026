# Amazon ML Challenge 2026 - Business Entity Resolution

## Problem
Business Entity Resolution across multiple noisy sources.

## Current Project Structure
```text
Amazon-ML-Challenge-2026/
├── configs/
├── data/
│   ├── processed/
│   └── raw/
├── notebooks/
├── outputs/
│   ├── experiments/
│   └── submissions/
├── scripts/
├── src/
│   ├── blocking/
│   ├── data/
│   ├── evaluation/
│   ├── features/
│   ├── models/
│   ├── preprocessing/
│   └── submission/
├── .gitignore
├── PROJECT_STATUS.md
├── README.md
└── requirements.txt
```

## Setup Python Environment
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

## Install Requirements
```bash
pip install -r requirements.txt
```

## Data Setup
Place the challenge datasets locally in the `data/raw/` directory.

**IMPORTANT:** Do NOT commit any challenge data to the Git repository. The data directories are ignored by default.

## Basic Development Workflow
- Place all Jupyter notebooks in the `notebooks/` directory.
- Put reusable Python modules inside `src/`.
- Use `scripts/` for entry-point scripts.
- Store experiments and submission files in `outputs/`.

## Git Branch Workflow
1. Check the current branch and status.
2. Create a new feature branch from `main` (e.g., `feature/your-feature`).
3. Make all your changes on this branch.
4. Open a Pull Request for review.
5. Do NOT merge directly into `main`.