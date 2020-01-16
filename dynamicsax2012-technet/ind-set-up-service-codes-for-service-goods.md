---
title: (IND) Set up service codes for service goods
TOCTitle: (IND) Set up service codes for service goods
ms:assetid: d38e66a7-0f5d-4068-a73c-5b8b470a0451
ms:mtpsurl: https://technet.microsoft.com/library/JJ664942(v=AX.60)
ms:contentKeyID: 49386273
author: Khairunj
ms.date: 04/25/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.EcoResProductDetailsExtended
- Forms.ServiceCodeTable_IN
audience: Application User
ms.search.region: India
---

# (IND) Set up service codes for service goods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

You can use the **Service codes** form to create service codes for services that are provided by an output service provider. You can also attach service codes to items that have a **Service** type to calculate the service tax.

In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: You can define an accounting code for each service code. When you select a service code for a transaction, the accounting code that is related to the service code is automatically updated for the transaction.

## Set up a service code

Use this procedure to create a service code for service items.


> [!NOTE]
> <P>You cannot delete a service code that is attached to an item of type <STRONG>Service</STRONG> in the <STRONG>Released product details</STRONG> form.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Service codes**.

2.  Create a service code.

3.  In the **Service code** field, enter the identification code for the service code.

4.  In the **Name** field, enter the description of the service code.

5.  In the **Minor head** field, enter the minor head for the service code.
    

    > [!NOTE]
    > <P>A minor head is defined for a service account that is created under a major head.</P>



6.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Accounting code** field, enter the accounting code that is associated with the service code.

## Attach a service code to a service item

Use this procedure to attach a service code to an item of type **Service**.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select or create an item of type **Service**. For more information, see [Key tasks: Define products](key-tasks-define-products.md).

3.  On the **Released products** list page, click **Edit**.

4.  On the **General** FastTab, in the **Service code** field, select the service code for the item of type **Service**.

## See also

[(IND) Service codes (form)](https://technet.microsoft.com/library/jj664830\(v=ax.60\))

  


