# FAIL Compliance

# Free AI License Compliance Specification

**Version:** 1.0.0

**Status:** Stable

**Document ID:** FAIL-COMPLIANCE-1.0

**Maintained by:** Free AI License Foundation

---

# Overview

The FAIL Compliance Specification defines the minimum technical, legal, and documentation requirements for projects distributed under the Free AI License (FAIL).

Its purpose is to ensure consistency, transparency, interoperability, and trust across the FAIL ecosystem.

Projects that satisfy these requirements may publicly declare themselves **FAIL Compliant**.

---

# Objectives

The FAIL Compliance Specification aims to:

- Define minimum compliance requirements.
- Protect attribution.
- Improve transparency.
- Encourage responsible AI development.
- Simplify project verification.
- Promote interoperability.

---

# Compliance Levels

## FAIL Core

Minimum requirements required for every project.

## FAIL Plus

Additional recommended practices for mature open-source AI projects.

## FAIL Enterprise

Best practices for organizations operating AI at scale.

---

# FAIL Core Requirements

A project MUST include:

- LICENSE.md
- README.md
- FAIL.md
- FAIL.toml
- SECURITY.md
- CHANGELOG.md

The project MUST clearly identify the FAIL License version being used.

---

# Documentation

Projects SHOULD document:

- Installation
- Usage
- Features
- Limitations
- Supported platforms
- AI capabilities
- Safety considerations

---

# Attribution

Projects MUST preserve attribution to original authors.

Copyright notices MUST NOT be removed.

The FAIL License MUST remain included within the repository.

---

# Repository Requirements

Repositories SHOULD be publicly accessible whenever possible.

Repositories SHOULD include:

- GitHub Issues
- Contribution Guidelines
- Version History
- Security Policy

---

# AI Components

Projects MUST identify which components are covered by FAIL.

Possible components include:

- Source Code
- AI Models
- Model Weights
- Datasets
- AI Agents
- APIs
- SDKs
- Prompt Libraries
- Documentation
- Training Pipelines
- User Interfaces

---

# FAIL.toml

Every compliant project SHOULD include a valid FAIL.toml manifest in the repository root.

The manifest identifies:

- License version
- Registry ID
- Organization
- Compliance level
- Covered components

---

# Security

Projects SHOULD:

- Publish a security policy.
- Document responsible disclosure procedures.
- Maintain dependency updates.
- Address known vulnerabilities.

---

# Transparency

Projects SHOULD publish:

- Current version
- Release history
- Public roadmap
- Documentation updates

---

# Registry

Projects may request inclusion in the FAIL Registry.

Registered projects receive:

- Registry ID
- Public listing
- Compliance verification status

Registration does not imply endorsement by the Free AI License Foundation.

---

# Compliance Badge

Projects satisfying FAIL Core requirements may display:

```text
FAIL Compliant
```

Projects satisfying additional requirements may display:

```text
FAIL Plus
```

or

```text
FAIL Enterprise
```

in accordance with future specifications.

---

# Verification

Compliance may be:

- Self-declared by the project maintainers.
- Community reviewed.
- Verified by the Free AI License Foundation, if such a verification program exists.

Verification status should always be clearly indicated.

---

# Non-Compliance

Projects must not claim FAIL compliance if they:

- Remove required attribution.
- Omit the FAIL License.
- Misrepresent compliance status.
- Publish false registry information.

The Free AI License Foundation may remove or update registry entries when inaccurate information is identified.

---

# Versioning

This specification follows Semantic Versioning.

Example:

FAIL Compliance 1.0.0

Major versions introduce incompatible changes.

Minor versions introduce new requirements or recommendations.

Patch versions clarify wording or fix errors.

---

# Future Work

Future versions may define:

- Automated compliance validation.
- Metadata schemas.
- Digital signatures.
- AI provenance support.
- Model cards.
- Dataset documentation.
- Certification criteria.
- Security scoring.

---

# Compliance Checklist

A FAIL Core project should include:

- ✅ LICENSE.md
- ✅ README.md
- ✅ FAIL.md
- ✅ FAIL.toml
- ✅ CHANGELOG.md
- ✅ SECURITY.md
- ✅ CONTRIBUTING.md
- ✅ Code of Conduct
- ✅ Public version information
- ✅ Attribution preserved

---

# Mission

The purpose of FAIL Compliance is not to restrict innovation.

Its purpose is to create a common foundation that helps developers, organizations, researchers, and users understand what it means for an Artificial Intelligence project to be compatible with the Free AI License.

---

**Free AI License Foundation**

**Building open standards for Artificial Intelligence.**
