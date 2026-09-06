# The Midyear Report Card

*Behavioral AI Predictions 2026 — Midyear Resolution Analysis*

## Executive Summary

### Where We Stand

Back in January we locked 40 predictions and asked 21 forecasters — 10 humans, 6 frontier AI models, and 5 of those same models wearing persona masks — to put a number on each one. The first report compared how they disagreed. Nobody could be scored, because nothing had happened yet.

Something has now happened. 7 of the 40 predictions have resolved, 1 has been thrown out, and 32 are still live. That is enough to put names on a leaderboard — and not nearly enough to settle the argument. Both of those things are true at once, and this report tries to hold them together.

### What We Found

**Humans are ahead.** Mean Brier score of 0.236, against 0.275 for AI models. Lower is better, and the gap is 0.039 — real, but built on 7 questions. Ask again in December.

**Every resolved prediction resolved YES — and that is the whole story so far.** 7 for 7. When everything that resolves resolves in the affirmative, the scoreboard stops measuring judgement and starts measuring nerve: whoever guessed highest wins, automatically. The correlation between a forecaster's average optimism across all 40 predictions and their score here is -0.64. That is not a finding about who reasons well. It is a finding about which way the year broke.

**The gap the first report found is the gap that is paying out.** Across all 40 predictions the humans averaged 45% and the models 37%. The humans thought more things would happen. So far more things have happened. Whether that is foresight or a coin landing the same way 7 times is exactly the question December answers.

**The masks changed the answers, and mostly not for the better.** Of the 5 personas we can compare against the model actually running them, 2 scored better with the mask on than the same model did playing it straight. A worldview moves your numbers. It does not reliably move them toward what happens.

**MAGA Council and human-5 are in a dead heat** at the top, separated by 0.0007 of a Brier point — both on 0.114, which is a tie in every sense that matters. Superforecaster props up the table at 0.434. Enjoy it or don't — on 7 resolved questions, the distance between first and last is one bad December away from meaningless.

---

## Layer 1: The Scoreboard

Brier score is the standard measure: take the gap between your probability and what actually happened, square it, average across questions. Zero is perfect. A forecaster who says 50% to everything scores 0.25 forever, which is why that line is drawn on every chart here — it is the score you get for having no opinion.

![Midyear Leaderboard](charts/12_midyear_leaderboard.png)

### The Full Table

| Rank | Forecaster | Type | Mean Brier | Beat the coin flip? |
|------|------------|------|-----------|---------------------|
| 1 | MAGA Council | persona | 0.114 | Yes |
| 2 | human-5 | human | 0.114 | Yes |
| 3 | human-1 | human | 0.129 | Yes |
| 4 | Grok 4.1 | model | 0.154 | Yes |
| 5 | Gemini 3 Pro | model | 0.165 | Yes |
| 6 | human-9 | human | 0.177 | Yes |
| 7 | human-2 | human | 0.198 | Yes |
| 8 | human-6 | human | 0.216 | Yes |
| 9 | GPT-5.2 | model | 0.254 | No |
| 10 | Techno-Optimist | persona | 0.255 | No |
| 11 | Doomer | persona | 0.262 | No |
| 12 | human-7 | human | 0.265 | No |
| 13 | AI Bro Council | persona | 0.270 | No |
| 14 | human-10 | human | 0.277 | No |
| 15 | human-4 | human | 0.280 | No |
| 16 | Mistral Large 3 | model | 0.321 | No |
| 17 | human-3 | human | 0.323 | No |
| 18 | Claude Opus 4.5 | model | 0.375 | No |
| 19 | Kimi K2.5 | model | 0.379 | No |
| 20 | human-8 | human | 0.380 | No |
| 21 | Superforecaster | persona | 0.434 | No |

8 of 21 forecasters are beating the no-opinion baseline, which means 13 would have done better by refusing to answer.

### By Tribe

![Group Brier](charts/13_midyear_group_brier.png)

| Group | Members | Mean Brier | Mean forecast (all 40) |
|-------|---------|-----------|------------------------|
| Humans | 10 | 0.236 | 45% |
| AI Models | 6 | 0.275 | 37% |
| AI Personas | 5 | 0.267 | 46% |

---

## Layer 2: The Resolved Calls

Here is every question that has actually landed, with where each tribe's median forecast sat when the answer was still unknown.

![Resolved Calls](charts/14_midyear_resolved_calls.png)

**How to read this:** the black diamond is the truth — hard right for YES, hard left for NO. The three bars are the group medians. A bar far from the diamond is a tribe that got it wrong; bars clustered on the wrong side of the diamond mean everybody missed it together.

