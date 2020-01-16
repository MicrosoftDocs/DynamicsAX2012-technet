---
title: (RUS) Register the transfer of property for a posted sales invoice
TOCTitle: (RUS) Register the transfer of property for a posted sales invoice
ms:assetid: 6d7617a2-3c10-46a4-86d9-c78c04de2489
ms:mtpsurl: https://technet.microsoft.com/library/JJ853192(v=AX.60)
ms:contentKeyID: 50396473
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Register the transfer of property for a posted sales invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Passing of property** form to register the transfer of property for a sales invoice that was posted. Each invoice line in the form contains the quantities of items that the property transfer has to be registered for. To confirm the transfer of property, you specify a date and the quantity on the invoice line. The sales tax charges and other charges are recalculated based on the quantity, date of shipment, and date of the transfer of property.

1.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  Select a sales invoice line that has a posting type of **Postponed passing of property**.

3.  Click **Passing of property** \> **Passing of property**.

4.  In the **Processing** field group, in the **Date** field, select the date of the property transfer.

5.  Select the **Mark** check box to select an invoice line for the property transfer.
    

    > [!NOTE]
    > <P>You can select the <STRONG>Select all</STRONG> check box to select all invoice lines.</P>



6.  In the **For processing** field, select the quantity to register for the property transfer.
    

    > [!NOTE]
    > <P>If the number of sales units or inventory units for processing equals the corresponding number of available units, you must select equal values in the <STRONG>Available</STRONG> and <STRONG>For processing</STRONG> fields for both sales units and inventory units.</P>



7.  Click **OK** to register the transfer of property.

## See also

[(RUS) Settle a sales invoice with delayed transfer of property](rus-settle-a-sales-invoice-with-delayed-transfer-of-property.md)

[(RUS) Cancel a shipment with delayed transfer of property](rus-cancel-a-shipment-with-delayed-transfer-of-property.md)

  


