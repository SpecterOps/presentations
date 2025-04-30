# There and Back Again: An Attacker's Tale of DCs in AWS

**Speaker:** James Henderson and Leo Tsaousis

## Abstract

You're a sysadmin, and you need to migrate your old digital infrastructure to the cloud. Annoyingly, some of those pesky servers rely on Active Directory, and your admins need to use their existing access methods. So, you end up with an Active Directory forest running on an EC2 instance in AWS. What could possibly go wrong?

Well, it turns out, quite a lot.

In this talk, we'll discuss the dangers of overlapping identity planes, demonstrated by Attack Paths that we've exploited in environments where customers have deployed AD in the cloud, combining cloud-native TTPs and well-known Active Directory exploitation techniques. These have led to DA/cloud administrator access in multiple engagements and are a result of the systemic risks when combining different identity management systems.

We'll also show the defender's perspective, discussing the underlying system design and detection engineering strategies that can mitigate these attacks.

## Tags

- Cloud
- Active Directory
- Offensive
- Defensive
