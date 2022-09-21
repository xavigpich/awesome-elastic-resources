# Awesome Elastic Resources
<img src="https://images.contentstack.io/v3/assets/bltefdd0b53724fa2ce/blt280217a63b82a734/6202d3378b1f312528798412/elastic-logo.svg" alt="elastic-logo" style="height:80px;"/>


A curated list of Elastic related resources. From products, general information, tooling to blogs and guides.

## Table of Contents

1. [Elastic Stack](#elastic-stack)
2. [General Information](#general-information)
3. [Detections & Alerting](#detections--alerting)
4. [Monitoring & Diagnostics](#monitoring--diagnostics)
5. [Observability, APM](#observability-apm)
6. [Orchestration in Kubernetes](#orchestration-in-kubernetes)
7. [Configuration Management](#configuration-management)
8. [Clients & SDKs](#clients--sdks)
9. [Blogs, Guides, Best Practices](#blogs-guides-best-practices)
10. [Webinars](#webinars)
11. [Additional Resources](#additional-resources)


## Elastic Stack
* Elasticsearch - [Link](https://github.com/elastic/elasticsearch)
    - Elasticsearch is the distributed, RESTful search and analytics engine at the heart of the Elastic Stack
* Logstash - [Link](https://github.com/elastic/logstash)
    - Logstash is a server-side data processing pipeline that ingests data from a multitude of sources simultaneously, transforms it, and then sends it to your favorite "stash."
* Kibana - [Link](https://github.com/elastic/kibana)
    - Kibana is your window into the Elastic Stack. Specifically, it's a browser-based analytics and search dashboard for Elasticsearch
* Beats - [Link](https://github.com/elastic/beats)
    - Beats are lightweight data shippers, written in Go, that you install on your servers to capture all sorts of operational data
* Elastic Agent - [Link](https://github.com/elastic/elastic-agent)
    - Elastic Agent is a single, unified way to add monitoring for logs, metrics, and other types of data to a host. It can also protect hosts from security threats, query data from operating systems, forward data from remote services or hardware, and more
* Fleet Server - [Link](https://github.com/elastic/fleet-server)
    - Fleet Server is a component that connects Elastic Agents to Fleet. It supports many Elastic Agent connections and serves as a control plane for updating agent policies, collecting status information, and coordinating actions across Elastic Agents
* ECS - [Link](https://github.com/elastic/ecs)
    - The Elastic Common Schema (ECS) defines a common set of fields for ingesting data into Elasticsearch. A common schema helps you correlate data from sources like logs and metrics or IT operations analytics and security analytics.


## General Information
* Elastic Official Website - [Link](https://www.elastic.co)
* Elastic Official Documentation - [Link](https://www.elastic.co/guide/index.html)
* Free Trial & Downloads - [Link](https://www.elastic.co/downloads)
* Elastic Pricing - [Link](https://www.elastic.co/pricing)
* Elastic Integrations - [Link](https://www.elastic.co/integrations/data-integrations)
* APIs Documentation
  * Elasticsearch API - [Link](https://www.elastic.co/guide/en/elasticsearch/reference/current/rest-apis.html)
  * Kibana API - [Link](https://www.elastic.co/guide/en/kibana/master/api.html)

## Detections & Alerting
* Elastic’s Detection Rules - [Link](https://github.com/elastic/detection-rules)
    - Rules for Elastic Security's detection engine
* ElastAlert - [Link](https://github.com/yelp/elastalert)
    - ElastAlert is a simple framework for alerting on anomalies, spikes, or other patterns of interest from data in Elasticsearch.
* ElastAlert2 - [Link](https://github.com/jertel/elastalert2)
    - ElastAlert 2 is a standalone software tool for alerting on anomalies, spikes, or other patterns of interest from data in Elasticsearch and OpenSearch.
    
## Monitoring & Diagnostics
* Elasticsearch Prometheus Exporter - [Link](https://github.com/prometheus-community/elasticsearch_exporter)
    - Elasticsearch stats exporter for Prometheus
* ECK Diagnostics - [Link](https://github.com/elastic/eck-diagnostics)
    - Diagnostic tooling for ECK installations
* Elasticsearch & Logstash Diagnostics - [Link](https://github.com/elastic/support-diagnostics)
    - Diagnostics tooling for Elasticsearch and Logstash installations
    
## Observability, APM
* Application Performance Monitoring - [Link](https://github.com/elastic/apm)
    - Application Performance Monitoring -  Accelerate development and improve application code

## Orchestration in Kubernetes
* Elastic Cloud on Kubernetes (ECK) - [Link](https://github.com/elastic/cloud-on-k8s)
    - Elastic Cloud on Kubernetes automates the deployment, provisioning, management, and orchestration of Elasticsearch, Kibana, APM Server, Enterprise Search, Beats, Elastic Agent, and Elastic Maps Server on Kubernetes based on the operator pattern.
* Elastic Stack Kubernetes Helm Charts - [Link](https://github.com/elastic/helm-charts)
    - These Helm charts are designed to be a lightweight way to configure Elastic official Docker images.
* Elasticsearch Openshift Operator - [Link](https://github.com/openshift/elasticsearch-operator)
    - Elasticsearch operator to run Elasticsearch cluster on top of Openshift and Kubernetes
* Elasticsearch Operator - [Link](https://github.com/zalando-incubator/es-operator)
    - Kubernetes Operator for Elasticsearch

## Configuration Management
* Elasticsearch Ansible [archived] - [Link](https://github.com/elastic/ansible-elasticsearch)
* Elasticsearch Puppet module (Forge) - [Link](https://forge.puppet.com/modules/elastic/elasticsearch)
* Elasticsearch Puppet module (Voxpupuli) - [Link](https://github.com/voxpupuli/puppet-elasticsearch)
* Elasticsearch Chef Cookbook - [Link](https://github.com/elastic/cookbook-elasticsearch)
* Elasticsearch Curator - [Link](https://github.com/elastic/curator)

## Clients & SDKs
* Elasticsearch Go client - [Link](https://github.com/elastic/go-elasticsearch)
* Elasticsearch Python client - [Link](https://github.com/elastic/elasticsearch-py)
* Elasticsearch Java client - [Link](https://github.com/elastic/elasticsearch-java)
* Elasticsearch Ruby client - [Link](https://github.com/elastic/elasticsearch-ruby)
* Elasticsearch PHP client - [Link](https://github.com/elastic/elasticsearch-php)
* Elasticsearch Javascript client - [Link](https://github.com/elastic/elasticsearch-js)
* Elasticsearch Rust client - [Link](https://github.com/elastic/elasticsearch-rs)
* Elasticsearch Cloud SDK - [Link](https://github.com/elastic/cloud-sdk-go)
* Elasticsearch Azure SDK - [Link](https://github.com/elastic/azure-sdk-for-go)

## Blogs, Guides, Best Practices
### Security

* Elastic on Elastic Deep Dive Into Our Siem Architecture - [Link](https://www.elastic.co/blog/elastic-on-elastic-deep-dive-into-our-siem-architecture)
* Fleet & Elastic Agent Overview - [Link](https://www.elastic.co/guide/en/fleet/current/fleet-overview.html)
* Automate Threat Detections and Avoid False Positives - [Link](https://www.elastic.co/elasticon/archive/2021/security/europe/automate-threat-detections-and-avoid-false-positives)
* Secure your Cloud with Cloud Workload Protection in Elastic Security - [Link](https://www.elastic.co/blog/secure-your-cloud-with-cloud-workload-protection-in-elastic-security)
* How To Build a Malware Analysis Sandbox with Elastic Security - [Link](https://www.elastic.co/blog/how-to-build-a-malware-analysis-sandbox-with-elastic-security)
* Full Time PII Data Protection - How Ranstad Uses Elastic Security to Keep Client Data Secure - [Link](https://www.elastic.co/elasticon/archive/2021/security/europe/full-time-pii-data-protection-how-randstad-uses-elastic-security-to-keep-client-data-secure)

### Observability

* Building Software Reliability With Distributed Tracing - [Link](https://www.elastic.co/blog/building-software-reliability-with-distributed-tracing) 
* Building Resilience for Applications and Services with Elastic Observability - [Link](https://www.elastic.co/blog/building-resilience-for-applications-and-services-with-elastic-observability) 
* APM Correlations - Elastic Observability Root Cause Transactions - [Link](https://www.elastic.co/blog/apm-correlations-elastic-observability-root-cause-transactions) 
* Automate Verification of Deployments with Argo Rollouts and Elastic Observability - [Link](https://www.elastic.co/blog/automate-verification-of-deployments-with-argo-rollouts-and-elastic-observability) 

### Enterprise Search

* Building a Search Experience with Elastic - [Link](https://www.elastic.co/blog/building-a-search-experience-with-elastic)
* 6 Ways Elastic Enterprise Search Creates a Competitive Edge in Ecommerce - [Link](https://www.elastic.co/blog/6-ways-elastic-enterprise-search-creates-a-competitive-edge-in-ecommerce)
* Harness the Power of the Cloud to Build Scalable Search Solutions - [Link](https://www.elastic.co/blog/harness-the-power-of-the-cloud-to-build-scalable-search-solutions)
* How Search Enables Role Based Data Classification Sharing Across Government - [Link](https://www.elastic.co/blog/how-search-enables-role-based-data-classification-sharing-across-government)

### Capacity Planning & Cluster Sizing

* Elasticsearch Sizing and Capacity Planning - [Link](https://www.elastic.co/pdf/elasticsearch-sizing-and-capacity-planning.pdf)
* Sizing Hot Warm Architectures for Logging and Metrics in the Elasticsearch Service on Elastic Cloud - [Link](https://www.elastic.co/blog/sizing-hot-warm-architectures-for-logging-and-metrics-in-the-elasticsearch-service-on-elastic-cloud)
* Implementing Hot Warm Cold in Elasticsearch With Index Lifecycle Management (ILM) - [Link](https://www.elastic.co/blog/implementing-hot-warm-cold-in-elasticsearch-with-index-lifecycle-management)
* How Many Shards Should I Have in my Elasticsearch Cluster? - [Link](https://www.elastic.co/blog/how-many-shards-should-i-have-in-my-elasticsearch-cluster)
* Bonsai.io - Capacity Planning - [Link](https://docs.bonsai.io/article/123-capacity-planning)
* 7 Tips for Better Elasticsearch Benchmarks - [Link](https://www.elastic.co/blog/seven-tips-for-better-elasticsearch-benchmarks)
* Clarification About Recommended Memory-Disk Ratio of 1-30 - [Link](https://discuss.elastic.co/t/clarification-about-recommended-memory-disk-ratio-of-1-30/221547/4)

## Webinars

### Security

### Observability

### Enterprise Search


## Additional Resources 
### Training
* Elastic Training - [Link](https://www.elastic.co/training)
* Elastic Free Training - [Link](https://www.elastic.co/training/free)
* Elastic Training Subscriptions - [Link](https://www.elastic.co/training/subscriptions)
* Elastic Private Training - [Link](https://www.elastic.co/training/private-training)

### Certifications
* Elastic Certified Engineer - [Link](https://www.elastic.co/training/elastic-certified-engineer-exam)
* Elastic Certified Analyst - [Link](https://www.elastic.co/training/elastic-certified-analyst-exam)
* Elastic Certified Observability - [Link](https://www.elastic.co/training/elastic-certified-observability-engineer)

### Other
* Elastic Blogs - [Link](https://www.elastic.co/blog)
    - Elastic Blog: Stories, Tutorials, Releases
* Elastic Discussion Forums - [Link](https://discuss.elastic.co)
    - Find advice and lend a helping hand
* Elastic Slack Community - [Link](https://communityinviter.com/apps/elasticstack/elastic-community)
    - Join the Elastic Slack to chat with other users and ask for advice
* Elastic Contributors Program - [Link](https://www.elastic.co/community/contributor)
    - Be recognised for your contributions to the Elastic community
* Elastic Security Labs - [Link](https://www.elastic.co/security-labs)
    - Latest research from Elastic's Security engineers, practitioners and researchers
* Elastic Upcoming Events - [Link](https://www.elastic.co/events)
* Elastic YouTube channel - [Link](https://www.youtube.com/c/Elastic)
* Elastic Community YouTube channel - [Link](https://www.youtube.com/c/OfficialElasticCommunity)
* Reddit - [Link](https://www.reddit.com/r/elasticsearch)
