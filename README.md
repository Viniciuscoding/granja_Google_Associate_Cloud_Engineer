# granja_Google_Associate_Cloud_Engineer
Studying for the GCP Associate Cloud Engineer certification

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

### Renewable Energy
```
- Google is one of the world's largest corporate purchasers of wind and solar energy.
- Google has been a hundred percent carbon neutral since 2007.
- Tts data centers energy source will shortly reach a hundred percent renewable energy.
```

### Payments and reliability
```
Google was the first major Cloud provider to deliver per second billing for its IaaS Compute offering.
```
```
Google gives customers the ability to run their applications elsewhere, 
if Google becomes no longer the best provider for their needs
```
#### Billing
GCP provides four tools to help with billing: 
**Budgets and Alerts:** You can define budgets either per billing account or per GCP project. A budget can be a fixed limit or you can tie it to another metric.
**Billing Exports:** lets you store detailed billing information in places where it's easy to retrieve for more detailed analysis, such as a BigQuery dataset or a Cloud storage bucket.
**Reports:** is a visual tool in the GCP console that allows you to monitor your expenditure.
**Quotas:** designed to prevent the over-consumption of resources, whether because of error or malicious attack. There are two types of quotasL rate quotas and allocation quotas
- **Rate Quotas:** reset after a specific time. For example, by default, the Kubernetes Engine service sets a quota of a 1000 calls to its API from each GCP project every 100 seconds. After that 100 seconds, the limit is reset.
- **Allocation Quotas:** govern the number of resources you can have in your projects. For example, by default, each GCP project has a quota allowing it no more than five Virtual Private Cloud networks. Although projects all start with the same quotas, you can change some of them by requesting an increase from Google Cloud support.


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


### Roles and permissions

- On the Navigation menu (Navigation menu), click IAM & Admin. This opens a page that contains a list of users and specifies permissions and roles granted to specific accounts.

[Roles Documentation](https://cloud.google.com/iam/docs/understanding-roles/#primitive%5C_roles)

#### Basic Roles
|**Role Name**|**Title**|**Permissions**|
|-------------|---------|---------------|
|roles/viewer	|Viewer   |Permissions for read-only actions that do not affect state, such as viewing (but not modifying) existing resources or data.|
|roles/editor	|Editor	  |All viewer permissions, plus permissions for actions that modify state, such as changing existing resources.<br>**Note:**<br>*The Editor role contains permissions to create and delete resources for most Google Cloud services. However, it does not contain permissions to perform all actions for all services. For more information about how to check whether a role has the permissions that you need, see [Role types](https://cloud.google.com/iam/docs/roles-overview#role-types).*|
|roles/owner	|Owner	  |All Editor permissions and permissions for the following actions:<br>- Manage roles and permissions for a project and all resources within the project.<br>- Set up billing for a project.<br>**Note:**<br>- *Granting the Owner role at a resource level, such as a Pub/Sub topic, doesn't grant the Owner role on the parent project.*<br>- *Granting the Owner role at the organization level doesn't allow you to update the organization's metadata. However, it allows you to modify all projects and other resources under that organization.*<br>- *To grant the Owner role on a project to a user outside of your organization, you must use the Google Cloud console, not the gcloud CLI. If your project is not part of an organization, you must use the Google Cloud console to grant the Owner role.*|

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









