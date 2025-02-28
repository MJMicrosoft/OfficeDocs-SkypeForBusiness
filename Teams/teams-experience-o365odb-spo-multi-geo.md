---
title: Teams experience in a Microsoft 365 Multi-Geo-enabled environment
ms.author: mikeplum
author: MikePlumleyMSFT
manager: serdars
ms.topic: conceptual
ms.service: msteams
ms.reviewer: snigdhav
audience: admin
localization_priority: Normal
search.appverid: MET150
ms.collection: 
  - M365-collaboration
  - SPO_Content
ms.custom: seo-marvel-apr2020
f1.keywords:
- NOCSH
appliesto: 
  - Microsoft Teams
description: In this article, you will learn about using Teams in a Microsoft 365 Multi-Geo-enabled environment.
---

# Teams experience in a Microsoft 365 Multi-Geo-enabled tenancy

Microsoft Teams is group chat software, the hub for teamwork in Microsoft 365. It is powered by the Microsoft 365 Groups service along with SharePoint and OneDrive for its files experience. In a Multi-Geo organization in which the tenant is extended to many geographic locations such as North America, Europe, and Australia, the underlying files experience is Multi-Geo aware, so the Teams experience with file collaboration is also Multi-Geo aware. This allows Teams to surface files hosted across multiple geo locations in its native files experience.

For example, in a Contoso tenancy with Europe as a satellite Geo and North America as the central Geo, a European satellite user will see his or her OneDrive files under the Files tab in left pane, although the files are hosted in the Europe data location and the United States is the tenant’s central location. Also, the user can access the most recently used files under the Recent view blade. Recent files may include files shared from users in other geo locations. 

A given Team’s SharePoint site is also Multi-Geo aware. That is, if a European satellite user is creating a Team, the corresponding SharePoint site will be created in the Europe location and the files associated with that Team will be kept at rest in that location. Any subsequent experiences, such as uploading a new file or editing the file, will be stored in that European location, keeping the promise of data residency for those files.

Note that conversations in chats and meeting IM notes within the Teams experience are not Multi-Geo aware and are all kept only inside the central location of the organization.

For more information about Multi-Geo, see [Microsoft Multi-Geo capabilities](https://aka.ms/multi-geo).
