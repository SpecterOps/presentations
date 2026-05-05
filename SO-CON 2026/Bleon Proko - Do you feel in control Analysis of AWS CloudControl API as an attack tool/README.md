# Do you feel in control? Analysis of AWS CloudControl API as an attack tool

**Speaker:** Bleon Proko

## Abstract

"Identity is the new perimeter" gets thrown around a lot in security discussions, fo a good reason. With the right privileges, cloud resources can be managed through APIs.  Each provider has their own way of handling API access on resources. If your identity has the right permissions for a specific API call, you can execute that action. 

The thing is, it's hard to remember every single API call you need to get specific information or access certain resources. AWS recognized this problem and created the AWS CloudControl API, a unified API that groups different resources together so you can create, update, delete, or retrieve them in bulk. This makes managing resources much simpler since you don't need to know which specific service, API call, or parameters to use.

But here's the catch: when something is easy for legitimate users, it's usually easy for attackers too. There are already tools available to use the AWS CloudControl API to pull resource information, and the technique is gaining attention. 

But is it actually a good way to do stealthy enumeration? In this article, we examine what the CloudControl API is, how it simplifies resource management, how attackers can weaponize it, its limitations, and detection methods.

## Track

Tradecraft

## Tags

- Cloud
- AWS
- Offensive
