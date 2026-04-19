# Amazon Private CA (amazon-private-ca)
AWS Private Certificate Authority (AWS Private CA) is a highly available, fully managed private CA service that helps you easily and securely manage the lifecycle of your private certificates. It allows you to create private CA hierarchies and issue X.509 certificates for your internal resources including TLS certificates for microservices, IoT devices, and user authentication.

**URL:** [https://aws.amazon.com/private-ca/](https://aws.amazon.com/private-ca/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Certificate Authority, Certificates, PKI, Security, X.509, TLS, IoT

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### AWS Private CA API
The AWS Private CA API provides programmatic access to create and manage private certificate authorities, issue X.509 certificates, manage certificate revocation lists, configure audit reports, and control permissions and policies for private PKI infrastructure.

**Human URL:** [https://aws.amazon.com/private-ca/](https://aws.amazon.com/private-ca/)

#### Tags:

 - Certificates, PKI, Security, Certificate Authority, X.509

#### Properties

- [Documentation](https://docs.aws.amazon.com/privateca/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-private-ca-openapi-original.yaml)
- [GettingStarted](https://aws.amazon.com/private-ca/getting-started/)
- [Pricing](https://aws.amazon.com/private-ca/pricing/)
- [FAQ](https://aws.amazon.com/private-ca/faqs/)
- [Authentication](https://docs.aws.amazon.com/general/latest/gr/signature-version-4.html)
- [RateLimits](https://docs.aws.amazon.com/privateca/latest/userguide/PcaLimits.html)

## Common Properties

- [Portal](https://aws.amazon.com/private-ca/)
- [Documentation](https://docs.aws.amazon.com/privateca/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/security/tag/aws-certificate-manager-private-ca/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/acm-pca/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [SpectralRules](rules/amazon-private-ca-spectral-rules.yml)
- [NaftikoCapability](capabilities/pki-management.yaml)
- [Vocabulary](vocabulary/amazon-private-ca-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Private CA Hierarchy | Create root and subordinate CA hierarchies for complete control over your PKI infrastructure. |
| X.509 Certificate Issuance | Issue end-entity and CA certificates signed by your private CAs for internal resources. |
| Certificate Revocation | Revoke compromised or expired certificates with CRL and OCSP support. |
| Audit Reports | Generate detailed audit reports of all certificate issuance activity stored in S3. |
| Short-Lived Certificates | Issue short-lived certificates to reduce revocation overhead and improve security posture. |
| Custom Templates | Use certificate templates to standardize certificate extensions and constraints. |
| IAM Integration | Control access to CA operations using fine-grained IAM policies and resource-based policies. |
| High Availability | Fully managed, highly available service with automatic failover across AWS Availability Zones. |

## Use Cases

| Name | Description |
|------|-------------|
| TLS for Internal Services | Issue TLS certificates for microservices, APIs, and internal web applications. |
| IoT Device Authentication | Provision unique X.509 certificates to IoT devices for mutual TLS authentication. |
| User and Workload Identity | Issue certificates for user authentication and workload identity in zero-trust architectures. |
| Code Signing | Sign software artifacts and container images with private CA-issued certificates. |
| VPN and Network Security | Issue certificates for VPN clients and network devices for mutual authentication. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Certificate Manager | Integrate Private CA with ACM to manage and deploy certificates on AWS services. |
| AWS IoT Core | Use Private CA to provision certificates for IoT devices connecting to AWS IoT Core. |
| Kubernetes | Integrate with cert-manager for automated certificate provisioning in Kubernetes clusters. |
| Amazon EKS | Issue certificates for service mesh and pod-to-pod TLS in EKS clusters. |
| AWS Secrets Manager | Store and rotate private keys associated with issued certificates. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AWS Private CA OpenAPI (full - 23 operations)](openapi/amazon-private-ca-openapi-original.yaml)

### JSON Schema

76 schema files covering all AWS Private CA API resource types including certificate authorities, certificates, revocation, permissions, and policies.

### JSON Structure

76 JSON Structure files converted from JSON Schema with strict typing.

### JSON-LD

- [Amazon Private CA Context](json-ld/amazon-private-ca-context.jsonld)

### Examples

59 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Private CA API](capabilities/shared/amazon-private-ca.yaml) — 6 operations for PKI management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [PKI Management](capabilities/pki-management.yaml) | AWS Private CA API | 6 | Security Engineer, Platform Engineer |

## Vocabulary

- [Amazon Private CA Vocabulary](vocabulary/amazon-private-ca-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Private CA Spectral Rules](rules/amazon-private-ca-spectral-rules.yml) — 20 rules across 9 categories enforcing AWS Private CA API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
