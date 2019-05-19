# AKS Engine on Azure Stack

<!-- TODO: TOC -->

<!-- Intro -->
Since release 0.35.XX, AKS Engine can be used to provision self-managed Kubernetes clusters on Azure Stack. However, not every configuration option is currently supported on this platform.

The goal of this guide is to detail the differences between Azure and Azure Stack deployments.

## Service Principals and Identity Providers

Kubernetes uses a Service Principal to talk to Azure Stack APIs to dynamically manage resources such a storage or load balances.

How you create and configure this Service Principals varies depending on what type of identity provider is used by your Azure Stack instance.

https://github.com/Azure/aks-engine/blob/master/docs/topics/clusterdefinitions.md#serviceprincipalprofile

### Azure Active Directory (AAD)

### Mooncake Active Directory

### Active Directory Federation Services (ADFS)

### Client Secret

### Client Certificates

## Supported Versions

## Cluster Definition

## Azure Stack instances registered with Mooncake AAD

## Deploying to disconnected 

## Addons
