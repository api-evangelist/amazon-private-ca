# Amazon Private CA

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AWS Private Certificate Authority (AWS Private CA) is a highly available, fully managed private CA service that helps you easily and securely manage the lifecycle of your private certificates. It allows you to create private CA hierarchies and issue X.509 certificates for your internal resources including TLS certificates for microservices, IoT devices, and user authentication.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-private-ca/refs/heads/main/apis.yml)

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
- [JSON-LD](json-ld/amazon-private-ca-context.jsonld)
- [JSONSchema](json-schema/amazon-private-ca-access-description-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-access-method-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-access-method-type-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-action-type-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-api-passthrough-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-asn1subject-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-audit-report-response-format-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-audit-report-status-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-certificate-authority-configuration-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-certificate-authority-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-certificate-authority-status-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-certificate-authority-type-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-certificate-authority-usage-mode-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-create-certificate-authority-audit-report-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-create-certificate-authority-audit-report-response-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-create-certificate-authority-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-create-certificate-authority-response-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-create-permission-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-crl-configuration-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-csr-extensions-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-custom-attribute-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-custom-extension-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-delete-certificate-authority-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-delete-permission-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-delete-policy-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-describe-certificate-authority-audit-report-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-describe-certificate-authority-audit-report-response-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-describe-certificate-authority-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-describe-certificate-authority-response-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-edi-party-name-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-extended-key-usage-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-extended-key-usage-type-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-extensions-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-failure-reason-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-general-name-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-get-certificate-authority-certificate-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-get-certificate-authority-certificate-response-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-get-certificate-authority-csr-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-get-certificate-authority-csr-response-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-get-certificate-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-get-certificate-response-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-get-policy-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-get-policy-response-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-import-certificate-authority-certificate-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-issue-certificate-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-issue-certificate-response-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-key-algorithm-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-key-storage-security-standard-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-key-usage-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-list-certificate-authorities-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-list-certificate-authorities-response-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-list-permissions-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-list-permissions-response-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-list-tags-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-list-tags-response-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-ocsp-configuration-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-other-name-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-permission-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-policy-information-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-policy-qualifier-id-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-policy-qualifier-info-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-put-policy-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-qualifier-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-resource-owner-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-restore-certificate-authority-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-revocation-configuration-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-revocation-reason-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-revoke-certificate-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-s3object-acl-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-signing-algorithm-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-tag-certificate-authority-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-tag-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-untag-certificate-authority-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-update-certificate-authority-request-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-validity-period-type-schema.json)
- [JSONSchema](json-schema/amazon-private-ca-validity-schema.json)
- [JSONStructure](json-structure/amazon-private-ca-access-description-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-access-method-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-access-method-type-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-action-type-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-api-passthrough-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-asn1subject-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-audit-report-response-format-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-audit-report-status-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-certificate-authority-configuration-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-certificate-authority-status-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-certificate-authority-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-certificate-authority-type-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-certificate-authority-usage-mode-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-create-certificate-authority-audit-report-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-create-certificate-authority-audit-report-response-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-create-certificate-authority-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-create-certificate-authority-response-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-create-permission-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-crl-configuration-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-csr-extensions-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-custom-attribute-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-custom-extension-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-delete-certificate-authority-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-delete-permission-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-delete-policy-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-describe-certificate-authority-audit-report-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-describe-certificate-authority-audit-report-response-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-describe-certificate-authority-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-describe-certificate-authority-response-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-edi-party-name-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-extended-key-usage-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-extended-key-usage-type-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-extensions-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-failure-reason-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-general-name-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-get-certificate-authority-certificate-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-get-certificate-authority-certificate-response-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-get-certificate-authority-csr-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-get-certificate-authority-csr-response-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-get-certificate-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-get-certificate-response-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-get-policy-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-get-policy-response-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-import-certificate-authority-certificate-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-issue-certificate-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-issue-certificate-response-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-key-algorithm-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-key-storage-security-standard-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-key-usage-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-list-certificate-authorities-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-list-certificate-authorities-response-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-list-permissions-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-list-permissions-response-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-list-tags-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-list-tags-response-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-ocsp-configuration-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-other-name-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-permission-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-policy-information-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-policy-qualifier-id-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-policy-qualifier-info-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-put-policy-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-qualifier-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-resource-owner-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-restore-certificate-authority-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-revocation-configuration-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-revocation-reason-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-revoke-certificate-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-s3object-acl-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-signing-algorithm-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-tag-certificate-authority-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-tag-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-untag-certificate-authority-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-update-certificate-authority-request-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-validity-period-type-structure.json)
- [JSONStructure](json-structure/amazon-private-ca-validity-structure.json)
- [Example](examples/amazon-private-ca-access-description-example.json)
- [Example](examples/amazon-private-ca-access-method-example.json)
- [Example](examples/amazon-private-ca-api-passthrough-example.json)
- [Example](examples/amazon-private-ca-asn1subject-example.json)
- [Example](examples/amazon-private-ca-certificate-authority-configuration-example.json)
- [Example](examples/amazon-private-ca-certificate-authority-example.json)
- [Example](examples/amazon-private-ca-create-certificate-authority-audit-report-request-example.json)
- [Example](examples/amazon-private-ca-create-certificate-authority-audit-report-response-example.json)
- [Example](examples/amazon-private-ca-create-certificate-authority-request-example.json)
- [Example](examples/amazon-private-ca-create-certificate-authority-response-example.json)
- [Example](examples/amazon-private-ca-create-permission-request-example.json)
- [Example](examples/amazon-private-ca-crl-configuration-example.json)
- [Example](examples/amazon-private-ca-csr-extensions-example.json)
- [Example](examples/amazon-private-ca-custom-attribute-example.json)
- [Example](examples/amazon-private-ca-custom-extension-example.json)
- [Example](examples/amazon-private-ca-delete-certificate-authority-request-example.json)
- [Example](examples/amazon-private-ca-delete-permission-request-example.json)
- [Example](examples/amazon-private-ca-delete-policy-request-example.json)
- [Example](examples/amazon-private-ca-describe-certificate-authority-audit-report-request-example.json)
- [Example](examples/amazon-private-ca-describe-certificate-authority-audit-report-response-example.json)
- [Example](examples/amazon-private-ca-describe-certificate-authority-request-example.json)
- [Example](examples/amazon-private-ca-describe-certificate-authority-response-example.json)
- [Example](examples/amazon-private-ca-edi-party-name-example.json)
- [Example](examples/amazon-private-ca-extended-key-usage-example.json)
- [Example](examples/amazon-private-ca-extensions-example.json)
- [Example](examples/amazon-private-ca-general-name-example.json)
- [Example](examples/amazon-private-ca-get-certificate-authority-certificate-request-example.json)
- [Example](examples/amazon-private-ca-get-certificate-authority-certificate-response-example.json)
- [Example](examples/amazon-private-ca-get-certificate-authority-csr-request-example.json)
- [Example](examples/amazon-private-ca-get-certificate-authority-csr-response-example.json)
- [Example](examples/amazon-private-ca-get-certificate-request-example.json)
- [Example](examples/amazon-private-ca-get-certificate-response-example.json)
- [Example](examples/amazon-private-ca-get-policy-request-example.json)
- [Example](examples/amazon-private-ca-get-policy-response-example.json)
- [Example](examples/amazon-private-ca-import-certificate-authority-certificate-request-example.json)
- [Example](examples/amazon-private-ca-issue-certificate-request-example.json)
- [Example](examples/amazon-private-ca-issue-certificate-response-example.json)
- [Example](examples/amazon-private-ca-key-usage-example.json)
- [Example](examples/amazon-private-ca-list-certificate-authorities-request-example.json)
- [Example](examples/amazon-private-ca-list-certificate-authorities-response-example.json)
- [Example](examples/amazon-private-ca-list-permissions-request-example.json)
- [Example](examples/amazon-private-ca-list-permissions-response-example.json)
- [Example](examples/amazon-private-ca-list-tags-request-example.json)
- [Example](examples/amazon-private-ca-list-tags-response-example.json)
- [Example](examples/amazon-private-ca-ocsp-configuration-example.json)
- [Example](examples/amazon-private-ca-other-name-example.json)
- [Example](examples/amazon-private-ca-permission-example.json)
- [Example](examples/amazon-private-ca-policy-information-example.json)
- [Example](examples/amazon-private-ca-policy-qualifier-info-example.json)
- [Example](examples/amazon-private-ca-put-policy-request-example.json)
- [Example](examples/amazon-private-ca-qualifier-example.json)
- [Example](examples/amazon-private-ca-restore-certificate-authority-request-example.json)
- [Example](examples/amazon-private-ca-revocation-configuration-example.json)
- [Example](examples/amazon-private-ca-revoke-certificate-request-example.json)
- [Example](examples/amazon-private-ca-tag-certificate-authority-request-example.json)
- [Example](examples/amazon-private-ca-tag-example.json)
- [Example](examples/amazon-private-ca-untag-certificate-authority-request-example.json)
- [Example](examples/amazon-private-ca-update-certificate-authority-request-example.json)
- [Example](examples/amazon-private-ca-validity-example.json)
- [NaftikoCapability](capabilities/shared/amazon-private-ca.yaml)

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

