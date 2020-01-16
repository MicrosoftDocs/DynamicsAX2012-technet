---
title: IApplication Interface (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: IApplication Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.IApplication
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.iapplication(v=AX.60)
ms:contentKeyID: 47129036
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.IApplication
dev_langs:
- CSharp
- C++
- VB
---

# IApplication Interface

The POS IApplication interface exposes all the public interfaces for use by third-party developers.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("37667869-7F38-4F49-B9C5-2F42F9576861")> _
Public Interface IApplication _
    Inherits IApplicationV1, IApplicationV2
'Usage
Dim instance As IApplication
```

``` csharp
[GuidAttribute("37667869-7F38-4F49-B9C5-2F42F9576861")]
public interface IApplication : IApplicationV1, 
    IApplicationV2
```

``` c++
[GuidAttribute(L"37667869-7F38-4F49-B9C5-2F42F9576861")]
public interface class IApplication : IApplicationV1, 
    IApplicationV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)

