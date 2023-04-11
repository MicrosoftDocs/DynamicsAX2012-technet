---
title: Prioritize automatic settlements
TOCTitle: Prioritize automatic settlements
ms:assetid: c1238d5f-4bef-4ff7-ab1c-5174fe0f6c6b
ms:mtpsurl: https://technet.microsoft.com/library/Hh242829(v=AX.60)
ms:contentKeyID: 36059268
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- prioritize settlements
- settlement priority
- settlement order
audience: Application User
ms.search.region: Global
---

# Prioritize automatic settlements 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to automatically settle payments by attribute type, transaction type, and billing classification. For example, when a payment is received from a customer, you can choose to settle interest notes with the largest amounts owed, first. The settlement priority will be applied to all automatic settlements. These include customer payments, payment journal lines, and open transactions that include multiple debits.


> [!NOTE]
> <P>This feature is available only if the <STRONG>Prioritize settlement</STRONG> check box is selected in the <STRONG>Accounts receivable parameters</STRONG> form.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**. Click **Settlement**, and then click **Manage priority**.

2.  Optional: Click **Billing classifications** to open the **Billing classifications** form, where you can arrange billing classifications and billing codes by settlement priority.
    

    > [!NOTE]
    > <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>

    
    For more information about billing classifications, see [Billing classifications (form) (Public sector)](https://technet.microsoft.com/library/hh208608\(v=ax.60\)).

3.  Close the **Billing classifications** form, if applicable.

4.  In the **Settlement priority** table, select an attribute to prioritize.

5.  Click the **Up** or **Down** buttons above the **Settlement priority** table until the selected attribute is in the appropriate order.
    

    > [!NOTE]
    > <P>The voucher attribute is always enabled and cannot be modified.</P>



6.  Select the **Active** check box to include the attribute in the settlement priority. Only attributes that have the **Active** check box selected will be included in the automatic settlement process.

7.  Specify other information, depending on the selected attribute and other settings that you have specified. For more information about these options, see [Settlement priority (form)](https://technet.microsoft.com/library/hh208717\(v=ax.60\)).
    
      - **Settlement order** – Specify the order in which the transactions that are displayed will be settled.
    
      - **Sort order** – Select the order in which to apply payments. For example, if the transaction amount is set to **Ascending**, payments will be applied to the transactions with the lowest amounts first.
    
      - **Invoice line priority** – Select **None**, **Billing code**, or **Proration**.
    
      - **Extend billing code priority across invoices** – Select this check box to settle all free text invoice lines in the order that is specified in the **Billing classifications** form for invoices that belong to the same billing classification.
        

        > [!NOTE]
        > <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>

    
      - **Proration type** – Select **Equal** or **Proportional**.

## See also

[Settlement priority (form)](https://technet.microsoft.com/library/hh208717\(v=ax.60\))

  