| Prediction | Outcome | Humans | AI Models | AI Personas | Widest miss |
|------------|---------|--------|-----------|-------------|-------------|
| #010: Therapy/Companionship Remains #1 | YES | 72% | 55% | 70% | AI Models |
| #021: AI Military System Investigation | YES | 50% | 51% | 42% | AI Personas |
| #023: Major Outlet AI Misinfo Retraction | YES | 62% | 60% | 35% | AI Personas |
| #026: AI Attachment Disorder Study | YES | 80% | 52% | 55% | AI Models |
| #029: METR: AI Speeds Up Devs | YES | 58% | 60% | 65% | Humans |
| #032: FrontierMath Tier 4 >50% | YES | 50% | 35% | 60% | AI Models |
| #033: Remote Labor Index >15% | YES | 32% | 32% | 40% | Humans |

The field's best question was **#010: Therapy/Companionship Remains #1** (mean Brier 0.140) — close to a collective read. Its worst was **#033: Remote Labor Index >15%** (0.430), where the field was not so much split as uniformly wrong.

One question, **#028: AI Companions & Loneliness Meta-Review**, was voided rather than scored. Voiding is the honest move when a question turns out to have been broken from the start — but it is also the move with no cost to anyone's record, so it deserves to be named rather than quietly dropped.

---

## Layer 3: Where It Is Heading

The scoreboard above uses 7 questions. There are 32 more, and the review has published a probability for every one of them. That is enough to project the finish: score each resolved question the ordinary way, and score each open one by what it is expected to cost — the distance from the reviewed estimate, plus the uncertainty that remains no matter what anybody said.

![Projected Standing](charts/17_midyear_projected_vs_resolved.png)

**How to read this:** the dashed line is "no change". Anyone below it is projected to finish better than their current position suggests; anyone above it is living on the resolved questions and is expected to give it back.

**The board turns over almost completely.** Gemini 3 Pro is projected first at 0.199, having sat 5th on resolved questions alone. The current leaders do not hold.

| Forecaster | Now | Projected | Move |
|-----------|-----|----------|------|
| Claude Opus 4.5 | 18 | 7 | up 11 |
| Superforecaster | 21 | 10 | up 11 |
| Kimi K2.5 | 19 | 9 | up 10 |
| human-1 | 3 | 17 | down 14 |
| human-5 | 2 | 15 | down 13 |
| human-9 | 6 | 18 | down 12 |

The reason is the one this report keeps returning to. Every resolved question so far landed YES, which flatters whoever guessed high. The reviewed outlook expects most of the 32 open questions to land NO — so the same optimism that built the current leaderboard is what the projection charges for.

Two honest caveats. This is a projection against an analyst estimate, not a result: if the outlook is wrong, the projection is wrong in exactly the same direction. And 0.125 of every projected score is irreducible — the uncertainty still sitting on the open questions, which no forecaster can score below. That is 63% of the projected leader's total, so most of this table is not yet skill.

---

## Layer 4: The Five Strongest Signals

Of the 32 questions still open, these five carry the most decisive reviewed outlook — the ones furthest from a coin flip, where the year has effectively already decided even though the calendar has not caught up.

### 1. #006 — heading NO at 1%

*A humanoid robot for home/consumer use will ship >500,000 units globally in 2026.*

The January crowd said **20%**; the review puts it at **1%** (likely no, high confidence) — a gap of 19 percentage points, well below what the field expected.

The strongest August estimate puts all-purpose humanoid shipments near 60,000 for 2026, only 12% of the home-consumer threshold, while qualifying consumer deliveries are only beginning.

*Against it:* 1X is preparing NEO home deliveries, and complete full-year shipment data is not yet available.

### 2. #016 — heading NO at 2%

*An AI system will be credited with solving a Millennium Prize Problem in 2026.*

The January crowd said **16%**; the review puts it at **2%** (likely no, high confidence) — a gap of 14 percentage points, well below what the field expected.

Clay still lists six problems as unsolved and its ordinary acceptance process takes at least two years.

*Against it:* An older AI-assisted proof could receive acceptance in 2026, while frontier systems continue advancing in research mathematics.

### 3. #037 — heading NO at 2%

*AI be able to generate a feature length high-quality film based on one prompt (one-shot)*

The January crowd said **18%**; the review puts it at **2%** (likely no, high confidence) — a gap of 16 percentage points, well below what the field expected.

A 90-minute AI feature exists, but it required a team, many prompts, editing, and post-production rather than one-shot generation.

*Against it:* Odysseus and Dark Paradise demonstrate 135-minute and 82-minute AI-assisted features, but both used prolonged human workflows.

### 4. #039 — heading NO at 5%

*A song with AI-generated vocals will reach Spotify global top 10 most-streamed in a single week in 2026.*

The January crowd said **46%**; the review puts it at **5%** (rule risk, medium confidence) — a gap of 41 percentage points, well below what the field expected.

AI-vocal tracks have entered global and viral charts, but none has approached Spotify's weekly global top ten.

