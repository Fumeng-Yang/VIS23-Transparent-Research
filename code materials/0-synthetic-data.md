Generating synthetic data
================
September 30, 2023

The purpose of this document is to generate some synthetic data to (1)
think about the data generation process (2) figure out visualization and
modeling plans. This is a good practice in conducing an experiment.

Our research question is people’s badge/button preference over two
designs: `cat` and `logo`. They are measured by three statements, each
on a 5-point Likert scale. The assumption behind a Likert scale is that
the responses are generated from an underlying normal distribution. So,
we can either average these ordinal responses first and then analyze the
average, or we can model them using an ordinal regression first and then
average the posteriors.
