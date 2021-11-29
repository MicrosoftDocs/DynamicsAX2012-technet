---
title: IInfoCodes Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IInfoCodes Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IInfoCodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iinfocodes(v=AX.60)
ms:contentKeyID: 47343820
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IInfoCodes
dev_langs:
- CSharp
- C++
- VB
---

# IInfoCodes Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IInfoCodes interface is used to process all infocodes in the system.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("1241FC71-45A9-4FCE-B4D6-E990B2F83B81")> _
Public Interface IInfoCodes _
    Inherits IService, IInfoCodesV1, IInfoCodesV2
'Usage
Dim instance As IInfoCodes
```

``` csharp
[GuidAttribute("1241FC71-45A9-4FCE-B4D6-E990B2F83B81")]
public interface IInfoCodes : IService, 
    IInfoCodesV1, IInfoCodesV2
```

``` c++
[GuidAttribute(L"1241FC71-45A9-4FCE-B4D6-E990B2F83B81")]
public interface class IInfoCodes : IService, 
    IInfoCodesV1, IInfoCodesV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

