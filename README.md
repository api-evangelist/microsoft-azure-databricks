# Azure Databricks (azure-databricks)

Azure Databricks is an Apache Spark-based analytics platform optimized for Microsoft Azure. It provides a collaborative workspace for data engineers, data scientists, and analysts to work together on big data and machine learning workloads.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/azure-databricks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/azure-databricks/refs/heads/main/apis.yml)

## Tags

- Analytics
- Apache Spark
- Big Data
- Data Engineering
- Machine Learning

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Azure Databricks REST API

Core REST API for managing Azure Databricks workspaces, clusters, jobs, notebooks, and other resources programmatically.

- **Human URL:** [https://learn.microsoft.com/azure/databricks/](https://learn.microsoft.com/azure/databricks/)
- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api`

#### Tags

- Clusters
- Jobs
- Notebooks
- Workspace

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/)
- [OpenAPI](openapi/azure-databricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/authentication)
- [API Reference](https://docs.databricks.com/api/azure/workspace/introduction)
- [JSON Schema](json-schema/azure-databricks-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-databricks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Clusters API

Manage Databricks clusters for running Spark jobs including creating, starting, editing, listing, terminating, and deleting clusters.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/clusters`

#### Tags

- Clusters
- Compute

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/clusters)
- [OpenAPI](openapi/azure-databricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/azure-databricks-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [API Reference](https://docs.databricks.com/api/azure/workspace/clusters)

### Jobs API

Create, manage, and run jobs on Databricks clusters including scheduling, listing runs, and managing job permissions.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.1/jobs`

#### Tags

- Automation
- Jobs
- Scheduling

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/jobs)
- [OpenAPI](openapi/azure-databricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://docs.databricks.com/api/azure/workspace/jobs)

### Workspace API

Manage notebooks, folders, and other workspace objects including listing, importing, exporting, and deleting workspace items.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/workspace`

#### Tags

- Folders
- Notebooks
- Workspace

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/workspace)
- [OpenAPI](openapi/azure-databricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://docs.databricks.com/api/azure/workspace/workspace)

### DBFS API

Access Databricks File System (DBFS) for file operations including uploading, downloading, listing, and deleting files and directories.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/dbfs`

#### Tags

- Files
- Storage

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/dbfs)
- [API Reference](https://docs.databricks.com/api/azure/workspace/dbfs)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Libraries API

Manage libraries and dependencies on clusters including installing, uninstalling, and listing library statuses.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/libraries`

#### Tags

- Dependencies
- Libraries

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/libraries)
- [API Reference](https://docs.databricks.com/api/azure/workspace/libraries)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Secrets API

Manage secrets and secret scopes for secure credential storage including creating scopes, putting secrets, and managing ACLs.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/secrets`

#### Tags

- Credentials
- Secrets
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/secrets)
- [API Reference](https://docs.databricks.com/api/azure/workspace/secrets)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Token Management API

Create and manage personal access tokens for API authentication including creating, listing, and revoking tokens.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/token`

#### Tags

- Authentication
- Security
- Tokens

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/token-management)
- [API Reference](https://docs.databricks.com/api/azure/workspace/tokenmanagement)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SQL Analytics API

Manage SQL warehouses, queries, and dashboards for Databricks SQL analytics workloads.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/sql`

#### Tags

- Analytics
- Queries
- Sql
- Warehouses

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/sql/api/)
- [API Reference](https://docs.databricks.com/api/azure/workspace/warehouses)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MLflow API

Track experiments, log metrics, and manage ML models using the MLflow tracking and registry APIs.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/mlflow`

#### Tags

- Experiments
- Machine Learning
- Mlops
- Model Tracking

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/mlflow/)
- [API Reference](https://docs.databricks.com/api/azure/workspace/experiments)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Instance Pools API

Create and manage instance pools to reduce cluster start and autoscaling times by maintaining a set of idle ready-to-use cloud instances.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/instance-pools`

#### Tags

- Clusters
- Compute
- Instance Pools

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/compute/pool-index)
- [API Reference](https://docs.databricks.com/api/azure/workspace/instancepools)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cluster Policies API

Create, list, and edit cluster policies to control cluster configurations and limit the ability to configure clusters based on a set of rules.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/policies/clusters`

#### Tags

- Clusters
- Governance
- Policies

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/admin/clusters/policy-definition)
- [API Reference](https://docs.databricks.com/api/azure/workspace/clusterpolicies)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Repos API

Manage Git repositories within Databricks workspaces for version control of notebooks and files.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/repos`

#### Tags

- Git
- Repositories
- Version Control

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/repos/)
- [API Reference](https://docs.databricks.com/api/azure/workspace/repos)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Git Credentials API

Manage Git credentials for authenticating with Git providers when using Databricks Repos.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/git-credentials`

#### Tags

- Authentication
- Credentials
- Git

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/gitcredentials)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pipelines API

Create, edit, delete, start, and view details about Delta Live Tables pipelines for building reliable data pipelines.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/pipelines`

#### Tags

- Data Engineering
- Delta Live Tables
- ETL
- Pipelines

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/ldp/)
- [API Reference](https://docs.databricks.com/api/azure/workspace/pipelines)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Permissions API

Manage permissions on workspace objects including clusters, jobs, notebooks, and other resources using access control lists.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/permissions`

#### Tags

- Access Control
- Permissions
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/security/auth/access-control/)
- [API Reference](https://docs.databricks.com/api/azure/workspace/permissions)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Unity Catalog - Catalogs API

Manage Unity Catalog catalogs for organizing and governing data assets across workspaces.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/catalogs`

#### Tags

- Catalogs
- Data Governance
- Unity Catalog

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/data-governance/unity-catalog/)
- [API Reference](https://docs.databricks.com/api/azure/workspace/catalogs)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Unity Catalog - Schemas API

Manage schemas within Unity Catalog catalogs for organizing tables, views, and functions.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/schemas`

#### Tags

- Data Governance
- Schemas
- Unity Catalog

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/schemas)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Unity Catalog - Tables API

