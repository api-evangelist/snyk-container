# Snyk Container

Snyk Container helps developers find and fix vulnerabilities in container images and Kubernetes workloads. It integrates into existing development workflows to provide continuous security monitoring throughout the container lifecycle, scanning Docker images, Kubernetes manifests, and Helm charts for known CVEs and misconfigurations.

## APIs

### Snyk Container

Vulnerability scanning and remediation for container images and Kubernetes workloads.

- **Documentation:** https://docs.snyk.io/scan-using-snyk/snyk-container
- **Getting Started:** https://docs.snyk.io/getting-started
- **REST API:** https://apidocs.snyk.io/
- **OpenAPI Spec:** [openapi/snyk-container-openapi.yml](openapi/snyk-container-openapi.yml)

**Key capabilities:**
- List and manage container scanning projects (images, Kubernetes monitors, Helm releases)
- Retrieve vulnerability issues with severity and status filtering
- Generate SBOMs in CycloneDX 1.4 and SPDX 2.3 formats
- Manage container registry scan targets
- Look up package-level CVEs by package URL (purl)

## Artifacts

| Type | File |
|------|------|
| OpenAPI Spec | [openapi/snyk-container-openapi.yml](openapi/snyk-container-openapi.yml) |
| JSON Schema (Project) | [json-schema/snyk-container-project-schema.json](json-schema/snyk-container-project-schema.json) |
| JSON Schema (Issue) | [json-schema/snyk-container-issue-schema.json](json-schema/snyk-container-issue-schema.json) |
| JSON Structure | [json-structure/snyk-container-project-structure.json](json-structure/snyk-container-project-structure.json) |
| JSON-LD Context | [json-ld/snyk-container-context.jsonld](json-ld/snyk-container-context.jsonld) |
| Spectral Rules | [rules/snyk-container-rules.yml](rules/snyk-container-rules.yml) |
| Vocabulary | [vocabulary/snyk-container-vocabulary.yml](vocabulary/snyk-container-vocabulary.yml) |
| Example: List Projects | [examples/snyk-container-list-projects-example.json](examples/snyk-container-list-projects-example.json) |
| Example: List Issues | [examples/snyk-container-list-issues-example.json](examples/snyk-container-list-issues-example.json) |

## Capabilities

### Workflows

| Capability | File | Description |
|-----------|------|-------------|
| Container Security | [capabilities/container-security.yaml](capabilities/container-security.yaml) | Unified container security scanning, vulnerability tracking, SBOM generation, and registry management |

### Shared Definitions

| API | File |
|-----|------|
| Snyk Container | [capabilities/shared/snyk-container.yaml](capabilities/shared/snyk-container.yaml) |

## Links

- **Website:** https://snyk.io/
- **Documentation:** https://docs.snyk.io/scan-using-snyk/snyk-container
- **GitHub Org:** https://github.com/snyk
- **CLI:** https://github.com/snyk/cli
- **Kubernetes Monitor:** https://github.com/snyk/kubernetes-monitor
- **Pricing:** https://snyk.io/plans/
- **Blog:** https://snyk.io/blog/
- **Sign Up:** https://app.snyk.io/signup
