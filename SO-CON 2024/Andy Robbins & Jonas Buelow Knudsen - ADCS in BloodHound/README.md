# Analyzing and Executing ADCS Attack Paths with BloodHound

**Speaker:** Andy Robbins & Jonas Buelow Knudsen

# Abstract

Active Directory Certificate Services (ADCS) is Microsoft’s native PKI solution, used by many 
organizations to facilitate smart card authentication, TLS certificate issuance and verification, 
code signing, and other tasks. ADCS is a complicated system with many moving parts and possible 
configurations, out of which privilege escalation opportunities often emerge. Discovering those 
opportunities by hand is a tedious, time-consuming, and error-prone process.

In this talk, we will explain and demonstrate how BloodHound dramatically simplifies the discovery, 
analysis, and execution of attack paths traversing ADCS objects. We will show how with just a few 
clicks, BloodHound reveals these attack paths in seconds that would otherwise take hours or even 
days to discover by hand. We will demonstrate how attackers execute these attack paths as well as 
using common tooling such as Rubeus and Certify.