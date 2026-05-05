# Guard me if you can: A Novel Passwordless-to-Password attack

**Speaker:** Yuya Chudo and Riku Bamba

## Abstract

When attackers compromise a device and use it as a foothold to stealthily explore an internal network, they commonly route reconnaissance traffic through malware on that device. For authenticated access within the internal network, attackers need credential material such as NTLM hashes, Kerberos TGTs, and session keys so obtaining these credentials is one of the objectives after the malware infection.

On modern Windows endpoints, Credential Guard is designed to prevent these credential theft, and it raises the bar for attackers. Prior research has uncovered several bypasses, but our investigation found that, by combining authentication flows with keys stored in the endpoint's TPM, malware running with only standard user privileges can acquire the credentials from infected device.

In this session we will explain the end-to-end authentication flows that makes this possible, show how device keys in TPM can be leveraged, and demonstrate the technique with an updated release of our open-source tool, BAADTokenBroker. We will also identify the protection gap in Credential Guard that allows this exfiltration, present real-world attack scenarios, and cover recommended mitigations.

## Track

Tradecraft

## Tags

- Cloud
- Identity
- Windows
- Azure
- Offensive
