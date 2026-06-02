---
title: AWS Transfer Family web apps now support federated permissions with IAM Identity
  Center across AWS Regions
url: https://aws.amazon.com/about-aws/whats-new/2026/05/aws-transfer-family-federated-permissions-across-regions/
date: '2026-05-20'
author: aws@amazon.com
feed_url: https://aws.amazon.com/rss
---
AWS Transfer Family web apps now support federated permissions with AWS IAM Identity Center across multiple AWS Regions. Previously, you could only create Transfer Family web apps in the Region where your IAM Identity Center instance was enabled. With IAM Identity Center's support for multi-Region replication, you can now replicate your identity configurations to another Region and create Transfer Family web apps there, reducing latency and improving reliability for your users. After you enable a new Region in IAM Identity Center, you can create a Transfer Family web app in that Region. IAM Identity Center automatically replicates your workforce identities to the new Region, eliminating the need to reconfigure user credentials. Administrators can manage fine-grained permissions using the same workforce identities already configured in IAM Identity Center, and your Transfer Family web app users can sign in immediately using their existing credentials. To get started, visit the Transfer Family User Guide . To enable IAM Identity Center across multiple Regions, refer to the IAM Identity Center User Guide . For regional availability, visit AWS Capabilities .
