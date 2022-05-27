# An Empirical Study on Performance Bugs in Deep Learning Frameworks

## Legend

perf_bugs_taxonomy.csv: our taxonomy of the root causes of the performance bugs.

pytorch_fixed_perf_trend_analysis.csv: number of fixed performance bugs among all fixed bugs in PyTorch (from December 2016 to April 2021).

pytorch_fixed_perf_trend_analysis.csv: number of open performance bugs among all open bugs in PyTorch (from December 2016 to April 2021).

pytorch_perf_bugs_information.csv: information on all performance bugs collected in PyTorch.

pytorch_perf_fixes_information.csv: information on all performance bugs' fixes collected in PyTorch.

pytorch_non_perf_bugs_information.csv: information on all non-performance bugs collected in PyTorch.

pytorch_non_perf_fixes_information.csv: information on all non-performance bugs' fixes collected in PyTorch.

pytorch_fixed_perf_trend_analysis.csv: number of fixed performance bugs among all fixed bugs in TensorFlow (from February 2016 to February 2021).

pytorch_fixed_perf_trend_analysis.csv: number of open performance bugs among all open bugs in TensorFlow (from February 2016 to February 2021).

tensorflow_perf_bugs_information.csv: information on all performance bugs collected in TensorFlow.

tensorflow_perf_fixes_information.csv: information on all performance bugs' fixes collected in TensorFlow.

tensorflow_non_perf_bugs_information.csv: information on all non-performance bugs collected in TensorFlow.

tensorflow_non_perf_fixes_information.csv: information on all non-performance bugs' fixes collected in TensorFlow.


## Keywords used in data collection for performance bug reports

In addition to the bug reports that are labelled as being performance-related by the developers themselves, we use a keyword search to further identify performance bug reports. More precisely, we use the following 29 keywords:

- performance regression
- regression in performance
- degradation
- laggy
- decline in performance
- lower performance
- worse performance
- worsening performance
- bad performance
- deterioration
- performance bug
- poor performance
- latency
- slowdown
- slower
- slow
- throughput
- hit in performance
- performance hit
- drop in performance
- performance drop
- worsen performance
- worsened performance
- memory leak
- memory issue
- memory usage
- gpu usage
- cpu usage
- response time


## P-values of Cox-Stuart test for increasing trends

For TensorFlow:
- P-value of Cox-Stuart test for increasing trend of the percentage of open performance bugs = 9.313e-10
- P-value of Cox-Stuart test for increasing trend of the percentage of fixed performance bugs = 9.313e-10

For PyTorch:
- P-value of Cox-Stuart test for increasing trend of the percentage of open performance bugs = 0.004678<br />
- P-value of Cox-Stuart test for increasing trend of the percentage of fixed performance bugs =  4.399e-05
