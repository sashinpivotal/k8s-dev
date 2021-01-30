

# Keubernetes basics

## Basic Concepts

- [Kubernetes Design Principles: Understand the Why - Saad Ali, Google](https://www.youtube.com/watch?v=ZuIQurh_kDk&ab_channel=CNCF%5BCloudNativeComputingFoundation%5D) - 12/12018, 4.3

## Development Tools

- [Develop cloud-native software faster | Developer Tool for Kubernetes | DevSpace](https://www.youtube.com/watch?v=kgfg8r6_zPk&ab_channel=TechWorldwithNana) - 01/2021, 4.5
  - Talks about DevSpace - fast development/deployment

- [10 awesome Kubernetes tools every user should know | DevNation Tech Talk](https://www.youtube.com/watch?v=5eIlfNGGuU8&ab_channel=RedHatDeveloper) - 08/2020, 4.0
- [kubectx+kubens](https://github.com/ahmetb/kubectx)
- kubespy
- kube-shell

- [Dead Easy Kubernetes Workflows With VS Code (Cloud Next '19)](https://www.youtube.com/watch?v=62GLbBDLiPE&ab_channel=GoogleCloudPlatform) - 04/2019

- [IntelliJ Kubernetes plugin](https://www.jetbrains.com/help/idea/kubernetes.html)

- [kubernetes intellij search in Youtube](https://www.youtube.com/results?search_query=kubernetes+intellij)


## Helm

- [An Introduction to Helm - Matt Farina, Samsung SDS & Josh Dolitsky, Blood Orange](https://www.youtube.com/watch?v=Zzwq9FmZdsU&ab_channel=CNCF%5BCloudNativeComputingFoundation%5D) - 11/2019, 4.3
  - Based on Helm 3
  - Talked about misc Helm projects (Helm eco-system)

- [Managing Helm Deployments with Gitops at CERN - Ricardo Rocha, CERN](https://www.youtube.com/watch?v=g9FQxzK9E_M&ab_channel=CNCF%5BCloudNativeComputingFoundation%5D) - 11/2019


## K8s Internals

- [Network Namespaces Basics Explained in 15 Minutes](https://www.youtube.com/watch?v=j_UUnlVC2Ss&ab_channel=KodeKloud) - 05/2019, 4.5

- [Deep dive into Kubernetes networking by Sreenivas Makam](https://www.youtube.com/watch?v=NUt9VVG_gac&ab_channel=CodeOpsTech)

# Tanzu TGI Tools

- [Deploying Tanzu Kubernetes Grid Extensions and Shared Services](https://docs.vmware.com/en/VMware-Tanzu-Kubernetes-Grid/1.2/vmware-tanzu-kubernetes-grid-12/GUID-extensions-index.html)

# Spring Boot with k8s

## Videos

- [Tanzu Tuesdays - Top tips for running Spring Boot applications on Kubernetes with Ollie Hughe](https://www.youtube.com/watch?v=R9mNUfvp8Dg&ab_channel=VMwareTanzu) - 01/2021, 4.1
  - IntelliJ K8s auto-completion
  - kustomize
  - skaffold with buildpack

- [Bulletproof Microservices with Spring and Kubernetes] (https://www.youtube.com/watch?v=aI19ZYV4-7o&t=697s&ab_channel=SpringDeveloper) - 09/2020,4.5
  - Securing spring apps with k8s
  - Basic authentication to the ingress controller
  - TLS to the ingress controller
  - External DNS configuration
  - Encryptit certification manager
  - Mutual authentication between services
  - OAuth2 to the ingress controller
  - Helm chart to install various components
  - Autocert

- [Spring Boot Loves K8s](https://www.youtube.com/watch?v=nPACI6-J9Jc&t=704s&ab_channel=SpringDeveloper) - 09/2020, 4.3

- [Whats New in Spring Boot 2.4](https://www.youtube.com/watch?v=lgyO9C9zdrg&ab_channel=SpringDeveloper) - 01/2021, 4.5

```
Intro:
00:27 Creating a Demo App

Upgrading:
07:24 Version Number Changes
08:29 JUnit Vintage Engine
09:07 Legacy Config Data Mode
10:48 Logback Property Changes and Property Migrator

New Features:
13:51 Java 15 and Startup Logging
15:03 Constructor Binding @ConfigurationProperties Updates
18:11 ApplicationStartup Metrics (Flight Recorder and JSON)
24:49 Changes to Application properties/yaml
30:46 Using 'spring.config.import'
34:46 Importing Files Without an Extension
35:28 Origin Chains
38:34 Config Tree Support (Kubernetes Volume Mounted Secrets)
40:51 Supporting Custom Config Data Import Types
42:57 Docker and Buildpack Updates
46:09 Publishing to a Private Docker Registry
```

- [Best Practices to Spring to Kubernetes Easier and Faster](https://www.youtube.com/watch?v=YTPUNesUIbI&t=3527s&ab_channel=SpringDeveloper) - 10/2019, 3.8 - by Google guy

# CI/CD tools

## Videos

- [Leveling Up Your CD: Unlocking Progressive Delivery on Kubernetes - Daniel Thomson & Jesse Suen - 11/2019](https://www.youtube.com/watch?v=Nv0PPwbIEkY&ab_channel=CNCF%5BCloudNativeComputingFoundation%5D) 4.5

### Tanzu

- [Tanzu Build Service - 09/2020](https://www.youtube.com/watch?v=IMmUjUjBzes&ab_channel=VMwareTanzu) - 4.5
- [kpack](https://tanzu.vmware.com/content/blog/introducing-kpack-a-kubernetes-native-container-build-service)

## Technologies

- [GitOps](https://www.gitops.tech/)
- [Argo](https://argoproj.github.io/projects/argo)

## Observability

## Service Mesh

- [Istio & Service Mesh - simply explained in 15 mins](https://www.youtube.com/watch?v=16fgzklcF7Y&ab_channel=TechWorldwithNana) - 01/2021, 4.5

```
0:00 - Intro
0:53 - Challenges of a microservice architecture
5:11 - Solution: Service Mesh with Sidecar Pattern
6:15 - Service Mesh Traffic Split feature
7:25 - Istio Architecture
9:05 - How to configure Istio?
11:57 - Istio Features: Service Discovery, Security, Metrics & Tracing
13:19 - Istio Gateway
14:06 - Final Overview: Traffic Flow with Istio
```

- [Tanzu Service Mesh](https://video.search.yahoo.com/yhs/search?fr=yhs-iba-syn&hsimp=yhs-syn&hspart=iba&p=tanzu+service+mesh#id=1&vid=2d23067a833e6376e504914235e63dd5&action=click) - 03/2020
  - Global namespace
  - https://github.com/vmwarecloudadvocacy

# edik8s


2021.01.29

eduk8s outline

what is eduk8s?
  see https://docs.edukates.io/
  author: Graham Dumpleton

" The educates projects provides a system for hosting interactive workshop environments in Kubernetes.
  It can be used for self paced or supervised workshops.
  It can also be useful where you need to package up demos of applications hosted in Kubernetes for users or potential customers. "

Resources:
- slack channels:
  #educates
  #educates_esp (esp: extensible service platform)

- docs: https://docs.edukates.io/
- sample workshops: https://docs.edukates.io/en/latest/getting-started/sample-workshops.html

- live environments:
  1. visit https://tanzu.vmware.com/developer/
  2. navigate: learn -> workshops

  these samples are all deployed here:
  - "container basics"
  - "kubernetes fundamentals"
  - "getting started with octant"

- setting up a local environment
  - install minikube, so that i can have an environment in which to deploy eduk8s and workshops
    https://docs.edukates.io/en/latest/installation-guides/deploying-to-minikube.html
    https://minikube.sigs.k8s.io/
  - deploy eduk8s
    https://docs.edukates.io/en/latest/getting-started/installing-operator.html
  - deploy a sample workshop and see if i can access and exercise it, what it looks/feels like
  - write your own workshop

- tanzu e2e
  recording: https://tech-talks.eng.vmware.com/talks/tanzu-end-to-end-demo-assets
  https://via.vmware.com/tsl-e2e
  portal: https://via.vmw.com/tanzu-e2e-demo
  slack #tanzu-e2e-demo
