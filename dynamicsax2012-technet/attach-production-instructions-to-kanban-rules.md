---
title: Attach production instructions to kanban rules
TOCTitle: Attach production instructions to kanban rules
ms:assetid: e9c7cc4b-9c6a-405d-81f6-799714c18ade
ms:mtpsurl: https://technet.microsoft.com/library/JJ730943(v=AX.60)
ms:contentKeyID: 49675119
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Attach production instructions to kanban rules 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to attach production instructions to kanban rules that are configured to use the **Manufacturing** type and the **Fixed** replenishment strategy. When you attach production instructions to a kanban rule, the production instructions for a kanban job are displayed in the **Kanban board for process jobs** form. You can also display the production instructions on kanban cards that you print.

The following conditions must be set up before you can complete the procedure:

  - The type of document that is used for production instructions is specified in the **Production control parameters** form. Click **Production control** \> **Setup** \> **Production control parameters**. Click **Lean manufacturing**. In the **Production instruction** field, select **File**.

  - The document that contains the production instructions must be saved to a location on the hard disk drive of a computer that can be accessed. The document formats that are supported include .txt, .jpeg, and .gif. Because high-resolution graphics can adversely affect the printing performance, we recommend that you use the minimum resolution that is needed for the document.

  - The kanban rule must be configured to print the production instructions. Click **Production control** \> **Setup** \> **Lean manufacturing** \> **Kanban rules**. On the **Kanban and cards** FastTab, in the **Print instructions** field, select **Work instructions**.


> [!NOTE]
> <P>You can also attach production instructions to production flow activities and to items.</P>



### Attach production instructions to kanban rules

1.  Click **Production control** \> **Setup** \> **Lean manufacturing** \> **Kanban rules**.

2.  Select the kanban rule to attach the production instructions to.

3.  Click **File**, and then select **Command** \> **Document handling**.

4.  In the **Document handling of %1** form, click **New** to create an attachment for the record, and then select **File**.

5.  In the window that is displayed, select the file that contains the production instructions, and then click **Open**. The name of this file is displayed in the **Description** field in the **Document handling of %1** form.

6.  Close the form.

### Print production instructions for kanbans

1.  Click **Production control** \> **Setup** \> **Lean manufacturing** \> **Kanban rules**.

2.  On the **Kanbans** FastTab, select a kanban, and then click **Details**.

3.  In the **Kanban** form, click **Print**, and then select **Print kanban** to print the kanban card. The production instructions are displayed on the kanban card.

## See also

[Kanban rules (form)](https://technet.microsoft.com/library/hh227370\(v=ax.60\))

[Kanban (form)](https://technet.microsoft.com/library/hh242799\(v=ax.60\))

[Kanban board for process jobs (form)](https://technet.microsoft.com/library/hh781101\(v=ax.60\))

  


