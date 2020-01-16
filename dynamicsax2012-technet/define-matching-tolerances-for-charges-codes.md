---
title: Define matching tolerances for charges codes
TOCTitle: Define matching tolerances for charges codes
ms:assetid: 5595569c-fa5f-45d3-becb-b348691afa20
ms:mtpsurl: https://technet.microsoft.com/library/Hh208961(v=AX.60)
ms:contentKeyID: 36057315
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Define matching tolerances for charges codes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If your organization wants to plan for expected freight costs, employees can enter the expected freight costs as charges on purchase orders. To help monitor the actual freight costs, you can use charges matching. Users can make sure that the variance between the total expected and total actual charges is within the acceptable tolerances that have been set up for the legal entity or for individual charges codes.

The default tolerance for charges matching is specified in the **Accounts payable parameters** form. You can set up tolerances for charges codes that override the default tolerance. For example, to add stricter control on freight than for other types of charges, you can define the charges matching tolerance for the charges code that represents freight.

1.  Click **Accounts payable** \> **Setup** \> **Invoice matching** \> **Charges tolerances**.

2.  Select a charges code.
    
    The charges code must have a debit type or credit type of **Customer/Vendor** and must have the **Compare purchase order and invoice values** check box selected in the **Charges code** form.

3.  Enter the variance percentage that you will accept for this charges code.

4.  Repeat steps 2 and 3 for additional charges codes, and then close the form.

## See also

[Charges tolerances (form)](https://technet.microsoft.com/library/hh227600\(v=ax.60\))

  


