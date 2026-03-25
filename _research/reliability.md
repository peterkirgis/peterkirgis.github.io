---
title: "Towards a Science of AI Agent Reliability"
collection: research
permalink: /research/reliability
excerpt: "We propose twelve metrics decomposing AI agent reliability along four dimensions — consistency, robustness, predictability, and safety — and evaluate 14 models, finding that recent capability gains have yielded only small improvements in reliability."
date: 2026-02-21
paperurl: 'https://arxiv.org/pdf/2602.16666'
websiteurl: 'https://hal.cs.princeton.edu/reliability/'
citation: 'Rabanser, S., Kapoor, S., Kirgis, P., Liu, K., Utpala, S., & Narayanan, A. (2026). Towards a Science of AI Agent Reliability. arXiv preprint arXiv:2602.16666.'
---

AI agents are increasingly deployed to execute important tasks. While rising accuracy scores on standard benchmarks suggest rapid progress, many agents still continue to fail in practice. This discrepancy highlights a fundamental limitation of current evaluations: compressing agent behavior into a single success metric obscures critical operational flaws. Notably, it ignores whether agents behave consistently across runs, withstand perturbations, fail predictably, or have bounded error severity. Grounded in safety-critical engineering, we provide a holistic performance profile by proposing twelve concrete metrics that decompose agent reliability along four key dimensions: consistency, robustness, predictability, and safety. Evaluating 14 models across two complementary benchmarks, we find that recent capability gains have only yielded small improvements in reliability. By exposing these persistent limitations, our metrics complement traditional evaluations while offering tools for reasoning about how agents perform, degrade, and fail.
