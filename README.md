# PALM: Data and Predictions

Anonymous release accompanying the ACL ARR 2026 May submission
"PALM: A Benchmark for Personalized Alignment of Local LLMs".

## Contents

- `data/personas/<user>.json` — 100 PANDORA-derived Reddit personas,
  five days of dialogue per user (days 1-4 observed, day 5 held out).
- `data/predictions/<method>/<model>/<user>.json` — per-cell predictions
  for five methods (few-shot, CoT, RAG, SFT, DPO) on six open-source
  backbones (Llama-3.2-1B, Qwen2.5-3B, Mistral-7B-v0.3, Qwen2.5-7B,
  Llama-3.1-8B, Qwen2.5-14B).

## Counts

- 100 personas
- 5 methods x 6 backbones = 30 evaluation cells
- 30 cells x 100 users = 3,000 per-cell prediction files

A non-anonymous code release will follow after the review period.
