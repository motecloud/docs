# Publishing Benchmarks

Public benchmarks should be reproducible, understandable, and scoped for publication.

Benchmark explanations live in this docs repository. Published artifacts live in [github.com/motecloud/benchmarks](https://github.com/motecloud/benchmarks).

## Publication Checklist

Before publishing benchmark material, confirm that it includes:

- A clear benchmark name and version.
- The task being measured.
- The systems or baselines being compared.
- Dataset or dataset-manifest information that is safe to publish.
- Result files or summary tables.
- Reproduction notes.
- Known limitations and caveats.

## Safety Checklist

Do not publish tenant data, private artifact paths, internal tuning notes, unreleased datasets, proprietary thresholds, credentials, or private repository links.

## Interpretation

Benchmark pages should explain what the benchmark does and does not prove. If a result measures retrieval quality, do not describe it as a full product-quality score unless the benchmark actually covers the full product workflow.

## Versioning

Published benchmark artifacts should be versioned so readers can connect methodology, data, and result files to the same evaluation run.