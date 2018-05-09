---
title: Work with RFID for inbound items
TOCTitle: Work with RFID for inbound items
ms:assetid: 39a9cc18-26b3-447d-93ae-23c881fa71d8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570146(v=AX.60)
ms:contentKeyID: 36056633
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- radio frequency identification
- RFID
- inbound items
---

# Work with RFID for inbound items 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

You must:

  - Decide which radio frequency identification (RFID) items should be tagged and the level of the tagging.

  - Activate the serial number dimension in the **Tracking dimension groups** form for the dimension group.

  - Specify the receipt quantity per number to one in the **Number groups** form as the tags are connected to serial numbers.

### Receive RFID items

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    The RFID tagging requirements are transferred to the purchase order line, but can still be changed.

2.  Click **Inventory management** \> **Journals** \> **Item arrival** \> **Item arrival**.

3.  On the **Default values** tab, enter the vendor number, the purchase order reference number, or both.

4.  Indicate the warehouse and select a location of the inbound dock type.

5.  Click **Functions**, and then select **Create lines** to retrieve the purchase order.
    

    > [!NOTE]
    > <P>You can choose to transfer the quantity from the purchase order by selecting the <STRONG>Initialize quantity</STRONG> check box. Microsoft Dynamics AX creates the lines corresponding to the quantity of items that fits onto a pallet. The lines are then shown in the <STRONG>Journal lines</STRONG> form.</P>



6.  Enter the **Pallet ID** in the **Journal lines** form. You can do Pallet numbering in two ways using the number on the pallet that has arrived:
    
    \- Select the number of the pallet in the **Pallet ID** field for the line.
    
    \- Use your own consecutive pallet numbering system. A series of numbers is used to get consecutive pallet numbers. Click **Functions**, and then select **Pallet ID** to create a new number.

7.  Click **Functions**, and then select **RFID mapping** to map RFID tags to the lines.

8.  Use the form to map RFID tag reads to inventory transactions for arrival journal lines.
    

    > [!NOTE]
    > <P>In the upper part of the form, you can filter on processes and dates so only tag identifications from the selected interval are shown.</P>



9.  Click **Apply** when finished.
    

    > [!NOTE]
    > <P>Only the identifications that contain the global trade item number GTIN of the item on the arrival journal line are shown in the lookup field.</P>



10. Check the journal, correct any mistakes, and post it. Following posting, the inventory transaction has the status of **Arrived**, and the item is registered at the inbound dock.

## See also

[About RFID](about-rfid.md)

[Ship outbound items with RFID](ship-outbound-items-with-rfid.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

