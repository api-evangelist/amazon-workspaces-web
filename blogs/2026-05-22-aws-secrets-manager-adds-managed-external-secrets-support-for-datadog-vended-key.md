---
title: AWS Secrets Manager adds managed external secrets support for Datadog vended
  keys and Snowflake Programmatic Access Tokens
url: https://aws.amazon.com/about-aws/whats-new/2026/05/secrets-manager-managed-external-secrets-datadog-snowflake/
date: '2026-05-22'
author: aws@amazon.com
feed_url: https://aws.amazon.com/rss
---
AWS Secrets Manager now extends its managed external secrets capability to include Datadog Keys and Snowflake Programmatic Access Tokens (PATs). Managed external secrets enable customers to automatically rotate third-party credentials directly from AWS Secrets Manager by offering first-class integration with supported third-party services. With this launch, you can manage rotation for three types of Datadog credentials — API keys, Application keys, and admin credential pairs for service accounts. For Snowflake, you can now rotate Programmatic Access Tokens using Snowflake's native authentication, with a configurable grace period that allows applications to seamlessly transition to new tokens without interruption. These new integrations join existing managed external secrets integrations with BigID, Confluent Cloud, MongoDB Atlas, and Salesforce, enabling customers to manage third-party software vended secrets. Datadog and Snowflake PAT managed external secrets are available in all AWS Regions where AWS Secrets Manager managed external secrets is supported. To learn more, visit the AWS Secrets Manager managed external secrets documentation .
