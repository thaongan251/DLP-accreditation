***Not update yet...***



# Fundamentals of the Databricks Lakehouse Platform Accreditation 

_Multiple Choice_
**1) Which of the following is a benefit of the Databricks Lakehouse Platform being designed to support all data and artificial intelligence (AI) workloads? Select four responses.**

- [x] Data workloads can be automatically scaled when needed.
- [x] Data teams can all utilize secure data from a single source to deliver reliable, consistent results across workloads at scale.
- [ ] There is increased need for multiple, specialist platform administrators to maintain each component of the unified platform.Data analysts, data engineers, and data scientists can easily collaborate within a single platform.
- [x] Analysts can easily integrate their favorite business intelligence (BI) tools for further analysis.
- [x] Data analysts, data engineers, and data scientists can easily collaborate within a single platform.

_Multiple Choice_
**2) Which of the following describes what challenges a data organization would likely face when migrating from a data warehouse to a data lake? Select two responses.**

- [ ] There are increased performance speeds in a data lake.
- [x] There are increased security and privacy concerns in a data lake.
- [ ] There are increased data quality guarantees in a data lake
- [x] There are increased data reliability issues in a data lake.
- [ ] There are increased cloud storage costs in a data lake.


_Multiple Choice_
**3) Data organizations need specialized environments designed specifically for machine learning workloads.
Which of the following is made available by Databricks as part of Databricks Machine Learning to support machine learning workloads? Select four responses.**

 - [x] Built-in automated machine learning development
 - [x] Built-in real-time model serving
 - [x] Support for distributed model training on big data
 - [ ] Lakehouse-specific deep learning frameworks
 - [x] Optimized and preconfigured machine learning frameworks



_Single choice_
**4) One of the foundational technologies provided by the Databricks Lakehouse Platform is an open-source, file-based storage format that provides a number of benefits. These benefits include ACID transaction guarantees, scalable data and metadata handling, audit history and time travel, table schema enforcement and schema evolution, support for deletes/updates/merges, and unified streaming and batch data processing.
Which of the following technologies is being described in the above statement? Select one response.**

 - [ ] MLflow
 - [x] Delta Lake
 - [ ] Photon
 - [ ] Apache Spark
 - [ ] Unity Catalog



_Single choice_
**5) Which of the following lists the relational entities in order from largest (most coarse) to smallest (most granular) within their hierarchy? Select one response.**

- [ ] Schema (Database) → Metastore → Catalog → Table
- [ ] Catalog → Metastore → Schema (Database) → Table
- [ ] Metastore → Catalog → Table → Schema (Database)
- [ ] Schema (Database) → Catalog → Table → Metastore
- [x] Metastore → Catalog → Schema (Database) → Table


_Single choice_
**6) In the past, a lot of data engineering resources needed to be contributed to the development of tooling and other mechanisms for creating and managing data workloads. In response, Databricks developed and released a declarative ETL framework so data engineers can focus on helping their organizations get value from their data. 
Which of the following technologies is being described above? Select one response.**

- [ ] Autologging
- [ ] Databricks SQL Queries
- [ ] Databricks Jobs
- [ ] Delta Lake
- [x] Delta Live Tables


_Multiple Choice_
**7) Which of the following architecture benefits is provided directly by the Databricks Lakehouse Platform? Select three responses.**

- [x] Available on and across multiple clouds
- [x] Built on open source and open standards
- [ ] Scalable, redundant cloud-based data storage
- [ ] Efficient on-premises optimized hardware
- [x] Unified security and governance approach for all data assets


_Multiple Choice_
**8) Many organizations use a variety of open-source and proprietary tools for data orchestration, but these tools often have their own limitations. To address the orchestration needs of these organizations, Databricks developed Databricks Workflows.
Which of the following is a benefit of using Databricks Workflows for orchestration purposes? Select two responses.**

