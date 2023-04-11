---
title: ITriggersV1.SuspendTriggers Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: SuspendTriggers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.SuspendTriggers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.itriggersv1.suspendtriggers(v=AX.60)
ms:contentKeyID: 47128582
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.SuspendTriggers
dev_langs:
- CSharp
- C++
- VB
---

# SuspendTriggers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the suspend triggers collection.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property SuspendTriggers As IEnumerable(Of ISuspendTrigger)
    Get
'Usage
Dim instance As ITriggersV1
Dim value As IEnumerable(Of ISuspendTrigger)

value = instance.SuspendTriggers
```

``` csharp
IEnumerable<ISuspendTrigger> SuspendTriggers { get; }
```

``` c++
property IEnumerable<ISuspendTrigger^>^ SuspendTriggers {
    IEnumerable<ISuspendTrigger^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ISuspendTrigger](isuspendtrigger-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)\>  
The [System.Collections.Generic.IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ITriggersV1 Interface](itriggersv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

