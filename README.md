# Awesome-Hallucination-Detection

## Top Hallucination Detection Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on LLM Hallucination Detection, Groundedness, Faithfulness, Factuality & RAG Evaluation*
**Last updated: August 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Hallucination Detection in Large Language Models (LLMs)**. These tools detect unsupported claims, factual errors, contradictions, ungrounded generations, retrieval failures, and other reliability problems in LLM and RAG applications.

**Examples** include Patronus AI, Galileo AI, Fiddler AI, Arize AI, WhyLabs, Aporia, Cleanlab, Vectara, NVIDIA NeMo, and Truera — spanning LLM evaluation, AI observability, RAG evaluation, model monitoring, guardrails, and specialized hallucination detection.

**Open-source emphasis**: This section is heavily expanded with open-source evaluation frameworks, hallucination classifiers, faithfulness metrics, RAG evaluation libraries, guardrails, model-evaluation toolkits, and observability platforms. These projects can be combined to build self-hosted hallucination-detection pipelines rather than relying exclusively on commercial APIs.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or canonical GitHub repositories.

## Table of Contents

* [SaaS/Hosted Platforms](#saashosted-platforms)
* [Open-Source GitHub Projects](#open-source-github-projects)
* [Open-Source Building Blocks](#open-source-building-blocks)
* [How to Contribute](#how-to-contribute)
* [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform / Product | Description & Hallucination Focus | Starting Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Patronus AI](https://www.patronus.ai/)** | AI evaluation and reliability platform with specialized hallucination evaluators (Lynx) to verify if responses are grounded in context. | $10.00 / 1,000 API calls (Pay-as-you-go API) | $5.00 free API credits upon signup + 45-minute evaluation strategy session |
| **[Galileo AI](https://galileo.ai/)** | LLM evaluation and observability platform providing quality/safety evaluation, RAG metrics, and hallucination scoring. | $100.00 / month (Pro plan; $0.002 / trace overage) | Free plan with 5,000 traces/month and access to core evaluation metrics |
| **[Fiddler AI](https://www.fiddler.ai/)** | AI observability and evaluation platform with real-time guardrails for hallucination, faithfulness, and safety scoring. | $0.002 / trace (Developer plan) | Free Forever plan for Fiddler Guardrails (real-time safety scoring, faithfulness, prompt injection & PII detection) |
| **[Arize AI](https://arize.com/)** | AI observability and evaluation platform with Phoenix integration for LLM tracing, RAG quality, and faithfulness analysis. | $50.00 / month (AX Pro plan; $0.001 / span overage) | Free plan (AX Free) with 25,000 trace spans/month, 1 GB storage, 15-day retention, and unlimited seats/evals |
| **[WhyLabs](https://whylabs.ai/)** | AI observability and monitoring platform for detecting data, model, and LLM quality/groundedness failures in production. | $0.00 (Fully transitioned to 100% open-source via `whylogs` & `langkit`) | 100% free open-source with unlimited predictions, models, and traces |
| **[Aporia](https://www.aporia.com/)** | AI observability and guardrails platform offering real-time monitoring and mitigation for LLM hallucinations. | $99.00 / month (Starter plan via Coralogix) | 14-day free trial (no credit card required) + Free Community tier for prototype projects |
| **[Cleanlab](https://cleanlab.ai/)** | AI quality platform and Trustworthy Language Model (TLM) API for detecting unreliable outputs and scoring RAG trustworthiness. | $0.001 / evaluation (TLM Lite / pay-per-token API tier) | Free tier with up to 5,000 data points in Cleanlab Studio + free initial TLM API credits |
| **[Vectara](https://www.vectara.com/)** | Grounded-generation and RAG platform with built-in Hallucination Evaluation Model (HHEM) to score answer-context grounding. | $100,000.00 / year (~$8,333.33/month for production SaaS tier) | 30-day free trial with 10,000 platform credits, agent creation, retrieval workflows, and HHEM evaluation |
| **[NVIDIA NeMo](https://developer.nvidia.com/nemo)** | Generative-AI development and guardrails ecosystem to constrain, evaluate, and monitor LLM outputs for hallucinations. | $1.00 / GPU hour (pay-as-you-go) or $4,500.00 / GPU / year (NVIDIA AI Enterprise) | 90-day free trial of NVIDIA AI Enterprise; core NeMo open-source framework is 100% free |
| **[Truera](https://truera.com/)** | AI quality and explainability platform (acquired by Snowflake) powering the open-source TruLens RAG Triad groundedness evaluator. | $0.00 (TruLens open-source; Snowflake AI Observability billed at standard Snowflake credit rates) | 100% free open-source TruLens library + 30-day Snowflake trial with $400 free credits for managed Cortex AI Observability |
| **[Confident AI](https://www.confident-ai.com/)** | Hosted continuous evaluation and monitoring platform built around DeepEval for hallucination and faithfulness testing. | $200.00 / month (Starter plan with unlimited seats, 5 projects, 5 GB-month traces; $1/GB-month overage) | Free tier ($0/month) with 2 seats, 1 project, 5 test runs/week, 1 GB-month trace spans (~100k traces), and 1-week retention |
| **[LangSmith](https://www.langchain.com/langsmith)** | LLM engineering and observability platform with tracing, datasets, automated evaluators, and production hallucination monitoring. | $39.00 / seat / month (Plus tier; $0.50 / 1,000 traces overage) | Free Developer plan with 1 user seat, 5,000 traces/month, and 14-day data retention |
| **[Weights & Biases Weave](https://wandb.ai/site/weave/)** | LLM evaluation and observability toolkit providing execution tracing, dataset benchmarking, and custom hallucination scoring. | $50.00 / user / month (W&B Models/Weave Teams plan; additional ingestion at $0.10/MB) | Free Forever personal/academic plan with 1 user seat, 100 GB storage, and full access to Weave traces/evals |
| **[Comet Opik](https://www.comet.com/docs/opik/)** | LLM observability and evaluation platform for tracing, testing, and evaluating RAG pipelines and agent hallucination rates. | $19.00 / month (Pro plan with up to 50 team members and 100,000 spans/month) | Free Cloud plan with up to 10 team members, 25,000 spans/month, and 60-day data retention (Self-hosted is 100% free) |
| **[Humanloop](https://humanloop.com/)** | Prompt engineering, evaluation, and observability platform supporting automated feedback and production hallucination tracking. | $400.00 / month (Team plan) | 14-day free trial with 2 team members, 50 evaluation runs, and 10,000 logs/month |
| **[Braintrust](https://www.braintrust.dev/)** | AI evaluation and observability platform supporting automated evaluations, scoring, datasets, and live production tracing. | $249.00 / month (Pro plan with 5 GB/month data, 50k scores/month, 30-day retention, unlimited seats) | Free Starter plan ($0/month, no credit card required) with 1 GB data/month, 10,000 scores/month, unlimited users, and 14-day retention |
| **[Langfuse Cloud](https://langfuse.com/)** | Hosted LLM engineering and observability platform supporting trace scoring, custom evaluators, and hallucination metrics. | $29.00 / month (Core plan with 100,000 units/month, 90-day retention, unlimited users; $8/100k units overage) | Free Hobby plan with 50,000 units/month, 2 users, and 30-day data retention (Self-hosted is 100% free) |
| **[Patronus Lynx](https://www.patronus.ai/lynx)** | Specialized hallucination detection model family (8B & 70B) for verifying response groundedness against reference documents. | $0.00 for open-source model weights (or $10.00 / 1,000 calls via Patronus RemoteEvaluator API) | 100% free open weights (CC-BY-NC-4.0) for local/Ollama inference + $5.00 free API credits on Patronus Cloud |

## Open-Source GitHub Projects

* **[DeepEval](https://github.com/confident-ai/deepeval)**
  Open-source LLM evaluation framework inspired by unit testing. It includes dedicated **Hallucination** and **Faithfulness** metrics along with contextual precision, recall, relevancy, RAGAS, and other evaluation methods.

* **[Ragas](https://github.com/explodinggradients/ragas)**
  Open-source framework for evaluating RAG pipelines. Its faithfulness metric measures whether generated answers are supported by retrieved context, and it integrates with multiple LLM application frameworks.

* **[TruLens](https://github.com/truera/trulens)**
  Open-source LLM evaluation and tracing framework with the RAG Triad, feedback functions, groundedness evaluation, and OpenTelemetry-based instrumentation.

* **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**
  Open-source AI observability and evaluation platform for LLM applications, RAG systems, and agents, providing tracing and evaluation capabilities for investigating quality and hallucinations.

* **[Cleanlab](https://github.com/cleanlab/cleanlab)**
  Open-source library for identifying label and data-quality problems and assessing model reliability. Its ecosystem includes tooling for evaluating hallucination-detection models across RAG datasets.

* **[Guardrails AI](https://github.com/guardrails-ai/guardrails)**
  Open-source framework for adding validation and guardrails around LLM outputs, including checks that can be used to prevent or reject unreliable generations.

* **[NVIDIA NeMo Guardrails](https://github.com/NVIDIA-NeMo/Guardrails)**
  Open-source toolkit for adding programmable rails to LLM applications, including topical, safety, conversational, and output controls that can help reduce hallucination risks.

* **[Deepchecks LLM Evaluation](https://github.com/deepchecks/deepchecks)**
  Open-source testing and validation ecosystem that can be used to identify quality and reliability problems in machine-learning and LLM pipelines.

* **[UpTrain](https://github.com/uptrain-ai/uptrain)**
  Open-source LLM evaluation framework with metrics for response quality, factuality, context relevance, and RAG performance.

* **[OpenLLMetry](https://github.com/traceloop/openllmetry)**
  Open-source OpenTelemetry instrumentation for LLM applications. It provides the tracing foundation required to correlate hallucinations with prompts, retrievals, tool calls, and model generations.

* **[Langfuse](https://github.com/langfuse/langfuse)**
  Open-source LLM engineering and observability platform with tracing, evaluation, datasets, prompt management, and custom scoring.

* **[Phoenix](https://github.com/Arize-ai/phoenix)**
  Open-source observability platform specifically designed for AI applications, including RAG tracing and evaluation workflows.

* **[LlamaIndex](https://github.com/run-llama/llama_index)**
  Open-source framework for context-augmented LLM applications with evaluation modules that can measure response faithfulness and retrieval quality.

* **[Haystack](https://github.com/deepset-ai/haystack)**
  Open-source framework for building RAG and LLM pipelines, including evaluation components useful for measuring groundedness and answer quality.

* **[LangChain](https://github.com/langchain-ai/langchain)**
  Open-source framework for LLM applications with integrations for evaluation, retrieval, tracing, and feedback systems.

* **[DSPy](https://github.com/stanfordnlp/dspy)**
  Open-source framework for programming and optimizing LLM pipelines. It can be combined with custom factuality and faithfulness metrics to optimize against hallucination.

* **[OpenAI Evals](https://github.com/openai/evals)**
  Open-source framework for evaluating LLM systems using configurable evaluation datasets and model-graded or deterministic criteria.

* **[EleutherAI lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness)**
  Open-source framework for standardized evaluation of language models across a large collection of benchmarks, useful for broader factuality and reliability testing.

* **[LightEval](https://github.com/huggingface/lighteval)**
  Hugging Face's open-source framework for evaluating language models against customizable evaluation suites and benchmarks.

* **[Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai)**
  Open-source framework from the UK AI Safety Institute for evaluating language-model capabilities and safety, including custom scorers and evaluation tasks.

* **[Prometheus](https://github.com/prometheus-eval/prometheus-eval)**
  Open-source evaluation ecosystem focused on LLM-as-a-judge models and automated evaluation of generated responses.

* **[FActScore](https://github.com/shmsw25/FActScore)**
  Research implementation for evaluating the factuality of generated text by decomposing outputs into atomic facts and assessing their support.

* **[SelfCheckGPT](https://github.com/potsawee/selfcheckgpt)**
  Research implementation for detecting hallucinations in generated text using consistency-based approaches that do not necessarily require external knowledge sources.

* **[MiniCheck](https://github.com/Liyan06/MiniCheck)**
  Lightweight open-source factuality-checking model designed to determine whether generated text is supported by a given source document.

* **[RAGTruth](https://github.com/ParticleMedia/RAGTruth)**
  Open research dataset and benchmark focused on hallucination detection in retrieval-augmented generation systems.

* **[HaluEval](https://github.com/RUCAIBox/HaluEval)**
  Benchmark and dataset for evaluating hallucinations in generated text, covering multiple task types and hallucination scenarios.

* **[TruthfulQA](https://github.com/sylinrl/TruthfulQA)**
  Benchmark for measuring whether language models generate truthful answers rather than reproducing common misconceptions.

* **[Vectara HHEM](https://huggingface.co/vectara/hallucination_evaluation_model)**
  Openly available model implementation/checkpoint family for hallucination evaluation, particularly useful for determining whether generated answers are grounded in source context.

### Additional Strong Open-Source Options

* **[RAGAS](https://github.com/explodinggradients/ragas)** — Faithfulness, answer relevancy, contextual precision and recall for RAG evaluation.
* **[DeepEval](https://github.com/confident-ai/deepeval)** — Pytest-like LLM evaluation with dedicated hallucination and faithfulness metrics.
* **[TruLens](https://github.com/truera/trulens)** — RAG Triad, groundedness evaluation and OpenTelemetry-native tracing.
* **[MiniCheck](https://github.com/Liyan06/MiniCheck)** — Specialized lightweight factuality verification.
* **[FActScore](https://github.com/shmsw25/FActScore)** — Atomic-fact-based factuality evaluation.
* **[SelfCheckGPT](https://github.com/potsawee/selfcheckgpt)** — Sampling/consistency-based hallucination detection.
* **[HaluEval](https://github.com/RUCAIBox/HaluEval)** — Hallucination benchmark and evaluation datasets.
* **[RAGTruth](https://github.com/ParticleMedia/RAGTruth)** — RAG hallucination corpus and benchmark.
* **[OpenAI Evals](https://github.com/openai/evals)** — General-purpose LLM evaluation framework.
* **[Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai)** — Flexible safety and capability evaluation framework.
* **[Guardrails AI](https://github.com/guardrails-ai/guardrails)** — Inline validation and output controls.
* **[NeMo Guardrails](https://github.com/NVIDIA-NeMo/Guardrails)** — Programmable conversational and output guardrails.
* **[UpTrain](https://github.com/uptrain-ai/uptrain)** — Open-source LLM/RAG evaluation.
* **[Phoenix](https://github.com/Arize-ai/phoenix)** — LLM tracing, evaluation and observability.
* **[Langfuse](https://github.com/langfuse/langfuse)** — Self-hosted LLM observability and evaluation.
* **[OpenLLMetry](https://github.com/traceloop/openllmetry)** — OpenTelemetry instrumentation for tracing hallucination-producing execution paths.

**Important distinction**: Not every project above is a dedicated hallucination detector. Some are **evaluation frameworks, datasets, observability systems, guardrails, or factuality benchmarks**. In practice, these components are complementary: a production hallucination-detection stack often combines retrieval evaluation, faithfulness scoring, specialized factuality models, tracing, and inline output validation.

**Frameworks for building a custom hallucination-detection system**: Combine **Ragas/DeepEval** for offline evaluation, **MiniCheck/HHEM** for specialized grounding checks, **TruLens/Phoenix/Langfuse** for tracing and observability, and **Guardrails AI/NeMo Guardrails** for runtime enforcement. This provides a largely self-hosted alternative to a commercial hallucination-monitoring platform.

## Open-Source Building Blocks

| Layer                   | Open-Source Options                | Purpose                                            |
| ----------------------- | ---------------------------------- | -------------------------------------------------- |
| Hallucination Detection | MiniCheck, HHEM, SelfCheckGPT      | Detect unsupported or inconsistent claims          |
| Factuality              | FActScore, MiniCheck               | Evaluate atomic factual claims                     |
| RAG Evaluation          | Ragas, DeepEval                    | Measure faithfulness and retrieval quality         |
| LLM Evaluation          | DeepEval, OpenAI Evals, Inspect AI | Automated model/application testing                |
| Observability           | Phoenix, TruLens, Langfuse         | Trace prompts, retrieval, generations and failures |
| Instrumentation         | OpenLLMetry, OpenTelemetry         | Capture structured LLM execution traces            |
| Guardrails              | Guardrails AI, NeMo Guardrails     | Block, validate or constrain unreliable outputs    |
| RAG Frameworks          | LlamaIndex, Haystack, LangChain    | Build and instrument retrieval pipelines           |
| Benchmarks              | HaluEval, RAGTruth, TruthfulQA     | Benchmark hallucination and truthfulness           |
| Model Evaluation        | lm-evaluation-harness, LightEval   | Standardized LLM benchmarking                      |
| Human Evaluation        | Label Studio                       | Create human factuality/grounding annotations      |
| Experiment Tracking     | MLflow                             | Track evaluation experiments and model versions    |
| Metrics / Dashboards    | Grafana, Prometheus                | Monitor hallucination rates and quality metrics    |
| Vector Retrieval        | Qdrant, Weaviate, Milvus           | Build grounded retrieval infrastructure            |

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` following the existing format.
3. Include: name, link, 1–2 sentence description, and whether it is SaaS, hosted, or open-source.
4. For GitHub projects, prefer the canonical upstream repository.
5. Distinguish **dedicated hallucination detectors** from general LLM-evaluation, observability, benchmark, and guardrail projects.
6. For open-source projects, verify the current repository activity and license before adding them.
7. Submit a PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

* This is a **community-curated list** — not exhaustive and not an endorsement.
* Hallucination detection is an evolving field; scores from different evaluators are not necessarily directly comparable.
* Some projects listed here are **evaluation frameworks, benchmarks, observability platforms, or guardrails**, rather than dedicated hallucination-detection models.
* LLM-as-a-judge systems can themselves make errors; critical applications should combine automated evaluation with appropriate human review and deterministic checks.
* Always verify current licensing, model availability, benchmark methodology, maintenance activity, and deployment requirements before using a project in production.
* A high faithfulness score does not necessarily prove that the retrieved source itself is correct. Grounding and factual correctness are related but distinct properties.

---

**Made for AI engineers, ML researchers, RAG developers, LLM platform teams, AI safety researchers, and developers building reliable generative-AI systems.**
Let's make LLM applications more **grounded, measurable, transparent, and reliable**.

