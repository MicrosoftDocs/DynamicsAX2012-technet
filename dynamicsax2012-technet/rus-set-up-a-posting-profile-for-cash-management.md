---
title: (RUS) Set up a posting profile for cash management
TOCTitle: (RUS) Set up a posting profile for cash management
ms:assetid: 7e2d87cd-a228-4643-a554-4d233c773cec
ms:mtpsurl: https://technet.microsoft.com/library/JJ678402(v=AX.60)
ms:contentKeyID: 49387632
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a posting profile for cash management 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The ledger posting profile defines cash management posting in ledger accounts. A posting profile can be linked to a single cash account, or it can be linked to all the cash accounts.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Cash and bank management** \> **Setup** \> **Cash posting profiles**.

2.  Click CTRL+N to create a new cash posting profile.

3.  In the **Cash posting** field, enter the posting profile code for the cash accounts.

4.  In the **Description** field, enter a description for the cash posting profile code.

5.  Click the **Ledger accounts** tab, and create a new record.

6.  In the **Valid for** field, select from the following values:
    
      - **Table** – The setup is for a single cash account.
    
      - **All** – The setup is for all cash accounts.

7.  In the **Cash** field, select the cash account code.
    

    > [!NOTE]
    > <P>The <STRONG>Cash</STRONG> field is not available if you selected <STRONG>All</STRONG> in the <STRONG>Valid for</STRONG> field.</P>



8.  In the **Main account** field, select the ledger account number for posting the transactions.

9.  Press CTRL+S or close the form.

## See also

[(RUS) Cash accounts (form)](https://technet.microsoft.com/library/jj665230\(v=ax.60\))

  


