# DevOps Git Workflow & Best Practices Project

This repository demonstrates industry-standard Git practices, branching strategies, conflict resolution, and release tagging for DevOps engineering.

## Branching Strategy
- `main`: Production-ready code and releases.
- `dev`: Active integration and testing branch.
- `feature/*`: Short-lived branches for individual features or fixes.

## Completed Tasks
1. Repository initialization with standard directory layout (`scripts/`, `docs/`, `config/`).
2. Configured `.gitignore` to exclude OS files, build artifacts, and sensitive files.
3. Implemented branch hierarchy (`main` -> `dev` -> `feature/*`).
4. Simulated Pull Request workflows and resolved merge conflicts manually.
5. Applied semantic version tagging (`v1.0.0`).

## Verification Commands
```bash
# View commit history graph
git log --graph --oneline --all

# View tags
git tag -l -n
```