- [amazon-private-ca-openapi-original.yaml](openapi/amazon-private-ca-openapi-original.yaml)

### JSON Schema

- [amazon-private-ca-access-description-schema.json](json-schema/amazon-private-ca-access-description-schema.json)
- [amazon-private-ca-access-method-schema.json](json-schema/amazon-private-ca-access-method-schema.json)
- [amazon-private-ca-access-method-type-schema.json](json-schema/amazon-private-ca-access-method-type-schema.json)
- [amazon-private-ca-action-type-schema.json](json-schema/amazon-private-ca-action-type-schema.json)
- [amazon-private-ca-api-passthrough-schema.json](json-schema/amazon-private-ca-api-passthrough-schema.json)
- [amazon-private-ca-asn1subject-schema.json](json-schema/amazon-private-ca-asn1subject-schema.json)
- [amazon-private-ca-audit-report-response-format-schema.json](json-schema/amazon-private-ca-audit-report-response-format-schema.json)
- [amazon-private-ca-audit-report-status-schema.json](json-schema/amazon-private-ca-audit-report-status-schema.json)
- [amazon-private-ca-certificate-authority-configuration-schema.json](json-schema/amazon-private-ca-certificate-authority-configuration-schema.json)
- [amazon-private-ca-certificate-authority-schema.json](json-schema/amazon-private-ca-certificate-authority-schema.json)
- ...and 66 more

