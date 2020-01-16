---
title: ICreateDatabase Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ICreateDatabase Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreateDatabase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icreatedatabase(v=AX.60)
ms:contentKeyID: 47344166
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreateDatabase
dev_langs:
- CSharp
- C++
- VB
---

# ICreateDatabase Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreateDatabase interface creates a new database instance according to the config file or to the default config file, if one does not exist.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("87C60857-3CA2-441E-873F-DE936689D928")> _
Public Interface ICreateDatabase _
    Inherits IService, ICreateDatabaseV1
'Usage
Dim instance As ICreateDatabase
```

``` csharp
[GuidAttribute("87C60857-3CA2-441E-873F-DE936689D928")]
public interface ICreateDatabase : IService, 
    ICreateDatabaseV1
```

``` c++
[GuidAttribute(L"87C60857-3CA2-441E-873F-DE936689D928")]
public interface class ICreateDatabase : IService, 
    ICreateDatabaseV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

