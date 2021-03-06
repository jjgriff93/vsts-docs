---
title: VSS/References/SDK.Interfaces ExtensionManifest API | Extensions for Visual Studio Team Services
description: Base class for extension properties which are shared by the extension manifest and the extension model
ms.assetid: 061b025a-4d0d-fed5-2110-32747d086619
ms.prod: devops
ms.technology: devops-ecosystem
generated: true
ms.manager: douge
ms.author: elbatk
author: elbatk
ms.topic: article
monikerRange: '>= tfs-2017'
ms.date: 08/04/2016
---

# ExtensionManifest

Defined in vss.d.ts


Base class for extension properties which are shared by the extension manifest and the extension model 

### Members

* `baseUri`: string. Uri used as base for other relative uri&#x27;s defined in extension

* `contributions`: [Contribution](../../../VSS/References/SDK_Interfaces/Contribution.md)[]. List of contributions made by this extension

* `contributionTypes`: [ContributionType](../../../VSS/References/SDK_Interfaces/ContributionType.md)[]. List of contribution types defined by this extension

* `eventCallbacks`: [ExtensionEventCallbackCollection](../../../VSS/References/SDK_Interfaces/ExtensionEventCallbackCollection.md). Collection of endpoints that get called when particular extension events occur

* `language`: string. Language Culture Name set by the Gallery

* `manifestVersion`: any. Version of the extension manifest format/content

* `scopes`: string[]. List of all oauth scopes required by this extension

* `serviceInstanceType`: string. The ServiceInstanceType(Guid) of the VSTS service that must be available to an account in order for the extension to be installed

