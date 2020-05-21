[Description]
This python package is a supplementary material to Ezaki et.al. arXiv:2001.08369.

This package contains three modules:
(1) "synthetic_time_series.py"
(2) "estimate models.py"
(3) "state_time_series_statistics.py"
and sample data ("sample_cov_1.txt", "sample_cov_2.txt", "sample_mean_1_2.txt", "trans.txt") used for defining probability distribusions of the hidden state in "synthetic_time_series.py".


(1) "synthetic_time_series.py" contains functions to generate three types of synthetic time series described in Ezaki et.al. arXiv:2001.08369.

(2) "estimate_models.py" contains functions to estimate GMM and HMM for given time series data.

(3) "state_time_series_statistics.py" contains functions to compute statistics (i.e., frequency, switching rate, and dwell time of hidden states) from a time series of the state.

For usage of each function, see the sample codes in each module.


[Requiements]
This package assumes python 3.6 or later.
This package requires the following packages:
-NumPy (https://numpy.org/)
-scikit-learn (https://scikit-learn.org/stable/)
-hmmlearn (https://hmmlearn.readthedocs.io/en/latest/)


License:
Copyright (c) 2020 Takahiro Ezaki
Released under the MIT license