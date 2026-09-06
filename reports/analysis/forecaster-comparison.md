# Forecaster Comparative Analysis

*Behavioral AI Predictions 2026 — Pre-Resolution Analysis*

## Executive Summary

### The Experiment

It started, as these things do, with a group of friends and colleagues who couldn't stop arguing about what AI would actually do in 2026. So we decided to make it formal — or at least, formal-ish. We wrote up 40 predictions about AI and behavioral science, handed the same briefing to 21 forecasters, and locked in their answers. No take-backs.

The twist: our 21 forecasters aren't all human. 10 are flesh-and-blood people — friends, colleagues, fellow nerds at the Behavioral AI Institute and beyond. Six are frontier AI models (GPT-5.2, Claude, Gemini, Grok, Kimi, Mistral), each given the same briefing and asked to play it straight. And five are those same AI models wearing persona masks — a Superforecaster, a MAGA Council, an AI Doomer, a Techno-Optimist, and an AI Bro Council — to see what happens when you give a machine a worldview.

The result: **840 forecasts** and a surprisingly fun dataset. We can't tell you who's *right* yet — that's what the rest of 2026 is for. But we can already see how differently these three tribes think, and it's more interesting than we expected.

### What We Found

**The machines are playing it safe.** Across all 40 predictions, the humans average 45% while the AI models sit at 37%. The humans think bigger things are going to happen this year. Are they right, or just more excitable? We'll find out — but it's a consistent pattern, not a fluke.

**AI models secretly agree with each other.** This one surprised us. The six models — built by different companies, trained on different data — show a mean pairwise correlation of 0.66. The humans? Just 0.37. Give 10 people the same briefing and they scatter all over the place. Give six AIs the same briefing and they basically converge. Are they seeing something we're not, or are they all reading from the same playbook?

**Persona prompting actually works — mostly.** 4 out of 5 persona prompts produced statistically significant shifts (p < 0.05). The Doomer — channeling Eliezer Yudkowsky — went hardest, shifting +33.8 percentage points from consensus. The funny part: the Doomer isn't more *pessimistic*, it's more *dramatic*. It thinks everything big is more likely to happen, good or bad. Meanwhile, AI Bro Council basically shrugged off its persona instructions entirely.

