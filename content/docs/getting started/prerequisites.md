---
title: "Prerequisites"
description: "Guides lead a user through a specific task they want to accomplish, often with a sequence of steps."
summary: ""
date: 2023-09-07T16:04:48+02:00
lastmod: 2023-09-07T16:04:48+02:00
draft: false
menu:
  docs:
    parent: ""
    identifier: "example-6a1a6be4373e933280d78ea53de6158f"
weight: 10
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---
The following pre-requisites are required to install ConsulKVCommander:

- go version v1.20.0+
- docker version 17.03+.
- kubectl version v1.11.3+.
- Access to a Kubernetes v1.11.3+ cluster.

Moreover, the following pre-requisites are required to ensure its optimal functioning:

- An account on PagerDuty setup with its token set as the environment variable `PAGERDUTY_TOKEN`
- A "from" sender E-mail address set as the environment variable `PAGERDUTY_SENDER` which would impersonate the sender when raising incident E-mails.
- An S3 bucket setup with its access keys (with relevant read and write privileges) setup as the environment variables `AWS_ACCESS_KEY` and `AWS_SECRET_ACCESS_KEY`
- A sheet uploaded to that S3 bucket which would act as the storage for audited reports from ConsulKVCommander. Export its link to the environment variable "SHEET_LINK"

