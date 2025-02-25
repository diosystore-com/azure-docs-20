---
title: Form Recognizer service encryption of data at rest
titleSuffix: Azure Applied AI Services
description: Microsoft offers Microsoft-managed encryption keys, and also lets you manage your Cognitive Services subscriptions with your own keys, called customer-managed keys (CMK). This article covers data encryption at rest for Form Recognizer, and how to enable and manage CMK. 
author: erindormier
manager: venkyv
ms.service: applied-ai-services
ms.subservice: forms-recognizer
ms.topic: conceptual
ms.date: 10/20/2022
ms.author: egeaney
ms.custom: applied-ai-non-critical-form
monikerRange: '>=form-recog-2.1.0'
recommendations: false
---

# Form Recognizer encryption of data at rest

[!INCLUDE [applies to v3.0 and v2.1](includes/applies-to-v3-0-and-v2-1.md)]

Azure Form Recognizer automatically encrypts your data when persisting it to the cloud. Form Recognizer encryption protects your data to help you to meet your organizational security and compliance commitments.

[!INCLUDE [cognitive-services-about-encryption](../../cognitive-services/includes/cognitive-services-about-encryption.md)]

> [!IMPORTANT]
> Customer-managed keys are only available resources created after 11 May, 2020. To use CMK with Form Recognizer, you will need to create a new Form Recognizer resource. Once the resource is created, you can use Azure Key Vault to set up your managed identity.

[!INCLUDE [cognitive-services-cmk](../../cognitive-services/includes/configure-customer-managed-keys.md)]

## Next steps

* [Form Recognizer Customer-Managed Key Request Form](https://aka.ms/cogsvc-cmk)
* [Learn more about Azure Key Vault](../../key-vault/general/overview.md)
