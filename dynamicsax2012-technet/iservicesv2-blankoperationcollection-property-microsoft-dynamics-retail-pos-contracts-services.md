---
title: IServicesV2.BlankOperationCollection Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: BlankOperationCollection Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV2.BlankOperationCollection
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iservicesv2.blankoperationcollection(v=AX.60)
ms:contentKeyID: 49831997
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV2.BlankOperationCollection
dev_langs:
- CSharp
- C++
- VB
---

# BlankOperationCollection Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Collection of blank operations service

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property BlankOperationCollection As IEnumerable(Of IBlankOperations)
    Get
'Usage
Dim instance As IServicesV2
Dim value As IEnumerable(Of IBlankOperations)

value = instance.BlankOperationCollection
```

``` csharp
IEnumerable<IBlankOperations> BlankOperationCollection { get; }
```

``` c++
property IEnumerable<IBlankOperations^>^ BlankOperationCollection {
    IEnumerable<IBlankOperations^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[IBlankOperations](iblankoperations-interface-microsoft-dynamics-retail-pos-contracts-services.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[IServicesV2 Interface](iservicesv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

