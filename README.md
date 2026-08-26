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

* **[Patronus AI](https://www.patronus.ai/)**
  AI evaluation and reliability platform with specialized hallucination evaluators including Lynx, which evaluates whether LLM responses are grounded in supplied context.

* **[Galileo AI](https://galileo.ai/)**
  LLM evaluation and observability platform providing quality and safety evaluation capabilities for generative-AI applications, including RAG and hallucination-related metrics.

* **[Fiddler AI](https://www.fiddler.ai/)**
  AI observability and evaluation platform providing monitoring, explainability, quality, safety, and performance analysis for machine-learning and generative-AI systems.

* **[Arize AI](https://arize.com/)**
  AI observability and evaluation platform with Phoenix and managed offerings for LLM tracing, evaluation, RAG quality, and hallucination/faithfulness analysis.

* **[WhyLabs](https://whylabs.ai/)**
  AI observability and monitoring platform focused on detecting data, model, and LLM quality problems in production systems.

* **[Aporia](https://www.aporia.com/)**
  AI observability and guardrails platform providing monitoring and protection for LLM applications, including hallucination and reliability-related controls.

* **[Cleanlab](https://cleanlab.ai/)**
  AI quality platform focused on identifying unreliable data and model outputs, with tooling for evaluating LLM/RAG systems and benchmarking hallucination-detection models.

* **[Vectara](https://www.vectara.com/)**
  Grounded-generation and RAG platform offering the Hallucination Evaluation Model (HHEM), a specialized model for evaluating whether generated responses are supported by retrieved context.

* **[NVIDIA NeMo](https://developer.nvidia.com/nemo)**
  NVIDIA's generative-AI development and evaluation ecosystem. NeMo Guardrails and NeMo evaluation tooling can be used to evaluate, constrain, and monitor LLM outputs.

* **[Truera](https://truera.com/)**
  AI quality and explainability platform whose open-source TruLens project provides evaluation and tracing for LLM applications, including groundedness and RAG metrics.

* **[Confident AI](https://www.confident-ai.com/)**
  Hosted platform around DeepEval for continuous LLM evaluation, testing, debugging, and monitoring, including hallucination and faithfulness evaluation.

* **[LangSmith](https://www.langchain.com/langsmith)**
  LLM engineering and observability platform with tracing, datasets, experiments, evaluators, and production monitoring useful for identifying hallucinations and grounding failures.

* **[Weights & Biases Weave](https://wandb.ai/site/weave/)**
  LLM evaluation and observability platform supporting tracing, evaluations, datasets, scoring, and analysis of AI application behavior.

* **[Comet Opik](https://www.comet.com/docs/opik/)**
  LLM observability and evaluation platform for tracing and testing AI applications, including RAG and agent evaluation.

* **[Humanloop](https://humanloop.com/)**
  LLM evaluation and observability platform supporting experiments, evaluations, feedback, and production-quality monitoring.

* **[Braintrust](https://www.braintrust.dev/)**
  AI evaluation and observability platform supporting automated evaluations, datasets, experiments, scoring, tracing, and production monitoring.

* **[Langfuse Cloud](https://langfuse.com/)**
  Hosted LLM engineering and observability platform supporting traces, evaluations, datasets, prompt management, and custom quality metrics.

* **[Patronus Lynx](https://www.patronus.ai/lynx)**
  Specialized hallucination-detection model from Patronus designed to identify responses that are not grounded in supplied context.

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

