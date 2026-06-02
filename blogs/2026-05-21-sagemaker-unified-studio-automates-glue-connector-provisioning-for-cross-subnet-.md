---
title: SageMaker Unified Studio automates Glue connector provisioning for cross-subnet
  job retries
url: https://aws.amazon.com/about-aws/whats-new/2026/05/sagemaker-unified-studio-glue/
date: '2026-05-21'
author: aws@amazon.com
feed_url: https://aws.amazon.com/rss
---
Amazon SageMaker Unified Studio now supports automatic creation of connections for Glue job retries across subnets to improve data pipeline resilience. This helps organizations running business-critical data pipelines reduce unplanned downtime and meet their SLAs — without requiring engineers to manually configure backup connectors or intervene during subnet failures. With this launch, SageMaker Unified Studio automates the provisioning of Glue connectors across subnets defined in the domain VPC configuration. Administrators can define their domain VPC with multiple private subnets across availability zones, and the system provisions the connectors needed for all new projects so that failed jobs can be retried on an alternate subnet automatically. If a Glue job fails because the primary subnet is unavailable due to IP address exhaustion or availability zone degradation, the job can be retried on a connector in a different subnet. No user action is needed beyond the initial VPC configuration on the domain. This feature is available in all AWS Regions where Amazon SageMaker Unified Studio is available. To learn more, visit the Amazon SageMaker Unified Studio documentation .