- [x] Databricks Workflows supports tasks for data ingestion, data engineering, machine learning, and business intelligence (BI)
- [ ] Databricks Workflows provides Git-backed version control capabilities to notebooks
- [x] Databricks Workflows supports workloads across multiple cloud service providers and tools
- [ ] Databricks Workflows supports automating workloads as long as they are not in notebooks
- [ ] Databricks Workflows provides multiple-task workflow functionality only for Delta Live Tables workloads


_Single choice_
**9) While the Databricks Lakehouse Platform provides support for many types of data, analytics, and machine learning workloads, some organizations prefer to continue using other preferred vendors for use cases like data ingestion, data transformation, business intelligence, and machine learning.**


- [ ] Databricks can be used on-premises to allow for secure, in-house integrations.
- [ ] Databricks can be used locally to allow developers to manually integrate with other systems.
- [ ] Databricks cannot be used alongside other big data tools and platforms.
- [ ] Databricks can use cloud service provider capabilities to efficiently share data with other data tools and platforms.
- [x] Databricks can be integrated directly with a large number of Databricks partners.


_Multiple Choice_
**10) Which of the following correctly describes how a specific capability of the Databricks Lakehouse Platform supports a data streaming pattern? Select three responses.**

- [x] Databricks Workflows automatically passes data from task to task in regular microbatches.
- [x] Auto Loader continuously and incrementally ingests streaming data.
- [ ] Structured Streaming enables stream-based machine learning inference.
- [x] Delta Live Tables processes ETL pipelines on streaming data with advanced monitoring mechanisms.
- [ ] MLflow ingests its automatic experiment tracking data into a stream for continuous monitoring.


_Multiple Choice_
**11) Which of the following is a common problem within a data lake architecture that can be easily solved by using the Databricks Lakehouse Platform? Select three responses.**

- [ ] Inability to use open-source data formats
- [x] Too many small files
- [ ] Lack of cloud service integrations
- [x] Lack of ACID transaction support
- [x] Ineffective partitioning


_Single choice_
**12) Unity Catalog offers improved Lakehouse data object governance and organization capabilities for data segregation.
Which of the following is a consequence of using Unity Catalog to manage, organize and segregate data objects? Select one response.**

- [ ] Databricks Machine Learning
- [ ] Delta Lake
- [ ] Unity Catalog
- [x] Data Science and Engineering Workspace
- [ ] Databricks SQL


_Single choice_
**13) It can be challenging for a data lakehouse to provide both performance and scalability for all of its query-based workloads to the standards of a data warehouse and a data lake. As a result, Databricks has introduced a technology built atop Apache Spark to further speed up and scale these varied workloads.
Which of the following technologies is being described in the above statement? Select one response.**

- [ ] Unity Catalog
- [ ] Delta Lake
- [ ] AutoML
- [x] Photon
- [ ] AutoML


_Multiple Choice_
**14) In which of the following ways do serverless compute resources differ from classic compute resources within the Databricks Lakehouse Platform? Select two responses.**

- [ ] They are always running and reserved for a single, specific customer when needed
- [x] They result in lower costs by not overprovisioning
- [ ] They are located within the cloud
- [x] They exist within the Databricks cloud account
- [ ] They exist within the customer cloud account


_Multiple Choice_
**15)The Databricks Lakehouse Platform architecture consists of a control plane and a data plane.
Which of the following resources exists within the Databricks control plane? Select two responses.**

- [ ] Classic compute resources
- [x] Cluster configurations
- [ ] Cloud object storage
- [ ] Serverless compute resources
- [x] Notebooks


_Multiple Choice_
**16) Maintaining and improving data quality is a major goal of modern data engineering.
Which of the following contributes directly to high levels of data quality within the Databricks Lakehouse Platform? Select two responses.**

- [ ] Data expectations enforcement
- [ ] Apache Spark’s data format flexibility
- [x] Table schema evolution
- [ ] Simplified machine learning model serving
- [x] Business intelligence (BI) tool integrations


_Single choice_
**17) Data sharing has traditionally been performed by proprietary vendor solutions, SSH File Transfer Protocol (SFTP), or cloud-specific solutions. However, each of these sharing tools and solutions comes with its own set of limitations. As a result, Databricks helped to develop the solution, Delta Sharing.
Which of the following describes Delta Sharing as a solution for data sharing? Select one response.**

