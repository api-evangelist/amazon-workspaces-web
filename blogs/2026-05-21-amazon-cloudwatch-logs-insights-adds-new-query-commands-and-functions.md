---
title: Amazon CloudWatch Logs Insights adds new query commands and functions
url: https://aws.amazon.com/about-aws/whats-new/2026/06/amazon-cloudwatch-logs-insights/
date: '2026-05-21'
author: aws@amazon.com
feed_url: https://aws.amazon.com/rss
---
Amazon CloudWatch Logs Insights query language now supports 13 new commands and functions that give you more powerful ways to query, transform, and analyze your logs. Customers analyzing logs in CloudWatch Logs Insights often need to perform string manipulation, encode or decode field values, parse non-JSON log formats, or calculate geographic distances, so they can derive deeper insights from their logs. With this launch, CloudWatch Logs Insights provides new string and numeric functions (round, startswith, endswith, case, regex_replace, haversine), encoding and decoding functions (urlencode, urldecode, base64encode, base64decode), and new parse and analysis commands (parse logfmt, expand, relevantfields). You can now filter logs by string prefixes, decode Base64 payloads inline, parse logfmt structured logs into fields, expand nested JSON arrays into individual records, calculate distances between coordinates, and automatically surface relevant fields in high-cardinality log groups. These commands and functions are available today in all commercial AWS Regions. To learn more, see the Amazon CloudWatch Logs documentation .
