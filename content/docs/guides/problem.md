---
title: "Why ConsulKVCommander?"
description: "Guides lead a user through a specific task they want to accomplish, often with a sequence of steps."
summary: ""
date: 2023-09-07T16:04:48+02:00
lastmod: 2023-09-07T16:04:48+02:00
draft: false
menu:
  docs:
    parent: ""
    identifier: "example-6a1a6be4373e933280d78ea53de6158x"
weight: 20
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

The widespread progression of the usage of Kubernetes has brought forth significant challenges of efficiently and securely managing the configuration data backed by Hashicorp Consul KV: 

* **Data Security Risks**: Sensitive data management in Kubernetes carries risks of breaches and noncompliance.
* **Resource Inefficiency**: Inefficiencies arise from improper resource allocation, affecting system performance and costs.
* **Operational Complexity**: Manual configuration management increases complexity and error potential.
* **Audit Shortfalls**: The lack of automated auditing and alerting delays issue detection and resolution.

This realizes a pressing need for a Kubernetes-native tool which can take on all these requirements such as being able to detect, analyze, notify and adaptively report about any downtime or exposures of sensitive data or overly large payloads in the ConsulKV stores. Not only  that, the tool should be capable of migrating the ConsulKV Store’s data selectively into the user’s cluster in a manner with which it can be  easily consumed by the deployed apps on the same cluster. Considering the fleeting nature of workloads on Kubernetes, it can’t be  ignored for such a tool to have a self-adaptive mechanism to restore consistency wherever and whenever need be.
