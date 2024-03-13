# Identity Providers for Red Teamers

**Speaker:** Adam Chester

# Abstract

It’s rare to find organisations who haven’t dipped their toe into the world of cloud-based Identity 
Providers. Whether it’s Okta, Ping, Entra ID, or the myriad of other providers gaining traction, 
the days of managing federated identities with on-premises solutions like ADFS are fading, instead 
replaced by third party services offering to offload the burden of securing the gates to critical 
assets.

However, as 2023 has continued to show us, attackers are quick to adapt. And with the rise in breaches 
coming from targeted attacks against Identity Providers, perhaps the Idp cloud-topia isn’t everything 
it was promised to be. Nevertheless, there remains a limited availability of information regarding the 
techniques used in these attacks.

In this talk I’ll aim to lift the lid on the methods we utilise during a Red Team assessment to target 
Identity Providers. I’ll show the tactics I’ve found to be effective, demonstrate tools and techniques 
that have proven useful when meeting objectives that lie beyond the Single Sign-On portal. We’ll look 
at why synchronisation servers should be treated with the same level of protection as domain 
controllers, look at how attackers within an organisation can pivot to external services protected by 
Identity Providers, and hopefully equip you with few new tools for your offensive arsenal.
