# deavgprime

Software engineer working on evaluation tools and reproducible benchmarks, with a focus on infrastructure as code. I work with Python and Go.

## Projects

| Project | Scope |
| --- | --- |
| [IaC Eval Bench](https://github.com/deavgprime/iac-eval-bench) | Six synthetic Kubernetes tasks, offline schema/rubric scoring and a resumable evaluation workflow. Fixture baselines and a [two-model Qwen2.5-Coder comparison](https://github.com/deavgprime/iac-eval-bench/tree/main/results/2026-10-18-qwen-comparison) published, retaining all 12 attempts, failure analysis, latency, token usage and resource measurements. |
| [Go microservices lab](https://github.com/deavgprime/go-microservices-lab) | Go services, messaging experiments, broker validation tests and a reproducible JSON microbenchmark. |

## Open-source contributions

My current contribution focus is Inspect Scout and upstream Inspect AI: preserving evaluation data, checking scoring behavior, and testing failure handling. I start with a reproducible case and add regression coverage before proposing a fix.

| Project | Submitted work |
| --- | --- |
| [Inspect Scout](https://github.com/meridianlabs-ai/inspect_scout) | [Preserving CSV validation identifiers](https://github.com/meridianlabs-ai/inspect_scout/pull/772) and [correcting refusal retry counts](https://github.com/meridianlabs-ai/inspect_scout/pull/773). |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) | Reproductions for [numeric scoring precision](https://github.com/UKGovernmentBEIS/inspect_ai/issues/6216), [Unicode matching](https://github.com/UKGovernmentBEIS/inspect_ai/issues/6218), and [dataset image metadata](https://github.com/UKGovernmentBEIS/inspect_ai/issues/6221). Fixes await maintainer acceptance. |

The linked pull requests show their current review and merge status. Benchmark results distinguish fixture checks from measured model runs and retain failed attempts.

[LinkedIn](https://www.linkedin.com/in/deavyansh)
