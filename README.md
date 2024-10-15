# Securing Your .NET Applications: Azure DevSecOps

This repository contains the source code and presentation materials for my session titled **Securing Your .NET Applications: Azure DevSecOps** at Devnot Dotnet Konf 2023, held on June 1st, 2023.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this session, we explore various strategies and tools to secure .NET applications using Azure DevSecOps practices. The focus is on integrating security into the DevOps pipeline to ensure that security is a continuous and integral part of the development process.

## Prerequisites

- .NET SDK 7.0.x
- Azure DevOps account
- SonarQube instance

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/mertyeter/dotnetkonf23-azuredevsecops.git
    
    cd dotnetkonf23-azuredevsecops
    ```

2. Install the required .NET SDK versions:
    ```sh
    dotnet --list-sdks
    ```

3. Configure your Azure DevOps pipeline using the provided `azure-pipeline.yml` file.

## Usage

To build and run the project locally, use the following commands:

```sh
dotnet build
dotnet run