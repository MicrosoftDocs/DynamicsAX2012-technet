---
title: Assign sequence values to an item
TOCTitle: Assign sequence values to an item
ms:assetid: e8dcb2e7-a64c-4522-af18-1845f15b4cf9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838752(v=AX.60)
ms:contentKeyID: 50120635
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Assign sequence values to an item 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to assign sequences and sequence values to an item, an item group, or all items.

1.  Click **Master planning** \> **Setup** \> **Sequencing** \> **Sequence value**.

2.  Create a record.

3.  In the **Sequence ID** field, select the identification code of a sequence.

4.  In the **Item code** field, select one of the following options to indicate the item code and determine the value that you can select in the **Item relation** field:
    
      - **Table** – Assign the sequence to an item. If you select this option, you can then select the identification code of the item in the **Item relation** field.
    
      - **Group** – Assign the sequence to an item group. If you select this option, you can then select the identification code of the item group in the **Item relation** field.
    
      - **All** – Assign the sequence to all the items. If you select this option, the **Item relation** field is not available.

5.  In the **Item relation** field, select the item or item group to assign the sequence and the sequence value to.
    

    > [!NOTE]
    > <P>This field is available only if you select either <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Item code</STRONG> field.</P>



6.  In the **Value** field, select the sequence value to assign to the item, the item group, or all items.

## See also

[Set up product sequences](set-up-product-sequences.md)

[Set up sequence groups](set-up-sequence-groups.md)

[Sequence item (form)](https://technet.microsoft.com/en-us/library/jj838760\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

