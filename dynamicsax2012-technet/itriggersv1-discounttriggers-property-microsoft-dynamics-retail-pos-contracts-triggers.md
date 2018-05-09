---
title: ITriggersV1.DiscountTriggers Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: DiscountTriggers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.DiscountTriggers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.triggers.itriggersv1.discounttriggers(v=AX.60)
ms:contentKeyID: 47129309
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.DiscountTriggers
dev_langs:
- CSharp
- C++
- VB
---

# DiscountTriggers Property

Gets the discount triggers collection.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property DiscountTriggers As IEnumerable(Of IDiscountTrigger)
    Get
'Usage
Dim instance As ITriggersV1
Dim value As IEnumerable(Of IDiscountTrigger)

value = instance.DiscountTriggers
```

``` csharp
IEnumerable<IDiscountTrigger> DiscountTriggers { get; }
```

``` c++
property IEnumerable<IDiscountTrigger^>^ DiscountTriggers {
    IEnumerable<IDiscountTrigger^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[IDiscountTrigger](idiscounttrigger-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)\>  
The [System.Collections.Generic.IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ITriggersV1 Interface](itriggersv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

