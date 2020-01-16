---
title: ICorporateCard Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ICorporateCard Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICorporateCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icorporatecard(v=AX.60)
ms:contentKeyID: 47344071
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICorporateCard
dev_langs:
- CSharp
- C++
- VB
---

# ICorporateCard Interface

A payment with a corporate card is assigned to the operation number 208.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("35DAEC8D-6D07-4A54-9D3D-3F7D43121A7E")> _
Public Interface ICorporateCard _
    Inherits IService, ICorporateCardV1
'Usage
Dim instance As ICorporateCard
```

``` csharp
[GuidAttribute("35DAEC8D-6D07-4A54-9D3D-3F7D43121A7E")]
public interface ICorporateCard : IService, 
    ICorporateCardV1
```

``` c++
[GuidAttribute(L"35DAEC8D-6D07-4A54-9D3D-3F7D43121A7E")]
public interface class ICorporateCard : IService, 
    ICorporateCardV1
```

## Remarks

When a card is recognized as corporate card, a new instance of the PayCorporateCard class is created.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

