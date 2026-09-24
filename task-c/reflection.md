# Task C — Research Reflection

> **BAFAD Accelerated Research Track · Fall 2026**

## Question 1 — Connecting the Work to Research

The SMAP sample had 500 timesteps across 25 telemetry channels, but only 24 rows (4.8%) were labelled anomalous. I noticed that channel 00’s normal and anomaly values overlap a lot, so a single-channel threshold may miss unusual events. The heatmap is useful because it lets me compare several channels at once and look for coordinated changes. This connects to the BAFAD anomaly-detection problem because an autoencoder may need to learn normal multichannel patterns, not just identify extreme values in one channel. Rare anomalies also make careful evaluation important.

## Question 2 — Self-Assessment of Readiness

I am still building confidence with Python data analysis, especially pandas groupby operations, plotting, and interpreting statistical summaries. I also have limited hands-on machine-learning experience, so concepts like training an autoencoder, choosing evaluation metrics, and avoiding overfitting will be new to me. I plan to review Python and pandas through small practice notebooks, revisit statistics from class, and work through introductory machine-learning material. I would also ask questions during onboarding, document what I learn, and practice by changing one part of a notebook at a time so I can understand the results instead of just copying code.
