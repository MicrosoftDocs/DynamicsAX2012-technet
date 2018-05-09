---
title: ITriggersV2.OperationTriggers Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: OperationTriggers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV2.OperationTriggers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.triggers.itriggersv2.operationtriggers(v=AX.60)
ms:contentKeyID: 49833007
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV2.OperationTriggers
dev_langs:
- CSharp
- C++
- VB
---

# OperationTriggers Property

Operation triggers collection.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property OperationTriggers As IEnumerable(Of IOperationTrigger)
    Get
'Usage
Dim instance As ITriggersV2
Dim value As IEnumerable(Of IOperationTrigger)

value = instance.OperationTriggers
```

``` csharp
IEnumerable<IOperationTrigger> OperationTriggers { get; }
```

``` c++
property IEnumerable<IOperationTrigger^>^ OperationTriggers {
    IEnumerable<IOperationTrigger^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[IOperationTrigger](ioperationtrigger-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ITriggersV2 Interface](itriggersv2-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

