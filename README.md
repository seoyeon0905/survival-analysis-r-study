# Survival Analysis Study with R

This repository is a personal study log for learning the basics of
survival analysis using R, in preparation for clinical research.

---

## Background

As an undergraduate research assistant, I have been participating in
clinical research projects that involve survival analysis.
My role has mainly involved visiting a medical data analysis center
on a regular basis, running provided R scripts in a restricted environment,
and checking and organizing the resulting outputs.

While repeatedly executing the code, I gradually realized a limitation:
although I could run the scripts as instructed,
I found it difficult to clearly explain **what each part of the code was doing
and why those analyses were necessary**.
I knew that the code was related to survival analysis,
but I was often following procedures without fully understanding
the underlying statistical concepts or modeling assumptions.

---

## Motivation

Initially, I planned to study survival analysis through a small group study
using R, starting from the basics.
Although related textbooks were prepared,
the study group was eventually cancelled due to various circumstances.

Meanwhile, the research itself continued,
and I was informed that I would soon be involved in writing
a survival-analysis-based research paper.
At that point, I felt that I could no longer remain in a state of
*“running code without fully understanding it.”*

My advisor recommended reading example clinical papers
to understand the overall research structure and analytical flow,
and also advised becoming familiar with analysis tools
and reference management software in advance.
Through this process, it became clear that I needed to
revisit survival analysis **from the fundamentals**.

---

## Study Goal

Since this is a self-directed study,
the goal is **not** to master survival analysis at an advanced theoretical level.

Instead, the objectives of this repository are:

- To understand what the survival analysis code I have been running is actually doing
- To be able to follow and interpret survival analysis methods used in clinical papers
- To develop the ability to ask meaningful methodological questions during research
- To build a solid conceptual foundation rather than focusing on model performance

Even if the depth is limited, the emphasis is on
**completing the study independently and documenting the learning process**.

---

## Study Plan

The study follows the structure of an introductory textbook on
survival analysis with R.
The chapters listed below reflect the planned learning trajectory,
and corresponding practice scripts will be added gradually.

1. Introduction to survival analysis
2. Basic concepts and statistical quantities in survival analysis
3. Censoring and likelihood functions
4. Counting processes and martingales
5. Nonparametric estimation of survival functions
6. Tests for equality of survival functions
7. Cox proportional hazards model
8. Residuals and model diagnostics
9. Parametric regression models for survival analysis
10. Competing risks models

Not all topics may be covered in full depth,
but each chapter will be approached with the goal of
conceptual understanding and practical familiarity.

---

## Repository Structure

```
survival-analysis-r-study/
├─ README.md
├─ data/ # Public or simulated datasets only
├─ scripts/ # R scripts for each concept
├─ notebooks/ # R Markdown files for exploration and notes
└─ references/ # Papers and reading notes (links only)
```
Each script focuses on a single concept,
and all examples are based on **public or simulated data only**.

---

## Notes on Data and Ethics

This repository does **not** contain:
- Real patient data
- Code from ongoing research projects
- Variables, outputs, or structures derived from restricted datasets

All materials here are created solely for learning and practice purposes.

---

## Final Note

This repository is intended as a learning record rather than a polished tutorial.
Concepts may be incomplete or revised over time as understanding improves.

The main purpose is to document the process of moving from
*“running code”* to *“understanding analysis”*
in the context of clinical research.
