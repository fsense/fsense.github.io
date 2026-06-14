---
layout: base.njk
title: What I do
permalink: /what-i-do/
---

# What I do

My research sits at the intersection of computational cognitive science and applied machine learning, with language learning as the primary domain of application. In practice this means I spend time on a handful of recurring problem types—some methodologically deep, some engineering-heavy, most both.

<h2 id="nlp-assessment">Applied NLP for language assessment</h2>

Classifying text by proficiency level (ILR, CEFR, ACTFL), modeling readability and complexity, and building automated assessment tools. I work primarily with Arabic and English, with approaches ranging from linguistic-feature engineering (morphological complexity, lexical diversity, frequency-based metrics) to fine-tuned transformer models to hybrid systems that combine LLM judgment with explicit feature extraction. Training data in this space is almost always limited, so a significant part of the work is figuring out how to do useful modeling with small, non-uniformly distributed samples.

<h2 id="llm-infrastructure">LLM infrastructure and content generation</h2>

Designing and building production pipelines that use LLMs for content generation, scoring, and evaluation. This includes structured-output systems (Pydantic schemas, tool-use patterns, prompt-based fallbacks for models without native function calling), evaluation frameworks for validating outputs against domain-specific criteria, and deployment into constrained environments (restricted-network government compute, containerized workflows, cross-account cloud setups). I think carefully about when to route to an LLM at all versus when a deterministic approach is more defensible.

<h2 id="learning-models">Computational models of learning and memory</h2>

Quantitative models of how people acquire, retain, and retrieve knowledge over time—and how to use those models to make good decisions about instruction. Working knowledge of Bayesian Knowledge Tracing, the Predictive Performance Equation and related memory models, spacing effects, and adaptive scheduling approaches. More broadly, I think about how these pieces fit into intelligent tutoring systems that decide what a learner should work on next. I'm interested in the planning side of this as much as the inference side: once you have a good model of what a learner knows, what do you do about it?

<h2 id="curriculum-design">Curriculum and assessment design at scale</h2>

Decomposing high-level learning outcomes into measurable, progressive indicators; mapping those indicators onto proficiency frameworks like ILR, CEFR, and ACTFL; and designing assessment systems that produce defensible evidence of learning. This is taxonomic and empirical work: a good indicator system has to be theoretically principled, operationally specific enough to measure, and aligned with how practitioners actually teach and test.

<h2 id="consulting">Research consulting and analysis</h2>

Occasional work outside the above categories: experimental design review, statistical analysis (R/tidyverse, mixed models, Monte Carlo approaches), methodology consultation for learning-science research, and similar. Most recently this has included co-supervision of PhD work on adaptive learning and forgetting-curve modeling.

---

## Selected work

A few representative examples, described at the level of problem type rather than specific clients:

**LLM-based content generation for proficiency-targeted reading materials.** For a government language training institute, designing and implementing a pipeline that generates reading passages at specified proficiency levels, with associated comprehension questions targeting specific cognitive operations. The system combines prompt-engineered content generation, automated complexity verification against external readability models, and structured-output evaluation against domain taxonomies.

**Automated text complexity classification for Arabic.** Building classifiers that estimate the ILR reading level of Arabic passages, trained on limited labeled data (fewer than 300 passages, skewed distribution). Approaches include feature-engineered baselines using CAMeL Tools and SAMER lexicon resources, fine-tuned BAREC-pretrained transformer models, and LLM-based classification pipelines with structured output for interpretability.

**Adaptive learning scheduling and knowledge tracing.** Academic and applied work on models that track what a learner knows over time and decide what they should practice next. Includes extensions to the Predictive Performance Equation and amortized Bayesian inference for parameter estimation.

**Curriculum taxonomy development for proficiency-based language training.** Developing atomic can-do indicators across four modalities and six proficiency levels, including a principled mapping between ILR level, text mode, and valid comprehension-question types that constrains both assessment design and content generation.

---

## Side projects

**Picolingo.** A European Portuguese language learning app I built as a personal project and run in production at [picolingo.app](https://www.picolingo.app/). It implements a CEFR-aligned curriculum, knowledge tracing for adaptive practice scheduling, and multiple practice modes—the same kind of system I work on professionally, built end-to-end by one person rather than a team. Free, not commercialized.

**PaZuFa.** An early-stage open-source civic-tech project that tracks parliamentary processes for government transparency. I lead the website team and contribute to the shared codebase. Source at [codeberg.org/PaZuFa](https://codeberg.org/PaZuFa).

---

If you're working on a problem in one of these areas and think I might be useful, [get in touch](mailto:floriansense@gmail.com).
