---
title: Set up update of purchase order lines
TOCTitle: Set up update of purchase order lines
ms:assetid: df8ccf54-80ce-4c61-b3be-d176a80c74f1
ms:mtpsurl: https://technet.microsoft.com/library/Aa551285(v=AX.60)
ms:contentKeyID: 36059699
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up update of purchase order lines 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up your parameters to make sure that purchase order lines are updated when changes occur in the purchase order header. You can specify the settings in the **Procurement and sourcing parameters** form.

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing parameters**.

2.  Go to the **Updates** link and then click **Update order lines**.

3.  For each field listed in the **Update order lines** form, select **Always** to enable the automatic update of purchase order lines when information changes in the purchase order header.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <tbody>
    <tr class="odd">
    <td><p><strong>Always</strong></p></td>
    <td><p>The order lines are updated when the order header is updated.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Never</strong></p></td>
    <td><p>The order lines are not updated when the order header is updated.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Prompt</strong></p></td>
    <td><p>A prompt enables you to decide whether to update the order lines.</p></td>
    </tr>
    </tbody>
    </table>


4.  Click **OK** to save your changes and close the **Procurement and sourcing parameters** form.

## See also

[Procurement and sourcing parameters (form)](https://technet.microsoft.com/library/hh208706\(v=ax.60\))

  


