# KubeHound and Beyond: Evolving Security Through Graphs and Automation

**Speaker:** Jeremy Fox

# Abstract

The attack surface within modern cloud-native organisations is vast, with often tens or hundreds of 
thousands of application instances. Understanding interdependencies in a system of this scale, in 
particular gaps left open by seemingly innocent configuration changes, is beyond human capability. 
As such, the current mental model of defense remains list-based; attempting to identify vulnerable 
configurations of single resources. This illustrates the well-known adage: “Defenders think in lists, 
attackers think in graphs; as long as this is true, attackers win”

In this talk we will focus on Kubernetes security, using our open source attack path calculator – 
KubeHound – to pivot the mental model of defense from list-based thinking to graph-based thinking. 
We will first highlight some of the shortcomings of list-based approaches. We will then demonstrate 
how attack graphs can address these shortcomings using KubeHound as an example. Finally, we will walk 
through the development process of KubeHound, how we created an abstract graph model of attacks in 
Kubernetes based on public research, and how the process could be expanded to other domains.

At the end of the talk you should have a good understanding of how graph-based techniques can help 
address the complexities of security in modern Kubernetes deployments, and a roadmap for creating 
your own graph based attack model in other domains.
