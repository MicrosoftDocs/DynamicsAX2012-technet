---
title: IItem Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IItem Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iitem(v=AX.60)
ms:contentKeyID: 47344196
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IItem
dev_langs:
- CSharp
- C++
- VB
---

# IItem Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IItem interface is responsible for retrieving all item properties for a given sale line item and providing search UI for items.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("3CEFFAE8-BBA4-495C-A6C2-4FD65615CB35")> _
Public Interface IItem _
    Inherits IService, IItemV1, IItemV2
'Usage
Dim instance As IItem
```

``` csharp
[GuidAttribute("3CEFFAE8-BBA4-495C-A6C2-4FD65615CB35")]
public interface IItem : IService, IItemV1, 
    IItemV2
```

``` c++
[GuidAttribute(L"3CEFFAE8-BBA4-495C-A6C2-4FD65615CB35")]
public interface class IItem : IService, 
    IItemV1, IItemV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

