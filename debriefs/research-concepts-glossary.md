# Research Concepts Glossary — For Academic Meetings

Educational definitions, without references to a particular professor, institution or project.

## 1. Statistics / statistician — 统计学／统计学家

**Statistics** is the field of learning from data under uncertainty: designing studies, estimating quantities, testing hypotheses, predicting outcomes, and evaluating assumptions and errors.

A **statistician** may develop new methods, support study design, or perform and interpret analyses. The job title alone does not tell you whether their work is methodological, applied, or both.

**English check:** “When you say your work is in statistics, is it mainly methodological research, collaborative applied work, or a combination?”

## 2. Biostatistics / biostatistician — 生物统计学／生物统计学家

**Biostatistics** applies statistical ideas to biology, medicine, and public health and may also involve creating statistical methods for these settings.

A **biostatistician** might help design trials, calculate sample size, analyze health data, handle missing data, or evaluate new statistical methods.

**Key nuance:** Biostatistics is **broader than statistical simulation**. Simulation is one possible tool; not every biostatistician conducts simulation studies.

## 3. Statistical simulation / Monte Carlo simulation — 统计模拟／蒙特卡洛模拟

A simulation study uses a specified **data-generating mechanism** to produce many hypothetical datasets, analyze them, and evaluate how a method performs.

Common metrics:
- **Bias:** Difference between an estimator's average result and the true parameter.
- **Type I error:** Probability of rejecting a true null hypothesis.
- **Power:** Probability of rejecting the null under a specified alternative.
- **Confidence-interval coverage:** Proportion of intervals that contain the true parameter.
- **Precision / variability:** How widely estimates vary across simulations.

**Simple example:** If we generate 1,000 datasets in which the true treatment effect is zero and a method gives 50 false positives at a 5% significance threshold, its estimated Type I error in those simulated conditions is 50/1,000 = **5%**.

**Limit:** A simulation's conclusions depend on the chosen scenarios and assumptions.

**English check:** “Would the thesis involve designing simulation scenarios to compare statistical methods?”

## 4. Statistical methodology research — 统计方法学研究

Research about **how to estimate, model, test, or design** more effectively.

Typical research questions:
- Does a method remain unbiased under missing data?
- How do competing methods perform in small samples?
- Under what conditions does an estimator have adequate confidence-interval coverage?

It may involve theoretical work, coding, simulation, and empirical examples. It can be clinically motivated.

## 5. Applied statistical analysis — 应用统计分析

Uses statistical tools to answer **substantive questions** in an application domain, such as medicine or public health.

Typical work: define outcomes and exposures, inspect data quality, fit models, check assumptions, conduct sensitivity analyses, and interpret limitations.

Applying a familiar method skillfully still requires methodological judgment.

## 6. Clinical trial — 临床试验

A **clinical trial** is an interventional study in which participants are prospectively assigned to one or more health-related interventions to evaluate effects on health outcomes.

- A **randomized controlled trial (RCT)** assigns interventions using randomization.
- Some clinical trials are **non-randomized**.
- Clinical trial activities include study design, trial operations, intervention implementation, data management, statistical analysis and reporting.

Saying “I want to work in clinical trials” does **not** specify which part interests you.

**English check:** “I'm interested in analyzing trial data to answer clinical questions, especially secondary analyses of existing datasets.”

## 7. Clinical epidemiology — 临床流行病学

Applies epidemiologic reasoning and research methods to clinical populations and health questions, including diagnosis, prognosis, treatment effects, risk factors and patient outcomes.

Key issues can include study design, selection bias, confounding, measurement error, effect modification, and generalizability.

The field overlaps with biostatistics, trials, observational research and causal inference.

## 8. Observational study — 观察性研究

Researchers observe exposures and outcomes without assigning an intervention for the purposes of the study. Examples include cohort, case-control and cross-sectional designs.

**Important:** Observational data can support causal questions, but causal interpretation requires explicit assumptions, defensible design and careful evaluation of biases.

## 9. Secondary data analysis — 现有数据的二次分析

Analysis of data already collected, often to answer a new or more focused question.

Data can come from **clinical trials, cohorts, registries, electronic health records, or surveys**. Secondary analysis is a description of how data are used; it is **not itself a study design** and does not automatically imply causal identification.

## 10. Causal inference — 因果推断

Methods and reasoning aimed at estimating **what would happen to an outcome under different interventions or exposures**, under specified assumptions.

Important ideas: counterfactuals, confounding, selection bias, exchangeability, positivity, consistency, target-trial emulation, and sensitivity analysis.

Causal inference is not synonymous with “using an advanced regression model.”

## 11. Clinical medicine / clinical practice — 临床医学／临床执业

**Clinical medicine** may refer to medical knowledge and clinical training, but **clinical practice** specifically concerns delivering medical care to patients.

In an international meeting, explicitly distinguish a medically informed research background from an intention to become a practicing clinician.

**English check:** “I have medical and public-health training, but I want a research career rather than clinical practice.”

## 12. How to differentiate the roles in one sentence

- **Statistician:** “I work with statistical questions and data across domains.”
- **Biostatistician:** “I work on statistical questions in health and biomedical settings.”
- **Methodology researcher:** “I study how statistical methods work and when they fail.”
- **Applied clinical researcher:** “I use study design and data analysis to answer clinically meaningful questions.”

*The labels overlap, and actual responsibilities vary across teams.*

## 13. Five rapid self-checks

1. Can I explain **why simulation uses generated rather than only observed data**?
2. Can I name **two things** a biostatistician might do besides simulation?
3. Can I distinguish **trial design** from **secondary analysis of trial data**?
4. Can I explain why **clinical epidemiology** and **biostatistics** overlap?
5. Can I state whether I prefer **method development**, **applied analysis**, or **a combination**—and why?

Related case: [Case 001 — Conceptual gaps](001-conceptual-gaps-and-research-fit.md).
