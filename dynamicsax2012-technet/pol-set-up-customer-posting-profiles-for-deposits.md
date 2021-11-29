---
title: (POL) Set up customer posting profiles for deposits
TOCTitle: (POL) Set up customer posting profiles for deposits
ms:assetid: 48ad9fff-cb9e-42e3-9476-3007d2d76c10
ms:mtpsurl: https://technet.microsoft.com/library/JJ911063(v=AX.60)
ms:contentKeyID: 52075332
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- customer posting profiles
- Poland
audience: Application User
ms.search.region: Poland
---

# (POL) Set up customer posting profiles for deposits 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Customer posting profiles** form to set up a main account number for the deposit amounts that are paid by customers. You can use the **Customers** form to indicate whether the customer is exempt from the deposit fee.

## Set up deposit exemption for a customer

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Create a new customer or double-click a customer record, and then click **Edit**.

3.  On the **Invoice and delivery** tab, clear the **Deposit exempt** check box to indicate that the customer is not exempt from the deposit fee.

## Set up a main account number for customer deposits

1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  Press CTRL+N to create a customer posting profile. For more information, see [Customer posting profiles (form)](https://technet.microsoft.com/library/aa600572\(v=ax.60\)).

3.  On the **Setup** tab, in the **Account code** field, select whether this posting profile is used for a single customer account, a group of customer accounts, or all customer accounts.

4.  In the **Account/Group number** field, select the customer account to include in the posting profile.

5.  In the **Deposits** field, select the main account number to post the deposit amounts to.

## See also

[(POL) Customer posting profiles (modified form)](https://technet.microsoft.com/library/jj923262\(v=ax.60\))

[(POL) Set up returnable packages for a customer](pol-set-up-returnable-packages-for-a-customer.md)

  