*Against it:* New licensing for AI-driven vocal covers could accelerate distribution and legitimacy.

### 5. #014 — heading NO at 7%

*A model from lab other than OpenAI, Anthropic, or Google will hold #1 on LiveBench on December 31, 2026.*

The January crowd said **19%**; the review puts it at **7%** (likely no, medium confidence) — a gap of 12 percentage points, well below what the field expected.

The verified leaderboard still has a big-three model first with Kimi K3 only sixth.

*Against it:* Rapid non-big-three progress means a late model release could overturn this exact-date snapshot.

Four of these resolve by simply running out of year. That is the quiet asymmetry in this tournament: a YES can arrive any day, but a NO only becomes true on December 31, which is why the board looks so one-sided at the midpoint and why it should not stay that way.

![Crowd versus Outlook](charts/18_midyear_crowd_vs_outlook.png)

**How to read this:** each line runs from what the forecasters believed in January to where the review now puts the question. Long lines are where the year has moved most against the original consensus — and where the leaderboard has most left to give.

---

## Layer 5: Does Nerve Beat Judgement?

![Bullishness vs Score](charts/15_midyear_bullishness_vs_score.png)

With every resolved question landing YES, this chart is close to a straight line by construction — correlation -0.64 between how optimistic a forecaster was overall and how well they have scored. The forecasters near the bottom right are not necessarily the sharpest thinkers in the tournament. They are the ones who leaned toward *things will happen*, in a half-year where things happened.

The interesting test is the other half of the year. If a run of NO resolutions arrives — deadlines passing with nothing filed, benchmarks unbeaten — this chart flips, and the current leaders fall furthest. Nothing in the data so far distinguishes a good forecaster from a lucky optimist. That is not a criticism of the leaders; it is a description of what 7 same-signed outcomes can support.

---

## Layer 6: Did the Mask Help?

Each persona was run on a specific model. That gives us a controlled comparison the human forecasters can't offer: the same machine, same briefing, same questions, once with a worldview and once without.

![Persona vs Base](charts/16_midyear_persona_vs_base.png)

| Persona | Base model | Persona Brier | Base Brier | Mask effect |
|---------|-----------|--------------|-----------|-------------|
| MAGA Council | Grok 4.1 | 0.114 | 0.154 | helped (-0.041) |
| Techno-Optimist | Kimi K2.5 | 0.255 | 0.379 | helped (-0.124) |
| Doomer | Gemini 3 Pro | 0.262 | 0.165 | hurt (+0.097) |
| Superforecaster | Claude Opus 4.5 | 0.434 | 0.375 | hurt (+0.059) |
| AI Bro Council | GPT-5.2 | 0.270 | 0.254 | hurt (+0.016) |

MAGA Council and Techno-Optimist came out ahead of the model underneath. Whether a worldview is an edge or a handicap depends entirely on whether the world is currently agreeing with it — which, this half-year, it partly was.

---

## Layer 7: The Full Board

All 40 predictions, with what the field said in January and where each one stands now. "Now" is 100% or 0% for anything settled, the reviewed outlook for anything open, and blank for the voided question.

