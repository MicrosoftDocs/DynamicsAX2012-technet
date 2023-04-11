---
title: IInfocodeTrigger Methods (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: IInfocodeTrigger Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IInfocodeTrigger
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iinfocodetrigger_methods(v=AX.60)
ms:contentKeyID: 47128061
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IInfocodeTrigger Methods


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [IInfocodeTrigger](iinfocodetrigger-interface-microsoft-dynamics-retail-pos-contracts-triggers.md) type exposes the following members.

## Methods

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iinfocodetriggerv1-postprocessinfocode-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PostProcessInfocode</a></td>
<td>Called after the infocode has been processed. Any checking and/or additional input validation can be done here. (Inherited from <a href="iinfocodetriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md">IInfocodeTriggerV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iinfocodetriggerv1-preprocessinfocode-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PreProcessInfocode</a></td>
<td>Called before the infocode is processed. If the infocode should not be processed after this trigger has finished running, PreTriggerResults must to be filled out accordingly. (Inherited from <a href="iinfocodetriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md">IInfocodeTriggerV1</a>.)</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IInfocodeTrigger Interface](iinfocodetrigger-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

