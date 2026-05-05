Trust in AI Chatbots Among Individuals with Multiple Sclerosis — Analysis Pipeline
This repository contains the complete analysis pipeline accompanying the study: Impact of Cognitive Status on Trust in AI Chatbots Among Individuals with Multiple Sclerosis.

The study is an observational, cross-sectional questionnaire study (N = 89) examining the relationships between self-reported cognitive functioning, technology acceptance constructs (UTAUT), and trust in AI chatbots among adults with Multiple Sclerosis. The full analysis was conducted in Python and is reproducible from the notebook in this repository.

What's in the notebook
The notebook (MS_AI_Trust_Analysis.ipynb) runs the full analysis in sequence:

Data loading, recoding, and composite-score computation
Reliability analysis (Cronbach's α)
Descriptive statistics
Pearson correlations
Multiple linear regression predicting trust
Bootstrapped mediation analysis (Cognitive Load → Effort Expectancy → Trust; 5,000 resamples, percentile method)
Exploratory moderation analysis (Effort Expectancy × AI Use Frequency)

All seven manuscript figures are generated inline.
Requirements

Python 3.11+
pandas, numpy, scipy, statsmodels, pingouin, matplotlib, seaborn
