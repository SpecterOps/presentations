# Read Only or RCE: Discovering New Kubernetes Attack Paths

**Speaker:** Graham Helton

## Abstract

Complex systems are full of surprises, and Kubernetes is a notoriously complex system that is quickly becoming a cornerstone technology at most companies. Yet its complexity makes it an unapproachable target for many offensive security researchers. I believe Kubernetes and its cloud-native ecosystem occupy a similar position to Active Directory ten years ago: widely deployed, mature, but full of interesting attack paths waiting to be discovered.

In this presentation, I will demonstrate this opportunity by walking through a currently undisclosed authorization bypass vulnerability in Kubernetes that allows service accounts with a widely granted, read-only permission to achieve full code execution in any pod across a cluster.

I will cover:
- A high-level overview of Kubernetes for those unfamiliar with the technology
- The current state of offensive Kubernetes research and where opportunities exist
- A deep dive into the authorization bypass vulnerability and its root cause
- How to chain this vulnerability to achieve full cluster compromise
- A live demonstration of exploiting this issue to gain access to every pod and node in a fully patched Kubernetes cluster
- Takeaways for discovering similar attack paths in Kubernetes

## Track

Tradecraft

## Tags

- Offensive
- Cloud
- Linux
- Kubernetes