Manage tables within Unity Catalog schemas including listing, getting, and deleting tables.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/tables`

#### Tags

- Data Governance
- Tables
- Unity Catalog

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/tables)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Unity Catalog - Volumes API

Manage Unity Catalog volumes for governing non-tabular data such as files and directories.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/volumes`

#### Tags

- Storage
- Unity Catalog
- Volumes

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/volumes)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Unity Catalog - Grants API

Manage permissions and grants on Unity Catalog objects including catalogs, schemas, tables, and other securable objects.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/permissions`

#### Tags

- Data Governance
- Permissions
- Unity Catalog

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/grants)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Unity Catalog - External Locations API

Manage external locations in Unity Catalog for connecting to cloud storage paths.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/external-locations`

#### Tags

- External Locations
- Storage
- Unity Catalog

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/externallocations)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Unity Catalog - Storage Credentials API

Manage storage credentials in Unity Catalog for authenticating access to cloud storage.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/storage-credentials`

#### Tags

- Credentials
- Security
- Storage
- Unity Catalog

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/storagecredentials)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Unity Catalog - Metastores API

Manage Unity Catalog metastores which serve as the top-level container for data governance.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/metastores`

#### Tags

- Data Governance
- Metastores
- Unity Catalog

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/metastores)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Model Serving Endpoints API

Create and manage model serving endpoints for deploying machine learning models as REST API endpoints.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/serving-endpoints`

#### Tags

- Deployment
- Inference
- Machine Learning
- Model Serving

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/machine-learning/model-serving/create-manage-serving-endpoints)
- [API Reference](https://docs.databricks.com/api/azure/workspace/servingendpoints)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Model Registry API

Manage registered models and model versions in the Databricks Model Registry for model lifecycle management.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/mlflow/databricks`

#### Tags

- Machine Learning
- Mlops
- Model Registry

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/modelregistry)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Registered Models API

Manage registered models in Unity Catalog for centralized model governance and sharing.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.1/unity-catalog/models`

#### Tags

- Machine Learning
- Model Registry
- Unity Catalog

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/registeredmodels)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Global Init Scripts API

Manage global cluster initialization scripts that run on every cluster in the workspace.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/global-init-scripts`

#### Tags

- Administration
- Clusters
- Initialization

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/globalinitscripts)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IP Access Lists API

