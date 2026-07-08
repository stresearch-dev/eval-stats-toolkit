# Eval Stats Toolkit

Wilson score confidence intervals, difference of proportions (Newcombe), and McNemar's paired test for LLM evaluation results.

**Live:** https://stresearch-dev.github.io/eval-stats-toolkit/

Enter accuracy counts per condition and get Wilson 95% CIs, Newcombe score intervals for comparing two models on independent samples, and McNemar's paired test (exact binomial fallback when b+c < 25). Includes paper-ready output sentences and LaTeX snippets.

Single HTML file. No dependencies. Runs entirely in the browser. MIT licensed.

Reference check: 19/20 → Wilson 95% CI [0.764, 0.991] · b=22, c=2 → χ²=16.67, p < .0001

---

Part of the LLM Evaluation Toolkit by [Shubham Tibrewal](https://github.com/stresearch-dev).
