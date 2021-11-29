---
title: (IND) Create excise ledger accounts
TOCTitle: (IND) Create excise ledger accounts
ms:assetid: ab2dee26-3033-42a5-beea-ce1085552203
ms:mtpsurl: https://technet.microsoft.com/library/JJ664780(v=AX.60)
ms:contentKeyID: 49386097
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create excise ledger accounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must maintain excise recoverable accounts and excise payable accounts separately for each combination of an Excise Control Code (ECC) number and an excise duty. The account type for the accounts must be **Balance sheet**. Create the accounts in the **Chart of accounts** form.

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**. On the **Main accounts** FastTab, select an existing account, or click **New** to create an account.
    
    –or–
    
    Click **General ledger** \> **Common** \> **Main accounts**. On the **Main accounts** list page, select and open an existing main account, or on the **Action Pane**, in the **New** group, click **Main account** to create a main account.

2.  Create the following ledger accounts for each excise tax component to record the excise transactions:
    
      - **Excise, payable**
    
      - **Excise, recoverable**
    
      - **Interim PLA account**
    
      - **PLA account**
    
      - **RG23A deferred account**
    
      - **RG23C deferred account**
    
      - **RG23D CENVAT credit transferred account**
    
      - **RG23D CENVAT credit account**

3.  On the **Setup** FastTab, in the **Posting type** field, select **Excise** to post the transactions that are related to excise tax to the ledger accounts.

4.  Enter information in the other required fields.

5.  Repeat steps 3 and 4 for each ledger account.

  


