---
title: Azure Blockchain Workbench Preview overview
description: Overview of Azure Blockchain Workbench Preview and its capabilities.
ms.date: 02/18/2022
ms.topic: overview
ms.reviewer: brendal
#Customer intent: As an developer or administrator, I want to understand what Azure Blockchain Workbench is and its capabilities.
---
# What is Azure Blockchain Workbench?

[!INCLUDE [Retirement note](./includes/retire.md)]

Azure Blockchain Workbench Preview is a collection of Azure services and capabilities designed to help you create and deploy blockchain applications to share business processes and data with other organizations. Azure Blockchain Workbench provides the infrastructure scaffolding for building blockchain applications enabling developers to focus on creating business logic and smart contracts. It also makes it easier to create blockchain applications by integrating several Azure services and capabilities to help automate common development tasks.

[!INCLUDE [Preview note](./includes/preview.md)]

## Create blockchain applications

With Blockchain Workbench, you can define blockchain applications using configuration and writing smart contract code. You can jumpstart blockchain application development and focus on defining your contract and writing business logic instead of building scaffolding and setting up supporting services.

## Manage applications and users

Azure Blockchain Workbench provides a web application and REST APIs for managing blockchain applications and users. Blockchain Workbench administrators can manage application access and assign your users to application roles. Azure AD users are automatically mapped to members in the application.

## Integrate blockchain with applications

You can use the Blockchain Workbench REST APIs and message-based APIs to integrate with existing systems. The APIs provide an interface to allow for replacing or using multiple distributed ledger technologies, storage, and database offerings.

Blockchain Workbench can transform messages sent to its message-based API to build transactions in a format expected by that blockchain's native API.  Workbench can sign and route transactions to the appropriate blockchain. 

Workbench automatically delivers events to Service Bus and Event Grid to send messages to downstream consumers. Developers can integrate with either of these messaging systems to drive transactions and to look at results.

## Deploy a blockchain network

Azure Blockchain Workbench simplifies consortium blockchain network setup as a preconfigured solution with an Azure Resource Manager solution template. The template provides simplified deployment that deploys all components needed to run a consortium. Today, Blockchain Workbench currently supports Ethereum.

## Use Active Directory

With existing blockchain protocols, blockchain identities are represented as an address on the network. Azure Blockchain Workbench abstracts away the blockchain identity by associating it with an Active Directory identity, making it simpler to build enterprise applications with Active Directory identities.

## Synchronize on-chain data with off-chain storage

Azure Blockchain Workbench makes it easier to analyze blockchain events and data by automatically synchronizing data on the blockchain to off-chain storage. Instead of extracting data directly from the blockchain, you can query off-chain database systems such as SQL Server. Blockchain expertise is not required for end users who are doing data analysis tasks.

## Support and feedback

For Azure Blockchain news, visit the [Azure Blockchain blog](https://azure.microsoft.com/blog/topics/blockchain/) to stay up to date on blockchain service offerings and information from the Azure Blockchain engineering team.

To provide product feedback or to request new features, post or vote for an idea via the [Azure feedback forum for blockchain](https://aka.ms/blockchainuservoice).

### Community support

Engage with Microsoft engineers and Azure Blockchain community experts.

* [Microsoft Q&A question page for Azure Blockchain Workbench](/answers/topics/azure-blockchain-workbench.html)
* [Microsoft Tech Community](https://techcommunity.microsoft.com/t5/Blockchain/bd-p/AzureBlockchain)
* [Stack Overflow](https://stackoverflow.com/questions/tagged/azure-blockchain-workbench)

## Next steps

> [!div class="nextstepaction"]
> [Azure Blockchain Workbench architecture](architecture.md)
