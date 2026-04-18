# Azure Databricks (azure-databricks)
Azure Databricks is an Apache Spark-based analytics platform optimized for Microsoft Azure. It provides a collaborative workspace for data engineers, data scientists, and analysts to work together on big data and machine learning workloads.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/azure-databricks/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, Apache Spark, Big Data, Data Engineering, Machine Learning

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Azure Databricks REST API
Core REST API for managing Azure Databricks workspaces, clusters, jobs, notebooks, and other resources programmatically.

**Human URL:** [https://learn.microsoft.com/azure/databricks/](https://learn.microsoft.com/azure/databricks/)

#### Tags:

 - Clusters, Jobs, Notebooks, Workspace

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/)
- [OpenAPI](openapi/azure-databricks-openapi.yml)
- [Authentication](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/authentication)
- [APIReference](https://docs.databricks.com/api/azure/workspace/introduction)
- [JSONSchema](json-schema/azure-databricks-cluster-schema.json)
- [JSONLD](json-ld/azure-databricks-context.jsonld)

### Clusters API
Manage Databricks clusters for running Spark jobs including creating, starting, editing, listing, terminating, and deleting clusters.

#### Tags:

 - Clusters, Compute

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/clusters)
- [OpenAPI](openapi/azure-databricks-openapi.yml)
- [JSONSchema](json-schema/azure-databricks-cluster-schema.json)
- [APIReference](https://docs.databricks.com/api/azure/workspace/clusters)

### Jobs API
Create, manage, and run jobs on Databricks clusters including scheduling, listing runs, and managing job permissions.

#### Tags:

 - Automation, Jobs, Scheduling

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/jobs)
- [OpenAPI](openapi/azure-databricks-openapi.yml)
- [APIReference](https://docs.databricks.com/api/azure/workspace/jobs)

### Workspace API
Manage notebooks, folders, and other workspace objects including listing, importing, exporting, and deleting workspace items.

#### Tags:

 - Folders, Notebooks, Workspace

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/workspace)
- [OpenAPI](openapi/azure-databricks-openapi.yml)
- [APIReference](https://docs.databricks.com/api/azure/workspace/workspace)

### DBFS API
Access Databricks File System (DBFS) for file operations including uploading, downloading, listing, and deleting files and directories.

#### Tags:

 - Files, Storage

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/dbfs)
- [APIReference](https://docs.databricks.com/api/azure/workspace/dbfs)

### SQL Analytics API
Manage SQL warehouses, queries, and dashboards for Databricks SQL analytics workloads.

#### Tags:

 - Analytics, Queries, Sql, Warehouses

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/sql/api/)
- [APIReference](https://docs.databricks.com/api/azure/workspace/warehouses)

### MLflow API
Track experiments, log metrics, and manage ML models using the MLflow tracking and registry APIs.

#### Tags:

 - Experiments, Machine Learning, Mlops, Model Tracking

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/mlflow/)
- [APIReference](https://docs.databricks.com/api/azure/workspace/experiments)

### Unity Catalog - Catalogs API
Manage Unity Catalog catalogs for organizing and governing data assets across workspaces.

#### Tags:

 - Catalogs, Data Governance, Unity Catalog

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/data-governance/unity-catalog/)
- [APIReference](https://docs.databricks.com/api/azure/workspace/catalogs)

### Model Serving Endpoints API
Create and manage model serving endpoints for deploying machine learning models as REST API endpoints.

#### Tags:

 - Deployment, Inference, Machine Learning, Model Serving

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/machine-learning/model-serving/create-manage-serving-endpoints)
- [APIReference](https://docs.databricks.com/api/azure/workspace/servingendpoints)

### Vector Search Indexes API
Manage vector search indexes for similarity search and retrieval-augmented generation workloads.

#### Tags:

 - AI, RAG, Similarity Search, Vector Search

#### Properties

- [APIReference](https://docs.databricks.com/api/azure/workspace/vectorsearchindexes)

## Common Properties

- [GettingStarted](https://learn.microsoft.com/azure/databricks/getting-started/)
- [Pricing](https://azure.microsoft.com/pricing/details/databricks/)
- [StatusPage](https://status.azuredatabricks.net/)
- [Security](https://learn.microsoft.com/azure/databricks/security/)
- [SDK](https://learn.microsoft.com/azure/databricks/dev-tools/)
- [CLI](https://learn.microsoft.com/azure/databricks/dev-tools/cli/)
- [Authentication](https://learn.microsoft.com/azure/databricks/dev-tools/auth/)
- [APIReference](https://learn.microsoft.com/azure/databricks/reference/api)
- [ReleaseNotes](https://learn.microsoft.com/azure/databricks/release-notes/product/)
- [ChangeLog](https://learn.microsoft.com/azure/databricks/release-notes/)
- [Support](https://learn.microsoft.com/answers/tags/166/azure-databricks)
- [SDK - Python](https://learn.microsoft.com/azure/databricks/dev-tools/sdk-python)
- [SDK - Java](https://learn.microsoft.com/azure/databricks/dev-tools/sdk-java)
- [SDK - Go](https://learn.microsoft.com/azure/databricks/dev-tools/sdk-go)
- [SDK - R](https://learn.microsoft.com/azure/databricks/dev-tools/sdk-r)
- [GitHubRepository](https://github.com/Azure/azure-databricks-client)

## Features

| Name |
|------|
| Collaborative notebooks with multi-language support |
| Auto-scaling Apache Spark clusters |
| Delta Lake for reliable data lakehouse architecture |
| Unity Catalog for unified data governance |
| MLflow integration for ML lifecycle management |
| Model serving endpoints for real-time inference |
| Delta Live Tables for declarative ETL pipelines |
| SQL analytics with serverless SQL warehouses |
| Vector search for RAG and similarity search |
| Lakeview dashboards for data visualization |
| Git integration for version control of notebooks |
| SCIM 2.0 for identity and access management |

## Use Cases

| Name |
|------|
| Building and managing data lakehouse architectures |
| Training and deploying machine learning models at scale |
| Running ETL pipelines for data transformation |
| Interactive data exploration and ad-hoc analytics |
| Real-time streaming analytics with Structured Streaming |
| Building retrieval-augmented generation (RAG) applications |
| Data governance and compliance with Unity Catalog |
| Collaborative data science with shared notebooks |

## Integrations

| Name |
|------|
| Azure Data Factory for orchestration |
| Azure Synapse Analytics for data warehousing |
| Azure Data Lake Storage for scalable storage |
| Azure Key Vault for secret management |
| Azure Active Directory for authentication |
| Power BI for business intelligence dashboards |
| Terraform for infrastructure as code |
| Apache Kafka for streaming data ingestion |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Azure Databricks REST API](openapi/azure-databricks-openapi.yml)

### JSON Schema

- [Azure Databricks Cluster Schema](json-schema/azure-databricks-cluster-schema.json)

### JSON-LD

- [Azure Databricks Context](json-ld/azure-databricks-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Azure Databricks](capabilities/shared/databricks.yaml) -- 31 operations for clusters, jobs, and workspace management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Data Engineering](capabilities/data-engineering.yaml) | Databricks | 27 | Data Engineer |

## Vocabulary

- [Azure Databricks Vocabulary](vocabulary/azure-databricks-vocabulary.yaml)

## Rules

- [Azure Databricks Spectral Rules](rules/azure-databricks-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
