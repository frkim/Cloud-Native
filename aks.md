# Azure Kubernetes Services - AKS Resources

Azure Kubernetes Service (AKS) simplifies deploying a managed Kubernetes cluster in Azure by offloading the operational overhead to Azure. As a hosted Kubernetes service, Azure handles critical tasks, like health monitoring and maintenance. When you create an AKS cluster, a control plane is automatically created and configured. This control plane is provided at no cost as a managed Azure resource abstracted from the user. You only pay for and manage the nodes attached to the AKS cluster.

This page gathers a lot of resources to start with [Azure Kubernetes Services - AKS](https://learn.microsoft.com/en-us/azure/aks/)

# Overview
 ![AKS 101](./media/aks-101.png)

 [Source: AKS Intro](https://learn.microsoft.com/en-us/azure/aks/intro-kubernetes)

# Container Hosting Services on Azure
 ![Container Hosting Service on Azure](./media/containers-comparison.png)

 [Source: How to choose a compute service](https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-decision-tree#choose-a-candidate-service)


# Architecture Sample
 ![AKS Architecture](./media/aks-architecture.png)
[Source: Microservices architecture on Azure Kubernetes Service](https://learn.microsoft.com/en-us/azure/architecture/browse/?terms=aks)

# AKS Landing Zone
Strategic design path and target technical state for an Azure Kubernetes Service (AKS) deployment.

 ![AKS Landing Zone](./media/aks-landingzone.png)

 [Source: AKS Landing Zone](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/aks/landing-zone-accelerator)

Reference architecture, we'll build a baseline infrastructure that deploys an Azure Kubernetes Service (AKS) cluster
- [AKS Baseline](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks)

# Links

## Basic Concepts
 - [Kubernetes core concepts for Azure Kubernetes Service](https://learn.microsoft.com/en-us/azure/aks/concepts-clusters-workloads)

## General product 
- [AKS Roadmap](https://github.com/Azure/AKS/projects/1)
- [AKS Release Notes](https://github.com/Azure/AKS/releases)

## Tutorials / Workshops

 - [AKS on Microsoft Learn](https://docs.microsoft.com/en-us/learn/browse/?expanded=azure&filter-products=kub&products=azure-kubernetes-service)
 - [AKS Workshop](https://docs.microsoft.com/en-us/learn/modules/aks-workshop/)
 - [AKS Learning Path](https://azure.microsoft.com/en-us/resources/kubernetes-learning-path/)

## Blogs

 - [Learn K8s](https://learnk8s.io/blog)
 - [Stanislas Quastana Blog (FR)](https://stanislas.io/?s=aks)

## Videos

 - [Brendan Burns](https://www.youtube.com/playlist?list=PLLasX02E8BPCrIhFrc_ZiINhbRkYMKdPT)
 - [John Savill](https://www.youtube.com/c/NTFAQGuy/search?query=aks)
 - [Houssem Dellai](https://www.youtube.com/playlist?list=PLpbcUe4chE79sB7Jg7B4z3HytqUUEwcNE)

## eBooks

 - [Kubernetes Learning Path](https://azure.microsoft.com/en-us/resources/kubernetes-learning-path/)
 - [Get up and running with K8s](https://azure.microsoft.com/en-us/resources/kubernetes-ebook-collection/)
 - [Designing Distributed Systems](https://azure.microsoft.com/en-us/resources/designing-distributed-systems/)

## Best practices 
 - [AKS Best Practices](https://docs.microsoft.com/en-us/azure/aks/best-practices)
 - [AKS GitHub Project](https://github.com/Azure/AKS)
 - [Production Baseline for AKS](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks/secure-baseline-aks)
 - [AKS CheckList by LG Morand](https://www.the-aks-checklist.com/)

## Advanced Networking 
- [AKS Networking Overview](https://blog.stevegriffith.nyc/posts/aks-networking/)
- [AKS Networking Part I](https://blog.stevegriffith.nyc/posts/aks-networking-part1)
- [AKS Networking Part II](https://blog.stevegriffith.nyc/posts/aks-networking-part2)
- [AKS Networking IP Tables](https://blog.stevegriffith.nyc/posts/aks-networking-iptables)
- [AKS in the HubSpoke](https://techcommunity.microsoft.com/t5/azure-developer-community-blog/aks-the-elephant-in-the-hub-amp-spoke-room-deep-dive/ba-p/3635985#content)

## BYO Private Zone
- [BYO Private Zone Demo Content and Links](https://github.com/swgriffith/azure-guides/tree/master/dns)

## Code to Cloud
 - [Code-to-cloud with Azure Kubernetes Service](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/code-to-cloud-with-azure-kubernetes-service-aks/ba-p/3669916)

## Usefull tools and 3rd party

 - [Lens - The K8s IDE](https://k8slens.dev/)
 

## Sample AKS Application

 - [Contoso band name generator for AKS developer experience demo](https://github.com/sabbour/contoso-names)
 - [AKS Fabrikam Drone Delivery](https://github.com/mspnp/aks-fabrikam-dronedelivery)

