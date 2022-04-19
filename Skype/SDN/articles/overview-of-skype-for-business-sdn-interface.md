---
title: Overview of Skype for Business SDN Interface (Lync Server 2013 | Skype for Business 2015)
TOCTitle: Overview of Skype for Business SDN Interface
ms:assetid: 5cd64da2-e0bb-4558-9ccb-6e8fa01663fd
ms:mtpsurl: https://msdn.microsoft.com/library/Dn785191(v=office.16)
ms:contentKeyID: 65258651
ms.date: 02/27/2017
mtps_version: v=office.16
---

# Overview of Skype for Business SDN Interface (Lync Server 2013 | Skype for Business 2015)


_**Applies to:** Lync Server 2013 | Skype for Business 2015_

The Microsoft Skype for Business SDN Interface provides a subscription-based interface for network controllers or network management systems to receive call and quality data to monitor and analyze network traffic in order to optimize the Skype for Business media stream quality.

The Microsoft Skype for Business SDN Interface is not a programming interface but a RESTful interface through which subscribed systems (generally called "subscribers") receive data about active calls and the end-to-end measured quality of media streams.

The data received is used to identify, diagnose and resolve quality and performance issues in the Skype for Business environment or the network infrastructure that it uses. The quality metrics are intended to correlate with information observed by the network infrastructure as well as with other calls, call-legs, devices and endpoints. Goals of the SDN Interface is to enable network management systems to provide the following:

  - Superior diagnostics

  - Dynamic QOS

  - Intelligent routing

The interface provides data as close to real-time as possible, although without any guarantees; this enables real-time tracking and diagnosis of calls in progress, as well as the collection of data for long-term analysis.

**In this section**

  - [Understanding Skype for Business SDN Interface](understanding-skype-for-business-sdn-interface.md)

  - [Installing Skype for Business SDN Interface](installing-skype-for-business-sdn-interface.md)

  - [Configuring Skype for Business SDN Interface](configuring-skype-for-business-sdn-interface.md)

  - [Running and debugging Skype for Business SDN Interface](running-and-debugging-skype-for-business-sdn-interface.md)

  - [Skype for Business SDN Interface Schema Reference](skype-for-business-sdn-interface-schema-reference.md)

