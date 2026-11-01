# Hi, 

I build evaluation tools, reproducible benchmarks, and infrastructure workflows in Python and Go. My current focus is evaluation data integrity, scoring behavior, and failure handling.

## Projects

| Project | Scope |
| --- | --- |
| [IaC Eval Bench](https://github.com/deavgprime/iac-eval-bench) | A prototype for evaluating model-generated Kubernetes configurations: six synthetic tasks, offline schema and rubric checks, and a resumable workflow. |
| [Go microservices lab](https://github.com/deavgprime/go-microservices-lab) | Go services, messaging experiments, broker validation tests and a reproducible JSON microbenchmark. |

The [IaC Eval Bench pilot](https://github.com/deavgprime/iac-eval-bench/tree/main/results/2026-10-18-qwen-comparison) retains all 12 attempts from two small models, with failure analysis, latency, token usage, and resource measurements. One attempt per model per task does not establish a model ranking. Schema and rubric checks do not establish runtime correctness.

## Writing

- [What exactly are AI evals?](https://dev.to/deavgprime/what-exactly-are-ai-evals-775): tasks, graders, metrics, and what an evaluation score can leave out.
- [Before scoring a model, test the evaluator](https://dev.to/deavgprime/before-scoring-a-model-test-the-evaluator-3noi): five scoring errors in IaC Eval Bench and the regression cases that caught them.
- [Resuming an eval without changing the experiment](https://dev.to/deavgprime/resuming-an-eval-without-changing-the-experiment-c8d): preserving saved attempts and checking that a resumed run still belongs to the same experiment.

## Open-source contributions

I focus on Inspect Scout and upstream Inspect AI, and maintain my existing Harbor and NeMo Gym contributions. My approach is to reproduce the failure, isolate the cause, and test the proposed change against regression cases and controls.

| Project | Submitted work |
| --- | --- |
| [Inspect Scout](https://github.com/meridianlabs-ai/inspect_scout) | [Preserving CSV validation identifiers](https://github.com/meridianlabs-ai/inspect_scout/pull/772) and [correcting refusal retry counts](https://github.com/meridianlabs-ai/inspect_scout/pull/773). |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) | Reproductions for [numeric scoring precision](https://github.com/UKGovernmentBEIS/inspect_ai/issues/6216), [Unicode matching](https://github.com/UKGovernmentBEIS/inspect_ai/issues/6218), and [dataset image metadata](https://github.com/UKGovernmentBEIS/inspect_ai/issues/6221). Fixes await maintainer acceptance. |
| [Harbor](https://github.com/harbor-framework/harbor) | [Configurable local tokenization for context estimates](https://github.com/harbor-framework/harbor/pull/3857). |
| [NeMo Gym](https://github.com/NVIDIA-NeMo/Gym) | [Calendar verifier checks](https://github.com/NVIDIA-NeMo/Gym/pull/5384) and [portable Harbor dataset paths](https://github.com/NVIDIA-NeMo/Gym/pull/5404). |

These are submitted fixes and bug reports. The linked issues and pull requests show their current acceptance, review, and merge status.

[LinkedIn](https://www.linkedin.com/in/deavyansh)
