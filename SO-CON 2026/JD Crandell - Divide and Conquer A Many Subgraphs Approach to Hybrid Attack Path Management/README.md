# Divide and Conquer: A Many Subgraphs Approach to Hybrid Attack Path Management

**Speaker:** JD Crandell

## Abstract

Modern enterprises use dozens of interconnected platforms: Active Directory, cloud providers, code repositories, CI/CD pipelines, and SaaS apps. Capturing hybrid attack paths spanning these boundaries is challenging.

This session presents a framework using technology subgraphs and graph abstractions to model cross-platform attacks at scale. Real red team examples show how one compromised service (GitHub Secret Scanner) created simultaneous paths to multiple clouds through credential exposure.

Learn to divide environments into technology-specific subgraphs, identify "credential watering holes" enabling lateral movement, and use BloodHound OpenGraph for attack path analysis. We introduce "subgraph-local tier zero nodes" (privileged principals like GitHub Org Admin, AWS Root, Domain Admins, etc.) and show how their compromise enables hybrid attacks.

By modeling horizontal expansion (across platforms) and vertical expansion (hardware through objectives using an extended OSI model), organizations gain practical strategies and insights for scalable attack path management. Leave with 3 concrete approaches for hybrid attack path management.

## Track

OpenGraph

## Tags

- BloodHound
- OpenGraph
- Attack Path Management
