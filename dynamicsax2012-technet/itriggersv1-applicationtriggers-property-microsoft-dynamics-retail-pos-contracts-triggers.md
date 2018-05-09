---
title: ITriggersV1.ApplicationTriggers Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: ApplicationTriggers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.ApplicationTriggers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.triggers.itriggersv1.applicationtriggers(v=AX.60)
ms:contentKeyID: 47129352
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.ApplicationTriggers
dev_langs:
- CSharp
- C++
- VB
---

# ApplicationTriggers Property

Gets the application triggers collection.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property ApplicationTriggers As IEnumerable(Of IApplicationTrigger)
    Get
'Usage
Dim instance As ITriggersV1
Dim value As IEnumerable(Of IApplicationTrigger)

value = instance.ApplicationTriggers
```

``` csharp
IEnumerable<IApplicationTrigger> ApplicationTriggers { get; }
```

``` c++
property IEnumerable<IApplicationTrigger^>^ ApplicationTriggers {
    IEnumerable<IApplicationTrigger^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[IApplicationTrigger](iapplicationtrigger-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)\>  
The [System.Collections.Generic.IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ITriggersV1 Interface](itriggersv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