### JSON Structure

- [amazon-private-ca-access-description-structure.json](json-structure/amazon-private-ca-access-description-structure.json)
- [amazon-private-ca-access-method-structure.json](json-structure/amazon-private-ca-access-method-structure.json)
- [amazon-private-ca-access-method-type-structure.json](json-structure/amazon-private-ca-access-method-type-structure.json)
- [amazon-private-ca-action-type-structure.json](json-structure/amazon-private-ca-action-type-structure.json)
- [amazon-private-ca-api-passthrough-structure.json](json-structure/amazon-private-ca-api-passthrough-structure.json)
- [amazon-private-ca-asn1subject-structure.json](json-structure/amazon-private-ca-asn1subject-structure.json)
- [amazon-private-ca-audit-report-response-format-structure.json](json-structure/amazon-private-ca-audit-report-response-format-structure.json)
- [amazon-private-ca-audit-report-status-structure.json](json-structure/amazon-private-ca-audit-report-status-structure.json)
- [amazon-private-ca-certificate-authority-configuration-structure.json](json-structure/amazon-private-ca-certificate-authority-configuration-structure.json)
- [amazon-private-ca-certificate-authority-status-structure.json](json-structure/amazon-private-ca-certificate-authority-status-structure.json)
- ...and 66 more

### JSON-LD

- [amazon-private-ca-context.jsonld](json-ld/amazon-private-ca-context.jsonld)

### Examples

- [amazon-private-ca-access-description-example.json](examples/amazon-private-ca-access-description-example.json)
- [amazon-private-ca-access-method-example.json](examples/amazon-private-ca-access-method-example.json)
- [amazon-private-ca-api-passthrough-example.json](examples/amazon-private-ca-api-passthrough-example.json)
- [amazon-private-ca-asn1subject-example.json](examples/amazon-private-ca-asn1subject-example.json)
- [amazon-private-ca-certificate-authority-configuration-example.json](examples/amazon-private-ca-certificate-authority-configuration-example.json)
- [amazon-private-ca-certificate-authority-example.json](examples/amazon-private-ca-certificate-authority-example.json)
- [amazon-private-ca-create-certificate-authority-audit-report-request-example.json](examples/amazon-private-ca-create-certificate-authority-audit-report-request-example.json)
- [amazon-private-ca-create-certificate-authority-audit-report-response-example.json](examples/amazon-private-ca-create-certificate-authority-audit-report-response-example.json)
- [amazon-private-ca-create-certificate-authority-request-example.json](examples/amazon-private-ca-create-certificate-authority-request-example.json)
- [amazon-private-ca-create-certificate-authority-response-example.json](examples/amazon-private-ca-create-certificate-authority-response-example.json)
- ...and 49 more

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [amazon-private-ca.yaml](capabilities/shared/amazon-private-ca.yaml)

### Workflow Capabilities

- [pki-management.yaml](capabilities/pki-management.yaml)

## Vocabulary

- [amazon-private-ca-vocabulary.yaml](vocabulary/amazon-private-ca-vocabulary.yaml)

## Rules

- [amazon-private-ca-spectral-rules.yml](rules/amazon-private-ca-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