Manage IP access lists to control network access to Azure Databricks workspaces.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/ip-access-lists`

#### Tags

- Access Control
- Networking
- Security

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/ipaccesslists)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Statement Execution API

Execute SQL statements on SQL warehouses and retrieve results for programmatic SQL access.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/sql/statements`

#### Tags

- Query Execution
- Sql
- Warehouses

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/statementexecution)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Command Execution API

Execute commands on running clusters and retrieve results programmatically.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/1.2`

#### Tags

- Clusters
- Commands
- Execution

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/commandexecution)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Files API

Manage files in Unity Catalog volumes and workspace filesystem with operations for uploading, downloading, and deleting files.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/fs/files`

#### Tags

- Files
- Storage
- Unity Catalog

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/files)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apps API

Deploy and manage Databricks Apps including creating, starting, stopping, and listing custom applications.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/apps`

#### Tags

- Applications
- Deployment

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/apps)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lakeview API

Manage Lakeview dashboards programmatically including creating, updating, and publishing dashboards.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/lakeview`

#### Tags

- Dashboards
- Lakeview
- Visualization

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/lakeview)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Online Tables API

Manage online tables for low-latency serving of feature data in Unity Catalog.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/online-tables`

#### Tags

- Feature Serving
- Machine Learning
- Online Tables

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/onlinetables)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vector Search Indexes API

Manage vector search indexes for similarity search and retrieval-augmented generation workloads.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/vector-search/indexes`

#### Tags

- AI
- RAG
- Similarity Search
- Vector Search

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/vectorsearchindexes)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vector Search Endpoints API

Manage vector search endpoints for hosting vector search indexes.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/vector-search/endpoints`

#### Tags

- AI
- Endpoints
- Vector Search

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/vectorsearchendpoints)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Query History API

Retrieve query history for SQL warehouses including query text, status, and performance metrics.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/sql/history/queries`

#### Tags

- Monitoring
- Query History
- Sql

#### Properties

- [API Reference](https://docs.databricks.com/api/azure/workspace/queryhistory)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Account SCIM API

Manage users, groups, and service principals across the Databricks account using SCIM 2.0 protocol.

- **Base URL:** `https://<databricks-instance>.azuredatabricks.net/api/2.0/account/scim/v2`

#### Tags

- Groups
- Identity Management
- SCIM
- Users

#### Properties

- [Documentation](https://learn.microsoft.com/azure/databricks/reference/scim-2-1)
- [API Reference](https://learn.microsoft.com/azure/databricks/dev-tools/api/latest/scim/scim-groups)
- [Postman Collection](collections/azure-databricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-databricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Getting Started](https://learn.microsoft.com/azure/databricks/getting-started/)
- [Pricing](https://azure.microsoft.com/pricing/details/databricks/)
- [Status Page](https://status.azuredatabricks.net/)
- [Security](https://learn.microsoft.com/azure/databricks/security/)
- [SDK](https://learn.microsoft.com/azure/databricks/dev-tools/)
- [C L I](https://learn.microsoft.com/azure/databricks/dev-tools/cli/)
- [Authentication](https://learn.microsoft.com/azure/databricks/dev-tools/auth/)
- [API Reference](https://learn.microsoft.com/azure/databricks/reference/api)
- [Release Notes](https://learn.microsoft.com/azure/databricks/release-notes/product/)
- [Changelog](https://learn.microsoft.com/azure/databricks/release-notes/)
- [Support](https://learn.microsoft.com/answers/tags/166/azure-databricks)
- [SDK](https://learn.microsoft.com/azure/databricks/dev-tools/sdk-python)
- [SDK](https://learn.microsoft.com/azure/databricks/dev-tools/sdk-java)
- [SDK](https://learn.microsoft.com/azure/databricks/dev-tools/sdk-go)
- [SDK](https://learn.microsoft.com/azure/databricks/dev-tools/sdk-r)
- [GitHub Repository](https://github.com/Azure/azure-databricks-client)
- [OpenAPI](openapi/azure-databricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/azure-databricks-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-databricks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/azure-databricks-spectral-rules.yml)
- [Vocabulary](vocabulary/azure-databricks-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [L L Ms Txt](https://docs.databricks.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
