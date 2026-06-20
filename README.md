# LlamaCloud (llamacloud)

LlamaCloud is the managed document parsing, extraction, indexing, and retrieval platform from LlamaIndex. It exposes REST APIs at `https://api.cloud.llamaindex.ai` for LlamaParse (document parsing to Markdown/JSON), managed ingestion pipelines and indexes, document management, retrieval, and LlamaExtract (schema-driven structured extraction), all secured with a Bearer API key. This is the hosted cloud platform, distinct from the open-source LlamaIndex framework.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/llamacloud/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/llamacloud/refs/heads/main/apis.yml)

> Note: This catalog covers the hosted **LlamaCloud** platform (cloud.llamaindex.ai) and its cloud APIs. It is intentionally kept distinct from the separate `llamaindex` repository, which covers the open-source LlamaIndex framework.

## Tags

- AI
- Document Parsing
- Extraction
- Indexing
- Retrieval
- RAG

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### LlamaParse API

Asynchronous document parsing that uploads files (PDF, DOCX, PPTX, images, and more) and returns clean Markdown or structured JSON. Submit a parse job, poll job status, and retrieve results in Markdown or JSON across Fast, Balanced, and Agentic tiers.

- **Human URL:** [https://developers.llamaindex.ai/llamaparse](https://developers.llamaindex.ai/llamaparse)
- **Base URL:** `https://api.cloud.llamaindex.ai/api/v1`

#### Tags

- Parsing
- Documents
- OCR
- Markdown

#### Properties

- [Documentation](https://developers.llamaindex.ai/llamaparse)
- [API Reference](https://developers.llamaindex.ai/cloud-api-reference/category/parsing)
- [OpenAPI](openapi/llamacloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/llamacloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamacloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LlamaCloud Pipelines and Indexes API

Managed ingestion and indexing pipelines that chunk, embed, and store documents into a scalable vector index with no infrastructure to manage. Create and configure pipelines, attach files and data sources, and monitor ingestion status.

- **Human URL:** [https://developers.llamaindex.ai/python/cloud/llamacloud/guides/api_sdk](https://developers.llamaindex.ai/python/cloud/llamacloud/guides/api_sdk)
- **Base URL:** `https://api.cloud.llamaindex.ai/api/v1`

#### Tags

- Pipelines
- Indexes
- Ingestion
- Embeddings

#### Properties

- [Documentation](https://developers.llamaindex.ai/python/cloud/llamacloud/guides/api_sdk)
- [API Reference](https://developers.llamaindex.ai/cloud-api-reference)
- [OpenAPI](openapi/llamacloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/llamacloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamacloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LlamaCloud Documents and Files API

Upload, list, and manage files and the documents inside a pipeline. Add documents to an index, list pipeline documents, fetch document chunks, and delete documents from the managed index.

- **Human URL:** [https://developers.llamaindex.ai/cloud-api-reference](https://developers.llamaindex.ai/cloud-api-reference)
- **Base URL:** `https://api.cloud.llamaindex.ai/api/v1`

#### Tags

- Documents
- Files
- Storage

#### Properties

- [Documentation](https://developers.llamaindex.ai/cloud-api-reference)
- [API Reference](https://developers.llamaindex.ai/cloud-api-reference)
- [OpenAPI](openapi/llamacloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/llamacloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamacloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LlamaCloud Retrieval API

Retrieve the most relevant chunks from a managed index for a natural language query, with Fast, Accurate, and Advanced retrieval modes, optional reranking, and metadata filtering for RAG workloads.

- **Human URL:** [https://developers.llamaindex.ai/python/cloud/llamacloud/guides/api_sdk](https://developers.llamaindex.ai/python/cloud/llamacloud/guides/api_sdk)
- **Base URL:** `https://api.cloud.llamaindex.ai/api/v1`

#### Tags

- Retrieval
- Search
- RAG
- Reranking

#### Properties

- [Documentation](https://developers.llamaindex.ai/python/cloud/llamacloud/guides/api_sdk)
- [API Reference](https://developers.llamaindex.ai/cloud-api-reference)
- [OpenAPI](openapi/llamacloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/llamacloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamacloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LlamaExtract API

Schema-driven structured data extraction from documents. Define an extraction agent with a JSON data schema, run extraction jobs against uploaded files, and retrieve typed JSON results with field-level citations and metadata.

- **Human URL:** [https://developers.llamaindex.ai/llamaextract](https://developers.llamaindex.ai/llamaextract)
- **Base URL:** `https://api.cloud.llamaindex.ai/api/v1`

#### Tags

- Extraction
- Structured Data
- Schema
- Agents

#### Properties

- [Documentation](https://developers.llamaindex.ai/llamaextract)
- [API Reference](https://developers.llamaindex.ai/python/cloud/llamaextract/getting_started/api)
- [OpenAPI](openapi/llamacloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/llamacloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamacloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/run-llama)
- [LinkedIn](https://www.linkedin.com/company/llamaindex)
- [Website](https://cloud.llamaindex.ai)
- [Documentation](https://developers.llamaindex.ai)
- [Plans](plans/llamacloud-plans-pricing.yml)
- [Rate Limits](rate-limits/llamacloud-rate-limits.yml)
- [Fin Ops](finops/llamacloud-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
