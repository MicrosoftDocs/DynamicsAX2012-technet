---
title: (BRA) Update incoming fiscal document models
TOCTitle: (BRA) Update incoming fiscal document models
ms:assetid: d2380f84-5093-4ffb-97ce-276f7b3378c6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ714202(v=AX.60)
ms:contentKeyID: 49651311
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BRA) Update incoming fiscal document models [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In releases before Microsoft Dynamics AX 2012 R2, you could enter identification codes of up to three characters for fiscal document models in incoming fiscal documents. In Microsoft Dynamics AX 2012 R2 and R3, the fiscal document models are available in the **Document model** form, and you can select these fiscal document models in incoming fiscal documents. During upgrade preprocessing, if an incoming fiscal document has a legacy fiscal document model that is not available in the **Document model** form in the target system, you must select a fiscal document model in the target system.

Use the following procedure to upgrade fiscal document models for incoming fiscal documents.

1.  In the **Preprocessing upgrade checklist**, expand **Prepare application data for preprocessing**, and then click **Update incoming fiscal document models** to open the **Update incoming fiscal document models** form.

2.  In the **New document model** field, select an identification code of the fiscal document model for incoming fiscal documents in the target system.

3.  After you select identification codes for all the fiscal document models for incoming fiscal documents in the target system, click **Set to ready for upgrade** to mark the checklist task as complete.

## See also

[(BRA) Update incoming fiscal document models (form)](https://technet.microsoft.com/en-us/library/jj713628\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

