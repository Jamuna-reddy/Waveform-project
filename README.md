# Waveform-project

Input : the dataset waveform.data
https://archive.ics.uci.edu/ml/datasets/Waveform+Database+Generator+%28Version+2%29
• 5000 data
• 3 classes of waves
• 21 attributes all of which include noise
• Optimal Bayes classification rate = 86% accuracy

List of experiments to perform (non exhaustive)
• Tune the best k of a kNN classifier by cross-validation (plot the accuracies over the
validation subset w.r.t. k) from 4000 randomly drawn examples (you will keep apart 1000
waves for the test set).
• Analysis of the bias-variance trade-off. Start with a very small training set (e.g. 100 waves
and a large k) and study the gap to the Bayes error.
• Reduce the complexity with the CNN and RNN algorithms. Compare with the original
dataset.
• Generate artificially imbalancy in the data and analyze the impact on the accuracy. Tune k
w.r.t. the F-measure and compare the performance with the accuracy.

See: https://icml.cc/Conferences/2020/StyleAuthorInstructions
