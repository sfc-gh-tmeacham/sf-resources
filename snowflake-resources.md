# Don't Panic! A Curated Collection of Snowflake Resources

## Overview
A curated guide to Snowflake resources for practitioners at every level — from getting started with free training to building production pipelines, deploying AI, and operating securely at scale.

## Table of Contents
- [Learning & Certification](#learning--certification)
- [Developer References](#developer-references)
- [General Resources](#general-resources)
- [Media](#media)
- [Community / Forums](#community--forums)
- [Blogs](#blogs)
- [Developer Tools](#developer-tools)
- [Streamlit](#streamlit)
- [Data Engineering](#data-engineering)
- [Cortex AI & Generative AI](#cortex-ai--generative-ai)
- [Machine Learning](#machine-learning)
- [Governance & Security](#governance--security)
- [Cost Management](#cost-management)
- [Snowflake Status and Release Notes](#snowflake-status-and-release-notes)
- [Snowflake Marketplace](#snowflake-marketplace)
- [Industry Solutions](#industry-solutions)


## Learning & Certification

1. [Key Concepts & Architecture](https://docs.snowflake.com/en/user-guide/intro-key-concepts)  
Foundational overview of Snowflake's three-layer architecture (storage, compute, cloud services), table types (Snowflake, Iceberg, Hybrid), and integrated workloads across data engineering, analytics, AI/ML, and applications.
2. [Snowflake University](https://learn.snowflake.com/en/#learningTracks)  
Free self-paced training paths, role-based learning journeys, Hands-On Essentials badges, and Level Up micro-courses.
3. [Snowflake Northstar Education Program](https://www.snowflake.com/en/developers/northstar/)  
Free Coursera courses created by Snowflake's developer advocates, including Intro to Snowflake, Data Engineering, Advanced Data Engineering, and Generative AI.
4. [Snowflake Quickstarts & Guides](https://www.snowflake.com/en/developers/guides/)  
Interactive hands-on tutorials, quickstarts, and reference architectures across data engineering, AI/ML, app development, and more.
5. [Frosty Friday](https://frostyfriday.org/)  
A series of weekly challenges released every Friday to help you practice and develop your Snowflake skills, created by Snowflake users, for Snowflake users.
6. [Get SnowPro Certified](https://www.snowflake.com/certifications/)  
Proctored exams at Associate, Core, Advanced (Architect, Data Engineer, Data Scientist, Administrator, Data Analyst, Security Engineer), and Specialty (Gen AI, Snowpark, Native Apps) levels.
7. [Webinars](https://www.snowflake.com/about/webinars/)  
Live and on-demand webinars covering new features, best practices, and customer stories.


## Developer References

1. [Snowflake Documentation](https://docs.snowflake.com/)  
Complete product documentation — SQL reference, user guides, developer guides, tutorials, and release notes.
2. [Snowflake Developers Portal](https://developers.snowflake.com/)  
Developer hub for downloading the Snowflake CLI, Snowpark, SnowSQL, ODBC driver, and other client libraries.
3. [Snowflake Clients, Drivers & Libraries](https://developers.snowflake.com/drivers-and-libraries/)  
Connectors and drivers for Python, JDBC, ODBC, Node.js, Go, .NET, and PHP PDO.
4. [Snowflake SQL API](https://docs.snowflake.com/en/developer-guide/sql-api/index)  
REST API for submitting SQL statements, checking execution status, and canceling queries. Supports OAuth and key-pair authentication.
5. [Snowflake Python API](https://docs.snowflake.com/en/developer-guide/snowflake-python-api/snowflake-python-overview)  
Manage Snowflake objects — tables, warehouses, tasks, roles, stages, and more — programmatically in Python without writing SQL. Distinct from the Python Connector (driver) and Snowpark (data processing).
6. [Snowflake Labs on GitHub](https://github.com/Snowflake-Labs)  
470+ open-source repos including schemachange, sf-samples, demo notebooks, and quickstart companion code.


## General Resources

1. [Official Snowflake Resources](https://resources.snowflake.com/)  
A searchable collection of whitepapers, videos, blog posts, and more.
2. [Partner Ecosystem](https://docs.snowflake.com/en/user-guide/ecosystem)  
Explore the ecosystem of 3rd-party partners and technologies certified to integrate with Snowflake.


## Media

1. [Snowflake on YouTube](https://www.youtube.com/user/snowflakecomputing/videos)  
Product demos, Summit talks, workload deep-dives, and feature walkthroughs.
2. [Snowflake Developers on YouTube](https://www.youtube.com/@snowaboratory)  
Short-form tutorials, live coding, and product tips from Snowflake developer advocates.
3. [The Data Cloud Podcast](https://www.snowflake.com/thedatacloudpodcast/)  
Interviews with data and engineering leaders on architecture, strategy, and real-world Snowflake use cases.


## Community / Forums

1. [Snowflake Community](https://community.snowflake.com/s/)  
Q&A forums, how-to guides, and the Data Superhero recognition program.
2. [Snowflake on Stack Overflow](https://stackoverflow.com/questions/tagged/snowflake-cloud-data-platform?tab=Active)  
Ask and answer the most challenging technical questions related to Snowflake.
3. [Snowflake subreddit](https://www.reddit.com/r/snowflake/)  
Unofficial subreddit for discussion relating to the Snowflake Data Cloud.


## Blogs

1. [Inside the AI Data Cloud](https://www.snowflake.com/blog/)  
Get the latest information from the official Snowflake Blog.
2. [Snowflake Builders Blog](https://medium.com/snowflake)  
Best practices, tips & tricks from Snowflake experts and community. Submissions welcome!


## Developer Tools

1. [Workspaces](https://docs.snowflake.com/en/user-guide/ui-snowsight/workspaces)  
Unified SQL editor in Snowsight with file-based organization, side-by-side results, inline Copilot, and Git integration. Replacing Worksheets as the default editor.
2. [Snowflake Notebooks](https://docs.snowflake.com/en/user-guide/ui-snowsight/notebooks)  
Jupyter-like notebooks running directly in Snowflake with SQL, Python, and Markdown. Available in Warehouse Runtime or Container Runtime (with GPU support).
3. [Notebooks in Workspaces](https://docs.snowflake.com/en/user-guide/ui-snowsight/notebooks-in-workspaces/notebooks-in-workspaces-overview)  
Enhanced notebook experience with full Jupyter compatibility, terminal access, file management, and a pre-built container runtime optimized for AI/ML with CPU and GPU support.
4. [Snowflake Extension for VS Code](https://docs.snowflake.com/en/user-guide/vscode-ext)  
Write and execute SQL directly in VS Code with autocomplete, syntax highlighting, and Snowpark Python debugging. Includes object explorer, query history, and Native App support.
5. [Snowflake CLI (`snow`)](https://docs.snowflake.com/en/developer-guide/snowflake-cli/index)  
The modern, open-source CLI for developer-centric workloads. Manages Streamlit apps, Native Apps, Snowpark, SPCS, notebooks, and SQL execution. Replaces legacy SnowSQL.
6. [Cortex Code](https://www.snowflake.com/en/product/features/cortex-code/)  
AI coding agent for Snowflake development. Generates, explains, and optimizes SQL and Python while respecting your warehouse's schemas and governance policies.
7. [Snowpark Container Services (SPCS)](https://docs.snowflake.com/en/developer-guide/snowpark-container-services/overview)  
Run OCI-compatible containerized applications, ML models, and custom services on Snowflake-managed compute pools with GPU support.
8. [Snowflake Native App Framework](https://docs.snowflake.com/en/developer-guide/native-apps/native-apps-about)  
Build, distribute, and monetize applications through the Snowflake Marketplace. Supports Snowpark, Streamlit, and containerized components.
9. [Snowflake Postgres](https://docs.snowflake.com/en/user-guide/snowflake-postgres/about)  
Managed PostgreSQL instances running on Snowflake for transactional and operational workloads. Fully compatible with existing Postgres tooling, ORMs, and SQL clients — no code changes required.


## Streamlit

1. [Streamlit in Snowflake (SiS)](https://docs.snowflake.com/en/developer-guide/streamlit/about-streamlit)  
Build and deploy Streamlit apps directly within Snowflake. Data never leaves the secure environment. Available in Warehouse Runtime or Container Runtime.
2. [Streamlit Docs](https://docs.streamlit.io/)  
Get started guide, API reference, and more advanced features of the core library including caching, theming, and Streamlit Components.
3. [30 Days of Streamlit](https://30days.streamlit.app/)  
Daily bite-sized lessons that walk you from zero to a working Streamlit app.
4. [30 Days of AI](https://30daysofai.streamlit.app/)  
Daily coding challenges building AI-powered Streamlit apps with Snowflake Cortex AI. Progresses from basic LLM calls through chatbots and RAG to multimodal AI and agents.
5. [Streamlit Cheat Sheet](https://docs.streamlit.io/develop/quick-reference/cheat-sheet)  
Quick-reference card for every Streamlit command and widget.
6. [Streamlit Sample Apps](https://github.com/Snowflake-Labs/snowflake-demo-streamlit)  
Every folder is an independent Streamlit app containing code, setup scripts, and sample data. Every app contains a README file which serves as a guide to setting up the app and using it.


## Data Engineering

1. [Dynamic Tables](https://docs.snowflake.com/en/user-guide/dynamic-tables-about)  
Declarative data pipelines that automatically keep results up-to-date. Define the target state in SQL and let Snowflake handle incremental refresh.
2. [Snowpipe](https://docs.snowflake.com/en/user-guide/data-load-snowpipe-intro)  
Serverless, continuous data loading from files in cloud storage stages. Triggers automatically via cloud event notifications or on-demand through REST endpoints.
3. [Snowpipe Streaming](https://docs.snowflake.com/en/user-guide/snowpipe-streaming/data-load-snowpipe-streaming-overview)  
Low-latency, row-level ingestion directly into Snowflake tables — no staging files required. Supports SDK-based and REST API ingestion with sub-second data availability.
4. [Snowflake Openflow](https://www.snowflake.com/en/product/features/openflow/)  
Managed data integration service built on Apache NiFi. Connect virtually any data source with visual drag-and-drop flow creation for structured and unstructured data.
5. [Semi-Structured Data](https://docs.snowflake.com/en/user-guide/semistructured-intro)  
Load and query JSON, Avro, Parquet, ORC, and XML using VARIANT, ARRAY, and OBJECT types. Supports automatic schema detection, hierarchical nesting, and direct SQL querying.
6. [Unstructured Data](https://docs.snowflake.com/en/user-guide/unstructured-intro)  
Access and process files (images, PDFs, audio, video) stored in stages. Provides scoped, file, and pre-signed URLs, directory tables, and the FILE data type for use in UDFs, stored procedures, and Document AI.
7. [Geospatial Data Types & Functions](https://docs.snowflake.com/en/sql-reference/data-types-geospatial)  
Native GEOGRAPHY and GEOMETRY types with WKT, WKB, GeoJSON, and EWKT support. Includes 80+ geospatial functions for spatial relationships, measurements, transformations, and H3 indexing.
8. [Apache Iceberg Tables](https://docs.snowflake.com/en/user-guide/tables-iceberg)  
First-class Iceberg table support with Snowflake-managed or externally managed tables, catalog-linked databases, and cross-engine interoperability.
9. [Hybrid Tables](https://docs.snowflake.com/en/user-guide/tables-hybrid)  
Row-based table type optimized for low-latency, high-concurrency transactional workloads. Enforces primary key, foreign key, and unique constraints with row-level locking and index-based reads/writes.
10. [Interactive Tables & Warehouses](https://docs.snowflake.com/en/user-guide/interactive)  
Specialized tables and warehouses for sub-second query latency at high concurrency. Designed for real-time dashboards, data APIs, and serving precomputed results with auto-refresh support.
11. [Snowflake Open Catalog](https://docs.snowflake.com/en/user-guide/opencatalog/overview)  
Managed Iceberg REST catalog service built on Apache Polaris. Provides centralized, secure read/write access to Iceberg tables across REST-compatible query engines.
12. [Semantic Views](https://docs.snowflake.com/en/user-guide/views-semantic/overview)  
Define curated business definitions with dimensions, facts, and metrics. Powers Cortex Analyst for consistent natural language querying.
13. [Snowpark API](https://docs.snowflake.com/en/developer-guide/snowpark/index)  
Build data pipelines, UDFs, and stored procedures in Python, Java, or Scala that run directly on Snowflake compute.
14. [pandas on Snowflake](https://docs.snowflake.com/en/developer-guide/snowpark/python/pandas-on-snowflake)  
Run pandas code at scale on Snowflake with minimal rewrites. Hybrid execution automatically routes operations to local pandas or the Snowflake engine based on data size.
15. [Snowpark Connect for Spark](https://docs.snowflake.com/en/developer-guide/snowpark-connect/snowpark-connect-overview)  
Run existing PySpark DataFrame and Spark SQL workloads directly on Snowflake compute without managing a Spark cluster. Supports interactive development and batch submission via Snowpark Submit.
16. [Tasks & Streams](https://docs.snowflake.com/en/user-guide/tasks-intro)  
Schedule and orchestrate SQL and procedural logic with tasks. Capture change data with streams for incremental processing.
17. [dbt Projects on Snowflake](https://docs.snowflake.com/en/user-guide/data-engineering/dbt-projects-on-snowflake)  
Deploy, execute, and schedule dbt Core projects natively in Snowflake as versioned DBT PROJECT objects. Includes Workspaces integration, Snowflake CLI support, task-based scheduling, and CI/CD pipelines.


## Cortex AI & Generative AI

1. [Snowflake Cortex AI Overview](https://docs.snowflake.com/en/guides-overview-ai-features)  
Overview of Snowflake's AI capabilities including Cortex AI Functions, Cortex Analyst, Cortex Search, Cortex Agents, and Snowflake Intelligence.
2. [Cortex AI Functions](https://docs.snowflake.com/en/user-guide/snowflake-cortex/llm-functions)  
Serverless AI functions that run directly in SQL: AI_COMPLETE, AI_EXTRACT, AI_CLASSIFY, AI_SENTIMENT, AI_SUMMARIZE, AI_TRANSLATE, AI_EMBED, AI_REDACT, AI_AGG, and more.
3. [Cortex Analyst](https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-analyst)  
Natural language to SQL for business users. Ask questions in plain English and get answers from your structured data.
4. [Cortex Search](https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-search/cortex-search-overview)  
Vector and hybrid search service for building RAG applications and searchable knowledge bases over unstructured data.
5. [Cortex Agents](https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agent)  
Build agentic AI workflows that orchestrate across structured and unstructured data sources using tools like Cortex Analyst and Cortex Search.
6. [Snowflake-Managed MCP Server](https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp)  
Expose Cortex Analyst, Cortex Search, Cortex Agents, SQL execution, and custom UDFs/procedures to external AI agents via the Model Context Protocol (MCP) standard. Includes OAuth authentication and RBAC for tool discovery and invocation.
7. [Cortex Fine-Tuning](https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-finetuning)  
Customize LLMs on your own data using parameter-efficient fine-tuning (PEFT). Supports Llama and Mistral model families with a fully managed, serverless workflow.
8. [Snowflake Intelligence](https://docs.snowflake.com/en/user-guide/snowflake-intelligence)  
Natural language analytics for business users. Build "data agents" that answer questions and take actions across platforms.
9. [AI Observability](https://docs.snowflake.com/en/user-guide/snowflake-cortex/ai-observability)  
Evaluate and trace generative AI applications using LLM-as-a-judge metrics (accuracy, groundedness, relevance), side-by-side comparison of configurations, and step-level execution tracing for debugging.


## Machine Learning

1. [Snowflake ML Overview](https://docs.snowflake.com/en/developer-guide/snowflake-ml/overview)  
End-to-end ML platform for feature engineering, model training, deployment, and monitoring — all on governed data with CPU and GPU compute.
2. [Feature Store](https://docs.snowflake.com/en/developer-guide/snowflake-ml/feature-store/overview)  
Define, manage, and discover ML features with automatic incremental refresh from batch and streaming sources. Integrates with Model Registry for inference-time feature retrieval.
3. [ML Jobs](https://docs.snowflake.com/en/developer-guide/snowflake-ml/ml-jobs/overview)  
Run ML workloads on Snowflake compute pools from any environment (VS Code, PyCharm, Jupyter). Dispatch functions, files, or modules to Container Runtime with GPU support.
4. [Experiments](https://docs.snowflake.com/en/developer-guide/snowflake-ml/experiments)  
Track and compare model training runs — log parameters, metrics, and artifacts, then evaluate results side-by-side in Snowsight to select the best model.
5. [Model Registry](https://docs.snowflake.com/en/developer-guide/snowflake-ml/model-registry/overview)  
Log, version, and serve ML models as first-class Snowflake objects. Supports scikit-learn, XGBoost, PyTorch, TensorFlow, Hugging Face, MLFlow, and custom models with warehouse or SPCS inference.
6. [ML Observability](https://docs.snowflake.com/en/developer-guide/snowflake-ml/model-registry/model-observability)  
Monitor production model performance, data drift, and volume over time. Set alerts on thresholds and compute Shapley values for model explainability.
7. [ML Lineage](https://docs.snowflake.com/en/developer-guide/snowflake-ml/ml-lineage)  
Trace end-to-end data flow from source tables through feature views, datasets, and models. Enables reproducibility, compliance, and debugging across the ML lifecycle.
8. [Datasets](https://docs.snowflake.com/en/developer-guide/snowflake-ml/dataset)  
Immutable, versioned snapshots of training data with native connectors for PyTorch, TensorFlow, and Snowpark ML. Supports distributed data loading and fsspec integration.


## Governance & Security

1. [Snowflake Horizon Catalog](https://docs.snowflake.com/en/user-guide/snowflake-horizon)  
Unified governance and discovery layer for data, apps, and models. Provides metadata, lineage, sensitive data classification, and access controls across Snowflake and external engines.
2. [Data Governance Overview](https://docs.snowflake.com/en/guides-overview-govern)  
Central guide to governance features: data quality monitoring (DMFs), column-level security (masking policies), row access policies, object tagging, tag-based masking, sensitive data classification, access history, and object dependencies.
3. [Trust Center](https://docs.snowflake.com/en/user-guide/trust-center/overview)  
Evaluate and monitor security risks in your account. Includes CIS benchmark scanners, threat intelligence, MFA enforcement checks, and anomalous access detection.
4. [Securing Snowflake](https://docs.snowflake.com/en/guides-overview-secure)  
Network policies, network rules, private connectivity, session policies, SCIM provisioning, and role-based access control (RBAC).
5. [Data Clean Rooms](https://docs.snowflake.com/en/user-guide/cleanrooms/introduction)  
Secure, isolated environments for privacy-preserving data collaboration. Combine and analyze data across organizations without exposing raw records.
6. [Compliance Center](https://trust.snowflake.com/)  
Self-service portal to download Snowflake's security certifications and compliance reports — SOC 1/2, ISO 27001, FedRAMP, HITRUST, PCI-DSS, GxP, C5, IRAP, CJIS, TISAX, and more.


## Cost Management

1. [Managing Cost in Snowflake](https://docs.snowflake.com/en/user-guide/cost-management-overview)  
End-to-end guide covering cost concepts, exploring costs in Snowsight, chargebacks, budgets, resource monitors, and optimization strategies.
2. [Controlling Cost (Budgets & Resource Monitors)](https://docs.snowflake.com/en/user-guide/cost-controlling)  
Set monthly spending limits with budgets (serverless + warehouses) or resource monitors (warehouses only). Configure alerts and auto-suspend at custom thresholds.
3. [ACCOUNT_USAGE Schema](https://docs.snowflake.com/en/sql-reference/account-usage)  
Query 1 year of historical usage data — warehouse metering, query history, storage, logins, and more — from the shared SNOWFLAKE database.
4. [Exploring Overall Cost](https://docs.snowflake.com/en/user-guide/cost-exploring-overall)  
Pre-built Snowsight dashboards and sample queries using ORGANIZATION_USAGE and ACCOUNT_USAGE views to analyze credit consumption across accounts.


## Snowflake Status and Release Notes

1. [Release Notes](https://docs.snowflake.com/en/release-notes)  
Weekly updates on new features, behavior changes, and deprecations.
2. [Snowflake Status Page](https://status.snowflake.com/)  
Real-time and historical data on system performance.


## Snowflake Marketplace

1. [Snowflake Marketplace](https://app.snowflake.com/marketplace)  
Discover and access 2,700+ listings from 670+ providers, including datasets, APIs, Native Apps, and AI products across finance, healthcare, geospatial, and more.


## Industry Solutions

1. [Industry Solutions Overview](https://www.snowflake.com/en/solutions/industries/)  
Landing page for Snowflake's industry-specific solutions, use cases, and partner ecosystems.
2. [Advertising, Media & Entertainment](https://www.snowflake.com/en/solutions/industries/advertising-media-entertainment/)  
Break down data silos across publishers, advertisers, and adtech platforms. Covers audience segmentation, identity resolution, campaign measurement, and content optimization.
3. [Financial Services](https://www.snowflake.com/en/solutions/industries/financial-services/)  
Unified data platform for banking, insurance, capital markets, and payments. Supports risk analytics, fraud detection, regulatory compliance, and secure data collaboration.
4. [Healthcare & Life Sciences](https://www.snowflake.com/en/solutions/industries/healthcare-and-life-sciences/)  
Build an AI and data foundation grounded in industry standards (HL7/FHIR, OMOP, FAIR, GxP, TEFCA) on HIPAA-eligible infrastructure. Unlock insights across multimodal data to improve patient outcomes, accelerate research, optimize supply chains, and reduce costs while meeting strict compliance.
5. [Manufacturing](https://www.snowflake.com/en/solutions/industries/manufacturing/)  
Connect supply chain, IoT, and operational data for demand forecasting, quality analytics, predictive maintenance, and smart factory initiatives.
6. [Retail & Consumer Goods](https://www.snowflake.com/en/solutions/industries/retail-consumer-goods/)  
Unify point-of-sale, inventory, and customer data for demand planning, personalization, supply chain visibility, and omnichannel analytics.
7. [Technology](https://www.snowflake.com/en/solutions/industries/technology/)  
Data infrastructure for SaaS, platform, and technology companies. Covers product analytics, usage-based billing, data monetization, and customer 360.
8. [Telecom](https://www.snowflake.com/en/solutions/industries/telecom/)  
Consolidate network, subscriber, and usage data for churn prediction, network optimization, 5G analytics, and personalized customer experiences.
9. [Public Sector](https://www.snowflake.com/en/solutions/industries/public-sector/)  
FedRAMP-authorized platform for government and education. Supports citizen services, fraud detection, public health surveillance, and cross-agency data sharing.
10. [Travel & Hospitality](https://www.snowflake.com/en/solutions/industries/travel-hospitality/)  
Unify booking, loyalty, and operational data for revenue management, personalized guest experiences, and real-time demand forecasting.
11. [Cybersecurity](https://www.snowflake.com/en/solutions/departments/cybersecurity/)  
Use Snowflake as a security data lake for detection and response, threat hunting, cloud security management, and compliance. Integrates with SIEM partners to replace or augment legacy security tooling.
12. [Marketing](https://www.snowflake.com/en/solutions/departments/marketing/)  
Build Customer 360 profiles, modernize CDPs, and maximize marketing ROI. Covers identity resolution, audience segmentation, campaign measurement, and privacy-safe data collaboration.
13. [Finance](https://www.snowflake.com/en/solutions/departments/finance/)  
Unify financial data for improved reporting, forecasting, and payment integrity. Provides real-time insights across budgeting, planning, and revenue analytics to support data-driven finance operations.
14. [Information Technology](https://www.snowflake.com/en/solutions/departments/information-technology/)  
Simplify IT operations, reduce infrastructure costs, and boost organizational agility. Consolidate data management, enhance security visibility, and accelerate productivity across the enterprise.
