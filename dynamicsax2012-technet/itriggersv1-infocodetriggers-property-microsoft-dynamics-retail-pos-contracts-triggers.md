---
title: ITriggersV1.InfocodeTriggers Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: InfocodeTriggers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.InfocodeTriggers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.itriggersv1.infocodetriggers(v=AX.60)
ms:contentKeyID: 47128420
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.InfocodeTriggers
dev_langs:
- CSharp
- C++
- VB
---

# InfocodeTriggers Property

Gets the infocode triggers collection.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property InfocodeTriggers As IEnumerable(Of IInfocodeTrigger)
    Get
'Usage
Dim instance As ITriggersV1
Dim value As IEnumerable(Of IInfocodeTrigger)

value = instance.InfocodeTriggers
```

``` csharp
IEnumerable<IInfocodeTrigger> InfocodeTriggers { get; }
```

``` c++
property IEnumerable<IInfocodeTrigger^>^ InfocodeTriggers {
    IEnumerable<IInfocodeTrigger^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[IInfocodeTrigger](iinfocodetrigger-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)\>  
The [System.Collections.Generic.IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ITriggersV1 Interface](itriggersv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

