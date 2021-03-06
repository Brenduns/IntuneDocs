---
# required metadata

title: How to assign device profiles with IntunetitleSuffix: "Intune on Azure"
description: Once you've created an Intune device profile, use this topic to learn how to assign it to devices."
keywords:
author: robstackmsft
ms.author: robstack
manager: angrobe
ms.date: 06/03/2017
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: f6f5414d-0e41-42fc-b6cf-e7ad76e1e06d

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: heenamac
ms.suite: ems
#ms.tgt_pltfrm:
ms.custom: intune-azure

---

# How to assign Microsoft Intune device profiles

[!INCLUDE[azure_portal](./includes/azure_portal.md)]


1. Sign into the Azure portal.
2. Choose **More Services** > **Monitoring + Management** > **Intune**.
3. On the **Intune** blade, choose **Device configuration**.
1. On the **Device configuration** blade, choose **Manage** > **Profiles**.
2. In the list of profiles blade, choose the profile you want to manage, and then, on the <*profile name*> **Reports** blade, choose **Manage** > **Assignments**.
3. On the next blade, click **Select groups**, and then, in the **Select groups** blade, choose the Azure AD groups to which you want to assign the profile. You can hold down the **CTRL** key to select multiple groups.
4. When you are done, on the **Select groups** blade, choose **Select**.

### Next steps
See [How to monitor device profiles](device-profile-monitor.md) for information to help you monitor device profile assignments.
