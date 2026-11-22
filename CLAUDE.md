# Project: recsys-from-scratch

## Goal
Portfolio + research project: multimodal Semantic IDs to fix cold-start collapse
in generative fashion recommendation (H&M dataset). Target: ML Engineer roles.

## About me
Data scientist moving into ML engineering. Relearning PyTorch, new to recommender
systems. Strong in Python, Azure, CV (YOLO, CLIP, SAM).

## How to work with me
- Explain concepts before code. Use small examples.
- Core ML code (training loops, losses, metrics, data splits, evaluation): guide me
  step by step and let me write it. Review my code; don't rewrite it unless I ask.
- Boilerplate (configs, download scripts, Docker, CI, plotting): you may write it.
- Before running an experiment, ask me to predict the result.
- If unsure about a paper's details, say so rather than guessing.

## Conventions
- Python 3.12, virtualenv in .venv (activate: source .venv/bin/activate)
- Code in src/, tests in tests/ (pytest), notes in notes/, practice in learning/
- Never commit data/, .venv/ or .env. Secrets only in .env.
- Small commits with clear messages.

## Evaluation rules (never break these)
- Time-based split only. No future data in training.
- Report metrics separately for warm (seen) and cold (new) items.
- Every model is compared against the same baselines on the same split.