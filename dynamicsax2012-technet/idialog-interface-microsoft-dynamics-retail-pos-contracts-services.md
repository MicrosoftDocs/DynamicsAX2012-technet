---
title: IDialog Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IDialog Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialog
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idialog(v=AX.60)
ms:contentKeyID: 47344439
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialog
dev_langs:
- CSharp
- C++
- VB
---

# IDialog Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialog interface provides common implementation of various UI dialog boxes such as search, lookup, and various messages.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("5F03A7B7-65EB-4761-8279-6E6E70EA6E3D")> _
Public Interface IDialog _
    Inherits IService, IDialogV1, IDialogV2
'Usage
Dim instance As IDialog
```

``` csharp
[GuidAttribute("5F03A7B7-65EB-4761-8279-6E6E70EA6E3D")]
public interface IDialog : IService, 
    IDialogV1, IDialogV2
```

``` c++
[GuidAttribute(L"5F03A7B7-65EB-4761-8279-6E6E70EA6E3D")]
public interface class IDialog : IService, 
    IDialogV1, IDialogV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

