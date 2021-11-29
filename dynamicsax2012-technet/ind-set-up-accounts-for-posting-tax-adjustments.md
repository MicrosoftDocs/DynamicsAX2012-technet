---
title: (IND) Set up accounts for posting tax adjustments
TOCTitle: (IND) Set up accounts for posting tax adjustments
ms:assetid: 92afc928-3bfa-4112-8d5d-07396bf6b27a
ms:mtpsurl: https://technet.microsoft.com/library/JJ678059(v=AX.60)
ms:contentKeyID: 49386020
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up accounts for posting tax adjustments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



When you run the tax settlement process, the tax amounts that are adjusted are posted to the ledger accounts that you define in the **Accounts for automatic transactions** form. The amounts are temporarily posted to the system accounts before they are finally posted to the main accounts in your chart of accounts.

1.  Click **General ledger** \> **Setup** \> **Posting** \> **Accounts for automatic transactions**.

2.  Press CTRL+N to create a new posting type for the tax amounts that are adjusted.

3.  In the **Posting type** field, select **Tax adjustment – Settlement**.

4.  In the **Main account** field, select the main account to temporarily post the tax adjustment amount to.
    

    > [!NOTE]
    > <P>You must define an account in the <STRONG>Chart of accounts</STRONG> form to post the tax adjustment amount.</P>



## See also

[(IND) System accounts (modified form)](https://technet.microsoft.com/library/jj664740\(v=ax.60\))

[(IND) Chart of accounts (modified form)](https://technet.microsoft.com/library/jj677830\(v=ax.60\))

  


