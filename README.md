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
### ML Strategy
```
Simple ML and more data > Fancy ML and small data.
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

### [Using Hyperparameter Tunning](https://cloud.google.com/vertex-ai/docs/training/using-hyperparameter-tuning#aiplatform_get_hyperparameter_tuning_job_sample-python)

Hyperparameter tuning searches for the best combination of hyperparameter values by optimizing metric values across a series of trials. Metrics are scalar summaries that you add to your trainer, such as model accuracy. Hyperparameter tuning optimizes target variables that you specify, called hyperparameter metrics. Model accuracy, as calculated from an evaluation pass, is a common metric. Metrics must be numeric.

### [Vertex AI Vizier](https://cloud.google.com/vertex-ai/docs/vizier/overview)
It is a hyperparameter optmizer. Vertex AI Vizier is a **black-box optimization service** that helps you tune hyperparameters in complex machine learning (ML) models. When ML models have many different hyperparameters, it can be difficult and time consuming to tune them manually. Vertex AI Vizier optimizes your model's output by tuning the hyperparameters for you.

**Black-box optimization** is the optimization of a system that meets either of the following criteria:<br>
- Doesn't have a known [objective function](https://developers.google.com/machine-learning/glossary#objective-function) to evaluate.
- Is too costly to evaluate by using the objective function, usually due to the complexity of the system.

#### How to use Vertex AI Vizier
This page describes how to make API requests to Vertex AI Vizier by using Python.

Tutorial on how to use [Vertex AI Vizier](https://cloud.google.com/vertex-ai/docs/vizier/using-vizier) in Python

## Vertex AI Feature Store
- It is a centralized repository to organize, store, and serve machine learning features.
- It aggregates all the different features from different sources and updates them to make them available from a central repository.
- Upon engineers need to model something, they can use the features available in the Feature Store dictionary to build a dataset.
### Benefits
``` 
1. Features are shareable for training or serving tasks: Features are managed and served from a central repository,
which helps maintain consistency across your organization.
2. Features are reusable: Helps save time and reduces duplicative efforts, especially for high-value features.
3. Features are scalable: Features automatically scale to provide low-latency serving, so you can focus on 
developing the logic to create the features without worrying about deployment.
4. Features are easy to use: Feature Store is built on an easy-to-navigate user interface.
```

## Confusion Matrix
|              | Predicted Value |  
|--------------|-----------------|
| **Actual Value** |    AV vs PV    |


|        | P(cat) | N(dog) |
|--------|--------|--------|
| **P(cat)** |   TP   |   FN   |
| **N(dog**) |   FP   |   TN   |

**True Positive:** Things that you correctly predicted. Label says something exists and the model predict it.<br>
**False Negatives (Type II error):** Things that you incorrectly did not predict. Things you exclude when it should be included. Label says something doesn't exist but the model predicts it.<br>
**False Positive (Type I Error):** Things that you incorrectly predict. Things you include when it should be excluded. Label says something doesn;t exist but the model predicts it.<br>
**True Negative:** Things that you correctly excluded.

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
```
- Continuous integration (CI)
- Continuous training (CT)
- Continuous delivery (CD)

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
STEP 1: Data Uploaing

STEP 2: Feature Engineering

**Data Types:**<br>
1. Streaming vs Batch Data
2. Structured vs Unstructured Data

#### Model Training
STEP 1: Training Data

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






## Glossary
**Training-serving skew:** is a difference between model performance during training and performance during serving. This skew can be caused by:
- A discrepancy between how you handle data in the training and serving pipelines.
- A change in the data between when you train and when you serve.
- A feedback loop between your model and your algorithm.



