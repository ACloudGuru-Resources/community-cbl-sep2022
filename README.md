# Cloud Builder Live - September 2022

![Cloud Builder Live Thumbnail](/thumbnail.jpg)

In this session, David will guide learners through the process of setting up the Azure Kubernetes Service and deploying a Next.js web application. This session doesn't assume any Kubernetes knowledge, so feel to join and learn!

Watch it Live - [Cloud Builder Live - September 2022](https://www.youtube.com/watch?v=V3AwbjzJ7PQ)  

## Warning

**It is important to note that you could incur substantial Azure charges if you do not delete the resources configured in this episode.** At the end of the episode I will cover the delete process in detail.

## Prerequisites

To follow along with this demo, you will need three things: an Azure subscription, the Azure CLI, and Docker.  You can get instructions on how to get these setup at the following links:

* [Create an Azure Subscription](https://azure.microsoft.com/en-us/free/)
* [Install the Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
* [Install Docker](https://docs.docker.com/get-docker/)

## Tools to Install

During the episode, I'll be walking you through some tools we will be using to deploy, monitor, and configure Kubernetes (k8s) via the Elastic Kubernetes Service (EKS).  I've listed them below along with the purpose for including them:

| Tool | Installation Instructions | Use |
|-----|-----|-----|
| **kubectl** | [Install kubectl](https://learn.microsoft.com/en-us/azure/aks/tutorial-kubernetes-deploy-cluster?tabs=azure-cli#install-the-kubernetes-cli) | The official k8s command line tool for interacting with the cluster API's. *This tool requires a proper config file referencing the cluster you will be working on.* |
| **k9s** | [Install k9s](https://k9scli.io/topics/install/) | Terminal based tool for the monitoring and management of a k8s cluster. *This tool requires kubectl to be installed.*<br><br>[Video Overview of k9s](https://www.youtube.com/watch?v=jovHiTobzKQ)|
