# Setup Guide

Follow these steps to deploy the application.

## Step 1: Clone Repository

```bash
git clone https://github.com/anilpirla/dotnet-webapp-cicd.git

cd dotnet-webapp-cicd
```

## Step 2: Create Azure App Service

Azure Portal

Create Resource Group:

dotnet-rg

Create App Service:

dotnet-webapp

Runtime:

.NET v10

---

## Step 3: Create Service Connection

Azure DevOps

Project Settings

→ Service Connections

→ New Service Connection

Choose:

Azure Resource Manager

Authentication:

Service Principal (Automatic)

Enable:

Grant access to all pipelines

Connection Name:

dotnet-webapp-connection

---

## Step 4: Add YAML pipeline

Create:

azure-pipelines.yml

Copy project YAML.

---

## Step 5: Commit and Push

```bash
git add .

git commit -m "Added CI/CD"

git push origin main
```

---

## Step 6: Run Pipeline

Pipelines

→ Run Pipeline

Verify:

Build Stage

Deploy Stage

Deployment Successful
