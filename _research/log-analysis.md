---
title: "Log Analysis is Necessary for Credible Evaluation of AI Agents"
collection: research
permalink: /research/log-analysis
excerpt: "We argue that log analysis — the systematic tracking and analysis of the inputs, execution, and outputs of an AI agent — is necessary to overcome validity threats in agent evaluation, presenting a taxonomy of threats and a set of guiding principles."
date: 2026-05-08
paperurl: 'https://arxiv.org/pdf/2605.08545'
citation: 'Kirgis, P., Kapoor, S., Rabanser, S., Nadgir, N., Ududec, C., Dubois, M., ... & Narayanan, A. (2026). Log Analysis is Necessary for Credible Evaluation of AI Agents. Accepted at ICML 2026 FAGEN Workshop.'
---

Agent benchmarks typically report only final outcomes: pass or fail. This threatens evaluation credibility in three ways. First, scores may be inflated or deflated by shortcuts and benchmark artifacts, misrepresenting capability. Second, benchmark performance may fail to predict real-world utility due to scaffold limitations and recurring failure modes. Finally, capability scores may conceal dangerous or catastrophic actions taken by the agent. We argue that log analysis — the systematic tracking and analysis of the inputs, execution, and outputs of an AI agent — is necessary to overcome these validity threats and promote credible agent evaluation. In this paper, we (1) present a taxonomy of threats to credible evaluation documented through log analysis, and (2) develop a set of guiding principles for log analysis. We illustrate these principles on tau-Bench Airline, revealing that pass^5 performance was under-elicited by nearly 50% and surfacing deployment failure modes invisible to outcome metrics. We conclude with pragmatic recommendations to increase uptake of log analysis, directed at diverse stakeholders including benchmark creators, model developers, independent evaluators, and deployers.
