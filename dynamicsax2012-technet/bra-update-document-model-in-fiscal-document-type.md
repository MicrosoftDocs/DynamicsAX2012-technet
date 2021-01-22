---
title: (BRA) Update document model in fiscal document type
TOCTitle: (BRA) Update document model in fiscal document type
ms:assetid: 2e946677-71a3-412e-a3f1-f8ebce990b7f
ms:mtpsurl: https://technet.microsoft.com/library/JJ714189(v=AX.60)
ms:contentKeyID: 49651298
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BRA) Update document model in fiscal document type 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In releases before Microsoft Dynamics AX 2012 R2, you could enter identification codes of up to three characters for fiscal document models in the **Document model** field in the **Fiscal document types** form. In Microsoft Dynamics AX 2012 R2 and R3, the fiscal document models are available in the **Document model** form, and you can select these fiscal document models in the **Document model** field in the **Fiscal document types** form. During upgrade preprocessing, if a fiscal document type has a legacy fiscal document model that is not available in the **Document model** form in the target system, you must select a fiscal document model in the target system.

Use the following procedure to upgrade fiscal document models in fiscal document types.

1.  In the **Preprocessing upgrade checklist**, expand **Prepare application data for preprocessing**, and then click **Update document model** to open the **Update document model in fiscal document type** form.

2.  In the **New document model** field, select an identification code of the fiscal document model for the fiscal document type in the target system.

3.  After you select identification codes for all the fiscal document models in fiscal document types in the target system, click **Set to ready for upgrade** to mark the checklist task as complete.

## See also

[(BRA) Update document model in fiscal document type (form)](https://technet.microsoft.com/library/jj713624\(v=ax.60\))

  


