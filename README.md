# My Azure

- [My Azure Projects](#my-azure-projects)
  - [Project 10](#project-10)
  - [Project 9](#project-9)
  - [Project 8](#project-8)
  - [Project 7](#project-7)
  - [Project 6](#project-6)
  - [Project 5](#project-5)
  - [Project 4](#project-4)
  - [Project 3](#project-3)
  - [Project 2](#project-2)
  - [Project 1](#project-1)
- [Azure Fuctions](#azure-fuctions)
- [Deploy a Spring Boot app to Azure](#deploy-a-spring-boot-app-to-azure)
- [Azure DevOps](#azure-devops)

## My Azure Projects

### Project 10

<!-- MOH -->

Worked on many C# .NET Blazor/Web API applications.

- Built a web app for Settlement Process Automation & Modernization.
- Process Transformation: Led the digital transformation of a manual, Excel-based settlement letter process into a modern, automated web application, significantly reducing operational risk and processing time.
- Full Stack Architecture: Engineered a robust service-oriented backend using C# .NET Core and Entity Framework, coupled with a rich, responsive frontend interface built with Blazor, DevExpress, JavaScript, and Bootstrap.
- Cloud & Data Implementation: Designed the persistence layer using Azure MS SQL Server for transactional data and integrated Azure Blob Storage to securely store and retrieve generated settlement documents and static files.
- DevOps & Security: Established Azure DevOps CI/CD pipelines to enforce automated quality gates, including unit and integration testing and CVE vulnerability scans, ensuring a secure and compliant deployment process.
- Agile Delivery: Managed the development lifecycle using Git, Azure Boards (Work Items), and structured Pull Request (PR) reviews to ensure code quality and alignment with business requirements.

### Project 9

<!-- MOH -->

Modernized multiple legacy web applications.

- Legacy Transformation: Led the end-to-end modernization of legacy systems into a scalable, cloud-native architecture, directly addressing technical debt and improving system reliability.
- Backend Development: Architected and developed robust backend services using C# .NET Core and Entity Framework, ensuring high performance, security, and seamless data integrity.
- Frontend Implementation: Designed and built a responsive, user-friendly interface using Blazor, DevExpress, JavaScript, and Bootstrap, enhancing user experience across devices.
- Cloud & DevOps: Established comprehensive Azure DevOps pipelines for CI/CD, automating builds, unit and integration testing, and CVE vulnerability scanning to ensure secure and rapid deployment. Managed agile workflows through Git, Work Items, and rigorous Pull Request reviews.
- Data & Storage: Managed the data layer using Azure MS SQL Server for relational data and implemented Azure Blob Storage for secure management of static assets and file uploads.
- Reporting: Integrated PowerBI to generate dynamic reports and visualizations, providing stakeholders with actionable data insights.

### Project 8

<!-- SatasCan -->

Authentication Architecture Update:

Adapted to upstream changes in the app's authentication system, transitioning from OpenID to OAuth 2.0. Updated Kubernetes (K8s) manifests, secrets, and ingress configurations accordingly. Modified Azure AD settings and redirect URIs to align with the new auth flow, ensuring seamless and secure user authentication under the new architecture.

### Project 7

<!-- RBC -->

Designed and implemented a web app with APIs and deployed to Azure

- Developed and deployed a cloud-native web application to Azure, leveraging modern DevOps practices and microservices architecture.
- Designed and implemented RESTful APIs using Java, integrating with Azure SQL, Redis, and Docker Compose for local orchestration.
- Built and automated CI/CD pipelines using Jenkins and shell scripts to deploy application components to Azure Cloud environments.
- Performed unit and integration testing using Python pytest and automated test execution as part of the deployment pipeline.

### Project 6

Created Full Stack REST APIs (backend) and VUE (front-end) apps to manage Dask Kubernetes Clusters and deployed to Azure

<!-- for Hatfield-->

- Coded the functions to manage Dask Kubernetes Clusters with Go and Python.
- Monitored the Clusters with Kubectl and dashboard.
- Programmed REST APIs with Go.
- Built the UI with VUE and Vuetify.
- Containerized the backend API app and UI app with Docker, managed with Azure ACR repository, deployed to Azure AKS and then exposed the API to a public IP.

### Project 5

Created REST APIs for a new web app and deployed to Azure Cloud

<!-- for RBC / a large bank -->

- Programmed REST APIs with Java, Spring Boot, Hibernate, Azure SQL, GitHub, Gradle, Redis, Docker, JSON, Postman and sidecar.
- Performed unit tests with Mockito test framework.
- Used pytest test framework to build the integration tests.
- Deployed to Azure with Kyvos Kubernetes and Jenkins pipelines.
- Onboard the endpoints to the Apigee API gateway.
- Monitored with Splunk and Dynatrace.

### Project 4

Built a new web app and a new tablet app and deployed to Azure Cloud

<!-- for Ministry of Transportation and Mistry of Labour, Immigration, Training and Skills Development -->

- For the offline mode tablet device app, built the backend REST APIs with .Net, C#, LINQ, Entity Framework; created the responsive front-end UI with .NET MAUI, Telerik UI and DevTools to follow the Zeplin wireframes; and persisted data in SQLite.
- For the online web app, created the backend REST APIs with .Net, C#, LINQ, Entity Framework; built the responsive front-end UI with Blazor, Telerik UI and DevTools to follow the Zeplin designs; and persisted data in Azure SQL database.
- Performed the unit testing with NUnit and XUnit.
- Automated the integration testing with Postman and Azure Data Studio.
- Managed code repositories with Git and Azure DevOps.

### Project 3

Created a progressive web application with Azure DevOps

<!-- for CBSA / a federal government client -->

- Built a new web application with React, TypeScript, Material UI, Router, i18n, axios, formik, lodash and S3 on front-end, Node.js, winstone, dotenv, AWS Lambda functions, Amazon API Gateway, Aurora PostgreSQL on middle and back end.
- Used CI/CD pipelines for different projects with Azure DevOps and AWS CloudFormation, CloudBuild, CodeCommit, CodePipeline.
- Created UI/UX mockups and wireframes with Balsamiq Studio.
- Created an Azure DevOps organization and an Azure DevOps project; Integrated Azure Repos with the DevOps project and Azure boards; Created a CI/CD pipeline for the React application (Build, staging and production); Used Azure test and feedback tool to identify and create work items (bugs) and manual testing with Azure Test Plans; Created a dashboard for an overview of the DevOps project.

### Project 2

Built a knowledge-based ontology graph database application

<!-- for GAC / a federal client -->

- Converted relational data model to Graph data model and imported to Neo4j.
- Used Python NLP libraries and Azure Cognitive Services APIs to analyse data, extracted entities, key phrases, and categories, then do sentiment analysis with data science algorithms in Jupyter Notebook.
- Visualized the ontology knowledge graphs with Neo4j Bloom and search phrases.

### Project 1

<!-- for Canada Post / Accenture -->

On-Premises Data Platform Migration to Azure HDInsight

- **Objective**: Led the migration of an on-premises data platform to Azure HDInsight, transforming a legacy system that included **DB2**, **SAP**, and **Enterprise Data Warehouse (EDW)** applications into a modern cloud-based architecture.
- **Technology Stack**: Azure HDInsight, **Azure SQL**, **Azure Data Factory** (ADF), DB2, SAP.
- **Key Responsibilities**:
  - Architected the migration process, ensuring seamless transition of data and applications from the legacy system to the cloud.
  - Utilized **Azure Data Factory** for orchestrating and automating the migration of large-scale data from on-premises databases to **Azure SQL**.
  - Optimized data pipelines to ensure efficient data flow and integration between legacy systems and the new Azure-based infrastructure.
  - Ensured data consistency, reliability, and performance through thorough testing and validation post-migration.
  - Collaborated with cross-functional teams to implement best practices and maintain the integrity of critical data throughout the migration process.

## Azure Fuctions

[Quickstart: Azure Functions (Windows 11 + Node.js)](AzFunctions/AzFuncHelloWorld.md)

## [Deploy a Spring Boot app to Azure](Deploy_SpringBoot_2_Azure.md)

## [Azure DevOps](AzureDevOps/README.md)
