---
title: (RUS) Cancel a shipment with delayed transfer of property
TOCTitle: (RUS) Cancel a shipment with delayed transfer of property
ms:assetid: 7499ec98-204c-40e1-a1d7-9c4ad8dc6b10
ms:mtpsurl: https://technet.microsoft.com/library/JJ911547(v=AX.60)
ms:contentKeyID: 53382714
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Cancel a shipment with delayed transfer of property 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can cancel a shipment for items for which the transfer of property is not registered, or for which the transfer of property is only partially registered. A credit note is created when you cancel a shipment.

1.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  Select a sales invoice line that has a posting type of **Postponed passing of property**.

3.  Click **Passing of property** \> **Shipment cancellation**.

4.  In the **Shipment cancellation** form, in the **Processing** field group, in the **Date** field, select the cancellation date.

5.  Select the **Credit correction (physical)** check box to indicate that the update to physical inventory is posted as a credit correction.
    

    > [!NOTE]
    > <P>This check box is selected if you selected the <STRONG>Storno for physical posting</STRONG> check box in the <STRONG>General</STRONG> area in the <STRONG>Inventory and warehouse management parameters</STRONG> form.</P>



6.  Select the **Credit correction** check box to post the credit note transaction as a credit correction.
    

    > [!NOTE]
    > <P>This check box is selected if you selected the <STRONG>Credit note as correction</STRONG> check box in the <STRONG>Updates</STRONG> area in the <STRONG>Accounts receivable parameters</STRONG> form.</P>



7.  Select the **Credit remaining quantity** check box to invoice the remaining quantity of the items that are returned when you post a negative quantity against a sales line. When a sales invoice is canceled, the quantity that is specified in the sales order becomes available for other shipments.

8.  Select the **Corrective document** check box to create a reference to the source sales invoice in the credit note.

9.  On the **Overview** tab, select the **Mark** check box to select an invoice line to cancel.

10. In the **For processing** field, modify the quantity that you have to cancel the shipment for.
    

    > [!NOTE]
    > <P>If the number of sales units or inventory units for processing equals the corresponding number of available units, you must select equal values in the <STRONG>Available</STRONG> and <STRONG>For processing</STRONG> fields for both sales units and inventory units.</P>



11. Click **OK** to cancel the shipment.

## See also

[(RUS) Shipment cancellation (form)](https://technet.microsoft.com/library/jj923572\(v=ax.60\))

  


