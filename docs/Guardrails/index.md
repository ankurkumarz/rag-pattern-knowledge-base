---
title: Guardrails
---

## Types of Guardrails

- Prventive
- Detective
- Corrective

## Considerations for Guardrails

Ensuring that Responsible AI practices are being followed such as:
- Content Filter (for harmful or legal/compliance reasons)
- PII Data Detection/Redaction
- Safety for Harmful Content
- Biasness Detection
- Hallucination Detection
- Grounding

## Guardrails Frameworks

| Framework | Provider | Description |
| -----|------|-------|
| [NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | NVIDIA | an open-source toolkit for easily adding programmable guardrails to LLM-based conversational systems |
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) | Guardrails AI | a Python framework that helps build reliable AI applications by performing -  Input/Output Guard and generate structured data |
| [LLM Guard](https://llm-guard.com/) | [Protect AI](https://protectai.com/) | a suite of tools to protect LLM applications by helping you detect, redact, and sanitize LLM prompts and responses, for real time safety, security and compliance. |
| [Guardrails for Amazon Bedrock](https://aws.amazon.com/bedrock/guardrails/) | AWS | Implement safeguards customized to your application requirements and responsible AI policies |
| [Azure AI Safety Evals](https://learn.microsoft.com/en-us/azure/ai-studio/concepts/evaluation-approach-gen-ai) | Microsoft | to assess an application’s vulnerability to jailbreak attacks and to generating content risks. [Click here](https://azure.microsoft.com/en-us/blog/announcing-new-tools-in-azure-ai-to-help-you-build-more-secure-and-trustworthy-generative-ai-applications/) to know more about other Azure AI tools. It provides configurable safety attributes but do not have an option for a customized guardrails development. It can be achieved via 3rd party solution/framework.|
| [Vertex AI Safety Attributes](https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/configure-safety-attributes) | Google Cloud | It provides configurable safety attributes but do not have an option for a customized guardrails development. It can be achieved via 3rd party solution/framework. |
