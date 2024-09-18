## Hi there 👋

We develop tools for applied (micro-) econometrics in Python.

- [pyfixest](https://github.com/py-econometrics/pyfixest) implements fast routines for fixed effects regression (OLS, IV, Poisson) and a wide range of inference procedures (iid, HC1-3, CRV1, CRV3,
randomization inference, multiple testing corrections via Bonferroni & Romano-Wolf) following the syntax of the formidable [fixest R package](https://github.com/lrberge/fixest).

- [duckreg](https://github.com/py-econometrics/duckreg) provides a simple interface to run lossless regressions on very large datasets that do not fit in memory by first reducing the data to a set of summary statistics out-of-memory using [duckdb](https://github.com/duckdb/duckdb) and then running weighted least squares with frequency weights.

- [wildboottest](https://github.com/py-econometrics/wildboottest) implements multiple fast wild cluster bootstrap algorithms as developed in [Roodman et al
(2019)](https://econpapers.repec.org/paper/qedwpaper/1406.htm) and [MacKinnon, Nielsen & Webb(2022)](https://www.econ.queensu.ca/sites/econ.queensu.ca/files/wpaper/qed_wp_1485.pdf).

- [fastmatch](https://github.com/py-econometrics/fastmatch) implements fast matching estimators for causal inference that uses [faiss](https://github.com/facebookresearch/faiss) for nearest neighbours.

- [gmm](https://github.com/py-econometrics/gmm) helps you minimize generalized methods of moments (GMM) objective functions.  

