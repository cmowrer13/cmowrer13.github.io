---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

## R Packages

### [qgcomp.multi: Estimating causal effects of multiple exposure mixtures and their interaction using marginal structural models](cmowrer13.github.io/qgcomp.multi)

In many environmental and epidemiologic studies, exposures come in distinct groups, such as metals, phthalates, or phenols, and investigators may want to estimate the effect of shifting one mixture while allowing the effect of that shift to depend on the level of another mixture. The package currently supports estimation with exactly two mixtures, optional interaction between the two mixture intervention variables, quantized analyses with q >= 2, original-scale analyses with q = NULL, MSM-based prediction, plotting, diagnostics, and sensitivity helpers. The package works by fitting an outcome regression model, computing predicted counterfactual means under joint interventions on the two mixtures, and then fitting a marginal structural model (MSM) to summarize that intervention-response surface.
