# Interpreting Benchmark Results

Benchmarks are useful when their scope is clear.

A strong benchmark page should help readers understand what the result supports, what it does not support, and which decisions the result can reasonably inform.

## Ask What Was Measured

Different benchmarks measure different layers:

- Retrieval quality.
- Context coverage.
- Reader or answer accuracy.
- End-to-end agent workflow quality.
- Latency or cost.
- Robustness under ambiguity or contradiction.

Do not treat a narrow retrieval result as proof of full product quality unless the benchmark covers the full workflow.

## Compare Like With Like

Public comparisons should use compatible metrics. If two systems report different metrics, the benchmark page should explain why they are not directly comparable.

## Look For Caveats

Good benchmark reports include caveats such as dataset size, task distribution, evaluation date, model versions, and unsupported scenarios.

## Prefer Reproducibility

Published results are more useful when readers can inspect methodology and reproduce the run from public artifacts.