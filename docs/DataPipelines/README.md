---
title: Data Pipelines
---


# Embedding Data Pipeline

## Configurable

- Types of supported file: PDF, Doc, PPT
- S3 location
- Sturcutred vs. Unstructured Data: connectors for CRM, DB
- PDF Parsing Options: PyPdf
- Chunking: Semantic chunking, Chunk size, Overlap
- Embedding Model to use

```

```

## Steps

- Retrieve PDF & Parse PDF
    - Figure out whether summary of PDF required (accordingly chunking will be done, possibly no chunking for summarized data)
- Chunk PDF based on chunking size (apply semantic chunking)
- Check quality of chunked data (relevance, etc.)
