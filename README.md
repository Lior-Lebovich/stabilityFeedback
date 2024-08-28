# stabilityFeedback


Overview
-------------------
This repository is associated with the paper "Idiosyncratic choice bias and feedback-induced bias differ in their long-term dynamics".

A well-known observation in repeated-choice experiments is that a tendency to prefer one response over the others emerges if the feedback consistently favors that response. However, choice bias, a tendency to prefer one response over the others, is not restricted to biased-feedback settings and is also observed when the feedback is unbiased. In fact, participant-specific choice bias, known as idiosyncratic choice bias (ICB), is common even in symmetrical experimental settings in which feedback is completely absent. Here we ask whether feedback-induced bias and ICB share a common mechanism. Specifically, we ask whether ICBs reflect idiosyncrasies in choice-feedback associations prior to the measurement of the ICB. To address this question, we compare the long-term dynamics of ICBs with feedback-induced biases. We show that while feedback effectively induced choice preferences, its effect is transient and diminished within several weeks. By contrast, we show that ICBs remained stable for at least 22 months. These results indicate that different mechanisms underlie the idiosyncratic and feedback-induced biases.

Data
-------------------
All data required to reproduce our results are available in the repository. 
Response data and inter-session-delays are stored in sorted tables ("sortedTable_") and assign tables ("assignTable_"), respectively, by experiments ([stability](https://github.com/Lior-Lebovich/stabilityFeedback/tree/e3c5340f25b259a9574fc7229f6b009472bf87f4/stability) folder and [feedback](https://github.com/Lior-Lebovich/stabilityFeedback/tree/d089520449686660b1f650722fa46e4e38a70fc6/feedback) folder) and delay groups: 
stabilityFeedback/[EXPERIMENT_NAME]/[TABLES_TYPE]_[EXPERIMENT_NAME]_[DELAY_NAME].csv

Analysis
-------------------
The code required to reproduce all data is available in the stabilityFeedbackICB.mlx MATLAB (R2023b) Live Editor file (also available as stabilityFeedbackICB.pdf).

All figures are saved in MATLAB FIG and PDF formats. File names for the vertical task are as in the paper. For the horizontal task, we add " - appendix.". 

For Binomial tests, we use the myBinomTest custom function, reference: Matthew Nelson (2015). https://www.mathworks.com/matlabcentral/fileexchange/24813-mybinomtest-s-n-p-sided MATLAB Central File Exchange. Retrieved February 9, 2016.

Cite
-------------------
If you use code from this repository, please cite it using the Zenodo DOI:
ADD_DOI

Contributors
-------------------
This code was authored by Lior Lebovich, 2024.
