# Haoran Chen (陈浩然)

Hi! I'm Haoran, a Master's student in Trustworthy & Responsible AI at École Polytechnique,
currently a research intern at HrFlow.ai and part of a research collaboration on Agentic RL.

I work on **the signals we use to evaluate and train LLM systems** — whether they measure what
we think they measure, and whether they land where they should. Most of my work is the same
question asked in different places: *is this signal real, and is it reaching the right target?*

- **Evaluation & auditing** — LLM-as-judge reliability, fairness audits for AI-assisted hiring,
  probe validity and artifact detection. I care about protocols that can actually fail:
  cluster bootstrap, BH-FDR, negative and positive controls, not point estimates.
- **Reward signals & post-training** — reward construction and leakage auditing, counterfactual
  data augmentation, controlled "same architecture, same loss, different training target"
  experiments. I'm currently extending this to **credit assignment in long-horizon agentic RL**,
  where a single terminal reward has to be attributed across a whole trajectory.

A result I keep running into: alignment quality is decided far more by the target you train
against than by the constraints you bolt onto the loss. Which is why I keep ending up auditing
signals instead of designing losses.

📍 Paris · [LinkedIn](https://linkedin.com/in/haoran-chen-9614a3388) · haoran.chen@polytechnique.edu

I'm open to PhD positions and 2027 intern roles.

`Python` · `PyTorch` · `TRL` · `pandas` / `scikit-learn` / `statsmodels` · LLM Evaluation, RLHF & Agentic RL
