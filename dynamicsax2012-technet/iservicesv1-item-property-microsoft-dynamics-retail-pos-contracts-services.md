---
title: IServicesV1.Item Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Item Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.Item
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iservicesv1.item(v=AX.60)
ms:contentKeyID: 47343971
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.Item
dev_langs:
- CSharp
- C++
- VB
---

# Item Property

Item service

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Item As IItem
    Get
'Usage
Dim instance As IServicesV1
Dim value As IItem

value = instance.Item
```

``` csharp
IItem Item { get; }
```

``` c++
property IItem^ Item {
    IItem^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IItem](iitem-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [IItem](iitem-interface-microsoft-dynamics-retail-pos-contracts-services.md) .  

## See Also

#### Reference

[IServicesV1 Interface](iservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

