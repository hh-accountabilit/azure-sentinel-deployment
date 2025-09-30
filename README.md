# Azure Sentinel Full Deployment

This repo deploys Log Analytics, Microsoft Sentinel, Defender for Cloud, a sample VM, and configures UEBA.

## 🚀 Deploy to Azure

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fhh-accountabilit%2Fazure-sentinel-deployment%2Fmain%2Ftemplates%2FazureDeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2Fhh-accountabilit%2Fazure-sentinel-deployment%2Fmain%2Ftemplates%2FdeploymentUI.json)

> Click the button to deploy the entire environment via the Azure Portal.

## 📁 Resources Deployed

- Log Analytics Workspace (retention, daily cap, commitment tier)
- Microsoft Sentinel (UEBA enabled)
- Sample Windows VM
- Defender for Cloud (Standard tier)

## ⚠️ Prerequisites

- You must have **Global Admin** and **Contributor** access
- Deployment will create resources in the specified region