- [ ] Delta Sharing is a multicloud, proprietary solution for efficiently copying and transferring data from the lakehouse to any external system.
- [ ] Delta Sharing is a multicloud, proprietary solution to securely and efficiently share data while maintaining control of the source data.
- [ ] Delta Sharing is a multicloud, open-source solution for distributing data across a number of compute resources for efficient data shuffling.
- [x] Delta Sharing is a multicloud, open-source solution to securely and efficiently share live data from the lakehouse to any external system.
- [ ] Delta Sharing is a multicloud, open-source solution to share data between Databricks workspaces within a single Databricks account.


_Single choice_
**18) Which of the following Databricks Lakehouse Platform services or capabilities provides a data warehousing experience to its users? Select one response.**

- [x] Databricks SQL
- [ ] Unity Catalog
- [ ] Data Science and Engineering Workspace
- [ ] Databricks Machine Learning
- [ ] Delta Lake


_Multiple Choice_
**19) Which of the following data engineering capabilities simplifies the work of data engineers on the Databricks Lakehouse Platform? Select three responses.**

- [x] SQL and Python development compatibility
- [x] End-to-end data pipeline visibility
- [x] Automatic deployment and data operations
- [ ] Serverless cluster startup times
- [ ] Flexible machine learning development solutions


_Multiple Choice_
**20) Which of the following is a security feature made available in the Databricks Lakehouse Platform by Unity Catalog? Select two responses.**

- [x] Single-source-of-truth identity management
- [ ] Databricks SQL warehouse access control
- [x] Fine-grained access control on data objects
- [ ] Workspace-specific identity management
- [ ] Workspace-specific data metastores


_Single choice_
**21) Which of the following do Databricks SQL users experience when using serverless Databricks SQL warehouses rather than classic Databricks SQL warehouses? Select one response.**

- [x] Expedited environment startup
- [ ] Availability of automatic scaling
- [ ] Performance degradation on long-running queries
- [ ] Availability of Photon
- [ ] Increased total cost of use


_Multiple Choice_
**22) Which of the following compute resources is available in the Databricks Lakehouse Platform? Select two responses.**

- [ ] On-premises clusters
- [ ] Serverless clusters
- [ ] Local Databricks SQL warehouses
- [x] Serverless Databricks SQL warehouses
- [x] Classic clusters


_Multiple Choice_
**23) A data architect is evaluating data warehousing solutions for their organization to use. As a part of this, the architect is considering the Databricks Lakehouse Platform.
Which of the following is a benefit of using the Databricks Lakehouse Platform for warehousing? Select four responses.**

- [x] Built-in governance for single-source-of-truth data
- [x] A rich ecosystem of business intelligence (BI) integrations
- [ ] Local development software to integrate with other capabilities
- [x] Engineering capabilities supporting warehouse source data
- [x] Best available price/performance


_Single choice_
**24) Which of the following describes the motivation for the creation of the data lakehouse? Select one response.**

- [x] Organizations needed a single, flexible, high-performance system to support data, analytics, and machine learning workloads.
- [ ] Organizations needed to reduce the costs of storing their open-format data files in the cloud.
- [ ] Organizations needed to be able to develop increasingly complex machine learning workloads using a simple, SQL-based solution.
- [ ] Organizations needed a way to scale their data lake workloads without investing in additional on-premises hardware.
- [ ] Organizations needed a reliable data management system with transactional guarantees for their structured data.


_Single choice_
**25) Which of the following describes how the Databricks Lakehouse Platform makes data governance simpler? Select one response.**

- [ ] Unity Catalog provides a different governance solution for each major Databricks Lakehouse Platform Service.
- [ ] Unity Catalog provides a different governance solution for each cloud.
- [ ] Unity Catalog provides a single governance solution across workload types and clouds.
- [ ] Unity Catalog provides a different governance solution for each workload.
- [x] Unity Catalog provides a single governance solution fully managed by the Databricks team.
