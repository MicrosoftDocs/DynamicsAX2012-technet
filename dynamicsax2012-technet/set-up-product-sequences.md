---
title: Set up product sequences
TOCTitle: Set up product sequences
ms:assetid: 0a699499-5e97-44c8-840c-0a9927f63f3b
ms:mtpsurl: https://technet.microsoft.com/library/JJ838720(v=AX.60)
ms:contentKeyID: 50120603
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up product sequences 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create product sequences that you can assign to items. A sequence is a characteristic of an item that is used to schedule production. You can define values for a sequence that specify the required order in which jobs are scheduled during production. For example, you can create a sequence for producing types of paints. You can then create sequence values for different types of paints, such as latex paint and enamel paint. If the latex paint is scheduled to be produced before the enamel paint, you can assign a lower rank (0) to the latex paint and assign a higher rank (1) to the enamel paint.

1.  Click **Master planning** \> **Setup** \> **Sequencing** \> **Sequences**.

2.  Create a sequence.

3.  In the **Sequence ID** and **Description** fields, enter an identification code and a description for the sequence.

4.  On the **Sequence value** FastTab, click **New** to create a value for the sequence.

5.  In the **Value** and **Rank** fields, enter a value and a rank for the sequence value. Zero (0) is the lowest possible rank.

6.  Repeat steps 4 and 5 to create additional values for the sequence.

## See also

[Sequences (form)](https://technet.microsoft.com/library/jj838758\(v=ax.60\))

[Set up sequence groups](set-up-sequence-groups.md)

[Assign sequence values to an item](assign-sequence-values-to-an-item.md)

  


