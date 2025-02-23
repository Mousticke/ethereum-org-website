---
title: 提升用户体验
description: 对于大多数人来说，使用以太坊仍然过于复杂。 为了促进以太坊的大规模普及，必须大幅降低其进入门槛 - 必须让用户在访问以太坊时，享受去中心化、无需许可和抗审查的好处，同时像使用传统的 Web2 应用程序一样丝滑顺畅。
lang: zh
image: /images/roadmap/roadmap-ux.png
alt: "以太坊路线图"
template: roadmap
---

从管理[密钥](/glossary/#key)和[钱包](/glossary/#wallet)到发起交易，**以太坊的使用过程都需要简化**。 为了促进以太坊的大规模普及，必须大幅提升使用的便捷性，让用户在访问以太坊时，体验无需许可和抗审查的好处，同时像使用 [Web2](/glossary/#web2) 应用程序一样丝滑顺畅。

## 超越助记词 {#no-more-seed-phrases}

以太坊帐户由一对密钥保护，其中，公钥用于帐户识别，私钥用于消息签名。 私钥类似于主密码，提供以太坊帐户的完全访问权限。 对于更熟悉代表用户管理帐户的银行和 Web2 应用程序的人来说，这是一种完全不同的操作方式。 为了使以太坊在不依赖中心化第三方的情况下大规模普及，必须有一种方法，可以让用户简单顺畅地掌握自己的资产并控制自己的数据，且无需了解公私钥加密法和密钥管理。

这个问题的解决办法是使用[智能合约](/glossary/#smart-contract)钱包与以太坊交互。 智能合约钱包提供了在密钥丢失或被盗时保护帐户的途径以及更好地发现和防范欺诈的机会，还可以让钱包拥有新功能。 虽然智能合约钱包现在已经存在，但很难构建，因为它们需要以太坊协议的更好支持。 这种额外支持被称为帐户抽象。

<ButtonLink variant="outline-color" to="/roadmap/account-abstraction/">更多关于帐户抽象的信息</ButtonLink>

## 人人皆有节点

运行[节点](/glossary/#node)的用户不必相信第三方将为他们提供数据，他们可以快速、匿名且无需许可地与以太坊[区块链](/glossary/#blockchain)交互。 然而，现在运行一个节点需要技术知识和大量磁盘空间，这意味着许多人不得不依赖第三方。

以太坊将进行几项升级，使节点更容易运行，资源密集程度更低。 存储数据的方式将改为使用更具空间效率的结构，称为**沃克尔树**。 同时，通过[无状态性](/roadmap/statelessness)或[数据到期](/roadmap/statelessness/#data-expiry)升级，以太坊节点将不再需要存储完整的以太坊状态数据的副本，从而大幅降低硬盘空间需求。 [轻节点](/developers/docs/nodes-and-clients/light-clients/)将具备运行全节点的许多好处，但是在手机或简单的浏览器应用程序中就可以轻松运行。

<ButtonLink variant="outline-color" to="/roadmap/verkle-trees/">阅读关于沃克尔树的信息</ButtonLink>

通过这些升级，运行节点的障碍实际上减少到零。 用户将可以安全、无需许可地访问以太坊，且不需要在计算机或手机上牺牲大量磁盘空间或 CPU，在使用应用程序时，也不必依赖第三方提供数据或网络访问权限。

## 当前进展 {#current-progress}

智能合约钱包已经推出，但需要进行更多升级以使其尽可能去中心化和无需许可。 EIP-4337 是一个成熟的提案，不需要对以太坊协议做出任何修改。 EIP-4337 需要的主要智能合约**于 2023 年 3 月部署**。

**完全无状态性仍处于研究阶段**，可能还需要几年才能实现。 在通往完全无状态性的道路上有许多里程碑，包括可能不久后就会实现的数据到期。 可能需要首先完成其他路线图项目，例如[沃克尔树](/roadmap/verkle-trees/)和[提议者-构建者分离](/roadmap/pbs/)。

沃克尔树测试网已经上线并运行，下一阶段是在私有测试网上运行启用沃克尔树的客户端，然后在公共测试网运行。 你可以通过在测试网部署智能合约或运行测试网客户端来帮助加速这一进程。
