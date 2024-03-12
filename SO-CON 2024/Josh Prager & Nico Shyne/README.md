# Domain Persistence: Detection, Triage, and Recovery

**Speakers:** Josh Prager & Nico Shyne

# Abstract

We’ll dive into Active Directory domain persistence techniques focused on identifying attacks and 
reclaiming control over organizational domains after a breach. The presentation explores various 
advanced adversarial techniques such as credential theft on domain controllers, NTDS access, DCSync, 
and the creation of Golden and Diamond Tickets. It emphasizes the importance of detecting these methods 
to effectively triage and counteract them. The presentation highlights the need for organizations to 
be vigilant in monitoring and securing their domains, as adversaries continually seek innovative ways 
to maintain access, posing significant threats to data security.

Additionally, we’ll cover post-compromise strategies, detailing the steps necessary for rotating 
domain secrets and enhancing Windows Security event auditing to better detect domain persistence 
activities. We’ll provide a comprehensive guide on resetting and securing various account types, 
including machine, user, and service accounts, and emphasizes the criticality of rotating the KRBTGT 
account to prevent the abuse of Golden Tickets. This presentation will serve as a starting guide for 
critical technique detection generation and organizational recovery scenarios.