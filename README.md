# granja_Google_ML_Engineer
Studying for the GCP Machine Learning Enginerr Professional certification

## Learning Paths

### [Machine Learning Engineer Learning Path](https://www.cloudskillsboost.google/paths/17)
[Training path for ML Engineer](https://cloud.google.com/training/machinelearning-ai)
### [Data Analyst Learning Path](https://www.cloudskillsboost.google/paths/18)
[Training path for Data Analyst](https://cloud.google.com/training/data-engineering-and-analytics)

- Teaches how to use Looker!
### Machine Learning Advanced Solutions Lab
[Advanced Solutions Lab (For Teams!)](https://cloud.google.com/asl)<br>
The Advanced Solutions Lab is an immersive training program that provides a unique opportunity for technical teams to learn from Google's machine learning experts in a dedicated, collaborative space on Google Campus.

### Looker Partner Connectors

#### Notable Partner Connectors
Not all data sources are hosted on Google tools or within the Google Marketing Platform. To bridge this gap, several partner connectors can be used to connect to other data sources. Here are four notable partner connectors:

#### Supermetrics
Connects to over 70 different marketing analytics tools and data sets. Most of its connectors are live connections, although some use snapshot data. Supermetrics can work around Universal GA sampling and provide fields not available in Google's built-in connector. It can also perform data transformations, join data, and aggregate data from multiple accounts at once. Data can be sent to Looker Studio, Google Sheets, or BigQuery.

#### Power My Analytics (PMA)
Offers 40+ connections, with connectors using a data warehouse approach. This makes loading data quicker and faster compared to live connections. PMA can send data to Looker Studio, Google Sheets, and BigQuery as well.

#### Funnel.io
A warehouse-based connector with many data sources available. It includes built-in data transformation features, allowing you to perform resource-intensive transformations before connecting to Looker Studio. Funnel.io supports additional destinations like BigQuery, Snowflake, and Tableau.

#### Dataddo
A newer player in the market with 90+ connectors. It can be a live connection or use a snapshot feature for warehouse connections. Dataddo includes built-in drag-and-drop data transformation features and supports various data destinations, including Looker Studio, Redshift, Power BI, and Tableau.

### Looker Studio Additional Resource
#### Tutorials and Courses
**Supermetrics**<br>
https://supermetrics.com/<br>
https://lookerstudio.google.com/u/0/reporting/6a211d82-26ef-4a4d-920c-7d5a2db2c279/page/MLdGB<br>
**Looker Studio Master Class by Ahmad Kanani**<br>
https://www.youtube.com/@siakanani/videos<br>





#### Function List
https://support.google.com/looker-studio/table/6379764?hl=en<br>
#### Google RE2 Regex Syntax
https://github.com/google/re2/wiki/Syntax<br>
https://support.google.com/a/answer/1371417?hl=en<br>

#### Templr
Tool that helps build your own custom visualizations in Google Data Studio using HTML, CSS, and JavaScript.<br>
https://www.templr.pro/<br>
https://www.templr.pro/article/getting-started-with-templr-pro

#### Coolors
Tool to generate color palletes<br>
https://coolors.co/

#### Icons for Looker Studio
Tools to generate or download icons for free<br>
https://icons8.com/<br>
https://www.flaticon.com/<br>


## Google Code Samples

### [Detect sentiment](https://cloud.google.com/natural-language/docs/samples/language-quickstart?hl=en)
Perform sentiment analysis by using client libraries [Link](https://cloud.google.com/natural-language/docs/sentiment-analysis-client-libraries)
### DELETE LATER
Load a CSV file from Cloud Storage using an explicit schema [Link](https://cloud.google.com/bigquery/docs/samples/bigquery-load-table-gcs-csv?hl=en)

## Google Cloud Platform Repo
git clone https://github.com/GoogleCloudPlatform/training-data-analyst

## Definitions by Coursera

The US National Institute of Standards and Technology created it, although, there is nothing US specific about it. Here it is, cloud computing is a way of using I.T. that has these five equally important traits.

1. *First, you get computing resources on-demand and self-service. All you have to do is use a simple interface and you get the processing power, storage, and network you need, with no need for human intervention.*
2. *Second, you access these resources over the net from anywhere you want.*
3. *Third, the provider of those resources has a big pool of them and allocates them to customers out of that pool. That allows the provider to get economies of scale by buying in bulk and pass the savings on to the customers. Customers don't have to know or care about the exact physical location of those resources.*
4. *Fourth, the resources are elastic. If you need more resources you can get more, rapidly. If you need less, you can scale back.*
5. *Last, the customers pay only for what they use or reserve as they go. If they stop using resources, they stop paying.*


## OPEN SOURCE

**Cloud Dataproc** offers the open source big data environment Hadoop, as a managed service.
**TensorFlow:** Machine learning open source software library developed inside Google, is at the heart of a strong open source ecosystem.
**Kubernetes:** gives customers the ability to mix and match microservices running across different clouds
**Google Stackdriver:** lets customers monitor workload across multiple cloud providers.


## FACTS

### According to public stimations
```
Google's network carries as much as 40% of the world's Internet traffic every day.
100,000 km of fiber cable and 8 subsea cables
```
### ML Compute Power
```
The requiring computing power for ML models was doubling every 2 years until 2012.
From 2013 to now requiring computing power for ML models was doubling every 3.5 months!
```
### ML Expectations
```
1. Collecting data is often the longest and hardest part of an ML project, and the one most likely to fail.
2. Manual analysis helps you fail fast and try new ideas in a more agile way.
3. To build a good ML model, you have to know your data. If you do not know analytics you cannot do ML.
4. ML is a journey towards automation and scale.
5. In ML it is necessary to build a Streaming Pipeline in addition to a Batch Bipeline.
6. The performance metrics you care about change between training and predictions as well. During training, the key
performance aspect you care about is scaling to a lot of data, distributed training if you will. During prediction, 
though, the key performance aspect is speed of response and high QPS.
7. Lots of ML frameworks exist for training, but not so many are equaly capable operationalization.
```
### ML Reality
```
1. Most ML value comes along the way.
2. ML improves almost everythign it touches.
3. ML is hard, so it is hard for competitors too.
4. ML is a great differentiator. 
```
### ML Practicioners's Pain Points
```
1. Keeping track of different versions.
2. Controllig the experiment space.
3. Pinpointing the best-performing model.
4. Collaboration is not easy.
```
### ML Strategy
```
Simple ML and more data > Fancy ML and small data.
```
### ML top reasons to failure
By International Data Corporation on May 2020
```
1. Lack of staff with the right expertise.
2. Lack of production-ready data.
3. Lack of and integrated development environment.
```
### ML three phases lifecycle
```
1. Discovery Phase
2. Development Phase
3. Deployment Phase
```
### Top 13 ML Pitfalls
1. Training your own ML algorithm would be faster than writting the software.

2. Start creating or using MLs without data analysis.
- It is necessary a Data Strategy first before a Machine Learning strategy. 
- "There is no Machine Learning without data, and there is no Machine Learning success without good data" by Robie Allen
3. Assume the data is ready to use.
- If you can't make a histogram chart of your data neither can your ML. This is because most MLs are usually making many plots and performing regression on them.

4. Not keeping humans in the loop.

5. Product launch focused on the ML algorithm only.

6. Optmizing ML model for wrong things.

7. Is the ML algorithm really improving things in the real world.

8. Using a pre-trained algorithm vs building your own.

9. Training ML algorithms only once.
- ML Algorithms must be trained more than once. Training requires resources.

10. Trying to design your own perception or NLP algorithm.

11. Trying to jump to a fully machine learned, automated end-to-end, auto-magic everything solution.
- Everyone wants to make this leap. However, it usually doesn't lead to great products or organization outcomes. Google has seen it internally and within their partner organizations.

12. Very high expectations of success
- 85% of Machine Learning Projects Fail
- [According to Gartner](https://www.gartner.com/en/newsroom/press-releases/2018-02-13-gartner-says-nearly-half-of-cios-are-planning-to-deploy-artificial-intelligence) it is predicted that through 2022, 85 percent of AI projects will deliver erroneous outcomes due to bias in data, algorithms or the teams responsible for managing them.

13. Thinking ML will completely exchange the human workforce.
- That's a very high expectation for an ML system to meet. You should think about ML as a way to expand or scale the impact of your people, not as a way of completely removing them.   

14. An ML model will bring higher returns very quick.
- Can you guess how well a company will do with just 1 or 2 quarters of data? Probably not because it takes at least a full year of a public company's returns information for investors and market to better access how well a company is doing now and two full years of data to forecast its future performance.
### Designing Adaptable ML Systems
```
1. Recognize the ways that a model is dependent on data.
2. Make cost-conscious engineering decisions.
3. Know when to roll back a model to an earlier version.
4. Debug the causes of observed model behavior.
5. Implement a pipeline that is immune to one type of dependency.
```
### ML Mismanaged Dependencies
```
1. Can be expensive.
2. Low model accuracy.
3. Long debugging.
```
### ML Technical Debt
```
1. Multi-functional teams: Requires a lot of experts in different fields. 
2. Experimental nature: Needs constant experimentation.
3. Testing complexity: It is more complex than testing other systems
4. Deployment complexity: Requires multi-step pipeline.
5. Model decay: Data is constantly changing, so it is important to monitor otherwise performance can drop.
```
### ML Algorithm Assumptions
```
1. Instances are generated at random according to some probability distribution D.
2. Instances are independent and identically distributed.
3. That D is stationary with fixed distributions.
```
### ML Models' Types of Drifts
```
1. Data Drift: A change in P(X) is a shift in the model's input distribution.
2. Concept Drift: A change in P(Y|X) is a shift in the actual relationship between the model's inputs and the outputs.
3. Prediction Drift: A change in P(Ÿ|X) is a shift in the model's predictions.
4. Label Drift: A change in P(Y Ground Truth) is a shift in the model's output or label distribution.
```
NOTE: Data Drift, Feature Drift, Population, and Covariate Shift describe changes in the data distribution of inputs.<br>
### ML Scalability Meaning.
1. Accelerators: GPUs, TPUs, et cetera
2. Disks
3. Skillsets: software engineers, researchers, data engineers, data analysts, data scientists, different skillsets
4. Teams across the org:<br>
4.1. Teams that are gonna be building the experiments.<br>
4.2. Teams that are gonna be using the experiments.<br>
4.3. Teams that are gonna be monitoring the machine learning models.<br>


### Enterprise Data
```
90% of Enterprise data is unstructured such as emails, video footage, texts, reports, catalogs,
fashion show, events, news, etc.
```
### Renewable Energy
```
- Google is one of the world's largest corporate purchasers of wind and solar energy.
- Google has been a hundred percent carbon neutral since 2007.
- Its data centers energy source will shortly reach a hundred percent renewable energy.
```

### Data quality attributes
```
Accuracy of Data
Consistency of Data
Timeliness of Data
Completenes of Data
```

### Payments and reliability
```
Google was the first major Cloud provider to deliver per second billing for its IaaS Compute offering.

Google gives customers the ability to run their applications elsewhere, 
if Google becomes no longer the best provider for their needs
```

## BILLING
GCP provides four tools to help with billing: 
**Budgets and Alerts:** You can define budgets either per billing account or per GCP project. A budget can be a fixed limit or you can tie it to another metric.
**Billing Exports:** lets you store detailed billing information in places where it's easy to retrieve for more detailed analysis, such as a BigQuery dataset or a Cloud storage bucket.
**Reports:** is a visual tool in the GCP console that allows you to monitor your expenditure.
**Quotas:** designed to prevent the over-consumption of resources, whether because of error or malicious attack. There are two types of quotasL rate quotas and allocation quotas
- **Rate Quotas:** reset after a specific time. For example, by default, the Kubernetes Engine service sets a quota of a 1000 calls to its API from each GCP project every 100 seconds. After that 100 seconds, the limit is reset.
- **Allocation Quotas:** govern the number of resources you can have in your projects. For example, by default, each GCP project has a quota allowing it 
no more than five Virtual Private Cloud networks. Although projects all start with the same quotas, you can change some of them by requesting an increase from Google Cloud support.

## CLOUD SECURITY
- Google enables **hardware encryption support** in hard drives and SSDs. ```That's how Google achieves encryption at rest of customer data.```
- Google services that want to make themselves available on the Internet register themselves with an infrastructure service called the **Google Front End**, which ```checks incoming network connections for correct certificates and best practices.```
- The GFE also additionally, applies protections against denial of service attacks. ```The sheer scale of its infrastructure, enables Google to simply absorb many denial of service attacks, even behind the GFEs.```
- Google also has **multi-tier, multi-layer denial of service protections** that further reduce the risk of any denial of service impact.
- Inside Google's infrastructure, **machine intelligence and rules warn of possible incidents**.
- Google conducts **Red Team exercises**, ```simulated attacks to improve the effectiveness of its responses.```
- Google aggressively **limits and actively monitors the activities of employees** who have been granted administrative access to the infrastructure.
- To **guard against phishing attacks** against Google employees, employee accounts including mine require use of **U2F compatible security keys**.
- To help ensure that code is as secure as possible Google stores its **source code centrally** and requires **two-party review of new code**.
- Google also ```gives its developers libraries that keep them from introducing certain classes of security bugs.```
- Externally, Google also runs a **vulnerability rewards program**, where we ```pay anyone who is able to discover and inform us of bugs in our infrastructure or applications.```

### GCP Hierarchy

```Policies are inherited downwards in the hierarchy.```

- All Google Cloud platform resources **belong to a project**.
- **Projects are the basis for enabling and using GCP** services like managing APIs, enabling billing and adding and removing collaborators and enabling other Google services.
- ```**Each project is a separate compartment** and each resource belongs to exactly one.```
- **Projects can have different owners and users**
- **Projects are built separately and they're managed separately.**
- Each GCP project **has a name and a project ID** that you assign.
- The **project ID** is ```a permanent, unchangeable identifier``` and it has to be unique across GCP.
- You use project IDs in several contexts to tell GCP which project you want to work with.
- On the other hand, **project names** are ```for your convenience and you can assign them```.
- GCP also assigns each of your projects a unique project number and you'll see a display to you in various contexts.

## PERMISSIONS & ROLES

### Roles and permissions

- On the Navigation menu (Navigation menu), click IAM & Admin. This opens a page that contains a list of users and specifies permissions and roles granted to specific accounts.

[Roles Documentation](https://cloud.google.com/iam/docs/understanding-roles/#primitive%5C_roles)

#### Basic Roles
|**Role Name**|**Title**|**Permissions**|
|-------------|---------|---------------|
|roles/viewer	|Viewer   |Permissions for read-only actions that do not affect state, such as viewing (but not modifying) existing resources or data.|
|roles/editor	|Editor	  |All viewer permissions, plus permissions for actions that modify state, such as changing existing resources.<br>**Note:**<br>*The Editor role contains permissions to create and delete resources for most Google Cloud services. However, it does not contain permissions to perform all actions for all services. For more information about how to check whether a role has the permissions that you need, see [Role types](https://cloud.google.com/iam/docs/roles-overview#role-types).*|
|roles/owner	|Owner	  |All Editor permissions and permissions for the following actions:<br>- Manage roles and permissions for a project and all resources within the project.<br>- Set up billing for a project.<br>**Note:**<br>- *Granting the Owner role at a resource level, such as a Pub/Sub topic, doesn't grant the Owner role on the parent project.*<br>- *Granting the Owner role at the organization level doesn't allow you to update the organization's metadata. However, it allows you to modify all projects and other resources under that organization.*<br>- *To grant the Owner role on a project to a user outside of your organization, you must use the Google Cloud console, not the gcloud CLI. If your project is not part of an organization, you must use the Google Cloud console to grant the Owner role.*|

## APIs

### [Google APIs Explorer](https://developers.google.com/apis-explorer/#p/dialogflow/v3/)

The Google APIs Explorer is a tool available on most REST API reference documentation pages that lets you try Google API methods without writing code. The APIs Explorer acts on real data, so use caution when trying methods that create, modify, or delete data. For more details, read the [APIs Explorer documentation](https://developers.google.com/explorer-help).

### GCP [API Design Guide](https://cloud.google.com/apis/design/)
This is a general design guide for networked APIs. It has been used inside Google since 2014 and is the guide that Google follows when designing [Cloud APIs](https://cloud.google.com/apis/docs/overview) and other [Google APIs](https://github.com/googleapis/googleapis). This design guide is shared here to inform outside developers and to make it easier for us all to work together.

[Cloud Endpoints](https://cloud.google.com/endpoints/docs/grpc) developers may find this guide particularly useful when designing gRPC APIs, and we strongly recommend such developers use these design principles. However, we don't mandate its use. You can use Cloud Endpoints and gRPC without following the guide.

This guide applies to both REST APIs and RPC APIs, with specific focus on gRPC APIs. gRPC APIs use Protocol Buffers to define their API surface and [API Service Configuration](https://github.com/googleapis/googleapis/blob/master/google/api/service.proto) to configure their API services, including HTTP mapping, logging, and monitoring. HTTP mapping features are used by Google APIs and Cloud Endpoints gRPC APIs for JSON/HTTP to Protocol Buffers/RPC [transcoding](https://cloud.google.com/endpoints/docs/transcoding).

This guide is a living document and additions to it will be made over time as new style and design patterns are adopted and approved. In that spirit, it is never going to be complete and there will always be ample room for the art and craft of API design.

### GCP Machine Learning Resources

[**Machine families resource and comparison guide**](https://cloud.google.com/compute/docs/machine-resource)

This document describes the machine families, machine series, and machine types that you can choose from to create a virtual machine (VM) instance with the resources you need. When you create a VM, you select a machine type from a machine family that determines the resources available to that VM. There are several machine families you can choose from and each machine family is further organized into machine series and predefined machine types within each series. For example, within the N2 series in the general-purpose machine family, you can select the n2-standard-4 machine type.

### GCP Regions and Zones

[**Regions and Zones**](https://cloud.google.com/compute/docs/regions-zones/)

Compute Engine resources are hosted in multiple locations worldwide. These locations are composed of regions and zones. A region is a specific geographical location where you can host your resources. Regions have three or more zones. For example, the us-west1 region denotes a region on the west coast of the United States that has three zones: `us-west1-a`, `us-west1-b`, and `us-west1-c`.

Resources that live in a zone, such as [virtual machine instances](https://cloud.google.com/compute/docs/instances) or zonal [persistent disks](https://cloud.google.com/compute/docs/disks), are referred to as zonal resources. Other resources, like [static external IP addresses](https://cloud.google.com/compute/docs/ip-addresses#reservedaddress), are regional. Regional resources can be used by any resource in that region, regardless of zone, while zonal resources can only be used by other resources in the same zone.

For example, to attach a zonal persistent disk to an instance, both resources must be in the same zone. Similarly, if you want to assign a static IP address to an instance, the instance must be in the same region as the static IP address.

Putting resources in different zones in a region reduces the risk of an infrastructure outage affecting all resources simultaneously. Putting resources in different regions provides an even higher degree of failure independence. This lets you design robust systems with resources spread across different failure domains.

Only certain resources are region- or zone-specific. Other resources, such as images, are global resources that can be used by any other resources across any location. For information on global, regional, and zonal Compute Engine resources, see [Global, Regional, and Zonal Resources](https://cloud.google.com/compute/docs/regions-zones/global-regional-zonal-resources).

## DATA

### Storage
Storage & Process Data depends on:<br>
- **Type of data**
- **Business need**

### Types of data
- **Unstructured (Relational Data)**
- **Structured Data (No-Relational Data)**

#### Unstructure Data
It is information stored in a non-tabular form such as documents images and audio files.<br>
**IMPORTANT:** *Cloud Storage is great for No-Relational Data.*

#### Structured Data
It is information stored in a non-tabular form. There are two types of such data: **transactional workloads** and **analytical workloads**.


## Data Engineering for Streaming Data

**Batch processing** is when the processing and analysis happens on a set of stored data.
- For example, `payroll and billing systems` that have to be processed on either a weekly or monthly basis.<br>
**Streaming data** is a flow of data records generated by various data sources. Streaming data processing means that the data is analyzed in near real-time and that actions will be taken on the data as quickly as possible.
- The processing of streaming data happens as the data flows through a system. This results in the analysis and reporting of events as they happen. An example would be `fraud detection` or `intrusion detection`.<br>

### 4Vs Problems
```
variety: Data can come in a variety of different sources and in various formats.
volume: The volume of data that varies from gigabytes to petabytes is not easy nor cheap to handle.
velocity: Data often needs to be processed in near-real time or late.
veracity: Data won't always be good quality and will come with some inconsistencies and uncertainties.
```

### Message-Oriented Architecture: IOT Devices Challenges
```
1. Data can be streamed from many different methods and devices.
2. It can be hard to distribute event messages to the right subscribers.
3. Data can arrive quickly and at high volumes
4. Ensuring services are reliable, secure, and perform as expected.
```

### Google Publisher/Subscriber (Pub/Sub)
[Pub/Sub Documentation](https://cloud.google.com/pubsub/docs/)

Pub/Sub is a distributed messaging service that can receive messages from a variety of device streams such as gaming events, IoT devices, and application streams. It ensures at-least-once delivery of received messages to subscribing applications, with no provisioning required. Pub/Sub’s APIs are open, the service is global by default, and it offers end-to-end encryption.

### Google Dataflow (ETL)
[Dataflow Documentation](https://cloud.google.com/dataflow/docs/)

Dataflow creates a pipeline to process both streaming data and batch data.
- “Process” in this case refers to the steps to: **extract**, **transform**, and **load data** **(ETL)**.<br>
Dataflow is a fully managed service for executing Apache Beam pipelines within the Google Cloud ecosystem.<br>
Dataflow is serverless and NoOps, which means No Operations.<br>
- A NoOps environment is one that doesn't require management from an operations team, because maintenance, monitoring, and scaling are automated.
- Serverless computing is a cloud computing execution model. This is when Google Cloud, for example, manages infrastructure tasks on behalf of the users. This includes tasks like: `resource provisioning`, `performance tuning`, and `ensuring pipeline reliability`.<br>
Dataflow is designed to be low maintenancemeans.
- It means that you can spend more time analyzing the insights from your datasets and less time provisioning resources to ensure that your pipeline will successfully complete its next cycles.

### Pipeline Design Questions
```
1. Will the pipeline code be compatible with both batch and streaming data, or will it need to be refactored?
2. Will the pipeline code software development kit (SDK) being used have all the transformations, mid-flight
aggregations and windowing?
3. Will the pipeline SDK be able to handle late data?
4. Are there existing templates or solutions that should be referenced?
```
### Process Pipelines (Apache Beam)
Popular soluton for pipeline design. It’s an open source, unified programming model to define and execute data processing pipelines, including ETL, batch, and stream processing.
```
1. Apache Beam is unified, which means it uses a single programming model for both batch and streaming data.
2. It’s portable, which means it can work on multiple execution environments, like Dataflow and Apache Spark,
among others.
3. It’s extensible, which means it allows you to write and share your own connectors and transformation libraries.
4. Apache Beam provides pipeline templates, so you don’t need to build a pipeline from nothing.
5. It can write pipelines in Java, Python, or Go.
6. The Apache Beam software development kit, or SDK, is a collection of software development tools in one
installable package. It provides a variety of libraries for transformations and data connectors to sources
and sinks.
7. Apache Beam creates a model representation from your code that is portable across many runners.
```

### Execution Engine (Dataflow)

#### Execution Engine Questions
```
1. How much maintenance overhead is involved?
2. Is the infrastructure reliable?
3. How is the pipeline scaling handled?
4. How can the pipeline be monitored?
5. Is the pipeline locked in to a specific service provider? 
```

### Dataflow task performed
When a job is received by Dataflow it does the following:
```
1. Graph Optimization
2. Work Scheduler
3. Auto-scaler
4. Auto-healing
5. Work rebalancing
6. Compute & Storage
```

### [Dataflow Templates](https://cloud.google.com/dataflow/docs/concepts/dataflow-templates)
`Steaming`, `Batching`, and `Utility`

[Pre-Built Templates](https://cloud.google.com/dataflow/docs/guides/templates/provided-templates)

**Streaming templates** are for processing continuous, or real-time, data.<br>
- Pub/Sub to BigQuery
- Pub/Sub to Cloud Storage
- Datastream to BigQuery
- Pub/Sub to MongoDB

**Batch templates**  are for processing bulk data, or batch load data.<br>
- BigQuery to Cloud Storage
- Bigtable to Cloud Storage
- Cloud Storage to BigQuery
- Cloud Spanner to Cloud Storage

**Utility templates** address activities related to bulk compression, deletion, and conversion.<br>
- Bulk compression of Cloud Storage files
- Firestore bulk deletion
- File format conversion


## BigQuery
It is a fully-managed data wherehouse.<br>
```Being fully managed means that bigquery takes care of the underlying infrastructure so you can focus on using SQL queries to answer business questions without worrying about deployment scalability and security.```

[BigQuery Usage Pricing](https://cloud.google.com/bigquery#section-5)

### BigQuey Export Schema
This article explains the format and schema of the data that is imported into BigQuery. The data used come from teh table: `data-to-insights.ecommerce.web_analytics`.

### Data Lake vs Data Wherehouse
**Data Lake** is just a pool of raw unorganized and unclassified data which has no specified purpose a data.<br>
**Data Wherehouse** contains structured and organized data which can be used for advanced querying.

## [BigQuery ML](https://cloud.google.com/bigquery-ml/docs)
BigQuery ML enables users to create and execute machine learning models in BigQuery by using standard SQL queries

[Tutorials](https://cloud.google.com/bigquery-ml/docs/tutorials)

[End-to-end user journey for each model](https://cloud.google.com/bigquery-ml/docs/reference/standard-sql/bigqueryml-syntax-e2e-journey)


## Vertex AI
It is a unified platform which means having one digital experience to create, deploy, and manage models over time, and at scale.<br>
1. Data Readiness
2. Feature Readiness
3. Training & Hyperparameter Tunning
4. Deployment & Model Monitoring

### Veterx AI interface does the following
1. Create a dataset and upload data.
2. Train an ML model on your data.
3. Upload and store your model in Vertex AI.
4. Deploy your trained model to an endpoint for serving predictions.
5. Send prediction requests to your endpoint.
6. Specify a prediction traffic split in your endpoint.
7. Manage your models and endpoints.

### Traditional Challenges
- Determining how to handle large quantities of data.
- Determining the right machine learning model to train the data.
- Harnessing the required amount of computing power.

### Production Challenges
- Scalability
- Monitoring
- Continuous Integration, Delivery and Deployment

### Usage Challenges
- Many tools require advanced coding skills.
- Take focus away from model configuration.
- No unified workflow.
- Difficulties finding tools.

## [Hyperparameter Tunning](https://cloud.google.com/vertex-ai/docs/training/hyperparameter-tuning-overview)

Hyperparameters are the variables that govern the training process itself. For example, part of designing a DNN is deciding how many hidden layers of nodes to use between the input and output layers, and how many nodes each hidden layer should use. These variables are not directly related to the training data. They are configuration variables. Note that parameters change during a training job, while hyperparameters are usually constant during a job.

### Resources
[Hyperparameter tuning in Cloud Machine Learning Engine using Bayesian Optimization](https://cloud.google.com/blog/products/ai-machine-learning/hyperparameter-tuning-cloud-machine-learning-engine-using-bayesian-optimization)

### Manage and Govern with Vertex AI
|**Feature Store**|**Model Registry**|**ML Metadata**|**Model Evaluation**|
|:----------------|:-----------------|:--------------|:-------------------|
|Shared and reuse ML features accross use cases.|Register, organize, track, and version your trained and deployed ML models.|Automatically track inputs or outputs of all components.|Iteratively run model evaluations on new datasets at scale.|
|Serve ML features at scale with low latency.|Govern the model launch process.|Query the metadata to help analyze, debug, and audit the performance.| Visualize and compare model evaluations to identify the best model for prod deployment.|
|Alleviate training serving skew.|Maintain model documentation and reporting.|Maintain model documentation and reporting.|Visualize, analyze, and compare detailed ML lineage.|Assess the performance of models on different slice and evaluated annotations.|


### [Using Hyperparameter Tunning](https://cloud.google.com/vertex-ai/docs/training/using-hyperparameter-tuning#aiplatform_get_hyperparameter_tuning_job_sample-python)

Hyperparameter tuning searches for the best combination of hyperparameter values by optimizing metric values across a series of trials. Metrics are scalar summaries that you add to your trainer, such as model accuracy. Hyperparameter tuning optimizes target variables that you specify, called hyperparameter metrics. Model accuracy, as calculated from an evaluation pass, is a common metric. Metrics must be numeric.

### Vertex Explainable AI
|**Provides robust, actionable explanations**|**Is built into multiple Vertex AI services**|**Is flexible, fast, and scalable**|
|:-------------------------------------------|:--------------------------------------------|:----------------------------------|
|Vertex Explainable AI integrates feature attributions into Vertex AI to show the most important features for specific predictions with Shapley, Integrated gradients, and eXplanation with Ranked Area Integrals (XRAI).|You can get explanations easily through Vertex AI Prediction, AutoML Table, and Vertex AI Workedbench.|Supports tabular, image, and text models from any ML framework. Fully managed, serverless, and significantly faster than open source.|

### [Vertex AI Vizier](https://cloud.google.com/vertex-ai/docs/vizier/overview)
It is a hyperparameter optmizer. Vertex AI Vizier is a **black-box optimization service** that helps you tune hyperparameters in complex machine learning (ML) models. When ML models have many different hyperparameters, it can be difficult and time consuming to tune them manually. Vertex AI Vizier optimizes your model's output by tuning the hyperparameters for you.

**Black-box optimization** is the optimization of a system that meets either of the following criteria:<br>
- Doesn't have a known [objective function](https://developers.google.com/machine-learning/glossary#objective-function) to evaluate.
- Is too costly to evaluate by using the objective function, usually due to the complexity of the system.

#### How to use Vertex AI Vizier
This page describes how to make API requests to Vertex AI Vizier by using Python.

Tutorial on how to use [Vertex AI Vizier](https://cloud.google.com/vertex-ai/docs/vizier/using-vizier) in Python


### Vertex AI Feature Store
It is managed cloud service for machine learning engineers and data scientists to store, serve, manage, and share machine learning features at scale.

- It is a centralized repository to organize, store, and serve machine learning features.
- It aggregates all the different features from different sources and updates them to make them available from a central repository.
- Upon engineers need to model something, they can use the features available in the Feature Store dictionary to build a dataset.

### Vertex AI Monitoring
|**Monitor and alert**|**Diagnose**|**Update the model**|
|:--------------------|:-----------|:-------------------|
|Monitor signals for model's predictive performance, and alert when those signals deviate.|Help identify the cause for deviation, for example, what changed, how, and how much.|Trigger model retraining pipeline or collect relevant training data to address performance degradation.|

### Vertex AI Experiments
Used to track, analyze, visualize, and compare ML experiments.<br>
1. Vary and track parameters and metrics as you experiment.
2. Organize Vertex AI Pipeline runs and compare their parameters, metrics, and artifacts.
3. Track steps and artifacts to capture the lineage of experiments.
4. Compare Vertex AI Pipeline against Vertex AI Workbench Notebook experiments.

### Vertex AI TensorBoard
Based on the OpenSource TensoBoard tool, it is used to track, analyze, visualize, and compare ML experiments.<br>
1. Track and visualize metrics such as loss and accuracy over time.
2. Visualize model computational graphs.
3. View histograms of weights, biases, or other tensors.
4. Project embeddings to a lower dimensional space.
5. Display image, text, and audio samples.

### Vertex AI Tabular Workflows (for Google AutoML)
It is a managed instance of Vertex AI Pipelines. It is a set of integrated, fully managed, and scalable pipelines for end-to-end ML with tabular data that uses Google's AutoML technology for model development and provising customization options to fit your needs.<br>
1. Supports large datasets that are multiple TB in size.
2. Allows you to improve stability and lower training time.
3. Allows you to improve training speed.
4. Allows you to reduce model size and improve latency.

### Three Key ML Features Challenges 
- Hard to share and reuse
- Hard to serve in production, reliably with low latency
- Inadvert skew in feature values between training and serving

**Feature Management Pain Points:**`hard to reuse, hard to serve, and training-serving skewness.`

### Benefits
``` 
1. Features are shareable for training or serving tasks: Features are managed and served from a central repository,
which helps maintain consistency across your organization.
2. Features are reusable: Helps save time and reduces duplicative efforts, especially for high-value features.
3. Features are scalable: Features automatically scale to provide low-latency serving, so you can focus on 
developing the logic to create the features without worrying about deployment.
4. Features are easy to use: Feature Store is built on an easy-to-navigate user interface.
```

### Fully Managed Feature Store
It is a rich feature repository to server, share and re-use ML features.
- **Share and resus ML features across use cases:** `Centralized feature repository with easy APIs to search & discover features, fetch them for training/serving and manage permissions.`
- **Serve ML Features at scale with low latency:** `Offload the operational overhead of handling infrastructure for low latency scalable feature serving.`
- **Alleviate training serving skewness:** `Compute feature values once, re-use for training and serving. Track & monitor for drift and other quality issues.`
- **Batch and Streaming Feature Ingestion:** `Ingest features efficiently in large batches, or in real-time as data streams in.`


## Confusion Matrix



|              | Predicted Value |  
|--------------|-----------------|
| **Actual Value** |    AV vs PV    |


|        | P(cat) | N(dog) |
|--------|--------|--------|
| **P(cat)** |   TP   |   FN   |
| **N(dog**) |   FP   |   TN   |

**True Positive:** Things that you correctly predicted. Things you include that should be included. Label says something exists and the model predicts it.<br>
**False Negatives (Type II error):** Things that you incorrectly did not predict. Things you exclude when it should be included. Label says something exists but the model doesn't predict it.<br>
**False Positive (Type I Error):** Things that you incorrectly predict. Things you include when it should be excluded. Label says something doesn't exist but the model predicts it.<br>
**True Negative:** Things that you correctly excluded. Things you exclude that should be excluded. Label says something doesn't exist and the model doesn't predict it.

### Recall
Refers to all the positive cases, and looks at how many were predicted correctly.<br>
```R = TP / (TP + FN)```

### Precision
Refers to all the cases predicted as positive and how many are actually positive.<br>
```P = TP / (FP + TP)```



## MLOps
[Google Cloud MLOps Gi](https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning#mlops_level_1_ml_pipeline_automation)

Machine Learning Development + Operations

**ML** = Upload Data + Engineering Feature + Train Model + Evaluate Model <br>
**Operations** = Deploy + Monitor + Release

### MLOps Goals
**ML** = Solve production challenges related to machine learning<br>
**Operations** = Building an intergrated system + Operating in production

```
Practicing MLOps means advocating for automation and monitoring at each step of 
the ML system construction. This means adopting a process to enable:
- Continuous integration (CI)
- Continuous training (CT)
- Continuous delivery (CD)
```

### Machine Learning Deployment Options
**Endpoint**<br>
1. Best when immediate results with low latency are needed.
2. A model must be deployed to an endpoint before that model can be used to serve real-time
- e.x: Making instant recommendations based on a user’s browsing habits whenever they’re online.
**Batch Predition**<br>
1. Best when no immediate response is required, and accumulated data should be processed with a single request.
- e.x: Sending out new ads every other week based on the user’s recent purchasing behavior and what’s currently popular on the market
**Offline Predition**<br>
1. Best when the model should be deployed in a specific environment off the cloud.
- e.x: Edge AI where a camera need to identify defects on a product during assembly line or packaging process. 

### Vertex AI Pipelines
It automates, monitors, and governs machine learning systems by orchestrating the workflow in a serverless manner

### Vertex AI Workbench
It is a notebook tool that helps to define one's own pipeline. You can do this with prebuilt pipeline components, which means that you primarily need to specify how the pipeline is put together using components as building blocks

### Machine Learning Workflow
#### Data Preparation
STEP 1: Data Uploading<br>
STEP 2: Feature Engineering

**Data Types:**<br>
1. Streaming vs Batch Data
2. Structured vs Unstructured Data

#### Model Training
STEP 1: Training Data<br>
STEP 2: Evaluating Data

#### Model Serving
STEP 1: Deployement
STEP 2: Monitoring
STEP 3: Managed


## Best Practices for Machine Learning Development on GCP

### Best Practices for Preparing and Storing Data
1. Avoid storing data in block storage like netwrok file systems or VM hard disks.
2. Avoid reading data directly from databases like Cloud SQL.
#### Structured Data (BigQuery)
1. Store **tabular** and **intermidiate processed** data in BigQuery.
2. Use Vertex AI Feature Store with structured data.
3. For optimal speed, better storing **materialized data** than using **views** or **subqueries** for training data.

#### Unstructured Data (Cloud Storage)
1. Store image, video, audio, and unstructured data in Cloud Storage.
2. This also applies to TFRecord files if using TensorFlow or AVRO files if using other framework.
3. Improve write and read throughput to Cloud Storage by mombining many individual images, videos or audio clips into large files.
4. Use Vertex Data Labeling for unstructured data.  

#### Vertex AI Feature Store
1. Search Vertex AI Feature Store.<br>
1.1. Search to see if a feature already exists.<br>
1.2. Fetch those features for your training labels using Vertex AI Feature Store's batch serving capability.<br>
2. Create a new feature.<br>
2.1. Create a new feature using your Cloud Storage bucker or BigQuwry location.<br>
2.2. Fetch raw data from your data lake and write your scripts to perform feature processing.<br>
2.3. Join the feature values and the new feature values. Merging those feature values produces the training data set.<br>
2.4. It is a solution for online serving of the features to online prediction use cases.<br>
2.5. You can share features among others in the organization for their own ML models.

### Best Practices for Training
1. Use notebooks intances for small datasets.
2. For large datasets, distributed training, or scheduled training, it is recommended using Vertex Training service.

#### Training with pre-built containers on Vertex AI
1. **Python Source Distribution:** Training application code package as Python source distribution. Can include custom Python dependencies or others.
2. **Cloud Storage Bucket:** Push the package training application code to Google Cloud Storage bucket.
3. **Vertex Training:** Configure and run custom job on Vertex Training with pre-built containers.

### Best Practices for Explainable AI
1. Offers feature attributions to provide insights into why models generate predictions.
2. Details the importance of each feature that a model uses as input to make a prediction.
3. Supports custom-trained models based on tabular and image data.

#### Vertex Training
1. Maximize a model's predictive accuracy.
2. Provides an automated model enhancer to test different hyperparameter configurations when training your model.

### Best Practices for using Workbench Notebooks
1. Use Notebooks to evaluate (development) and understand (experimentation) your models.
2. Use for writing code, starting jobs, running queries, and checking status.
3. Notebooks offers What-if-Tool (WIT) and Language Interpretability Tool (LIT).
4. Create a notebook for each team member.
5. Use Vertex SDK for Python.
6. Secure Personaly Identifiable Information (PII) in Notebooks.<br>
6.1. Apply data governance and security policies to help protect your Notebooks that contain PII data.<br>
6.2. Follow Notebooks security blueprint: Protecting PII data guide.
### Best Practices for usin Vertex AI TensorBoard
1. It is an enterprise-ready managed solution.
2. Vertex AI TensorBoard service lets you track experiment metrics such as loss and accuracy over time.
3. Visualize a model graph.
4. Project enbeddings to a lower dimension space.
5. Allows cost effective, secure solutions, and easy colaboration among Data Scientists and ML Researchers to track, compare and share experiments.

## Best Practices for Data Preprocessing

### Preprocessed Features
1. BigQuery for tabular data
2. Dataflow to process unstructured data
3. Use Dataflow to convert the unstructured data into binary data formats like TFRecord to improve ingestion performance during training.
4. TensorFlow Extended for leveraging TensorFlow ecosystem.
5. TensorFlow Transform is the TensorFlow component that enables defining and executing a preprocessing function to transform your data.

## Responsible AI Development

### Origin of Bias
**Interaction Bias:** People drew more all-stars than hills in a recent game. The AI did not recognize hills.
**Latent Bias:** Training a model to identify famous phisicists is likely to be bias towards men.
**Selection Bias:** Chosing photos from your family to train a model to identify anybody.
**Confirmation Bias:** Refers to only looking for data which confirm your hypotheses.
**Reporting Bias:** Refers to choices in data that reveal certain aspects about the trainers or their opinions.
**Automation Bias:** Refers to the biases which appear when the data we use is only the data we can easily automate.

### Checklist for Bias-Related Issues

Biometrics | Country | Dialect | Health | Income | Language | Location | Race | Religion | Sexual Orientation | Skin Color | Socialeconomic Status

### What-If Tool
1. It is available for free within the TensorBoard.
2. Designed to let you visualize inference results.
3. Edit data a data point.
4. See how your model performs.
5. Explore the effects of a single feature.
6. Arrange examples for similarity.
7. View confusion matrices and other metrics.
8. Test algorithmic fairness constraints.

### ML Trade-Offs

### Equality of Opportunity

### Understand Your Data


## Facets (dataset errors finder)
1. Developed by Google and Open-Sourced
2. **Facets Overview:** Provide users a quick understanding o fthe distribution of values accross features.
3. **Facets Dive:** Provide users an easy-to-customize, intuitive interface.

## TensorFlow
A tensor is an D-dimensional array of data. They behave like numpy n-dimensional arrays except that:<br>
**tf.constant** produces constant tensors.<br>
**tf.Variable** produces tensors that can be modified.

```
reshape() by itself cannot be used to transpose a matrix unless the matrix happens to be a vector. If the matrix
is not a vector then transpose alters the internal storage order of the elements, whereas reshape() never does.
For example, internally [1 2; 3 4] is stored in the order 1 3 2 4, and transpose of [1 2;3 4] would be [1 3;2 4] 
which would be stored in the order 1 2 3 4. You can see that the 2 and 3 have swapped internal places in the transpose.
Reshape never swaps internal orderings.
```
by [Walter Roberson](https://www.mathworks.com/matlabcentral/answers/32914-transposing-matrix-using-reshape)<br>

### GradientTape records operations for automatic differentiation
TensorFlow can compute the derivative of a function with respect to any paremeter.<br>
- The computation is recorded with GradientTape (a context manager).
```
def compute_gradients(X, Y, w0, w1):
    with tf.GradientTape() as tape:
        loss = loss_mse(X, Y, w0, w1)
    return tape.gradient(loss, [w0, w1])

w0, w1 = tf.Variable(0.0), tf.Variable(0.0)

dw0, dw1 = compute_gradients(X, Y, w0, w1)
```
- The function is expressed with TensorFlow ops only!

## Tensorflow Dataset Manipulation

`Dataset = tf.data` can do more than just ingesting data.<br>


`Feature Columns = tf.feature_column` tells the model what inputs to expect.<br>
- Feature columns take care of packing the inputs into the input vector of the model.
For example, one-hot enconding bellow.
```
tf.feature_column.categorical_column_with_vocabulary_list("type", ["house","apt"])
"house" = 1, 0
"apt"   = 0, 1
```
Other examples of feature columns"
```
tf.feature_column.bucketized_column(..)
tf.feature_column.embedding_column(..)
tf.feature_column.crossed_column(..) # Enables a model to lean separate for combination of features.
tf.feature_column.categorical_column_with_hash_bucket(..)
...
```

### Embeddings
Lower Dimensions = Less Accuracy + More Lossy Compression<br>
vs<br>
Higher Dimensions = Overfitting + Slow Training


## TensorFlow SavedModel
SavedModel is a universal serialization format for TensorFlow models.
1. SavedModel provides a language neutral format to save your machine learning models that is both recoverable and hermetic.
2. It enables higher level systems and tools to produce, consume and transform your TensorFlow models. The resulted SavedModel is then servable.
3. Models saved in this format can be restored using the tf.

Save a model using SavedModel in the `gcloud ai-platform`.
```
gcloud ai-platform versions create \
--model=$MODEL_NAME $VERSION NAME \
--framework=tensorflow \
--python-version=3.5 \
--runtime-version=2.1 \
--origin=$EXPORT_PATH \
--staging-bucket=gs://$BUCKET
```
Deploy the model saved using SavedModel commands on `gcloud ai-platform`.
```
input.json = {"sq_footage": 3140, "type": 'house'} #This is an input to test the model loaded.

gcloud ai-platform predict \
--model propertyprice \
--version dnn \
--json-instances input.json
```


## Keras
Keras processing layers: `text preprocessing`, `numerical features preprocessing`, `categorical features preprocessing`, `image preprocessing`, and `image data augmentation`.

### Text Features Vectorization
`tf.keras.layers.TextVectorization` -> turns raw strings into and encoded representation that can be read by an Embedding or Dense layer.<br>

### Numerical Features Preprocessing
`tf.keras.layers.Discretization` -> turns continous numerical features into bucket data with discrete ranges.

### Categorical Features Preprocessing
`tf.keras.layers.CategoryEncoding` -> turns integer categorical features into one-hot, multi-hot, or count dense ecodings.<br>
`tf.keras.layers.Hashing` -> performs categorical feature hashing, also known as the "hashing trick."<br>
`tf.keras.layers.StringLookup` -> turns strings categorical values into an encoded representation that can be read by an Embedding or Dense layer.<br>
`tf.keras.layers.IntegerLookup` -> turns integer categorical values into an encoded representation that can be read by an Embedding or Dense layer.<br>

### The adapt() method
Stateful preprocessing layers that compute based on training data:
- TextVectorization: Holds mapping between string tokens and integer indices.
- StringLookup and IntegerLookup: Holds a mapping between inputs values and integer indices.
- Normalization: Holds the mean and standard deviation of the features.
- Discreditization: Holds information about value bucket boundaries.
```
NOTE: These layers are non-trainable. Their state is not set during training. It must be set before training.
```
### Feature Columns


Categorical Features Processing

## Keras Models

### Sequential Model
1. Not advisable  for multiple inputs and outputs.
2. Any of the layers in the model have multiple inputs and multiple outputs that, that model needs to do layer sharing or the model has a nonlinear topology such as a residual connection or if it multi-branches. 

### Functional Model
Functional API gives your model the ability to have multiple inputs and outputs.<br>
1. It allows for models to share layers and actually it's a little bit more than that.
2. It allows you to define ad hoc network graphs, should you need. With that functional API, models are defined by creating instances of layers and then connecting them directly to each other in pairs, then defining a model that specifies the layers act as the input and the output to the model when stringing everything together.
3. Create models that are more flexible than the sequential API.
4. It can handle models with nonlinear topology, models with shared layers, and models with multiple inputs or outputs, so consider that functional API in those use cases.
5. The API also makes it easy to manipulate multiple inputs and outputs which is not possible in Sequencial API.

#### Functional Model Pros
1. Less verbose than using keras.Model subclasses.
2. Validates your model while you are defining it.
3. Your model is plottable and inspectable.
4. Your model can be serialized or cloned.

#### Functional Model Cons
1. Does not support deynamic architectures.
2. Sometimes you have to write from scratch and you need to build subclasses, e.g. custom training or inference layers.

## Activation Function
Also known as Non-linear Transformation Layer. 

1. Act as a transtition point between layers, and so you get nonlinearity.
2. Adding in this noliniear transformation is the only way to stop the neural network to condense down into a shallow network.

### Rectified Linear Unit (ReLU)

1. ReLU hidden activations often have 10 times the speed of training than networks with Sigmoid hidden activations.
2. Due to the negative domain's function always being zero, one can end up with ReLU layers dying. When updating the weights, since one have to multiply error's derivative by the activation, one end up with a gradient zero.

### Softplus
1. The logistics sigmoid function is a smooth approximation of the derivative of the rectifier (ReLU).

### Leaky ReLU
1. Rectifier that allows small negative values when the input is less than zero.

### Parametric ReLU
1. Learns parameters that controls the leakiness and shape of the function.
2. It adaptively learns parameters of the rectifiers.  

### Exponetial Linear Unit (ELU)
1. It is generalization of ReLU that uses parameterized exponential function to transform from positive to small negative values.

### Gaussian Error Linear Unit (GELU)
1. Nonlinearity results in the expected transformation of a stochastic regularizer , which randomly applies the identity or zero map to the neuron's inut.


## Keras Optmizers

### Stochastic Gradient Descent (SGD)

### Adam
Adam is not an acronym. It is an extension to Stochastic gradient decent and can be used in place of classical stochastic gradient descent to update network weights more efficiently. [PAPER: Adam: A method for Stochastic Optimization](https://arxiv.org/pdf/1412.6980.pdf)

1. It is a procedure to update the network weights iteratively based in training data.
2. Invariability due to the diagonal rescaling of the gradients.
3. Well-suited for models that have large and large and large data sets.
4. When you have a lot of parameters that you're adjusting.
5. Problems with very noisy or sparse gradients and nonstationary objectives.

### Momentum
It reduces learning rate when the gradient values are small
### AdaGrad
It gives frequently occurring features low learning rates
### Adadelta
It improves AdaGrad by avoiding and reducing LR to zero
### Follow the Regularized Leader (FTRL)
1. It works well on wide models.
2. FTRL, liek Adam, make really good defaults for deep neural nets as well as linear models that you're building.

## Callbacks
Callbacks are utilities called at certain points during model training for activities such as logging and visualization using tools such as TensorBoard. Saving the training iterations to a variable allows for plotting of all your chosen evaluation metrics like mean absolute error, root mean squared error, accuracy, et cetera, versus the epochs.


## Regularization
Refers to any technique that helps generalize a model.
```
A generalized model performs well not just on training data, but also on never-seen test data.
```
### L1 Regularization
L1 Norm measures the absolute value of distance a and b
### L2 Regularization (weight decay)
L2 Norm is the Euclidean Distance. It is the square root of the sum of the squares.

- Regression model that uses the L1 regularization technique is called **Lasso Regression**.<br>
- Regression model that uses the L2 Regularization technique is called **Ridge Regression.**<br>

**Lasso vs Ridge difference**<br>
```
Lasso shrinks the less important feature’s coefficient to zero, thus removing some features altogether.
Ridge regression adds “squared magnitude” of coefficient as a penalty term to the loss function.
```

## Feature Engineering
"It is the process of transforming raw data into features that better represent the underlying problem to the predictive models, resulting in improved model accuracy on unseen data." Dr. Andrew Ng<br>
Different problems in the same domain may need different features. It depends on you and your subject matter expertise to determine which fields you want to start with for your hypothesis.<br>
Feature engineering it an iterative process.<br>
### Feature engineering types
**Using indicator variables to isolate key information:** Isolates a specific area for a training dataset.<br>
**Highlighting interactions between two or more features:** Sum of two featuers, product of two feature, etc.<br>
**Representing the same feature in a different way:**<br>
1. Create new feature "grade" with "Elementary School","Middle School", and "High School" as classes.
2. Group similar classes, and then group the remaining ones into a single "Other" class.
3. Transform categorical features into dummy variables.

### Feature Points
1. Features should be related to the objective. Look for good features and avoid bad features.
2. Features should be known at prediction-time.
3. Features should be numeric.<br>
3.1. The vocabulary and the mapping of the vocabulary needs to be identical at prediction time. If new data is added in problems arise for sparce columns (one-hot encoding).
4. Features should have enough examples. 

## BigQuery Preprocessing
It involves two aspects, representation transformation and feature construction.<br>

### Representation Transformation
1. Feature representation is converting a numeric feature to a categorical feature through bucketization.
2. Converting categorical features to a numeric representation through one-hot encoding, learning with counts, sparse feature embeddings, etc.
3. Some models work only with numeric or categorical features.
4. Other models handle mixed type features. Even when models handle both types.

### Feature Construction
1. Polynomial expansion by using **univariate mathematical functions**.
2. **Feature crossing** to capture feature interactions.<br>
2.1. It is all about memorization. Memorization is the oposite of generalization, which is what machine learning aims to do. The goal of ML is generalization.<br>
2.2. It only works on large data sets.<br>
2.3. Feature crosses lead to sparcity. Sparce models contain fewer features, soon, they are easier to train on limited data with less chances of overfitting.<br>
3. Using **business logic** from the domain of the ML use case. 


Does the feature cross of all the combinations: `ML.FEATURE_CROSS(STRUCT(features))`<br>
Specify all the preprocessing during model: `TRANSFORM (ML.FEATURE_CROSS(STRUCT(features)), ML.BUCKETIZE(f, split_points) etc...)`<br>
Where split_points is an array: `ML.BUCKETIZE(f, split_points)`

### Memorization
Memorization works when you have so much data that for any single grid cell within your input space the distribution of data is statistically significant. When that is the case, you can memorize. You are essentially just learning the mean for every grid cell.

### Spatial Features
**ST_Distance:** returns the shortest distance in meters between two non-empty geographies.<br>
**ST_GeoPoint:** 

### BUCKETIZE (BigQuery clause)
It is a preprocessing function that creates buckets or bins. That is, it bucketizes a continuous numerical feature into a string feature with bucket names as the value.

### TRANSFORM (BigQuery clause)
When the TRANSFORM clause is used, user specify transforms during training will be automatically applied during model serving, prediction, evaluation, etc.<br>
1. TRANSFORM clause ensures that transformations are automatically applied during prediction.

## Dataflow (Data Processing Pipeline)
Uses open-source API (Apache Beam) to execute Flink, Spark, Parallen tasks, etc.

### Apache Beam Pipeline
1. Beam is a way to write elastic data processing pipelines.
2. A Pipeline is a directed graph of steps.
3. Pipeline must have a source, which is where the pipeline gets input data.
4. The pipeline has a series of steps. Each of the steps in Beam is called a transform.
```
Each transform works on a structure called PCollection.
I'll return to a detailed explanation of PCollections shortly.
For now, just remember that every transform gets a PCollection as input and outputs the
result to another PCollection. The result of the last transform in a pipeline is important.
```
3. None of the pipeline operators actually run the pipelineYou need a runner to run the pipeline. A runner takes the pipeline code and executes.
4. Runners are platform-specific, meaning that there's a dataflow runner for executing a pipeline on Cloud dataflow. There's also a direct runner that will execute a pipeline on your local computer. You can even implement your own custom runner for your own distributed computing platform. 
5. PCollection is like a data structure with pointers to where the dataflow cluster stores your data. That's how dataflow can provide elastic scaling of the pipeline.
6. Dataflow is elastic and can use a cluster of servers for your pipeline. So PCollection is like a data structure with pointers to where the dataflow cluster stores your data.
7. One way to implement the transformation is to take a PCollection of strings, which are called lines in the code, and return a PCollection of integers. This specific transform step in the code computes the length of each line.
```
pipe = beam.Pipeline()
(pipe
| beam.io.ReadStringsFromPubSub('project/topic')
| beam.WindowInto(SlidingWindows(60))
| beam.Map(Transform)
| beam.GroupByKey()
| beam.FlatMap(Filter)
| beam.io.WriteToBigQuery(table)
)
pipe.run()
```
8. Apache Beam SDK comes with a variety of connectors that enable dataflow to read from many data sources, including text files in Google Cloud Storage or file systems.
9. With different connectors, it's possible to read even from real time streaming data sources, like Google Cloud Pub/Sub or Kafka.
10. There are connectors for Cloud Storage, Pub/Sub, BigQuery and more.


## TensorFlow Transform
It is a hybrid of Apache and TensorFlow.

### TFX
TFX is an end-to-end ML platform based on TensorFlow.<br>
NOTE: `Artifacts produced by tf.Transform's are consumed at both training and serving time to avoid skew.`<br>
```
1. tf.transform is a hybrid of Apache Beam and TensorFlow
2. One of the goals of tf.Transform is to provide a TensorFlow graph for preprocessing that can be incorporated
into the serving graph (and, optionally, the training graph).
```

### Preprocessing function
The Preprocessing function is the most important concept of tf.Transform. It is a logical description of a transformation of the dataset. The preprocessing function accepts and returns a dictionary of tensors, where a tensor means Tensor or 2D SparseTensor.

### Problems with typical ML Pipeline
```
1. Need to keep batch and live processing in sync.
2. All other tooling, such as evaluation, must be kept in sync with batch processing.
```
### Partial solutions for ML Pipeline
```
Do everything in the training graph
1. Loses the benefits of matearialization.
2. Doesn't allow for "reduces".
Do everything in the training graph + using statistics/vocabs generated from raw data.
1. Only allows for stats/vocabs on raw data.
2. Doesn't address materialization.
Transform does batch process but also emits a tf.Graph that can be used to repeat these transformations in survey.
1. By combining this graph with the trained model graph into a single serving graph,
you can guarantee that the same operations that were done to the training data
```

NOTE:
```
Gradient ascent works better input raw data is scaled. In order to do that, you will first have to find the minimum
and the maximum of the numeric feature over the entire training data set. And then you will scale every input value
by the min and max that were computed on the training data set.
```

## Supporting Serving
For serving, we need to write out the transformation data.<br>

## ML Development

### Activities involved in ML Development
1. Experimentation
2. Training Operationalization
3. 

### Training Operationalization
It is an automated training pipeline with the purpose to help the model be repeatedly retrained.

```
NOTE: Process that Data Scientists use to develop the models on an experimentation platform.
1. Problem Definition
2. Data Selection
3. Data Exploration
4. Feature Engineering
5. Model Propotyping
6. Model Validation
```

### Model Prototyping
It is the process algorithm selection, model training, hyperparameter tuning, and model evaluation in the Experimentation and Prototyping activity.


## Google's Enterprise Data Management and Governance Tools
```
Feature Store
Data Catalog
Data Plex
Analytics Hub
Dataprep
```

### Online Serving
Online serving is for low-latency data retrieval of small batches of data for real-time processing.


## Data Catalog

### Challenges
Data stakeholders (consumers, producers and administrators) within an organization face a number of challenges:
#### Searching for insightful data
- Data consumers don't know what data is where. They have to navigate data "swamps" they stumble into.
- Data consumers don't know what data to use to get insights because most data is not well documeted and, even if documented, is not well maintained.
- Data can't be found and is often lost when it resides only in people's minds.

#### Understanding data
- Is the data fresh, clean, validated, approved for use in production?
- Which data set out of several duplicate sets is relevant and up-to-date?
- How does one data set relate to another?
- Who is using data set related to another?
- Who and what processes are transforming the data?

#### Making data useful
- Data producers don't have an efficient way to put forward their data for consumers. If there's no self-service, consumers may overwhelm producers. Several data engineers can't manually provide data to thousands of data analysts.
- Valuable time is lost if data consumers have to find out how to request data access, request it, wait without a defined response time, escalate, and wait again.

## Dataplex
Organize and manage your data in a way that makes sense for your business without data movement or duplication. It provides logical constructs like lakes, data zones and assets that enable you to abstract away underlying storage systems and become the foundation for setting policies around data access, security, life-cycle management, and more.

1. Achieve freedom of choice.
2. Store data wherever you want.
3. Choose the best analytics tools for the job.
4. Enforce consistent controls.
5. Use built-in fata intelligence.
6. Automate data management.
7. Get access to higher quality data.

### Making high quality data available for analytics and Data Science
1. Structure Data | Semi-structured Data | Unstructured Data
2. Automatic metadata extraction and classification
3. Apply data validation and quality checks
4. Data Catalog (for search & discovery) and Unified Metadata (accross BigQuery and Open Source)

### Attach data to zones
1. Landing Zone
2. Structured Zone
3. Refined Zone

## Analytics Hub
Exchanges data analytics assets across organizations to address challenges of data reliability and cost. You can exchange data, ML models, or other analytics assets, and easily publish or subscribe to shared datasets in an open, secure, and privacy-safe environment.
```
Analytics Hub makes it convenient for you to build a data ecosystem. 
This data ecosystem could include, public exchanges like data from the World Bank,industry exchanges
from healthcare and retail, commercial exchanges that will include logistics, consumer, and energy data,
and also Google exchanges, which include, patents, web analytics, and trend data.
```

### Traditional data sharing ecosystems challenges
Traditional data sharing requires batch data pipelines that extract data from databases, store it in flat files, and transmit them to the consumer where they are ingested into another database.
1. **Expensive and fragile data pipelines:** Pipelines are expensive to run, but any changes to the source data can cause them to break.
2. **Unecessary data replication:** Pipelines result in multiple copies of the data which bring unnecessary cost, especially with multi-petabyte datasets.
3. **Late arriving or asynchronous data assets:** The time required by batch pipelines also means that data is late arriving, leading to less timely business decisions.
4. **Loss of visibility and control of data:** Traditional data sharing techniques, also bypass data governance processes. As a provider of data, how do you know how your data is being used?
5. **Commercialization of data workflows management:** If you want to monetize your data, how do you manage subscriptions and entitlements
```
NOTE: Altogether, these challenges mean that organizations are unable to realize the true potential
to transform their business with shared data.
```

### 3 Roles in Analytics Hub
1. Data Publisher
2. Exchange Administrator
3. Data Subscriber

### Exchanges
They are collections of data and analytics assets designed for sharing. Administrators can easily curate an exchange by managing the dataset listings within the exchange.

### Shared datasets
They are collections of tables and views in BigQuery defined by data publisher and make up the unit of cross-project or cross-organization sharing.


## Dataprep
Dataprep is a tool to instantly prepare data. Dataprep will produce Dataflow jobs. You can automate or schedule Dataprep jobs because of Dataflow.

1. Discover
2. Cleanse
3. Structure
4. Enrich
5. Validate

```
NOTE: When you are importing data into Dataprep, you are creating a reference to a source of data. 
When the data is required for use, Dataprep reads a sample of the source data into the application 
for your use through an object known as a connection.
```

### Three connection types
This means ways to upload or download your data from Dataprep.<br>
- **Upload/Download:** Upload data directly from a local desktop and also save it locally on export.
- **Cloud Storage:** Read from and write to files in Cloud Storage
- **BigQuery:** Store relational content in BigQuery, from which Dataprep can read.

### Pros
1. Automatically identify schemas, data types, possible joints, and anomalies.
2. Anomalies detection include missing values, outliers, and duplicates, so you can skip the time-consuming work of data profiling.
3. Offer visual representation with Histograms, Ranges and key statistical information.
4. Automatically detect 17 different datatypes.
5. Can trsnform structured and unstructured datasets stored in CSV, JSON or relational table formats
6. It can store any size, from megabytes to petabytes with equal ease and simplicity.

### Intelligent data cleansing with predictive transformation
- Quickly indentify data quality issues.
- Get automatic data transformation suggestions.
- Standardize, structure and join datasets easily with a guided approach.

### Powerful data professing
- Process diverse datasets
- Prepare datasets of any size
- Built on top of Dataflow
- Auto-scalable

```
NOTE: In Dataprep, the flows are implemented as sequence of recipes. The recipes are data processing
steps built from a library of Wrangler. Cloud Dataprep Wranglers write beam code in Cloud Dataflow.
1. Build recipes in Cloud Dataprep UI.
2. Converts repices to Beam.
3. Runs a Cloud Dataflow job pipeline.
```
### Recipes
Recipes are a repeatable set of transformation steps, built by chaining data Wranglers together. You can include end-to-end steps from ingestion, transformation, aggregation, and save to BigQuery. You will run your Dataprep job to process your recipes against your entire dataset.




## Learning Rate
Learning rate controls the size of the step in weight space. If steps are too small, the training will take a long time. If steps are too large, the training will bounce around and miss the optimal point.<br>
`NOTE: The default value for linear aggressor estimator in TensorFlow library is set to 0.2 or one over the square root of the number of features. This assumes your feature and label values are small numbers.`

## Batch size
Batch size controls the number of samples that gradient is calculated on. If batch size is too small, we could be bouncing around because the batch may not be a good enough representation of the input. If batch size is too large, training will take a very long time.<br>
- As a rule of thumb, 40 to 100 tends to be a good range for batch size.
- Larger batch sizes require smaller learnign rates.
- _Recent research suggests small mini batch sizes provide more up-to-date gradient calculations which yields more stable and reliable training. And in experimental results for the C410, C4100, and ImageNet data sets, the best performance has been consistently obtained for many batch sizes between m = 2 and m = 32. So it may be better to start with a smaller batch size._

## Distributed Training
It is running training in parallel on many devices such as CPUs or GPUs or TPUs in order to make your training faster.

### Common Distributed Training Architectures
Data parallism and model parallism.

### Data Parallelism
it is a common architecture for distributed training where you run the same model and computation on every device. But train each of them using different training samples. Each device computes loss and gradients based on training samples it sees. Then we update the models' parameters using these gradients. The updated model is then used in the next round of computation.

**Two Model Approaches**<br>
#### Async parameter server architecture
An async parameter server architecture some devices are designated to be parameter servers and others as workers. Each worker independently fetches the latest parameters from the PS and computes gradients based on a subset of training samples. It then sends the gradients back to the PS, which then updates its copy of the parameters with those gradients. Each worker does this independently. This allows it to scale well to a large number of workers. This worked well for many models in Google, for training workers might be preempted by higher-priority production jobs, or a machine may go down for maintenance, or where there is asymmetry between the workers. These don't hurt the scaling because workers are not waiting for each other.
#### Downside
The downside of this approach, however, is that workers get out of sync. They compute parameter updates based on scale values, and this can delay convergence.

#### Sync Allreduced Architecture
In this approach, each worker holds a copy of the model's parameters. There are no special servers holding the parameters. Each worker computes gradients based on the training samples they see and communicate between themselves to propagate the gradients and update their parameters. All workers are synchronized. Conceptually, the next forward pass doesn't begin until each worker has received the gradients and updated their parameters. With fast devices in a controlled environment, the variance between the step time on each worker is small. When combined with strong communication links between the workers, the overhead of synchronization is also small. So overall this approach can lead to faster convergence. Given these two broad strategies, that is asynchronous parameter server approach and the synchronous allreduce approach

#### When should you pick one over the other
**Async parameter server approach**<br>
1. Multiple machines. 
2. Many low-power or unreliable workers. Such as a cluster of machines with just CPUs.
3. More mature approach. It is supported well by TensorFlow by the estimator API's train and evaluate method.
4. Constrained by I/O.
**Sync allreduced approach**<br>
1. Multiple devices on one machine.
2. When there are fast devices with strong communication links such as multiple GPUs on one host, or TPUs.
3. Fast devices with strong links. Gaining a lot more traction recently because of the improvements in hardware.
4. Constrained by compute power.

### Model Paralism
It is when your model is so big that it doesn't fit on one device's memory. So you divide it into smaller parts that compute over the same training samples on multiple devices. For example, you could put different layers on different devices.

### Vertex AI custom service benefits
1. **Local Training First:** instead of training your model directly within your notebook instance, you can submit a training job from your notebook. The training job would automatically provision computing resources and deprovision those resources when the job is complete. There's no worrying about leaving a high-performance virtual machine configuration running.
2. **Modulerized Architecture:** The training service can help to modularize your architecture. Put your training code into a container to operate as a portable unit. The training code can have parameters passed into it such as input data location and hyperparameters to adapt to different model type scenarios without redeployment. Also, the training code can export the trained model file, thus enabling working with other AI services in a decoupled manner.
3. **Cloud Logging:** The training service also supports reproducibility. Each training job is tracked with inputs, outputs and the container image used. Log message are available in Cloud logging, and jobs can be monitored while running.
4. **Distributed Training:** The training service also supports distributed training, which means that you can train models across multiple nodes in parallel. That translates into faster training times than would be possible within a single VM instance.

## Batch Prediction Requirements

### BigQuery table requirements
1. BigQuery data source tables cannot be larger than 100 gigabytes.
2. You must use a multi-regional BigQuery dataset in the US or EU locations.
3. If the table is in a different project, you must provide the `BigQuery Data Editor role` to the Vertex AI service account in that project.

### CSV file requirements
1. The first line of the data source must contain the name of the columns.
2. Each data source file cannot be larger than 10 gigabytes. You can include multiple files up to a maximum size of 100 gigabytes.
3. If the cloud storage bucket is in a different project where you use Vertex AI, you must provide the Storage Object Creator role to the Vertex AI service account in that project.


**Artifact Lineage:** it describes all the factors that resulted in an artifact such as training data or hyperparameters used for model training.
```
- The training, test, and evaluation data used to create the model.
- The hyperparameters uesd during model training.
- The code that was used to train the model.
- Metadata recorded from the training and evaluation process.
- Artifacts that desended from this model.
```



## Best Practices

### Artifact Organization
```
Source control repo (storage location)
- Notebooks
- Pipeline source code
- Preprocessing functions
- Model source code
```
```
Experiments and ML metadata (storage location)
- Experiments
- Parameters
- Metrics
- Datasets (reference)
- Pipeline metadata
```
```
Vertex AI (storage location)
- Trained models
```
```
Artifact Registry
- Pipeline containers
- Custom training environments
- Custom prediction environments
```
```
Vertex Prediction
- Deployed models
```

## Performance Monitoring
```
- Traffic Patterns
- Error rates
- Latency
- Resource Utilization
```

### Model Registry
The machine learning model registry is a centralized tracking system that stores linage, versioning, and related metadata for published machine learning models.<br>
**Registry can capture governance data required for auditing purposes:**<br>
```
1. Who trained and published a model.
2. WHich datasets were used for training.
3. The values of metrics measuring predictive performance.
4. When the model was deployed to production.
```


## Training Design Solutions

### Static Training


### Dynamic Training


| Static Training | Dynamic Training |
|:---------------------:|:---------------------:|
| Space intensive | Compute intensive |
| Higher storage cost | Lower storage cost |
| Low, fixed latency | Variable latency |
| Lower maintenance | Higher maintenance |

## Serving Design Decisions
### Peakedness
**Highly Peaked:** A model that predicts the next word based on the current word, which you might find in your mobile phone keyboard app would be highly peaked bexause a small number of words account for the majority of words used.<br>
**Low Peaked:** A model that predicted quaterly revenue for all sales verticals in order to populate a report would be right on the same verticals.<br>

### Cardinality
**Low Cardinality:** Model predicting sales revenue given organization division number.<br>
**High Cardinality:** Model predicting lifetime value given a user friendly e-commerce platform.<br>

### Modular program
```
1. Modular programs are more maintainable.
2. Easier to reuse.
3. Easier to test.
4. Easier to fix because they allow engineers to focus on small pieces of code rather than the entire program.
```

### When it comes to adapting to change
```
1. An upstream model.
2. A data source maintained by another team.
3. The relationship between features and labels.
4. The distributions of inputs.
```

### Concept Drift
It is the change in relationships between the model inputs and the model output.

#### Four types of Concept Drift
**Sudden Drift:** a new concept occurs within a short time.<br>
**Gradual Drift:** a new concept gradually replaces an old one over a period of time.<br>
**Incremental Drift:** an old concept incrementally changes to a new concept over a period of time.<br>
**Recurring Concepts:** an old concept may reoccur after some time.<br>

### Data and Concept Drift Examples
|**Data Drift**|**Concept Drift**|
|:-------------|:----------------|
|Change in spamming behavior to try to fool the model|e-Commerce apps eliance on personalization, for example, the fact that people’s preferences ultimately do change over time|
|Rule update in the app change in the limit of user messages per minute, selection bias, and non-stationary environment, training data for a given season that has no power to generalize to another season|Sensors nature of the data they collect and how it may change over time|
|Section bias as training data for a given season that has no power to generalize to another season|Movie recommendations rely on user preferences and they may change|
|Non-stationary environment training data for a given season that has no power to generalize to another season|Demand forecasting heavily relies on time, and as we have seen, time is a major contributor to potential concept drift|

### Solution for Data and Concept drift
**Data drift:** If you diagnose data drift, enough of the data needs to be labeled to introduce new classes and the model retrained.<br>
**Concept drift:** If you diagnose concept drift, the old data needs to be relabeled and the model retrained. Periodically updating your static model with more recent historical data, for example, is a common way to mitigate concept drift. Or either discard the static model completely or you can use the existing state as the starting point for a better model to update your model by using a sample of the most recent historical data.<br>

## Three Phases of a Pipeline
1. Ingest and validade data.<br>
1.1 TensorFlow Data Validation.<br>
1.2 Two common use-cases of TensorFlow Data Validation within a TensorFlow Extended pipelines: `validation of continuously arriving data` and `training-serving skew detection`.
2. Train and analyze model.<br>
2.1. MLOps.
3. Deploy in production.

#### Validation of continuously arriving data
On day one you generate statistics based on data from day one. Then, you generate statistics based on day two data. From there, you can validate day two statistics against day one statistics and generate a validation report. You can do the same for day three, validating day three statistics against statistics from both day two and day one.

#### training-serving skew detection
Training-serving skew occurs when training data is generated differently from how the data used to request predictions is generated.

**What causes distribution skew?**<br>
1. Possible causes might come from a change in how data is handled in training vs in production, or even a faulty sampling mechanism that only chooses a subsample of the serving data to train on. For example, if you use an average value, and for training purposes you average over 10 days, but when you request prediction, you average over the last month. In general, any difference between how you generate your training data and your serving data, the data you use to generate predictions, should be reviewed to prevent training-serving skew.
2. Training-serving skew can also occur based on your data distribution in your training, validation, and testing data splits.
3. To summarize, distribution skew occurs when the distribution of feature values for training data is _significantly different_ from serving data and one of the key causes for distribution skew is how data is handled or changed in training vs production.


### The TFDV Pipeline Components
1. ExampleGen component: which takes raw data as input and generates TensorFlow examples, it can take many input formats for example CSV, TF Record. It also splits the examples for you into Train/Eval.
2. StaticsGen (Statistics Generation) component: which generates statistics for feature analysis.
3. SchemaGen (Schema Generation) component: which gives you a description of your data.
4. Example Validator component: which allows you to check for anomalies.

### Reasons to analyze and transform your data
|Common problems|Identity effective features|
|:--------------|:--------------------------|
|Missing Data|Informative features|
|Labels treated as features|Redundant features|
|Features with values outside an expected range|Features that vary so widely in scale that they may slow learning|
|Data anomalies|Features with little or no unique predictive information|

### StatisticsGen data validation checks
1. Feature min, max, mean, mode, and median.
2. Feature correlations.
3. Class imbalance.
4. Check to see missing values.
5. Histograms of features, both numerical and categorical.

### SchemaGen data validation checks
Types, Categories and Ranges of the data.<br>
1. **Type:** indicates the feature datatype
2. **Presence:** indicates whether the feature must be present in 100% of examples or not, so whether it’s required or optional.
3. **Valency:** indicates the number of values required per training example.
4. **Domain and Values:** indicates the feature domain and its values. In the case of categorical features, single indicates that each training example must have exactly one category for the feature.

### Example Validator data validation checks
1. It can detect different classes of anomalies in the data and emit validation results.
2. The ExampleValidator pipeline component identifies any anomalies in the example data by comparing data statistics computed by the StatisticsGen pipeline component against a schema.
3. It takes the inputs and looks for problems in the data, like missing values, and reports any anomalies.

## High-Performance Machine
It is the time taken to trian a model

###
|**Constraint**|**Input/Output**|**CPU**|**Memory**|
|:-------------|:---------------|:------|:---------|
|**Commonly Occurs**|*Large inputs. *Input requires parsing. *Small models|*Expensive computations. *Underpowered Hardware|*Large number of inputs. *Complex model|
|**Take Action**|*Store efficiently. *Parallelize reads.  *Consider batch size|*Train on faster accel. *Upgrade processor. *Run on TPUs. *Simplify model|*Add memory. *Use fewer layers. *Reduce batch size.|


## Distriduted Training
Distributed training distributes training workloads across multiple mini-processors, or worker nodes. These worker nodes work in parallel to accelerate the training process. Their parallelism can be achieved via two types of distributed training architecture: **Data Paralism** and **Model Paralism**.

### Data Paralism
It is model-agnostic, making it the most widely used paradigm for parallelizing neural network training. In data parallelism, you run the same model and computation on every device, but train each of them using different training data samples. Each device computes loss and gradients based on the training samples. Then you update the model's parameters using these gradients. The updated model is then used in the next round of computation.

There are two approaches used to update the model using gradients.<br>

### Synchronous
All of the devices train their local model using different parts of data from a single, large mini-batch. They then communicate their locally calculated gradients, directly or indirectly, to all devices. In this approach, each worker device computes the forward and backward passes through the model on a different slice of input data. The `computed gradients from each of these slices are then aggregated across all of the devices and reduced, usually using an average, in a process known as` **Allreduce**. The optimizer then performs the parameter updates with these reduced gradients, thereby keeping the devices in sync.

#### Cons
Because each worker cannot proceed to the next training step until all the other workers have finished the current step, this gradient calculation becomes the main overhead in distributed training for synchronous strategies. Only after all devices have successfully computed and sent their gradients, so that all models are synchronized, is the model updated.

#### Pros
The asynchronous parameter server approach, in which the parameter servers contain fewer features, consume less memory, and can run just a cluster of CPUs, is great for sparse models, as it shards the model across parameter servers, and workers only need to fetch the part they need for each step.

### Asynchronous
No device waits for updates to the model from any other device. The devices can run independently and share results as peers, or communicate through one or more central servers known as parameter servers. Thus, in an asynchronous parameter server architecture, some devices are designated to be parameter servers and others as workers. Devices used to run computations are called worker devices, while devices used to store variables are parameter devices. Each worker independently fetches the latest parameters from the parameter servers and computes gradients based on a subset of training samples. It then sends the gradients back to the parameter server, which then updates its copy of the parameters with those gradients. Each worker does this independently. This allows it to scale well to a large number of workers, where training workers might be preempted by higher priority production jobs, or a machine may go down for maintenance, or where there is asymmetry between the workers. This doesn't hurt the scaling, because workers are not waiting for each other.

#### Cons
The downside of this approach, however, is that workers can get out of sync. They compute parameter updates based on stale values, and this can delay convergence.

#### Pros
For dense models, the parameter server transfers the whole model each step, and this can create a lot of network pressure. Therefore, the synchronous Allreduce approach should be considered for dense models which contain many features and thus consume more memory. In this approach, all machines share the load of storing and maintaining the global parameters. This makes it the best option for dense models, like BERT, Bidirectional Encoder Representations from Transformers.


### Model Paralism
When a model is too big to fit on one device's memory, you can divide it into smaller parts on multiple devices and then compute over the same training samples. This is called model parallelism.

Model parallelism feeds or gives every processor the same data, but applies a different model to it. Think of model parallelism as simply multiple program, same data. Model parallelism splits the weights of the net equally among the threads. And all threads work on a single mini-batch. Here, the generated output after each layer needs to be synchronized, i.e. stacked, to provide the input to the next layer. In this approach, each GPU has different parameters and computation of different parts of a model.

#### Pros
In other words, multiple GPUs do not need to synchronize the values of the parameters.

#### Cons
Model parallelism needs special care when assigning different layers to different GPUs, which is more complicated than data parallelism. The gradients obtained from each model and each GPU are accumulated after a backward process, and the parameters are synchronized and updated. However, a hybrid of the data and model parallelism approaches is sometimes used together in the same architecture.

## TensorFlow Distributed Training Strategies

[Optimize TensorFlow performance using the Profiler](https://www.tensorflow.org/guide/profiler)

### Challenges
1. How will you distribute the data accross the different devices.
2. How will you accumulate the gradients during backpropagation.
3. How will the model parameters be updated.

### Solution
`tf.distribute.Strategy is a TensorFlow API to distribute training across multiple GPUs, multiple machines, or TPUs. There are four TensorFlow distributed training strategies that support data parallelism: Mirrored Strategy, Multi-Worker Mirrored Strategy, TPU Strategy, Parameter Server Strategy.`

### Mirrored Strategy
`You can use mirrored strategy when you have a single machine with multiple GPU devices.`

1. Mirrored strategy will create a replica of the model on each GPU.<br>
2. During training, one minibatch is split into n parts, where "n" equals the number of GPUs, and each part is fed to one GPU device.<br>
3. For this setup, mirrored strategy manages the coordination of data distribution and gradient updates across all of the GPUs.
```
To improve training, we can use the MirroredStrategy.
```
### Multi-Worker Mirrored Strategy
It implements synchronous distributed training across multiple workers, each with potentially multiple GPUs.<br>
Similar to mirrored strategy, it creates copies of all variables in the model on each device across all workers. If you've mastered single-host training and are looking to scale training even further, then adding multiple machines to your cluster can help you get an even greater performance boost.

```
For faster training, we can use the MultiWorkerMirroredStrategy.
```

#### Cluster
The "cluster" key contains a dictionary with the internal IPs and ports of all the machines. This is set up through TF_CONFIG.

#### Worker Machines
All machines are designated as "workers", which are the physical machines on which the replicated computation is executed.

#### Chief Machine
There needs to be one worker that takes on some extra work, such as saving checkpoints and writing summary files to TensorBoard. This machine is known as the "chief".

#### tf.distribute
1. Create a strategy object.
2. Wrap the creation of the model parameters within the Scope of the strategy.
3. Scale the batch size by the number of replicas in the cluster.

```
If the data is not stored in a single dataset, then TensorFlow's AutoShardPolicy will autoshard 
the elements accross all the workers.
```

#### Saving
Saving the model is slightly more complicated in the multi-worker case, because there needs to be different destinations for each worker. The chief worker will save to the desired model directory, while the other workers will save the model to temporary directories. It's important that these temporary directories are unique in order to prevent multiple workers from writing to the same location. Saving can contain **collective ops**, so all workers must save, not just the chief.

### TPU Strategy
TPUStrategy uses a single machine where the same model is replicated on each core with its variables synchronized (mirrored) across each replica of the model.<br>
`The main difference, however, is that TPUStrategy will all-reduce across TPU cores, whereas MirroredStrategy will all-reduce across GPUs.`
```
For really fast training, we can use the TPUStrategy.
```

#### Pros
1. TPUs read training data exclusively from Google Cloud Storage (GCS).
2. GCS can sustain a pretty large throughput if it is continuously streaming from multiple files in parallel.
3. Too few files: GCS will not have enough streams to get max throughput.
4. Too many files: time will be wasted accessing each individual file.

#### Parameter Server Strategy
Parameter server training cluster consists of Workers and ParameterServers. Variables are created on ParameterServers, and they are read and updated by Workers in each step.

### tf.data API
The tf.data API makes it possible to handle large amounts of data, read it in different file and data formats, and perform those complex transformations.

**tf.data.Dataset** represents a sequence of elements in which each element consists of one or more components. For example, in an image pipeline an element might be a single training example with a pair of tensor components representing the image and its label.

`The dataset API will help you create input functions for your model that load data in progressively throttling it.`

**Two ways to create a dataset:**
```
1. A data source constructs a dataset from data stored in memory or in one or more files.
2. Data transformation constructs a dataset from one or more tf.dataset objects.
```
Large datasets tend to be sharded or broken apart into multiple files, which can be loaded progressively. Remember that you train on mini batches of data. You don't even have the entire dataset in memory. `One mini batch is all you need for one training step.`

There are specialized dataset classes that can read data from text files like CSVs, TensorFlow records, or fixed length record files. Datasets can be created from many different file formats.
1. Use **TextLineDataset** to instantiate a dataset object, which is comprised of, as you might guess, one or more text files.
2. Use **TFRecordDataset** for TFRecord files.
3. **FixedLengthRecord Dataset** is a dataset object from fixed length recordsor one or more binary files.
4. For anything else you can use the generic dataset class and add your own decoding code.

### Performance Batch Pipelines
1. In terms of raw processing speed, you'll want to use Cloud ML Engine batch predictions.
2. The next fastest is to directly load the SavedModel into your Dataflow job and then invoke it.
3. The third option, in terms of speed, is to use TensorFlow Serving on Cloud ML Engine.
4. But if you want maintainability, the second and third options reverse. The batch prediction is still the best.
5. Using online predictions as a microservice allows for easier upgradability and dependency management than loading up the current version into the Dataflow job.

## Hybrid ML Systems

### Kubeflow
An open-source machine learning platform designed to enable the use of machine learning pipelines to orchestrate complicated workflows running on Kubernetes. Kubeflow helps build hybrid cloud machine learning models.

```
1. It makes deploying machine learning workflows on Kubernetes simple, portable, and scalable.
2. It helps you migrate between cloud and on-prem environments.
3. It also extends Kubernetes' ability to run independent and configurable steps with 
machine-learning-specific frameworks and libraries.
4. Kubeflow is an open-source machine learning stack built on Kubernetes.
5. On Google Cloud, you can run Kubeflow on Google Kubernetes Engine (GKE).
6. Kubeflow can be ran on anything from a phone, to a laptop, to an on-prem cluster.
7. Your code remains the same.
8. Some of the configuration settings just change.
```


### Kubeflow Benefits


3. It is open source, so it can run on Google Kubernetes Engine which is part of Google Cloud.
4. Kubeflow can actually run on anything, whether it's a phone, a laptop, or an on-premises cluster. Regardless of where it's run, the code remains the same. 

### Confederated learning
The idea is you continuously train the model on the device, and then you combine the model updates from a federation of user devices to update the overall model. The goal is for each user to get their customized experience because there's model training happening on the device, but still retain privacy because it's the overall model update.

## Recommendation Systems
recommendation systems are about personalization it's about taking your product that works for everyone and personalizing it for an individual user 

### Content-based Recommendations
Content-based recommendation system you use the metadata about your products for example perhaps you know which movies are cartoons and which movies are sci-fi.<br>
Use item features to recommend new items that are similar to what the user has already liked based on their previous actions or explicit feedback. They don't rely on information about other users or other user item interactions.
```
1. Needs metadata about the items.
2. Needs market segmentation of the users.
3. Uses attributes of the items to recommend new items to a user.
3. Recommendation relies on the behaviors and item interactions of a single user.
4. Recommended when large number of items were rated. 
5. Doesn't take into account the behavior or ratings of other users.
6. There is no machine learning.
7. Relies on the builder of the recommendation system to assign proper tags to items and users.
8. Doesn't need information about other users.
9. Can recommend niche items that the user was not initially interested in.
10. Requires domain knowledge to hand-engineer features.
11. Difficult to expand interests of user.
```

#### Structured
```
1. Genres  2. Themes  3. Actors/directors involved  4. Professional Ratings
```
#### Unstructured
```
1. Movies Summary. 2. Stills from movie. 3. Movie Trailer  4. Professional Reviews
```

### Collaborative Filtering
Collaborative filtering you don't have any metadata about the products instead you learn about item similarity and user similarity from the ratings data itself. We might store our user movie data in a matrix like this with check marks indicating whether the user watched the complete movie or commented on it or gave it a star rating or however it is that we measure that a specific user.
```
1. No need of any metadata about your items.
2. No need of market segmentation of your users.
3. Recommendation relies on the behaviors and item interactions of other users.
3. As long as you have an interactions matrix (user-interaction matrix) you're ready to go.
4. Uses similarities between users and items simultaneously to determine recommendations.
5. Recommended when a few number of items were rated.
6. Collaborative filtering learns latent factors and can explore outside user's personal bubble.
```

#### Structured
```
1. User Ratings. 2. User Views  3. User wishlist/cart history  4. User Purchase/Return History
```
#### Unstructured
```
1. User Reviews  2. User-answered questions  3. User-submitted photos. 4. User-submitted videos
```

NOTE: 'Embeddings can be learned from data.`

As long as the number of latency features is less than half the harmonic mean of the number of users and the number of items this will save space for this hypothetical website that would be almost 10 000 latent features 9998 to be precise. Each movie is essentially its own feature.
```
k < U * V / 2(U + V)
```

### Factorization Approaches

#### Stochastic Gradient Descent (SGD)
```
Flexible and Paralyzable algorithm. You can scale your problem to handle much larger data.
Slower and hard to handle unobserved interaction pairs,
```
#### Alternating Least Squares (ALS)
Solve U holding v constant and solve v holding U constant
```
Only works for Least Square Problems.
Paralyzable algorithm. You can scale your problem to handle much larger data.
Faster convergence than SDG.
Easily to handle unobserved interaction pairs.
```
#### Singular Value Decomposition (SVD)
Unobserved pairs are given values of zero. Poor performance and recommendation
```
|A-UV^T|^2
```
#### Matrix Factorization ALS
Just ignore the missing values. 
```
SUM(i,j)(Aij-UiVj)^2
```
#### Weighted ALS (WALS)
Assigns a weight for those interaction pairs that are missing as a way to represent low confidence.
```
SUM(i,j)(Aij-UiVj)^2 + w0 * SUM(i,j)(0-UiVj)^2
```

### Building an End-to-End Recommendation Systems
`NOTE: If you have metadata and an interactions matrix a neural network solution is recommended.`<br>
Use neural networks to combine all of the advantages and eliminate the disadvantages of all three types of recommendation systems three types well.

### Knowledge Based Recommendation
Is based on explicit knowledge about the user's preferences items and or recommendation criteria. They are especially useful when alternative approaches such as collaborative filtering or content-based methods cannot be applied. This occurs in situations where items are not purchased very often.
```
1. System that can be used to provide business impact inputs to systems.
2. Used in situations where items are not purchased very often.
3. Recommended when there is no rated information about an item or user.
4. Will often explicitly ask users for their preferences and then use that information to begin making
recommendations.
```
#### Structured
```
1. Demographic information  2. Location/country/language  3. Genre preferences  4. Global filters
```
#### Unstructured
```
1. User "about me" snippets.
```


### Hybrid Approach
Hybrid models of all three of these types of systems use all the data available and connect all of these models together into an ml pipeline.

## Recommendation Systems Pitfalls

1. User space and the product space are sparse and skewed.<br>
1.1. Iteraction matrix is sparse because there are potentially few interactions within the entire user item space<br>
1.2. Most items are rated by very few users.<br>
1.3. Most users rate only a small fraction of items.<br>
1.4. Iteraction matrix is skewed because some properties are very popular.<br>
1.5. Iteraction matrix is skewed because some properties are very prolific.<br>
2. Cold start problem when there aren't enough interactions for users or items.
3. Lack of explicit user feedback leads to the need of implicit user feedback.<br>
3.1. Number of clicks.<br>
3.2. Play counts.<br>
3.3. Fraction of video watch.<br>
3.4. Site navigation.<br>
3.5. Time spent on page.<br>
4. Explicit rating is not easily available.

## Similarity Measures
Is a metric for items in an embedding space.

### Dot product
s(a,b) = SUMi(ai x bi)

``` Python Dot Product Function
def dot(ai, bi):
    return sum(a*b for a, b in zip(ai, bi))
```

### Cosine Similarity
It is a dot product and magnitude (norm). It is the dot product scaled by the norm of the feature vectors.

s(a,b) = SUMi(ai x bi) / (|a||b|)
s(a,b) = SUMi(ai x bi) / (sqrt(SUMi(a^2i)) x sqrt(SUMi(a^2i)))


``` Python Norm Function
def norm(vi):
    return sum(v*v for v in vi) ** 0.5
```

``` Python Cosine Similarity
def cos_sim(ai, bi):
    dot = dot(ai, bi)
    norm_a, norm_b = norm(ai), norm(bi)
    
    return dot / (norm_a*norm_b)
```

### Deep Learning Models
Deep learning models can also be used when building a recommendation system.<br>
Deep neural networks work well because they are flexible and can be trained to have varying outcomes such as predicting ratings interactions or even next items.

### Context-Aware Recommendation Systems (CARS)
Context aware recommendation systems add an extra dimension to our usual collaborative filtering problem. Traditional collaborative filtering recommendation systems use a rank two tensor a user item interaction matrix containing explicit or implicit ratings. Contextual collaborative filtering recommendation systems on the other hand use a multi-dimensional tensor but the user item interaction matrix flow ratings is stratified across multiple dimensions of context.

#### Contextual prefiltering
```
Data
U x I x C -> R
Apply [C] Context Vector
Contextualized Data
U x I -> R
2D Recommender
U x I -> R
Apply [U] User Vector
Contextual Recommendations
i1,i2,i3, ...
```
##### Examples
```
1. Reduction-Based Approach (2005)
2. Exact and Generalized Prefiltering (2009)
3. Item Splitting (2009)
4. User Splitting (2011)
5. Dimensions as Virtual Items (2011)
6. User-Item Splitting (2014)
```

#### Item\User\User-Item Splitting
```
t-value
tmean = | Mic - Mić| \ |sqrt(Sic/Nic + Sić/Nić)|
```
#### Contextual Postfiltering
```
Data
U x I x C -> R
2D Recommender
U x I -> R
Apply [U] User Vector
Recommendations
i1,i2,i3, ...
Apply [C] Context Vector
Contextual Recommendations
i1,i2,i3, ...
```
```
Weight postfiltering method
R'ij = Rij * P
```
#### Contextual Modeling
```
Data
U x I x C -> R
MD Recommender
U x I x C -> R
Apply [U] User Vector
Apply [C] Context Vector
Contextual Recommendations
i1,i2,i3, ...
```
### Deviation-based context-aware matrix factorization
- How is user's rating deviated?
- Contextual rating deviation (CRD)
- Looks at the deviations of users across context dimensions

CRD is used to adjust rating recommendations

**Biased Matrix Factorization in Traditional RS**
```
Rui = M + bu + bi + pu^Tqi
M = Global Average Rating
bu = User Bias
bi =  Item Bias
pu^Tqi = User-Item interaction
```

**Deviation-based Context Aware Matrix Factorization (CAMF_C approach)**
```
Ruicic2...cN = M + bu + bi + pu^Tqi + SUMj=i^N(CRDcj)
M = Global Average Rating
bu = User Bias
bi =  Item Bias
pu^Tqi = User-Item interaction
Ruicic2...cN = Contextual Rating
SUMj=i^N(CRDcj) = Contextual Rating Deviation
```

## Reinforcement Learning (RL)
Reinforcement learning is borrowed from an area of behavior psychology known as operant conditioning and deals with learning the relationship between stimuli action and consequences that is the occurrence of rewards or punishments. These rewards and punishments then guide the learner on the desired behavior or policy.

Reinforcement learning in software is an area of machine learning where an agent or system of agents learns to achieve a goal by interacting with its environment. By goal, we mean that we want the agent to learn the optimal path or behavior that collects the maximum reward.

```
The agents learn to:
1. Achieve a goal.
2. Achieve the optimal behavior.
3. Obtain the maximum reward.
```
### Characteristics of RL
1. There is no supervisor. There is only a real number of reward signal.
2. Decision Making is sequencial.
3. Time plays a crucial role in RL problems.
4. Feed back is alaways delayed, not instanteneous.
5. The agent's actions determine the subsequent data it receives. 

### Reinforcement Learning Framework

Agent -> Environment: States | Actions | Rewards

#### Terminology in Reinforcement Learning
```
State: Summary of events so far; the current situation.
Action: One or more events that alter the state.
Environment: The scenario the agent has to respond to.
Agent: The learner entity that performs actions in an environment.
Reward: Feedback on agent actions, also known as reward signal.
Policy: Method to map the agent's to actions.
Episode: A termination point.
Value: Long-term reward gained by the end of an episode.
Value Function: Measure of potential future rewards from being in a particular state, or V(S)
Q(S,A): "Q-value" of an action in various state/action pairs.
```

#### Model-based vs model-free RL
|Qualities|Model-based|Model-Free|
|:--------|:---------:|:--------:|
|You have access to or knowledge about the environment|YES|NO|
|You can avoid needless exploration by focusing on areas you already know are worthwhile|YES|NO|
|Need to make more assumptions and approximations|YES|NO|
|Need lots of samples|NO|YES|
|Over many episodes, results become less optimal|YES|NO|
|Over many episodes, results become more optimal|NO|YES|
|Applicable accross a wide variety of applications|NO|YES|

#### Examples of Model-based and Model-free methods
|Model-based methods|Model-free methods|
|:-----------------:|:----------------:|
|Analytic gradient computation|Value-based|
|Sampling-based planning|Policy-based|
|Model-based data generation|Contextual bandits|
|Value-equivalence prediction|Actor-critic|
| |On-policy|
| |Off-policy|

### Value-based Approach
You explore in order to learn state-action values and maximize a value function, V(S).

The agent can sample and generalize to derive a policy, pi, that maximizes the value of action for each state.

#### Sample backups
**Sample backup:** the agent learns from environment sampling which may provide an incomplete picture of the environment dynamics with enough samples. The sample backup approaches come closer to the full backup approaches.<br>
**Deep backup:** the agent learns the whole trajectory of the chosen action up to the termination point. This can be the whole trajectory of the sample and not necessarily the full environment.<br>
**Shallow backup::** the agent learns one step at a time in a breadth-first search manner of the chosen action trajectory.<br>
**Full backup:** the agent learns from the ability to access the complete environment.<br>

#### Monte Carlo backup
``` Cons
1. It tends to evaluate the whole trajectory of actions the agent took up to the terminal state of
the episode because this method of reward attribution is sensitive to the trajectory.
2. Actions taken it tends to overfit and exhibit higher variance
3. If a particular value was achieved it's assumed that each action was equally responsible for the outcome.
4. There is an inherent assumption that an episode has a terminal state or endpoint and reaches 
that in a feasible amount of time.
```
``` Pros
1. Easy to implement at each time step with each action that the agent takes it gets a reward.
2. The rewards accumulate throughout the episode and are backed up throughout, so that the agent 
learns that these actions led to a certain cumulative reward. 
```
#### Temporal Difference backup
The td method can learn directly from raw experience without the model of the environment's dynamics.<br>
Unlike the Monte Carlo method, td estimates are based in part on other learned estimates without waiting until the end of the episodes bootstrapping. The agent learns from one or more intermediate time steps in a recursive fashion.<br>
The recursive learning helps in accelerating overall learning even in cases where there might not be any well-defined terminal states in td backup.

`NOTE: Because td backups haven't seen the whole set of trajectories, they have a narrow perspective and tend to underfit especially in the beginning despite higher complexity and higher bias`

TD backups are used more often than Monte Carlo backups.

### Policy-based RL
You want the action performerd in every state to help you to gain maximum reward in the future.

The agent will:<br>
- Learn the stochastic policy function that maps state to action.
- Act by sampling policy.
- Utilize exploration techniques.

|Poly-based method|Value-based|
|:----------------|:----------|
|There are large action spaces.| |
|Stochastic is needed.| |
|An agent will learn the policy directly.| |
|Lower bias in the policy is needed.| |

### Multi-armed bandits
An agent simultaneously attempts to:
- Explore (acquire new knowledge).
- Exploit (optimize its decision based on existing knowledge.

### Contextual Bandits
It is an extension of multi-armed bandits or simplified RL.
- In a sequence of trials, the agent acts based on a given context.
- Each data point is a new episode.
- Value of exploration strategies is much easier to quantify/tune.
- Context can be the input feature space (recommender|personalization systems).
- A policy as the function approximator: Estimation value gain from an action.

Bandits problem is a simplified reinforcement learning problem which has only one time step and note state transition dynamics in the diagram.

## Computer Vision


**Batch Normalization:** Our input pixel values are in the range [0,1] and this is compatible with the dynamic range of the typical activation functions and optimizers. However, once we add a hidden layer, the resulting output values will no longer lie in the dynamic range of the activation function for subsequent layers. When this happens, the neuron output is zero, and because there is no difference by moving a small amount in either direction, the gradient is zero. There is no way for the network to escape from the dead zone.

To fix this, batch norm normalizes neuron outputs across a training batch of data, i.e. it subtracts the average and divides by the standard deviation. This way, the network decides, through machine learning, how much centering and re-scaling to apply at each neuron. In Keras, you can selectively use one or the other:

x^(k) = (x^(k) - E[x^(k)]) / sqrt(Var[x^(k)])
```
def batchnorm(data, gamma, beta, eps=1e-5):  
    """
    
    Arguments:
        - data = Data of shape (X,Y)
        - gamma = Scale parameter of shape (Y,)
        - beta = Shift paremeter of shape (Y,)
        - eps = Constant for numeric stability
    
    Returns:
        - out = Data result of shape (X,Y)
        - cache = A tuple of values needed for backward pass
    """
    
    sample_mean = x.mean(axis=0)
    sample_var = x.var(axis=0)
    
    std, x_center = np.sqrt(sample_var + eps), x - sample_mean

    x_norm = x_center / std
    
    result = (gamma * x_norm) + beta
    
    cache = (x_norm, x_center, std, gamma)

    return out, cache
```


## Convolution





## MLOps


### DevOps concepts translated to MLOps
|**Conitnuous Integration (CI)**|**Continuous Delivery or Deployment (CD)**|**Continuous Training**|
|:------------------------------|:-----------------------------------------|:----------------------|
|Checkout the code|Build|Monitor|
|Complete the task|Test|Measure|
|Validate against the code base|Release|Retrain|
|Perform unit testing| | |
|Merge the code| | |

### DevOPS vs MLOps differences
|**DevOps**|**MLOps**|
|:---------|:--------|
|Tests and validates code and components|Tests and validates data, data schemas and models|
|Focuses on a single software package service|Considers the whole system: the ML training pipeline|
|Deploys code and moves to the next task|Constantly monitors, retrains, and serves the model|



The difference between Continuous Delivery and Continuous Deployment is the automation deployment.<br>
**Continuous delivery:** automates integration or acceptance tests, deployment to staging and smoke tests. Deployment to the production still done manually.<br>
**Continuous deployment:** compliments continuous integration with additional steps by automating the configuration and deployment application to the production evironment. 

### Technical Debt
Represents the pressure to prioritize releases over quality, which might mean not paying close attention to code quality.

### ML Lifecycle
|**Discovery Phase**|**Development Phase**|**Deployment Phase**|
|:------------------|:--------------------|:-------------------|
|Business use case definition|Data pipeline creation and feature engineering|Plan for deployment|
|Data exploration|Model building|Model operationalization|
|Architecture and algorithm selection|Model evaluation|Model monitoring|
| |Presentation results| |


## Tensorflow Extended (TFX)


**TFX Component:** it is an implementation of the machine learning task in your pipeline. They are designed to be modular and extensible, while incorporating Google's machine learning best practices on tasks such as data partitionaing, validation, and transformation. 

### Components 5 elements
**Component specification:** A configuration protocol buffer defines how components communicate with each other via input and output artifact channels and runtime parameters.<br>
**Component driver:** A drive coordinates job execution.<br>
**Component executor:** Code to perform ML workflow step such as data preprocessing or TensorFlow model training.<br>
**Component publisher:** Updates ML Metadata store.<br>
**Component interface:** Packages component specification and executor for use in pipeline.

### TFX components at runtime
1. **Driver** reads the component specification for parameters and artifacts and retrieves input artifacts from the metadata store for the component.
2. **Executor** performs computation on artifacts.
3. **Publisher** uses the component specification and executor results to store the component's output artifacts in the metadata store.

### TFX Pipeline
It is a sequence of components connected be channels in a directed acyclic graph (DAG) of artifact dependencies.
```
1. Uses Medata storage<br>
1.1. It stores the metadata in a relational back end.<br>
1.2. It does not store the actual pipeline artifacts.<br>
2. It is task aware. They can be authored in a script or notebook to run manually by the user as tasks.<br>
2.1. A task can be an entire pipeline run or a partial pipeline run of an individual component and its downstream components.
3. It is data aware. It means TFX pipelines store all the artifacts from every component over many executions.
```

NOTE: TFX pipeline uses ML Metadata storage, an open source library to standardize the definition storage and querying of metadata for ML pipelines. ML metadata stores the metadata in a relational back end. It does not store the actual pipeline artifacts.

### TFX Horizontal Layers
Coordinate pipeline components. These are primarily shared libraries if utilities and protobuffs for defining abstractions that simplify development of TFX pipelines accross different computing and orchestration environments.

### TFX Orchestrators
They take the logical pipeline object, which can contain pipeline arcs components in a DAG, and are responsible for scheduling components of the TFX pipeline sequentially based on the artifact dependencies.

### TFXIO
It defines a common in-memory data representation shared by all TFX libraries and components based on **Apache Arrow**, a columnar memory format for efficient analytics on CPUs and GPUs.

### ExampleGen
1. It is the entry point to one's pipeline that adjusts data.
2. It supports inputs like CSV, TF Records, Avro, and Parquet.
3. As outputs is produces TF examples or TF sequence examples.

ExampleGen brings configurable and reproducible data partitioning and shuffling into TF Records, a common data representation used by all components in your pipeline.<br>
ExampleGen supports external ingestion of CSV, Avro, Parquet, and TF Record data sources. This can be done across sharded file systems using glob file patterns as well.

`NOTE: A span is a grouping of training examples.`

### Benefits of ExampleGen
```
1. Brings configurable and reproducible data partitioning.
2. Shuffling into TF records, a common data representation used by all components in one's pipeline.
3. Supports external ingestion of CSV< Avro, Parquet and TF Record data sources.
4. Supports BigQuery ingestion through configuring sequel queries for each data partition. 
5. Leverages Apache Beam for scalable, fault-tolerant data ingestion.
6. Customizable tonew inout data formats and ingestion methods which makes it easier to incorporate
into one's machine learning project.
7. Supports advanced data management capabilities such as data partitioning, versioning, and custom
splitting on features or time.
```

### ExampleValidator
The ExampleValidator pipeline component identifies any anomalies in the example data by comparing data statistics computed by the StatisticsGen pipeline component against a schema.<br>

1. It can perform validity checks by comparing data set statistics against a schema that codifies expectations of the user.
2. It can detect feature train-serving skew by comparing training and serving data.
3. It can also detect data drift by looking at a series of feature data across different data splits. 

### Transform
The Transform TFX pipeline component performs feature engineering on the TF examples data artifact emitted from the ExampleGen component using the data schema artifact from SchemaGen or imported from external sources as well as TensorFlow transformations typically defined in a pre-processing function as shown in the example on the slide.<br>

1. It brings consistent feature engineering at training and serving time to benefit your machine learning project.
2. Including feature engineering directly into your model graph reduces train-serving skew from differences in feature engineering.
3. It is also underpinned by Apache Beam, so you can scale up your future transformations using distributed compute as your data grows.

### Component: Trainer
1. It trains the TensorFlow model.
2. It supports TF1 estimators and native TF2 Keras models via the generic executer.
3. Trainers component spec also allows you to parameterize your training and evaluation arguments, such as the number of steps as shown in the example on the screen.

### Component: Tuner
1. It makes extensive use of the Python Keras tuner API for tuning hyper parameters.
2. As inputs, the tuner component takes in the transform data and transform graph artifacts.
3. As outputs the tuner components output a hyper parameter artifact.<br>
4. You can modify the trainer configurations to directly ingest the best hyperparameters found from the most recent tuner run.
5. Brings the benefits of tight integration with the trainer component to perform hyperparameter tuning in a continuous training pipeline.
6. You can also perform distributed tuning by running parallel trials on Google Cloud to significantly speed up your tuning jobs.

### Component: Evaluator
1. Evaluates how well the model performed during trainer and tuner.
2. It will perform a thorough analysis using the TensorFlow Model Analysis library to compute machine learning metrics across data splits and slices.
3. As outputs, the evaluator component produces two artifacts, an evaluation metrics artifact that contains configurable model performance metrics slices, and a "model blessing" artifact that indicates whether the models performance was higher than the configured thresholds and that it is ready for production.
4. Brings standardization to your machine learning projects for easier sharing and reuse.
5. Evaluator blesses the model if the new trained model is good enough to be pushed to production. In other words, it assures that your pipeline will only graduate a model to production when it has exceeded the performance of previous models.

### Component: InfraValidator
1. It is used as an early warning layer before pushing a model to production.
2. It blesses the model if the model is mechanically serviceable in a production environment
3. As inputs, InfraValidator takes the SavedModel artifact from the trainer component, launches a sandboxed model server with the model, and tests whether it can be successfully loaded and optionally queried using the input data artifact from the example Gen component.
4. Focuses on the compatibility between the model server binary, such as TensorFlow serving, in the model ready to deploy.
5. It is the user's responsibility to configure the environment correctly.
6. Only interacts with the model server in the user configured environment to see whether it works well.
7. Brings an additional validation check to your TFX pipeline by ensuring that only top-performing models are graduated to production and that they do not have any failure-causing mechanical issues.
8. Brings standardization to this model infra check and is configurable to mirror model-serving environments such as Kubernetes clusters and TF Serving.

### Component: Pusher
1. It is used to push a validated model to a deployment target during model training or retraining.
2. Relies on one or more blessings from other validation components as input to decide whether to push the model.
3. As output a pusher component will wrap model versioning data with the train TensorFlow SavedModel for export to various deployment targets.
4. The pusher component brings the benefits of a production gatekeeper to your TFX pipeline to ensure that only the best performing models that are mechanically sound make it to production.
5. Standardizes the code for pipeline model export for reuse and sharing across machine learning projects while still having the flexibility to be configured for Filesystem and Model Server deployments.

### Component: Bulkinferrer
1. Used to perform batch inference on unlabeled TF examples.
2. It is typically deployed after an evaluator component to perform inference with a validated model, or after the trainer component to directly perform inference on an exported model.
3. It currently performs in memory model inference and remote inference.
4. Remote inference requires the model to be hosted on Cloud AI platform.
5. As inputs, BulkInferer reads from the following artifacts, a train TensorFlow SavedModel from the trainer component, optionally a model blessing artifact from the evaluator component, input data TF example artifacts from the example jam component.
6. As output BulkInferer generates an inference result proto, which contains the original features and the prediction results.
7. If your machine learning use case only calls for batch inference, BulkInferer is a great option for your machine learning project to directly include inference in your pipeline.
8. Enables you to have task and data-driven batch inference in a continuous training and inference pipeline.

### PipelineNode
They are special purpose classes for performing advanced metadata operation such as importing external artifacts into ML metadata, performing queries of current ML metadata based on artifact properties and their history.

### ImporterNode
Imports (register) an external data object into ML Metadata.<br>
1. The primary use case for this node is to bring in external artifacts like a schema into the TFX pipeline for use by the transform and trainer components.
2. Instead of regenerating the schema for each pipeline read, you can use the ImporterNode to bring a previously generated or updated schema into your pipeline.

### ResolverNode
Handles special artifact resolution logistics that will be used as inputs for downstream nodes.<br>
1. It is only required if you're performing model validation in addition to evaluation.
2. The LatestArtifactResolver returns the latest N artifacts in a given channel. This is useful for comparing multiple run artifacts, such as those generated by the evaluation component.
3. The latest bless model resolver returns the latest validated and bless model.

## Apache Beam
**Pipeline:** Entire set of operations being performed, including reading input, applying transformations, writing output, and the execution engine to be used.<br>
**PCollection:** Represents an unordered set of data, e.g, for input and output.<br>
**PTransform:** Data processing operation that operates over 1:many PCollections. ParDO is the core parallel processing transform.<br>
**Runners:** Excute and translate pipelines to massively parallel big-data processing systems.

## TF Metadata

### TFX Metadata Store
**Trained models:** Type definitions of artifacts and their propertities.<br>
**Trainer:** Execution records (runs) of components.<br>
Data provenence accross all executions.<br>

## Cloud Coposer
It is a managed Apache Airflow service that helps you create, schedule, monitor and manage workflows.

1. Author end-to-end workflows on Google Cloud.
2. Integrate with BigQuery, Cloud Storage, AI Plaftform, etc.
3. Security for yours worflows accross Google Cloud using tools such as Cloud IAM.
4. Have your infrastructure fully managed by Google.
5. Explore Cloud Composer and Airflows logs through Cloud Operations Logging and Monitoring.

In Airflow, A DAG is defined in a Python script, which represents the DAG structure (tasks and dependencies) as code.<br>

A DAG is usually created by the Airflow scheduler, but it can also be created by an external trigger.<br>

## CDA vs EDA vs Baysesian Analysis

### Classical Data Analysis
The data collection is followed by the imposition of a model, normality, linearity, analysis, estimation and testing that follows are focused on the parameters of that model.
### Exploratory Data Analysis
1. The data collection is not followed by a model imposition.
2. It is followed immediately by analysis with a goal of inferring what model would be appropriate.
3. It does not impose deterministic or probabilistic models on the data.
4. It allows the data to suggest admissible models that best fit the data.
### Bayesian Analysis
1. Analyst attempts to answer research questions about unkown parameters using probability statements based on prior data.
2. They may bring their own domain knowledge and/or expertise to the analysis as new information is obtained.
3. The purpose is to determine posterior probabilities based on prior probabilities and new information.
4. Posterior probabilties

## Difference between Mean Square Error and Cross Entropy?
**Mean Square Error:** There is a quadratic penalty for means-squared error, so it is essentially trying to minimize the Euclidean distance between the actual label and the predicted label.<br>
**Cross Entropy:** The penalty is almost linear when the predicted probability is close to the actual label, but as it gets farther away it becomes exponential when it gets close to predicting the opposite class of the label.

## Machine Learning vs Statistics
||**Machine Learning**|**Standard Statistics (linear/logistic regression)**|
|:--|:----------------|:---------------------------------------------------|
|**Data Preparation**|Doesn't require explicit commands to find patterns in data|Need to know variables and and parameters before hand|
|**Hypothesis**|No hypothesis needed|Need hypothesis to test|
|**Type of data?**|Multi-dimensional data that can be non-linear in nature|Linear data|
|**Training?**|Needs to be trained|No training|
|**Goal?**|Generally better for predictions|Generally better for inferences /hypothesis testing|
|**Scientific Question?**|What will happen?|How/why will happen?|

## Loss Function 

### Error
One measure of the quality of the prediction at a single point is simply the sign differnece between the prediction and actual value. This difference is called the error.<br>
1. Get the errors for the training sample: `Error = Actual Value - Predicted Value` or `Error = Ÿi - Yi`
2. Compute the squares of the errors in step 1: `(Ÿi - Yi)^2`<br>
2.1 Ÿi = actual value
2.2 Yi = predicted value
4. Computer  mean of the squared errors: `Mean = 1/n * sum(Error^2)` or `Mean = 1/n * sum((Ÿi - Yi)^2)

### Root Mean Squared Errors (RMSE)
`sqrt(1/n * sum(Error^2))`<br>
n = number of values

```
Pro blem: RMSE doesn't work as well for classification.
```

### Cross Entropy (Log loss)
` -1/N * sum(y*log(ÿ) + (1-y)*log(1-ÿ)` which is -1/N * sum(Positive Term + Negative Term)

### Gradient Descent
Search for the minima by descending the gradient
```
def computeLoss(params):
    while loss is ? Epsilon:
        direction = computeDirection()
        for i in range(self.params):
            self.params[i] = self.params[i] + stepsize * direction[i]
loss = computeLoss()
```

In order to converge step sizes are necessary.
```
1. Small step sizes (learning rate) can take very long to converge.
2. Large step sizes (learning rate) may never converege to the true minimum. Process is not guarantee to converge.
3. A correct step size requires try and error. However, one correct step size does not fit all models.
```



## Glossary

**Ablation Analysis:** analysis where the value of an individual feature is computed by comparing it to a model trained without it. What might this engineer be concerned about? The engineer might be concerned about legacy and bundled features.

**AlloyDB:** A fully managed PostgreSQL - compatible dabase service for your most demanding enterprise workloads. It combines the best of Google with PostgreSQL, for superior performance, scale, and availability.

**AlloyDB AI:** automates embeddings generation, to easily transform operational data into vector embeddings. 

**Artifact Lineage:** it describes all the factors that resulted in an artifact such as training data or hyperparameters used for model training. One can understand differences in performance or accuracy over several pipeline runs

**Average Pooling:** instead of calculating a max value like max pooling, average pooling calculates the average value for each block on the feature map.

**Bundled Features:** are features that were added as part of a bundle, which collectively are valuable but individually may not be.

**Cardinality:** refers to the number of values in a set.

**Changes in the Distribution:** The statistical term for changes in the likelihood of observed values like model inputs.

**Cold Start:** when your model is not updating to new users, new products, and new patterns in user preference because the model only knows about your older products, it continues to recommend them long after they’ve fallen out of favor. Ultimately, users simply ignored the recommendations altogether, and made do with the site’s search functionality.

**Composability:** the ability to compose a bunch of microservices together and the option to use what makes sense for your problem.

**Compulation:**

**Concept Drift:** occurs when there is a change in the relationship between the input feature and the label, or target. It can occur due to shifts in the feature space and/or the decision boundary, so we need to be aware of these during production.

**Container:** it is an abstraction that packages applications and libraries together so that the applications can run on a greater variety of hardware and operating systems. This ultimately makes hosting large applications better.

**Convolution:** is the mathematical combination of two functions to produce a third function.

**DAR Run:** is a physical instance of a DAG, containing task intances that run for a specific execution_date.

**DAG Runner:** it refers to an implementation that supports an orchestration.

**Data Leakage:** it is when the label is somehow laking into the training data.

**Directed Acyclic Graphs (DAGs):** A DAG is a collection of all tasks you want to run, organized in a way that reflects their relationships and dependencies.

**Distributed Training:** it is running training in parallel on many devices such as CPUs or GPUs or TPUs in order to make your training faster.

**Drift:** Drift occurs when the statistical properties of the inputs and the target which the model is trying to predict change over time in unforeseen ways. In other words, it is the change in an entity with respect to its baseline.

**Drift Detection:** How significantly are service requests evolving over time.

**Data Dredging:** It is the statistical manipulation of data in order to find patterns which can be presented as statistically significant, when in reality there is no underlying effect.

**Data Parallelism:** it is a common architecture for distributed training where you run the same model and computation on every device. But train each of them using different training samples. Each device computes loss and gradients based on training samples it sees. Then we update the models' parameters using these gradients. The updated model is then used in the next round of computation.

**Embedding:** is a map from our collection of items to some finite dimensional vector space. They are commonly used to represent input features in machine learning problems.

**Extrapolation::** means to generalize outside the bounds of what we’ve previously seen.

**Explicit feedback:** the user is intentionally explicitly leaving feedback for that item.

**Feature cross:** It is a process of combining features into a single feature. It enables a model to learn separate weights for each combination of features. A feature cross is a synthetic feature formed by multiplying (crossing) two or more features. Crossing combinations of features can provide predictive abilities beyond what those features can provide individually.

**Implicit feedback:** It is not intentionally given as a means of reading the item the user has interacted with. However, there was some type of interaction and from that we can infer whether the user had a positive or a negative experience. This could be whether someone viewed a video, how long they watched a video, if a user spent a lot of time on a page, if they clicked certain areas, or buttons on the page, etc.

**Interpolation::** is the opposite of Extrapolation. It means to generalize within the bounds of what we’ve previously seen.

**Latent Factors:** Compress the data to find the best generalities to rely on.

**Latent Feature:** It is a feature that we are not directly observing or defining but are instead inferring through our model from the other variables that are directly observed.

**Legacy Features:** are older features that were added because they were valuable at the time. The have become redundant because of the implementation of new features without our knowledge.

**Loss Function:** it takes the quality of predictions for a group of data points from our training set and compose them into a single number with which to estimate the quality of the models current parameters.

**Machine Learning Metadata:** Data about data, but not the data itself. Who triggerd the pipeline run? What hyperparameters were used for training? Where is the model file stored? When was the model pushed to production? Why was model A prefered over model B? How was the training environmnet configured?

**Max Pooling:** operation like a convolution that returns the maximum value out of all the input data values pass to a kernel.

**Model Definition:**

**Model Staleness:** Data that you used to train the model in the research or production environment does not represent the data that you actually have in your live system. 

**Model Residuals:** it is the difference between its predictions and the labels.

**Occam's razor:L** When presented with competing hypothetical answers to a problem, one should select the one that makes the fewest assumptions.<br>

**Peakedness:** is the degree to which data values are concentrated around the mean in a data distribution, or in this case, how concentraded the distribution of the prediction workload is. You can also think of it as inverse entropy.

**PKL:** it is standard method of serialization objects in python.

**Portability:** Because it is necessary to configure the stack over and over again and production services is not done on your laptop, portability is needed.

**Root Mean Squared Error (RMSE):** RMSE measures the difference between the predictions of a model and the observed values. A large RMSE is equivalent to a large average error, so smaller values of RMSE are better.<br>
```
1. RMSE is a useful way to see how well a model is able to fit a dataset.
2. The larger the RMSE, the larger the difference between the predicted and observed values.
This means the worse a model fits the data.
3. Conversely, the smaller the RMSE, the better a model is able to fit the data.
4. One nice property of RMSE is that the error is given in the units being measured, 
so you can tell very directly how incorrect the model might be on the unseen data.
```
**Training-serving skew:** is a difference between model performance during training and performance during serving. This skew can be caused by:<br>
- A discrepancy between how you handle data in the training and serving pipelines.
- A change in the data between when you train and when you serve.
- A feedback loop between your model and your algorithm.<br>



