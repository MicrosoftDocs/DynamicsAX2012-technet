---
title: IGiftCard Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IGiftCard Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCard
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.igiftcard(v=AX.60)
ms:contentKeyID: 47344070
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# IGiftCard Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCard interface provides methods to handle store-issued gift cards.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("09F5E444-6C09-43F9-9D98-29BA204B702D")> _
Public Interface IGiftCard _
    Inherits IService, IGiftCardV1, IGiftCardV2
'Usage
Dim instance As IGiftCard
```

``` csharp
[GuidAttribute("09F5E444-6C09-43F9-9D98-29BA204B702D")]
public interface IGiftCard : IService, 
    IGiftCardV1, IGiftCardV2
```

``` c++
[GuidAttribute(L"09F5E444-6C09-43F9-9D98-29BA204B702D")]
public interface class IGiftCard : IService, 
    IGiftCardV1, IGiftCardV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

