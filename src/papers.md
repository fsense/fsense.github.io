---
layout: base.njk
title: Selected papers
permalink: /papers/
---

# Selected papers

Eight papers I'd point to first, grouped by theme. Shared first authorships are marked with a caret (^).

## Rate of forgetting as an individual-differences construct

**Sense, F., Behrens, F., Meijer, R. R., & van Rijn, H. (2016).** An individual's rate of forgetting is stable over time but differs across materials. *Topics in Cognitive Science*, 8, 305–321. [DOI](https://onlinelibrary.wiley.com/doi/full/10.1111/tops.12183) · [OSF](https://osf.io/yt9qs/) · [PDF](/files/Sense_Behrens_Meijer_VanRijn_2016.pdf)

A learner's rate of forgetting is stable across weeks, but the same person forgets vocabulary, country flags, and maps at measurably different rates. Adaptive systems should therefore carry per-item rate-of-forgetting estimates across sessions rather than collapsing them into a single trait.

**Sense, F., Meijer, R. R., & van Rijn, H. (2018).** Exploration of the rate of forgetting as a domain-specific individual differences measure. *Frontiers in Education*, 3:112. [DOI](https://www.frontiersin.org/articles/10.3389/feduc.2018.00112/full) · [OSF](https://osf.io/yz7bn/) · [PDF](/files/Sense_Meijer_vanRijn_2018.pdf)

Rate of forgetting is essentially uncorrelated with working-memory capacity and general cognitive ability, suggesting it captures a kind of individual variation that standard IQ-style measures don't pick up on.

**Zhou, P., Sense, F., van Rijn, H., & Stocco, A. (2021).** Reflections of idiographic long-term memory characteristics in resting-state neuroimaging data. *Cognition*, 212. [DOI](https://doi.org/10.1016/j.cognition.2021.104660) · [bioRxiv](https://biorxiv.org/cgi/content/short/2020.04.18.047662v1) · [GitHub](https://github.com/UWCCDL/EEG_RateOfForgetting)

A learner's rate of forgetting—estimated from a short fact-learning session—can be predicted from their resting-state brain connectivity, indicating the parameter reflects a stable neural trait rather than task noise.

## Adaptive learning, from lab to deployment

**van der Velde, M., Sense, F., Borst, J. P., & van Rijn, H. (2021).** Alleviating the cold start problem in adaptive learning using data-driven difficulty estimates. *Computational Brain & Behavior*. [DOI](https://doi.org/10.1007/s42113-021-00101-6) · [PsyArXiv](https://doi.org/10.31234/osf.io/hf2vw) · [OSF](https://osf.io/snfyz/)

Addresses a practical deployment problem: adaptive systems behave poorly in their first few minutes with a new learner because they have no prior data. The paper shows that item-difficulty estimates aggregated from prior learners are enough to warm-start new users meaningfully.

**Sense^, F., van der Velde^, M., & van Rijn, H. (2021).** Predicting university students' exam performance using a model-based adaptive fact-learning system. *Journal of Learning Analytics*, 1–15. [DOI](https://doi.org/10.18608/jla.2021.6590) · [OSF](https://osf.io/e28nw/)

In-session rate-of-forgetting estimates from an adaptive fact-learning system predict university students' exam grades weeks later—which reframes adaptive practice as a source of formative-assessment data, not only an instructional tool.

**Wilschut, T., Sense, F., & van Rijn, H. (2025).** Modality matters: Evidence for the benefits of speech-based adaptive retrieval practice in learners with dyslexia. *Topics in Cognitive Science*, 17(1), 57–72. [DOI](https://onlinelibrary.wiley.com/doi/pdf/10.1111/tops.12769)

Learners with dyslexia benefit disproportionately from speech-based adaptive retrieval practice compared to typing-based practice. Modality of response is a real lever for equity in adaptive learning technology, not a cosmetic choice.

## Cognitive modeling and machine learning for real-world skills

**Sense, F., Wood, R., Collins, M. G., Fiechter, J., Wood, A., Krusmark, M. A., Jastrzembski, T., & Myers, C. W. (2021).** Cognition-enhanced machine learning for better predictions with limited data. *Topics in Cognitive Science*. [DOI](http://doi.org/10.1111/tops.12574)

Uses a cognitive model of memory, the Predictive Performance Equation, to engineer timing-related input features for a gradient-boosted decision trees model. The cognitive model's narrow but specialized knowledge about the temporal dynamics of learning and forgetting jump-starts the ML model, yielding better predictions than the default model, especially when training data are limited.

**Maass^, S. C., Sense^, F., Gluck, K., & van Rijn, H. (2019).** Keeping bystanders active: Resuscitating resuscitation skills. *Frontiers in Public Health*, 7:177. [DOI](https://www.frontiersin.org/articles/10.3389/fpubh.2019.00177/full) · [OSF](https://osf.io/zpjrt/) · [PDF](/files/Maass_Sense_Gluck_VanRijn_2019.pdf)

Only 2% of adults trained years earlier could still perform CPR to guideline standard, but a six-minute video refresher with brief practice restored 81% to competency. Argues empirically for routine short refreshers over one-and-done certification for lifesaving skills.

---

For the full list, see [Google Scholar](https://scholar.google.com/citations?hl=en&user=e38VtRgAAAAJ).
