# BrandBench

**Open benchmarks for how AI understands and recommends brands.**

Being named in an AI answer is only one part of the buying decision. BrandBench is a PerceptCore initiative to evaluate whether AI describes a brand accurately, matches it to the buyer's needs, and recommends it with supporting evidence.

**Status: repository foundation.** This repository currently contains project documentation and contribution templates. Benchmark datasets, runners, scoring implementations, model integrations, and published results are not available yet. There is no package to install or runnable benchmark.

## What we plan to evaluate

| Dimension | Question |
| --- | --- |
| Factual accuracy | Are statements about the brand supported by dated reference sources? |
| Buyer fit | Does the answer respect the buyer's stated needs, market, budget, and constraints? |
| Recommendation | Is the brand recommended, merely mentioned, or advised against? What reasoning is given? |
| Citation support | Do the cited sources support the claims attached to them? |
| Stability | How much do the observations vary across repeated runs? |

These dimensions will be reported separately. A name match does not establish a recommendation; a citation does not establish correctness.

## Planned evaluation workflow

1. Define a category, market, and buyer scenarios before collecting answers.
2. Version the prompts and reference evidence, including source URLs and collection dates.
3. Record each run's provider, model identifier, date, available settings, and search or grounding configuration. Keep API runs distinguishable from consumer-interface observations.
4. Preserve publishable answers and citations, then annotate them against a documented rubric. Identify automated judgments and human-reviewed labels separately.
5. Repeat runs and report the sample sizes, variation, collection conditions, and limitations behind comparisons.

The objective is a reproducible collection and evaluation process. Live model answers can change even when the recorded setup remains the same.

## Roadmap

- [ ] Specify the evaluation rubric and run metadata format.
- [ ] Publish an initial question set for one industry with documented selection criteria.
- [ ] Define reference-evidence and annotation formats.
- [ ] Add benchmark runners with explicit setup, provider, and cost requirements.
- [ ] Add repeat-run analysis and an inspectable results report.
- [ ] Publish the first reviewed dataset and findings with a versioned methodology.

No scores, leaderboards, model rankings, or visibility gains are claimed at this stage. Data redistribution rights and dataset licensing will be documented before any dataset release.

## Contribute

Read [CONTRIBUTING.md](CONTRIBUTING.md) to propose a buyer scenario, evaluation method, or reproducibility improvement. Include the decision it helps assess and evidence that another contributor can inspect. Follow [SECURITY.md](SECURITY.md) for sensitive reports.

## PerceptCore

**[PerceptCore — AI Brand Intelligence](https://perceptcore.com/)**  
*Shape how AI sees your brand.*

BrandBench is an open-source initiative by PerceptCore. Visit [perceptcore.com](https://perceptcore.com/) for the company and its work.

## License

The current repository contents are licensed under [MIT](LICENSE) — Copyright (c) 2026 PerceptCore. Third-party source material is not relicensed by this repository.