| # | Prediction | Category | Jan avg | Now | Status |
|---|-----------|----------|--------:|----:|--------|
| 001 | Major AI Lab IPO | AI Industry | 52% | 62% | open |
| 002 | AI Unicorn Failure/Acquisition | AI Industry | 49% | 65% | open |
| 003 | AI Lab Claims AGI | AI Industry | 29% | 10% | open |
| 004 | ChatGPT 1B WAU | AI Industry | 73% | 86% | open |
| 005 | AI 5%+ GDP Growth Country | AI Industry | 20% | 45% | open |
| 006 | Consumer Humanoid >500K Units | AI Industry | 20% | 1% | open |
| 007 | AI Wearable 10M Units | AI Industry | 37% | 35% | open |
| 008 | OpenAI Consumer Hardware Launch | AI Industry | 41% | 20% | open |
| 009 | AI Therapy App 10M MAU | AI Industry | 46% | 20% | open |
| 010 | Therapy/Companionship Remains #1 | AI Industry | 65% | 100% | **YES** |
| 011 | OpenAI Leads LiveBench EOY | Benchmarks | 40% | 48% | open |
| 012 | Anthropic Leads LiveBench EOY | Benchmarks | 29% | 27% | open |
| 013 | Google Leads LiveBench EOY | Benchmarks | 33% | 10% | open |
| 014 | Other Lab Leads LiveBench EOY | Benchmarks | 19% | 7% | open |
| 015 | Open Model in LiveBench Top 5 | Benchmarks | 44% | 48% | open |
| 016 | AI Solves Millennium Prize | Benchmarks | 16% | 2% | open |
| 017 | Behavioral Benchmark Adopted | Benchmarks | 45% | 25% | open |
| 018 | AI Autonomous Blackmail >$10K | AI Safety | 25% | 15% | open |
| 019 | No Major AI Catastrophe | AI Safety | 71% | 55% | open |
| 020 | AI Misinfo Election Impact | AI Safety | 47% | 30% | open |
| 021 | AI Military System Investigation | AI Safety | 50% | 100% | **YES** |
| 022 | AI Liability Lawsuit Win | AI Safety | 50% | 12% | open |
| 023 | Major Outlet AI Misinfo Retraction | AI Safety | 53% | 100% | **YES** |
| 024 | Platform Mandates AI Watermarking | AI Safety | 41% | 8% | open |
| 025 | Companion-Specific Age Verification | AI Safety | 53% | 25% | open |
| 026 | AI Attachment Disorder Study | Research | 67% | 100% | **YES** |
| 027 | AI Critical Thinking Meta-Review | Research | 51% | 10% | open |
| 028 | AI Companions & Loneliness Meta-Review | Research | 53% | — | VOID |
| 029 | METR: AI Speeds Up Devs | Research | 59% | 100% | **YES** |
| 030 | AI Top Problem >2% Gallup | Research | 32% | 8% | open |
| 031 | METR 18+ Hour Task Horizon | AI Capabilities | 57% | 67% | open |
| 032 | FrontierMath Tier 4 >50% | AI Capabilities | 49% | 100% | **YES** |
| 033 | Remote Labor Index >15% | AI Capabilities | 37% | 100% | **YES** |
| 034 | OpenAI-Proof Q&A >25% | AI Capabilities | 40% | 20% | open |
| 035 | GSOBench >60% | AI Capabilities | 44% | 45% | open |
| 036 | AI Autonomously Earns $1K+ | AI Capabilities | 46% | 60% | open |
| 037 | AI One-Shot Feature Film | AI Capabilities | 18% | 2% | open |
| 038 | AI Film Festival Nomination | AI Capabilities | 35% | 25% | open |
| 039 | AI Song Spotify Top 10 | AI Capabilities | 46% | 5% | open |
| 040 | AI Book Bestseller | AI Capabilities | 35% | 10% | open |

### Which categories the field misread

Average gap between the reviewed outlook and the January crowd, by category. Negative means the field was more optimistic than the year turned out to warrant.

| Category | Open questions | Mean gap |
|----------|---------------:|---------:|
| Research | 2 | -32pp |
| AI Safety | 6 | -24pp |
| AI Capabilities | 8 | -11pp |
| Benchmarks | 7 | -8pp |
| AI Industry | 9 | -2pp |

**Research** is where the field was most over-optimistic, by 32 percentage points on average. That is also where most of the projected leaderboard movement comes from.

---

## Layer 8: What This Doesn't Tell You Yet

A few things worth saying plainly, because a leaderboard invites more confidence than this one has earned.

**The sample is 7 questions.** Not 40. One badly missed call on question 8 would take MAGA Council from 0.114 to 0.224 — first place to roughly 9th, on a single question. Rankings this tight are noise until the denominator grows.

**There are no NO resolutions.** Calibration — the thing Brier is actually for — needs outcomes in both directions. Until a prediction resolves NO, this table cannot distinguish a well-calibrated forecaster from an optimistic one, and it should not be read as if it can.

**5 predictions sit in a category the board doesn't show.** #005, #009, #017, #020, #025 were adjudicated *ambiguous* rather than too-early — the reviewers found the locked wording could not cleanly decide the case, and in one instance withdrew a YES that had already been recorded. On the site they look identical to the questions simply waiting for December. They are not the same thing, and the difference is a judgement about the question rather than about the world.

**Resolution timing is not neutral.** Questions that resolve early are questions whose answers arrived early, which skews toward things happening rather than failing to happen. The 32 open predictions include most of the year-end deadlines — the ones that can only resolve NO by running out of time.

---

## Methodology

- **Data**: 40 binary predictions, 21 forecasters (10 human, 6 AI model, 5 AI persona)
- **Forecasts**: Collected January-February 2026 using identical briefing documents, locked before resolution
- **Scored on**: 7 resolved predictions (7 YES, 0 NO); 1 voided and 32 open predictions are excluded from all scores
- **Scoring rule**: Brier score, mean of (forecast - outcome)² across resolved predictions; 0.25 is the all-50% baseline
- **Group medians**: median of member forecasts, not mean, to limit the pull of single extreme calls
- **Projection**: expected Brier — (forecast − p)² + p(1 − p) per prediction, where p is the outcome for resolved questions and the reviewed year-end outlook for open ones
- **Outlook source**: reviews/2026-midyear/year-end-outlook.yaml, methodology midyear-outlook-v1, evidence cutoff 2026-08-15
- **Visualizations**: matplotlib + seaborn, palette shared with the pre-resolution analysis
