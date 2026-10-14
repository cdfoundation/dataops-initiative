# DataOps Landscape

Here are the open source tools we found useful for DataOps. Please create a pull request if you believe one is missing and feel free to [Join CDF Slack](https://join.slack.com/t/cdeliveryfdn/shared_invite/zt-44c6rpi1z-dFDPNRchD37ehiyB6QcdnQ) to ask any questions.

The same list is shown as the DataOps group of the CD Foundation landscape: [landscape.cd.foundation/?group=dataops](https://landscape.cd.foundation/?group=dataops). The categories below match the categories on the landscape.

## Inclusion criteria

A tool is listed when it:

- Is used to build, run, test, govern or observe data pipelines.
- Has its source code on GitHub, with at least 300 stars (the CDF landscape threshold).
- Is not archived and has had a commit in the last 12 months.
- Is released under an open source license. A few widely used source-available tools are also listed; their license is marked "source available" in the table.

## Adding a tool

1. Open a pull request here that adds a row to the table, in the category and subcategory where it fits best.
2. Open a pull request to [cdfoundation/cdf-landscape](https://github.com/cdfoundation/cdf-landscape) that adds the item to the matching category in `landscape.yml`, with an SVG logo in `hosted_logos`. If the tool is already on the landscape in another category, add a `second_path` to the existing entry instead of a duplicate.

## Tools

| Project | Category | Subcategory | Repository | License |
| --- | --- | --- | --- | --- |
| Debezium | Data Integration & Streaming | Change Data Capture | [debezium/debezium](https://github.com/debezium/debezium) | Apache-2.0 |
| Airbyte | Data Integration & Streaming | Data Integration | [airbytehq/airbyte](https://github.com/airbytehq/airbyte) | ELv2 (source available) |
| Apache NiFi | Data Integration & Streaming | Data Integration | [apache/nifi](https://github.com/apache/nifi) | Apache-2.0 |
| Meltano | Data Integration & Streaming | Data Integration | [meltano/meltano](https://github.com/meltano/meltano) | MIT |
| SeaTunnel | Data Integration & Streaming | Data Integration | [apache/seatunnel](https://github.com/apache/seatunnel) | Apache-2.0 |
| Vector | Data Integration & Streaming | Data Integration | [vectordotdev/vector](https://github.com/vectordotdev/vector) | MPL-2.0 |
| Flink | Data Integration & Streaming | Stream Processing | [apache/flink](https://github.com/apache/flink) | Apache-2.0 |
| RisingWave | Data Integration & Streaming | Stream Processing | [risingwavelabs/risingwave](https://github.com/risingwavelabs/risingwave) | Apache-2.0 |
| Kafka | Data Integration & Streaming | Streaming & Messaging | [apache/kafka](https://github.com/apache/kafka) | Apache-2.0 |
| Pulsar | Data Integration & Streaming | Streaming & Messaging | [apache/pulsar](https://github.com/apache/pulsar) | Apache-2.0 |
| Redpanda | Data Integration & Streaming | Streaming & Messaging | [redpanda-data/redpanda](https://github.com/redpanda-data/redpanda) | BSL-1.1 and RCL (source available) |
| Apache Pinot | Data Storage & Query | Analytical Databases | [apache/pinot](https://github.com/apache/pinot) | Apache-2.0 |
| ClickHouse | Data Storage & Query | Analytical Databases | [ClickHouse/ClickHouse](https://github.com/ClickHouse/ClickHouse) | Apache-2.0 |
| Doris | Data Storage & Query | Analytical Databases | [apache/doris](https://github.com/apache/doris) | Apache-2.0 |
| Druid | Data Storage & Query | Analytical Databases | [apache/druid](https://github.com/apache/druid) | Apache-2.0 |
| DuckDB | Data Storage & Query | Analytical Databases | [duckdb/duckdb](https://github.com/duckdb/duckdb) | MIT |
| StarRocks | Data Storage & Query | Analytical Databases | [StarRocks/starrocks](https://github.com/StarRocks/starrocks) | Apache-2.0 |
| Ceph | Data Storage & Query | Object Storage | [ceph/ceph](https://github.com/ceph/ceph) | LGPL-2.1 / LGPL-3.0 |
| Apache Iceberg | Data Storage & Query | Open Table Formats | [apache/iceberg](https://github.com/apache/iceberg) | Apache-2.0 |
| Delta Lake | Data Storage & Query | Open Table Formats | [delta-io/delta](https://github.com/delta-io/delta) | Apache-2.0 |
| Hudi | Data Storage & Query | Open Table Formats | [apache/hudi](https://github.com/apache/hudi) | Apache-2.0 |
| Alluxio | Data Storage & Query | Query Engines & Data Access | [Alluxio/alluxio](https://github.com/Alluxio/alluxio) | Apache-2.0 |
| Trino | Data Storage & Query | Query Engines & Data Access | [trinodb/trino](https://github.com/trinodb/trino) | Apache-2.0 |
| Metabase | Data Processing & Analytics | BI & Visualization | [metabase/metabase](https://github.com/metabase/metabase) | AGPL-3.0 core, commercial license for EE code |
| Superset | Data Processing & Analytics | BI & Visualization | [apache/superset](https://github.com/apache/superset) | Apache-2.0 |
| Arrow | Data Processing & Analytics | DataFrames & Columnar | [apache/arrow](https://github.com/apache/arrow) | Apache-2.0 |
| pandas | Data Processing & Analytics | DataFrames & Columnar | [pandas-dev/pandas](https://github.com/pandas-dev/pandas) | BSD-3-Clause |
| Polars | Data Processing & Analytics | DataFrames & Columnar | [pola-rs/polars](https://github.com/pola-rs/polars) | MIT |
| Apache Spark | Data Processing & Analytics | Distributed Processing | [apache/spark](https://github.com/apache/spark) | Apache-2.0 |
| Beam | Data Processing & Analytics | Distributed Processing | [apache/beam](https://github.com/apache/beam) | Apache-2.0 |
| Dask | Data Processing & Analytics | Distributed Processing | [dask/dask](https://github.com/dask/dask) | BSD-3-Clause |
| Ray | Data Processing & Analytics | Distributed Processing | [ray-project/ray](https://github.com/ray-project/ray) | Apache-2.0 |
| Apache Zeppelin | Data Processing & Analytics | Notebooks | [apache/zeppelin](https://github.com/apache/zeppelin) | Apache-2.0 |
| JupyterHub | Data Processing & Analytics | Notebooks | [jupyterhub/jupyterhub](https://github.com/jupyterhub/jupyterhub) | BSD-3-Clause |
| dbt Core | Data Processing & Analytics | SQL Transformation | [dbt-labs/dbt](https://github.com/dbt-labs/dbt) | Apache-2.0 |
| SQLMesh | Data Processing & Analytics | SQL Transformation | [SQLMesh/sqlmesh](https://github.com/SQLMesh/sqlmesh) | Apache-2.0 |
| Bitol | Data Pipeline Orchestration & CI/CD | Data Contracts | [bitol-io/open-data-contract-standard](https://github.com/bitol-io/open-data-contract-standard) | Apache-2.0 |
| Buf | Data Pipeline Orchestration & CI/CD | Data Contracts | [bufbuild/buf](https://github.com/bufbuild/buf) | Apache-2.0 |
| DVC | Data Pipeline Orchestration & CI/CD | Data Versioning | [treeverse/dvc](https://github.com/treeverse/dvc) | Apache-2.0 |
| lakeFS | Data Pipeline Orchestration & CI/CD | Data Versioning | [treeverse/lakeFS](https://github.com/treeverse/lakeFS) | BSL-1.1 (source available) |
| Crossplane | Data Pipeline Orchestration & CI/CD | Infrastructure as Code | [crossplane/crossplane](https://github.com/crossplane/crossplane) | Apache-2.0 |
| OpenTofu | Data Pipeline Orchestration & CI/CD | Infrastructure as Code | [opentofu/opentofu](https://github.com/opentofu/opentofu) | MPL-2.0 |
| Pulumi | Data Pipeline Orchestration & CI/CD | Infrastructure as Code | [pulumi/pulumi](https://github.com/pulumi/pulumi) | Apache-2.0 |
| Terraform | Data Pipeline Orchestration & CI/CD | Infrastructure as Code | [hashicorp/terraform](https://github.com/hashicorp/terraform) | BSL-1.1 (source available) |
| Bytebase | Data Pipeline Orchestration & CI/CD | Schema & Database Change Management | [bytebase/bytebase](https://github.com/bytebase/bytebase) | Apache-2.0 core, enterprise license for EE code |
| Flyway | Data Pipeline Orchestration & CI/CD | Schema & Database Change Management | [flyway/flyway](https://github.com/flyway/flyway) | Apache-2.0 |
| Liquibase | Data Pipeline Orchestration & CI/CD | Schema & Database Change Management | [liquibase/liquibase](https://github.com/liquibase/liquibase) | FSL-1.1-ALv2 (source available) |
| Apache Airflow | Data Pipeline Orchestration & CI/CD | Workflow Orchestration | [apache/airflow](https://github.com/apache/airflow) | Apache-2.0 |
| Argo | Data Pipeline Orchestration & CI/CD | Workflow Orchestration | [argoproj/argo-workflows](https://github.com/argoproj/argo-workflows) | Apache-2.0 |
| Dagster | Data Pipeline Orchestration & CI/CD | Workflow Orchestration | [dagster-io/dagster](https://github.com/dagster-io/dagster) | Apache-2.0 |
| Flyte | Data Pipeline Orchestration & CI/CD | Workflow Orchestration | [flyteorg/flyte](https://github.com/flyteorg/flyte) | Apache-2.0 |
| Kestra | Data Pipeline Orchestration & CI/CD | Workflow Orchestration | [kestra-io/kestra](https://github.com/kestra-io/kestra) | Apache-2.0 |
| Luigi | Data Pipeline Orchestration & CI/CD | Workflow Orchestration | [spotify/luigi](https://github.com/spotify/luigi) | Apache-2.0 |
| Mage | Data Pipeline Orchestration & CI/CD | Workflow Orchestration | [mage-ai/mage-ai](https://github.com/mage-ai/mage-ai) | Apache-2.0 |
| Prefect | Data Pipeline Orchestration & CI/CD | Workflow Orchestration | [PrefectHQ/prefect](https://github.com/PrefectHQ/prefect) | Apache-2.0 |
| Temporal | Data Pipeline Orchestration & CI/CD | Workflow Orchestration | [temporalio/temporal](https://github.com/temporalio/temporal) | MIT |
| Apache Ranger | Data Quality, Governance & Observability | Access & Policy | [apache/ranger](https://github.com/apache/ranger) | Apache-2.0 |
| Open Policy Agent (OPA) | Data Quality, Governance & Observability | Access & Policy | [open-policy-agent/opa](https://github.com/open-policy-agent/opa) | Apache-2.0 |
| Elementary | Data Quality, Governance & Observability | Data & Pipeline Observability | [elementary-data/elementary](https://github.com/elementary-data/elementary) | Apache-2.0 |
| OpenObserve | Data Quality, Governance & Observability | Data & Pipeline Observability | [openobserve/openobserve](https://github.com/openobserve/openobserve) | AGPL-3.0 |
| SigNoz | Data Quality, Governance & Observability | Data & Pipeline Observability | [SigNoz/signoz](https://github.com/SigNoz/signoz) | MIT core, enterprise license for ee/ |
| Marquez | Data Quality, Governance & Observability | Data Lineage | [MarquezProject/marquez](https://github.com/MarquezProject/marquez) | Apache-2.0 |
| OpenLineage | Data Quality, Governance & Observability | Data Lineage | [OpenLineage/OpenLineage](https://github.com/OpenLineage/OpenLineage) | Apache-2.0 |
| Great Expectations | Data Quality, Governance & Observability | Data Quality & Testing | [fivetran/great_expectations](https://github.com/fivetran/great_expectations) | Apache-2.0 |
| Apache Atlas | Data Quality, Governance & Observability | Metadata & Catalogs | [apache/atlas](https://github.com/apache/atlas) | Apache-2.0 |
| DataHub | Data Quality, Governance & Observability | Metadata & Catalogs | [datahub-project/datahub](https://github.com/datahub-project/datahub) | Apache-2.0 |
| Egeria | Data Quality, Governance & Observability | Metadata & Catalogs | [odpi/egeria](https://github.com/odpi/egeria) | Apache-2.0 |
| Gravitino | Data Quality, Governance & Observability | Metadata & Catalogs | [apache/gravitino](https://github.com/apache/gravitino) | Apache-2.0 |
| OpenMetadata | Data Quality, Governance & Observability | Metadata & Catalogs | [open-metadata/OpenMetadata](https://github.com/open-metadata/OpenMetadata) | Apache-2.0 |
| Unity Catalog | Data Quality, Governance & Observability | Metadata & Catalogs | [unitycatalog/unitycatalog](https://github.com/unitycatalog/unitycatalog) | Apache-2.0 |
| Feast | Data for AI & ML | Feature Stores | [feast-dev/feast](https://github.com/feast-dev/feast) | Apache-2.0 |
| Kubeflow | Data for AI & ML | ML Lifecycle | [kubeflow/kubeflow](https://github.com/kubeflow/kubeflow) | Apache-2.0 |
| MLflow | Data for AI & ML | ML Lifecycle | [mlflow/mlflow](https://github.com/mlflow/mlflow) | Apache-2.0 |
| Chroma | Data for AI & ML | Vector Databases | [chroma-core/chroma](https://github.com/chroma-core/chroma) | Apache-2.0 |
| Milvus | Data for AI & ML | Vector Databases | [milvus-io/milvus](https://github.com/milvus-io/milvus) | Apache-2.0 |
| Qdrant | Data for AI & ML | Vector Databases | [qdrant/qdrant](https://github.com/qdrant/qdrant) | Apache-2.0 |
| Weaviate | Data for AI & ML | Vector Databases | [weaviate/weaviate](https://github.com/weaviate/weaviate) | BSD-3-Clause core, Weaviate License for some modules |
