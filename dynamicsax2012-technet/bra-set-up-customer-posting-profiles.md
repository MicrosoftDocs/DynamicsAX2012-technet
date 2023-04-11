---
title: (BRA) Set up customer posting profiles
TOCTitle: (BRA) Set up customer posting profiles
ms:assetid: f3e60c6b-eb1f-4ceb-be5e-110e3c12e47e
ms:mtpsurl: https://technet.microsoft.com/library/JJ663971(v=AX.60)
ms:contentKeyID: 49384556
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- customer
- posting profiles
- BRA
- Brazil
- Customer posting profiles
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up customer posting profiles 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Customer posting profiles** form to specify an account to credit the Imposto sobre Circulação de Mercadorias e Serviços (ICMS) tax amount to. You can apply a customer posting profile to a single customer, a group of customers, or all customers.

1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  Create a customer posting profile.

3.  In the **Posting profile** and **Description** fields, enter a name and a description for the posting profile.

4.  Click the **Setup** FastTab, and then in the **Account code** field, select an account code from the following options:
    
      - **Table** – The posting profile is for a specific customer.
    
      - **Group** – The posting profile is for a specific customer group.
    
      - **All** – The posting profile is for all customers.

5.  In the **Account/Group number** field, select a customer account or a customer group.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Account code</STRONG> field.</P>



6.  In the **Tax transfer** field, select an account to credit the ICMS tax amount to.

## See also

[Customer posting profiles (form)](https://technet.microsoft.com/library/aa600572\(v=ax.60\))

[(BRA) Customer posting profiles (modified form)](https://technet.microsoft.com/library/jj663980\(v=ax.60\))

  


