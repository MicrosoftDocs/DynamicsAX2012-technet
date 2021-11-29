---
title: ITriggersV1.CustomerTriggers Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: CustomerTriggers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.CustomerTriggers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.itriggersv1.customertriggers(v=AX.60)
ms:contentKeyID: 47129062
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.CustomerTriggers
dev_langs:
- CSharp
- C++
- VB
---

# CustomerTriggers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer triggers collection.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property CustomerTriggers As IEnumerable(Of ICustomerTrigger)
    Get
'Usage
Dim instance As ITriggersV1
Dim value As IEnumerable(Of ICustomerTrigger)

value = instance.CustomerTriggers
```

``` csharp
IEnumerable<ICustomerTrigger> CustomerTriggers { get; }
```

``` c++
property IEnumerable<ICustomerTrigger^>^ CustomerTriggers {
    IEnumerable<ICustomerTrigger^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ICustomerTrigger](icustomertrigger-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)\>  
The [System.Collections.Generic.IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ITriggersV1 Interface](itriggersv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

