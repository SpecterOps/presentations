# Hybrid Attacks and Identities in Motion: Anatomy of Modern Attack Paths

**Speaker:** Elad Shamir and Will Schroeder

## Abstract

Authorization is downstream from authentication: first, a user is authenticated, then access is granted. In modern environments, that mental model breaks down. Authentication can itself be downstream from authorization.

Credential material now lives everywhere - browser cookies on endpoints, API keys in CI/CD systems, OAuth tokens in SaaS integrations, and sometimes even clear-text passwords where they should (or shouldn't!) be. Any identity or workload authorized to access these artifacts can effectively authenticate as someone else and take over their account.

As organizations adopt hybrid identity models and SaaS-heavy architectures, trust is no longer centralized. It is fragmented across on-prem identity systems, cloud providers, applications, and automation pipelines. The implicit trust relationships between these components - the connective tissue - are where defenders are most often caught off guard.

This talk breaks down the mechanisms and concepts that allow identities and adversaries alike to move across platforms, how authorization boundaries quietly become authentication boundaries, and how attackers chain these behaviors into real-world hybrid attack paths.

## Track

Practice

## Tags


