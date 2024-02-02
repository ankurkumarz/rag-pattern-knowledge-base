# RAG Pattern Knowledge Base

A repository to consolidate knowledge articles, patterns, white papers, relevant articles supporting RAG pattern.

<p align="center">
<a href="https://opensource.org/licenses/Apache"><img src="https://img.shields.io/badge/license-Apache--2.0-blue"></a>
</p>

## Design Patterns

### Pre-check/practices

- Entity Recognition
- PII Check

### Post-check

- Redaction

## Prompt Engineering

- [Step by step guide to learning Prompt Engineering](https://roadmap.sh/prompt-engineering)

## Prompt Flow


## Frameworks

## Vector Databases

## Whitepapers

- [RestGPT: Connecting Large Language Models with Real-World RESTful APIs](https://arxiv.org/pdf/2306.06624.pdf)

## Evaluation and Testing

### Measure LLM Performance

```mermaid
journey
    section Create/Generate Test Cases
        Write Test Cases: 5: QA
        Generate Test Cases: 4: Developer
        Synthesize Requests: 3: Developer
    section Create Data Sets
        Document Expected Response: 5: QA
    section Automate Execution
        Integrate with CI/CD Pipeline: 5:DevOps
        Run/Execute Pipeline: 4:DevOps
        Synthesize Results: 3:QA
        Capture Metrics: 3:QA
    
```

- Measure LLM Performance by integrating it in CI Pipeline (run parallel tests with prepared data sets)
- If customization is needed, writing your own Test Runner.


## Production Best Practices

- 