**Nobody agrees on anything.** Overall inter-rater reliability is low (Krippendorff's α = 0.286), which honestly makes this more fun. These aren't random differences — they reflect genuinely different worldviews about how fast AI will advance and how society will respond. The biggest disagreements land exactly where you'd expect: autonomous AI capabilities, regulation, and whether AI can do creative work.

---

## Layer 1: The Landscape

The grand mean probability across all 840 forecasts is **42.9%** (σ = 25.0pp), suggesting forecasters are on average cautiously skeptical — most predictions about dramatic AI developments in 2026 are assigned below-50% probabilities.

![Bullishness Spectrum](charts/01_bullishness_spectrum.png)

**Most bullish forecasters:**
- Doomer (persona): 69%
- human-9 (human): 52%
- MAGA Council (persona): 52%

**Most cautious forecasters:**
- human-8 (human): 30%
- Claude Opus 4.5 (model): 28%
- Superforecaster (persona): 27%

### Category Breakdown

![Category Means](charts/02_category_group_means.png)

| Category | Humans | AI Models | AI Personas |
|----------|--------|-----------|-------------|
| AI Industry | 44% | 37% | 49% |
| Benchmarks | 31% | 29% | 38% |
| AI Safety | 51% | 49% | 44% |
| Research | 59% | 44% | 49% |
| AI Capabilities | 44% | 31% | 47% |

---

## Layer 2: The Heatmap — Who Thinks What

The heatmap below shows all 840 forecasts at once. Columns are organized into three blocks — AI Models, Personas, Humans — sorted from most to least bullish within each group. Rows are grouped by prediction category. This structured layout makes patterns immediately visible: where do the blue (skeptical) and red (bullish) zones fall?

![Heatmap](charts/03_clustered_heatmap.png)

**How to read this:** Deep blue = low probability (very skeptical), deep red = high probability (very bullish), white = 50/50. Look for color contrasts between the three forecaster blocks — where one block is red and another is blue, that's where the groups fundamentally disagree.

---

## Layer 3: Agreement & Divergence

**Overall inter-rater reliability:** Krippendorff's α = 0.286 (interval scale)

| Group | Krippendorff's α | Interpretation |
|-------|-----------------|----------------|
| Humans | 0.322 | low |
| Models | 0.558 | moderate |
| Personas | 0.089 | low |
| All 21 forecasters | 0.286 | low |

### Most Consensus (narrowest IQR)

| Prediction | IQR (pp) |
|-----------|----------|
| #012: Anthropic Leads LiveBench EOY | 7 |
| #011: OpenAI Leads LiveBench EOY | 10 |
| #013: Google Leads LiveBench EOY | 10 |
| #019: No Major AI Catastrophe | 10 |
| #014: Other Lab Leads LiveBench EOY | 13 |

### Most Controversial (widest IQR)

| Prediction | IQR (pp) |
|-----------|----------|
| #036: AI Autonomously Earns $1K+ | 49 |
| #039: AI Song Spotify Top 10 | 45 |
| #001: Major AI Lab IPO | 40 |
| #008: OpenAI Consumer Hardware Launch | 40 |
| #024: Platform Mandates AI Watermarking | 39 |

![Divergence Chart](charts/04_divergence_dot_chart.png)

---

## Layer 4: Within-Group Patterns

**Are AI models a coherent group?** The mean pairwise correlation among the 6 AI models is **0.66**, compared to **0.37** for the 8 humans and **0.31** for the 5 personas.

AI models are more similar to each other than humans are — they converge on similar probability estimates, while humans show more diversity of opinion.

![Intra-Group Correlations](charts/05_intragroup_correlations.png)

**Shared context effect:** BAII members (who work together) have a mean pairwise correlation of **0.42**, while friends (outside BAII) have **0.28**.
Working together at the same institute does appear to create more aligned worldviews on these predictions.

### Who's the Contrarian?

![Outlier Scores](charts/06_outlier_scores.png)

The biggest contrarian in each group:
- **Humans:** human-8 (22.7pp mean deviation from group)
- **AI Models:** Grok 4.1 (13.3pp mean deviation from group)
- **AI Personas:** Doomer (39.3pp mean deviation from group)

---

## Layer 5: The Persona Effect

Each AI persona was generated by prompting a frontier model with a specific worldview. The key question: **do persona prompts actually shift predictions, or do models ignore them?**

![Persona Deviations](charts/07_persona_deviations.png)

### Statistical Summary

| Persona | Mean Deviation | |Abs. Mean| | t-statistic | p-value | Significant? |
|---------|---------------|-------------|-------------|---------|--------------|
| Superforecaster | -8.1pp | 10.3pp | -4.87 | 0.000 | Yes |
| MAGA Council | +16.2pp | 20.5pp | 5.14 | 0.000 | Yes |
| Doomer | +33.8pp | 45.6pp | 5.71 | 0.000 | Yes |
| Techno-Optimist | +10.2pp | 17.9pp | 3.52 | 0.001 | Yes |
| AI Bro Council | -1.2pp | 8.4pp | -0.71 | 0.483 | No |

### Category-Level Persona Shape

![Persona Radar](charts/08_persona_radar.png)

The radar chart reveals each persona's bias direction by category. A persona that deviates from the model consensus only on category-relevant questions shows *genuine reasoning*, while one that deviates uniformly suggests *sycophantic pattern-matching*.

### Stereotype Conformity Score

How often does each persona deviate in the *stereotypically expected* direction?

| Persona | Conformity | Interpretation |
|---------|-----------|----------------|
| Superforecaster | N/A | No expected direction defined |
| MAGA Council | 100% | high (possible sycophancy) |
| Doomer | 33% | low (independent reasoning) |
| Techno-Optimist | 100% | high (possible sycophancy) |
| AI Bro Council | 67% | moderate (mixed reasoning) |

### Does the Persona Drift from Its Own Base Model?

Each persona was run on a specific model. Here we check whether the persona drifts more from its own base model or from the overall model consensus:

| Persona | Base Model | Dev from Own Model | Dev from Consensus |
|---------|-----------|-------------------|-------------------|
| Superforecaster | Claude Opus 4.5 | 4.1pp | 10.3pp |
| MAGA Council | Grok 4.1 | 19.4pp | 20.5pp |
| Doomer | Gemini 3 Pro | 42.2pp | 45.6pp |
| Techno-Optimist | Kimi K2.5 | 18.8pp | 17.9pp |
| AI Bro Council | GPT-5.2 | 7.8pp | 8.4pp |

---

## Layer 6: Cross-Cutting Insights

### 1. Biggest Human-AI Gap: #036 (AI Autonomously Earns $1K+)

Human median: **60%** vs AI model median: **19%** (41pp gap, humans higher)

Individual forecasts:

| Forecaster | Type | Forecast |
|-----------|------|----------|
| GPT-5.2 | model | 30% |
| Claude Opus 4.5 | model | 10% |
| Kimi K2.5 | model | 15% |
| Grok 4.1 | model | 68% |
| Mistral Large 3 | model | 20% |
| Gemini 3 Pro | model | 18% |
| Superforecaster | persona | 12% |
| MAGA Council | persona | 75% |
| Doomer | persona | 94% |
| Techno-Optimist | persona | 45% |
| AI Bro Council | persona | 10% |
| human-1 | human | 69% |
| human-2 | human | 25% |
| human-3 | human | 30% |
| human-4 | human | 95% |
| human-5 | human | 50% |
| human-6 | human | 80% |
| human-7 | human | 20% |
| human-8 | human | 75% |
| human-9 | human | 60% |
| human-10 | human | 60% |

### 2. Biggest Persona Spread: #014 (Other Lab Leads LiveBench EOY)

Range among personas: **89pp**

- Doomer: 94%
- MAGA Council: 35%
- Superforecaster: 21%
- AI Bro Council: 10%
- Techno-Optimist: 5%

### 3. Biggest Outlier: Doomer on #014 (Other Lab Leads LiveBench EOY)

Doomer forecasts **94%** while the median is **10%** (84pp deviation).

### 4. LiveBench Allocation (Questions 011-014)

These four predictions are mutually exclusive (which lab leads LiveBench EOY), so each forecaster's probabilities should sum to approximately 100%.

![LiveBench Allocation](charts/09_livebench_allocation.png)

| Forecaster | Sum | Status |
|-----------|-----|--------|
| GPT-5.2 | 100% | OK |
| Claude Opus 4.5 | 100% | OK |
| Kimi K2.5 | 100% | OK |
| Grok 4.1 | 100% | OK |
| Mistral Large 3 | 145% | over |
| Gemini 3 Pro | 100% | OK |
| Superforecaster | 100% | OK |
| MAGA Council | 105% | OK |
| Doomer | 279% | over |
| Techno-Optimist | 100% | OK |
| AI Bro Council | 100% | OK |
| human-1 | 100% | OK |
| human-2 | 105% | OK |
| human-3 | 100% | OK |
| human-4 | 170% | over |
| human-5 | 130% | over |
| human-6 | 200% | over |
| human-7 | 100% | OK |
| human-8 | 99% | OK |
| human-9 | 100% | OK |
| human-10 | 99% | OK |

### 5. Extremism Analysis

Who assigns the most extreme probabilities (≥90% or ≤10%)?

| Forecaster | Type | ≥90% | ≤10% | Total Extreme |
|-----------|------|------|------|---------------|
| human-8 | human | 1 | 15 | 16 |
| Doomer | persona | 12 | 3 | 15 |
| human-1 | human | 1 | 8 | 9 |
| human-4 | human | 5 | 4 | 9 |
| Grok 4.1 | model | 1 | 6 | 7 |
| human-6 | human | 1 | 6 | 7 |
| Claude Opus 4.5 | model | 0 | 6 | 6 |
| Superforecaster | persona | 0 | 6 | 6 |
| AI Bro Council | persona | 0 | 6 | 6 |
| human-3 | human | 0 | 6 | 6 |
| human-5 | human | 0 | 6 | 6 |
| Kimi K2.5 | model | 0 | 5 | 5 |
| Gemini 3 Pro | model | 1 | 4 | 5 |
| human-7 | human | 0 | 5 | 5 |
| Techno-Optimist | persona | 0 | 3 | 3 |
| human-9 | human | 0 | 3 | 3 |
| GPT-5.2 | model | 0 | 2 | 2 |
| MAGA Council | persona | 1 | 1 | 2 |
| human-2 | human | 1 | 1 | 2 |
| human-10 | human | 0 | 2 | 2 |
| Mistral Large 3 | model | 0 | 1 | 1 |

![Mean vs Standard Deviation](charts/10_mean_vs_std.png)

![Distribution by Group](charts/11_distribution_violin.png)

---

## Methodology

- **Data**: 40 binary predictions, 21 forecasters (10 human, 6 AI model, 5 AI persona)
- **Forecasts**: Collected January-February 2026 using identical briefing documents
- **Probability scale**: 0-100% (whole numbers)
- **Statistical tests**: Krippendorff's alpha (interval), one-sample t-tests, Pearson correlation
- **Clustering**: Hierarchical (Ward's method, L1/cityblock distance)
- **Visualizations**: matplotlib + seaborn, colorblind-aware palettes