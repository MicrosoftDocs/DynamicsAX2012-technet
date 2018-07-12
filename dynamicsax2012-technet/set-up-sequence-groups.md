---
title: Set up sequence groups
TOCTitle: Set up sequence groups
ms:assetid: 42e3a7a6-93e5-4cc2-ae9a-ba6339d8b432
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838731(v=AX.60)
ms:contentKeyID: 50120614
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up sequence groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create sequence groups that are used to schedule production. You can assign sequences to a sequence group and then rank these sequences in the order of preference. For example, in the paint industry, color-based paints can have color properties and other attributes, such as latex or enamel. You can create a sequence that contains values for colors that are ranked according to preference in which these colors are ordered or sorted. You can create another sequence that contains values for the type of paint, so that latex is preferred to enamel. You can then assign these sequences to a sequence group, and then rank the sequences so that all the colors that are available for a specified type of paint are sequenced, or all the types of paint that are available for a specified paint are sequenced, according to the ranks of the sequences in the sequence group.

1.  Click **Master planning** \> **Setup** \> **Sequencing** \> **Sequence group**.

2.  Create a sequence group.

3.  In the **Sequence group ID** and **Description** fields, enter an identification code and a description of a sequence group.

4.  In the lower pane, click **New** to assign a sequence to the specified sequence group.

5.  In the **Sequence** field, select the identification code of the sequence to assign to the sequence group.

6.  In the **Rank** field, enter a rank for the specified sequence.

7.  Repeat steps 4 through 6 to add more sequences to the sequence group.

## See also

[Set up product sequences](set-up-product-sequences.md)

[Assign sequence values to an item](assign-sequence-values-to-an-item.md)

[Sequence group (form)](https://technet.microsoft.com/en-us/library/jj838755\(v=ax.60\))

  


