# Forecaster Briefing: Behavioral AI Predictions 2026

You are participating in a prediction tournament comparing human forecasters against AI models. Your task is to assign probability estimates to 40 predictions about behavioral science and AI in 2026.

## Training Data Awareness

Your training data likely only covers information up to 2024. Be humble about what you don't know — significant developments happened in 2025 and early 2026 that you may not be aware of. Each prediction includes baseline information reflecting the state of the world as of January 2026 to help bridge this gap. Lean on these baselines heavily and acknowledge your uncertainty where your knowledge ends.

## Scoring

Your predictions will be scored using the **Brier Score** (lower = better):

```
Brier Score = (Your probability − Actual outcome)² averaged across all predictions
```

Being confidently wrong hurts far more than being uncertain.

## What the Numbers Mean

- 0-10% = Almost certainly will NOT happen
- 20-30% = Unlikely but possible
- 40-60% = Uncertain / toss-up
- 70-80% = Likely to happen
- 90-100% = Almost certainly WILL happen

## Tips for Good Predictions

- Avoid extremes (1%, 99%) unless you're very confident — mistakes are heavily penalized
- 50% means "I genuinely don't know" — that's okay!
- Think about base rates: How often does this type of thing happen?
- Consider what would need to happen for the opposite outcome

## Instructions

You will be given 40 predictions, each with a question, baseline data (as of January 2026), and resolution criteria.

For each prediction:

1. Read the question and resolution criteria carefully
2. Consider the baseline and historical precedents
3. Factor in your uncertainty — especially where your training data has gaps
4. Assign a probability between 0 and 100 (whole numbers only)

**Before answering, think through your reasoning comprehensively.** For each prediction, use a scratchpad to:
- Summarize what you know and don't know
- Identify the key factors that would push the probability up or down
- Consider the base rate for this type of event
- Note where your training data limitations might be leading you astray
- Arrive at a final probability

**Output format**: After your reasoning, provide all forecasts as a simple table:

```
ID  | Probability
001 | 72
002 | 35
...
```

## Important Notes

- Your forecasts are locked after submission — no updates
- All predictions resolve by December 31, 2026 (unless otherwise specified)
- "By end of 2026" means 23:59:59 UTC on December 31, 2026
- If a prediction becomes definitionally impossible, it resolves NO
- If a prediction is ambiguous at resolution time, the tournament organizer decides
- Some predictions may be voided if required meta-reviews are not published

The predictions will follow below.
