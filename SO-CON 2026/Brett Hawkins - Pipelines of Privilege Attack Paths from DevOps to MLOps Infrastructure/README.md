# Pipelines of Privilege: Attack Paths from DevOps to MLOps Infrastructure

**Speaker:** Brett Hawkins

## Abstract

As DevOps automation extends into machine learning, the attack surface expands in ways many organizations haven’t yet noticed. Today’s CI/CD and MLOps ecosystem are built on platforms like Jenkins, AWS CodeBuild, GitHub and Azure DevOps, which are deeply interconnected, packed with credentials, automation logic, and deployment secrets that can be exploited as pivot points. Once breached, these CI/CD pipelines offer attackers a direct path into high-value ML environments such as Azure ML, Amazon SageMaker, and Kubeflow Pipelines.

This research showcases live demos of real DevOps to MLOps attack chains that lead to remote code execution in ML training compute. Each demo highlights the details of the attack path and exposes why standard IAM, segmentation, and logging controls often fail to detect or prevent them. On the defensive side, we’ll explore practical countermeasures for locking down service account scopes, isolating build and training clusters, and enforcing artifact trust boundaries. Attendees will leave with guidance on how to detect, contain, and harden against these emerging DevOps to MLOps attack paths.

## Track

Tradecraft

## Tags

- AI/ML
- Offensive
