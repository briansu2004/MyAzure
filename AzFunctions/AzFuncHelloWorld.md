# Quickstart: Azure Functions (Windows 11 + Node.js + TypeScript)

- [**1. Prepare Your Azure Account**](#1-prepare-your-azure-account)
- [**2. Install Azure CLI**](#2-install-azure-cli)
- [**3. Install Azure Functions Core Tools**](#3-install-azure-functions-core-tools)
- [**4. Initialize a Function App Project**](#4-initialize-a-function-app-project)
- [**5. Start the Local Function Host**](#5-start-the-local-function-host)
- [**6. (Optional but Recommended) Create a Function Trigger**](#6-optional-but-recommended-create-a-function-trigger)
- [**7. (Optional) Test the Function Locally**](#7-optional-test-the-function-locally)

<!-- The following are detailed one-by-one quickstart Azure Functioin steps.

Note: for demo purpose, use Windows 11 and NodeJS

## 1. Have Azure Account/Subscription

## 2. Install Azure CLI

- Download Azure CLI
- Install Azure CLI
- Az login

## 3. Install Azure Function Core Tools

- Download Azure Function Core Tools
- Install Azure Function Core Tools

## 4. Func init

## 5. Func start -->

## **1. Prepare Your Azure Account**

- Ensure you have an active Azure account and subscription.
- If you don't have one, create it at the Azure Portal.

![1782570784729](image/AzFuncHelloWorld/1782570784729.png)

- Note: for demo purpose, this quickstarts uses Windows 11, NodeJS and Typescript - download and install NodeJS if needed.

---

## **2. Install Azure CLI**

- Download Azure CLI from Microsoft's official site.
- Install Azure CLI on Windows 11.
- Sign in to Azure:

```dos
az login
```

![1782570442506](image/AzFuncHelloWorld/1782570442506.png)

---

## **3. Install Azure Functions Core Tools**

- Download Azure Functions Core Tools (version matching your Azure Functions runtime).
- Install the Core Tools.
- Verify installation:

```dos
func --version
```

![1782570538424](image/AzFuncHelloWorld/1782570538424.png)

---

## **4. Initialize a Function App Project**

Create a new Azure Functions project:

```dos
func init myfuncapp --javascript
```

Or for TypeScript:

```dos
func init myfuncapp --typescript
```

---

## **5. Start the Local Function Host**

Run the project locally:

```dos
func start
```

This launches the Azure Functions runtime on your machine and exposes local endpoints for testing.

---

## **6. (Optional but Recommended) Create a Function Trigger**

Example: HTTP trigger

```dos
func new --name HttpDemo --template "HTTP trigger"
```

---

## **7. (Optional) Test the Function Locally**

Use browser or curl:

```dos
curl http://localhost:7071/api/HttpDemo
```

<!-- ---

If you want, I can also prepare:

- **Quickstart: Azure Functions + Event Hub Trigger**
- **Quickstart: Azure Functions + Durable Functions (Orchestrator)**
- **Quickstart: Azure Functions for ML model inference (perfect for CMHC)**

Just tell me which one you want next. -->
