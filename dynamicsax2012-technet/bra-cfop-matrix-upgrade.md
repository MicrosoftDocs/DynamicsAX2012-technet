---
title: (BRA) CFOP matrix (upgrade)
TOCTitle: (BRA) CFOP matrix (upgrade)
ms:assetid: af069531-d83a-40e2-9071-70a5c4b59601
ms:mtpsurl: https://technet.microsoft.com/library/JJ714197(v=AX.60)
ms:contentKeyID: 49651306
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BRA) CFOP matrix (upgrade) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In releases before Microsoft Dynamics AX 2012 R2, you could not create a Código Fiscal de Operações e Prestações (CFOP) matrix to determine the CFOP code and CFOP group to be used specifically in free text invoices. Instead, all CFOP codes with the sales transaction type were available for free text invoices. In Microsoft Dynamics AX 2012 R2 and R3, you can create a CFOP matrix to determine a CFOP code and CFOP group to be used only in free text invoices. During upgrade preprocessing, you can select the CFOP matrices to use only in free text invoices in the target system.

Use this procedure to upgrade the CFOP matrix to use in free text invoices in Microsoft Dynamics AX 2012 R2 and R3.

1.  In the **Preprocessing upgrade checklist**, expand **Prepare application data for preprocessing**, and then click **CFOP matrix** to open the **CFOP matrix** form.

2.  Select the **Use CFOP in Free text invoice** check box to use the selected CFOP matrix in free text invoices.

3.  Repeat step 2 for each CFOP code that is used in free text invoices.

4.  After you select all the CFOP matrices to use in free text invoices, click **Set to ready for upgrade** to close the form and mark the upgrade task as complete.

## See also

[(BRA) CFOP matrix (upgrade) (form)](https://technet.microsoft.com/library/jj713623\(v=ax.60\))

  


