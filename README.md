# log-stretched-basis

Small package for handling log-stretching of a basis / weighting function for neuroscience

The goal of this package is to handle log-stretched basis / weighting function /
pooling windows that have been useful in some applications in neuroscience:
applied to time-series for fitting generalized linear models (GLMs) to
electrophysiology data ([Pillow et al.,
2008](https://www.nature.com/articles/nature07140)) or weighting image
statistics in a fovated model of the primate visual system ([Freeman and
Simoncelli, 2011](https://www.nature.com/articles/nn.2889), [Broderick et al.,
2023](https://elifesciences.org/reviewed-preprints/90554v1)).

This package will handle the log-stretching of the domain, as well as several
functional forms that accept this log-stretched domain. We will explore the
parameter space, both for the log-stretching and the functions, and provide
guidance on which parameter sets are reasonable and what tradeoffs need to be
considered when picking parameters.
