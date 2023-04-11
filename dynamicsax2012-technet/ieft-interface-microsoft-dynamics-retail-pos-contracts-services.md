---
title: IEFT Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IEFT Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFT
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ieft(v=AX.60)
ms:contentKeyID: 47344147
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFT
dev_langs:
- CSharp
- C++
- VB
---

# IEFT Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFT interface provides methods that can be used by external service providers to process card payments.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("618A4984-F83E-48A6-99E8-AD36C7F0411A")> _
Public Interface IEFT _
    Inherits IService, IEFTV1, IEFTV2
'Usage
Dim instance As IEFT
```

``` csharp
[GuidAttribute("618A4984-F83E-48A6-99E8-AD36C7F0411A")]
public interface IEFT : IService, IEFTV1, 
    IEFTV2
```

``` c++
[GuidAttribute(L"618A4984-F83E-48A6-99E8-AD36C7F0411A")]
public interface class IEFT : IService, 
    IEFTV1, IEFTV2
```

## Remarks

This interface provides the ability to authorize, refund, and void debit and credit card payments.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

