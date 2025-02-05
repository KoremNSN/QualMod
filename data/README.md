# Qualitative Decision-Making Under Uncertainty Dataset

## Overview
This repository contains data from the study *"Modeling Decision-Making Under Uncertainty with Qualitative Outcomes."* The dataset includes decision-making responses from **66 participants** who completed both monetary and medical choice tasks. The data has been **pre-cleaned** and contains only the participants used in the final analysis.

## Files
- **`monetary_data.csv`** – Decision-making data for monetary choices.
- **`medical_data.csv`** – Decision-making data for medical choices.

## Columns

|   | Description |
|-------------|------------|
| **choice** | Binary (1/0) – Did the participant choose the lottery? |
| **value** | Outcome level (5/8/12/25). In the medical dataset, participants saw qualitative outcomes instead of these numerical values. |
| **risk** | Lottery probability: 25%, 50%, or 75%. |
| **ambiguity** | Ambiguity level: 0%, 24%, 50%, or 74% (percent of uncertainty). |
| **sub** | Participant ID (integer). |
| **rt** | Reaction time (float). |
| **catch** | Binary (1/0) – Was it a catch trial? (e.g., choosing between a sure small gain vs. an equivalent lottery). |
| **gender** | M/F – Participant's self-reported gender. |
| **age** | Participant age (integer). |
| **moca_score** | MoCA cognitive test score; participants below the dementia threshold were removed. |
| **ageZ** | Z-transformed age variable. |
| **subn** | Dense function mapping for subject numbers. |
| **level** | Ordinal outcome level (1-4). |
| **l1, l2, l3, l4** | Binary indicators for cumulative levels (e.g., Level 3 → `1 1 1 0`). |

## Usage
This dataset is useful for studying:
- Decision-making under uncertainty.
- Risk and ambiguity attitudes.
- Cross-domain comparisons between monetary and medical decision-making.

## Citing this Dataset
If you use this dataset, please cite:

**Korem, N.,** Duek, O., Jia, R., Wertheimer, E., Metviner, S., Grubb, M., & Levy, I. (2024). Modeling Decision-Making Under Uncertainty with Qualitative Outcomes. (Accpted), PLOS Computational Biology
