# Project Catalog

Public repositories grouped by purpose. Descriptions reflect the contents reviewed in November 2026. Private projects are intentionally absent from this public index.

Use browser Find for a technology or keyword, or search the [machine-readable catalog](projects.json). Repository topics provide another way to filter the account.

## Software & websites

| Repository | What is here | Topics |
| --- | --- | --- |
| [tenantledger](https://github.com/Raghava-Gatadi/tenantledger) | Multi-tenant expense approvals with FastAPI, PostgreSQL and Keycloak, plus an executable authorization security lab. | `portfolio-project`, `web-application`, `python`, `fastapi`, `postgresql`, `keycloak`, `authorization` |
| [QC-club-Main-website](https://github.com/Raghava-Gatadi/QC-club-Main-website) | Django website for the Quantum Computing Club with team, gallery, blog, magazine, and contact pages. | `web-application`, `python`, `django`, `quantum-computing` |
| [blog-qc-club](https://github.com/Raghava-Gatadi/blog-qc-club) | Quantum Computing Club blog built with Gatsby and Netlify CMS; a customized fork of the Delog starter. | `web-application`, `gatsby`, `javascript`, `quantum-computing`, `blog` |
| [Portfolio](https://github.com/Raghava-Gatadi/Portfolio) | Static portfolio website with security projects, software work, research write-ups, and certifications; hosted on GitHub Pages. | `portfolio-website`, `html`, `css`, `javascript`, `github-pages` |
| [job-opportunities](https://github.com/Raghava-Gatadi/job-opportunities) | Recruitex team coursework: job-platform reports, use-case diagrams, presentation, and UI screenshots; application source is not included. | `coursework`, `project-documentation`, `job-portal`, `software-engineering` |

## Security tools & engineering

| Repository | What is here | Topics |
| --- | --- | --- |
| [appsec-assistant](https://github.com/Raghava-Gatadi/appsec-assistant) | Offline source security triage: maps entry points, sensitive functions, and review findings across Python, JavaScript/TypeScript, and common backend languages. | `portfolio-project`, `security-tool`, `python`, `application-security`, `static-analysis`, `code-review` |
| [verifiedrelease](https://github.com/Raghava-Gatadi/verifiedrelease) | Verified container releases for TenantLedger: signed SBOM and provenance, security scans, digest and identity admission, rejection tests, and expiring exceptions. | `portfolio-project`, `devsecops`, `supply-chain-security`, `sbom`, `cosign`, `github-actions` |
| [automation-scripts](https://github.com/Raghava-Gatadi/automation-scripts) | Python security utilities for source checks, dependency audits, secret scanning, TLS certificates, subdomains, and scheduled reports. | `security-tool`, `python`, `automation`, `application-security`, `security-scanning` |
| [aws-detection-engineering-splunk](https://github.com/Raghava-Gatadi/aws-detection-engineering-splunk) | Six Splunk detections for AWS CloudTrail with attack coverage, rule documentation, and a public incident-response dataset. | `portfolio-project`, `aws`, `splunk`, `detection-engineering`, `cloud-security` |

## Labs & learning

| Repository | What is here | Topics |
| --- | --- | --- |
| [Portswigger](https://github.com/Raghava-Gatadi/Portswigger) | Python lab exercises for PortSwigger Web Security Academy authentication and SQL injection topics. | `security-lab`, `python`, `portswigger`, `web-security`, `sql-injection`, `authentication` |
| [auth-vulnerabilities-scripts](https://github.com/Raghava-Gatadi/auth-vulnerabilities-scripts) | Python exercises for PortSwigger Web Security Academy authentication labs; also included in the broader Portswigger lab collection. | `security-lab`, `python`, `authentication`, `portswigger`, `web-security` |
| [AES-Socket-Programming](https://github.com/Raghava-Gatadi/AES-Socket-Programming) | Python socket chat demo with a handwritten AES implementation and shared-key message encryption. | `learning-project`, `python`, `cryptography`, `socket-programming` |
| [Network-Scanner](https://github.com/Raghava-Gatadi/Network-Scanner) | Django and Scapy learning project for local-network device discovery and TCP port checks. | `learning-project`, `python`, `django`, `scapy`, `network-scanner` |
| [Password-Manager](https://github.com/Raghava-Gatadi/Password-Manager) | Educational Python CLI password manager using MySQL and AES-CBC; includes entry search and clipboard support. | `learning-project`, `python`, `mysql`, `cryptography`, `password-manager` |
| [Python-Scripts](https://github.com/Raghava-Gatadi/Python-Scripts) | Python learning experiments: a network scanner, password checker, image steganography, and a political-tweet notebook. | `learning-project`, `python`, `scapy`, `steganography`, `jupyter-notebook` |
| [cybersecurity](https://github.com/Raghava-Gatadi/cybersecurity) | Earlier Python security project collection: socket encryption, network scanning, password management, and small experiments. | `learning-project`, `python`, `cybersecurity`, `network-security` |

## Research & case studies

| Repository | What is here | Topics |
| --- | --- | --- |
| [Cloud-Security-Projects](https://github.com/Raghava-Gatadi/Cloud-Security-Projects) | Cloud security case-study reports covering AWS breach reconstruction, EC2 SSRF/IMDS, HIPAA risk, and multi-cloud recovery. | `case-study`, `cloud-security`, `aws`, `incident-response`, `risk-assessment` |
| [PUF-research](https://github.com/Raghava-Gatadi/PUF-research) | Research-paper artifact on physically unclonable functions (PUFs) and IoT authentication. | `research`, `hardware-security`, `puf`, `iot`, `authentication` |

## Upstream forks

| Repository | What is here | Topics |
| --- | --- | --- |
| [gittuf](https://github.com/Raghava-Gatadi/gittuf) | Fork of gittuf, the upstream Git repository security layer based on TUF concepts. | `open-source-fork`, `go`, `git`, `supply-chain-security`, `tuf` |

## Placeholders & practice

| Repository | What is here | Topics |
| --- | --- | --- |
| [Major-Project](https://github.com/Raghava-Gatadi/Major-Project) | Empty project placeholder; no source code or documentation has been committed. | `project-placeholder` |
| [Test](https://github.com/Raghava-Gatadi/Test) | Markdown practice sandbox containing a short sample README. | `learning-project`, `markdown` |

## Relationships to know

- **TenantLedger → VerifiedRelease:** the former demonstrates application authorization; the latter extends it with container release verification.
- **Portswigger → auth-vulnerabilities-scripts:** the broader collection also includes SQLi. All 12 authentication scripts matched across both repositories at audit time.
- **cybersecurity → standalone learning repos:** the older collection overlaps with AES-Socket-Programming, Network-Scanner, Password-Manager, and Python-Scripts. The READMEs point out those relationships.
- **Recruitex / job-opportunities:** reports and screenshots are available; application source is not in that repository.
- **gittuf and blog-qc-club:** GitHub forks; preserve upstream attribution when discussing the work.

## Useful GitHub searches

- [Web applications](https://github.com/search?q=user%3ARaghava-Gatadi%20topic%3Aweb-application&type=repositories)
- [Security labs](https://github.com/search?q=user%3ARaghava-Gatadi%20topic%3Asecurity-lab&type=repositories)
- [Learning projects](https://github.com/search?q=user%3ARaghava-Gatadi%20topic%3Alearning-project&type=repositories)
- [Research](https://github.com/search?q=user%3ARaghava-Gatadi%20topic%3Aresearch&type=repositories)
- For a specific file or symbol, use repository code search or search locally in a clone. Topic search groups repositories; it does not search their source.

[Profile](README.md) · [Maintenance guide](MAINTENANCE.md)
