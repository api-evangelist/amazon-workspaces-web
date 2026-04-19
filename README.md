# Amazon WorkSpaces Web (amazon-workspaces-web)
Amazon WorkSpaces Web is a purpose-built, low-cost, fully managed service that enables secure browser access to internal websites and SaaS applications. It provides persistent browser sessions with built-in security controls, preventing users from downloading content to local devices while maintaining a seamless browsing experience. The service offers 58 API operations for managing portals, user settings, browser policies, network settings, trust stores, and IP access controls.

**URL:** [https://raw.githubusercontent.com/api-evangelist/amazon-workspaces-web/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-workspaces-web/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, End User Computing, Secure Browser, Virtual Desktop, Zero Trust

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon WorkSpaces Web API
The Amazon WorkSpaces Web API provides programmatic access to create and manage web portals, network settings, user access logging, user settings, browser settings, and trust store configurations for secure browser deployments. 58 operations covering portals, user settings, browser policies, network settings, trust stores, and IP access controls.

**Human URL:** [https://aws.amazon.com/workspaces/web/](https://aws.amazon.com/workspaces/web/)

#### Tags:

 - AWS, End User Computing, Secure Browser, Zero Trust

#### Properties

- [Documentation](https://docs.aws.amazon.com/workspaces-web/latest/adminguide/)
- [APIReference](https://docs.aws.amazon.com/workspaces-web/latest/APIReference/)
- [GettingStarted](https://docs.aws.amazon.com/workspaces-web/latest/adminguide/getting-started.html)
- [Pricing](https://aws.amazon.com/workspaces/web/pricing/)
- [FAQ](https://aws.amazon.com/workspaces/web/faqs/)
- [OpenAPI](openapi/amazon-workspaces-web-openapi-original.yaml)
- [JSONSchema](json-schema/workspaces-web-portal-schema.json)
- [JSONLD](json-ld/amazon-workspaces-web-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/workspaces/web/)
- [Documentation](https://docs.aws.amazon.com/workspaces-web/latest/adminguide/)
- [Console](https://console.aws.amazon.com/workspaces-web/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [Login](https://aws.amazon.com/console/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [GitHubOrganization](https://github.com/aws)

## Features

| Name | Description |
|------|-------------|
| Secure Browser Portals | Purpose-built browser portals that provide secure access to internal websites and SaaS applications without VPN requirements. |
| Data Loss Prevention Controls | Built-in controls to prevent users from downloading, uploading, printing, or copying content to local devices. |
| Browser Policy Management | Configurable browser policies to control features like clipboard access, printing, and file transfers. |
| Network Isolation | VPC-based network settings to isolate browser sessions within enterprise network boundaries. |
| Trust Store Management | SSL certificate trust stores for validating internal website certificates in secure browser sessions. |
| IP Access Controls | IP-based access rules to restrict portal access to specific corporate IP ranges or geographic locations. |
| User Access Logging | Detailed session logging for audit and compliance purposes with Kinesis data stream integration. |
| Identity Integration | SAML-based identity provider integration for single sign-on to secure browser portal sessions. |

## Use Cases

| Name | Description |
|------|-------------|
| Secure Third-Party Access | Provide contractors and third-party vendors secure access to internal tools without requiring VPN or device enrollment. |
| BYOD Security | Enable bring-your-own-device policies while maintaining security controls over corporate application access. |
| Compliance-Driven Browsing | Enforce data handling compliance requirements through browser-level controls for regulated industries. |
| SaaS Application Security | Provide secure, controlled access to SaaS applications with session recording and data exfiltration prevention. |
| Developer Sandbox Environments | Create isolated browser environments for development and testing of internal web applications. |

## Integrations

| Name | Description |
|------|-------------|
| AWS IAM Identity Center | Single sign-on integration for WorkSpaces Web portal authentication. |
| Amazon Kinesis | User access logging integration to stream session data for analysis. |
| AWS KMS | Encryption key management for browser settings and data at rest. |
| Amazon VPC | VPC integration for network isolation of browser sessions. |
| AWS Certificate Manager | Certificate management for trust store and SSL configurations. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon WorkSpaces Web OpenAPI](openapi/amazon-workspaces-web-openapi-original.yaml)

### JSON Schema

195 JSON Schema files extracted from the OpenAPI specification.

### JSON Structure

195 JSON Structure files converted from JSON Schema definitions.

### JSON-LD

- [Amazon WorkSpaces Web Context](json-ld/amazon-workspaces-web-context.jsonld)

### Examples

79 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon WorkSpaces Web API](capabilities/shared/workspaces-web.yaml) — 6 operations for portal, user settings, browser settings, network, and trust store management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Secure Browser Management](capabilities/secure-browser-management.yaml) | Amazon WorkSpaces Web | 6 | IT Administrator, Security Engineer |

## Vocabulary

- [Amazon WorkSpaces Web Vocabulary](vocabulary/amazon-workspaces-web-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 7 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon WorkSpaces Web Spectral Rules](rules/amazon-workspaces-web-spectral-rules.yml) — 18 rules across 9 categories enforcing Amazon WorkSpaces Web API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
