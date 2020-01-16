---
title: IGiftCardLineItem Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IGiftCardLineItem Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.igiftcardlineitem(v=AX.60)
ms:contentKeyID: 47128370
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItem
dev_langs:
- CSharp
- C++
- VB
---

# IGiftCardLineItem Interface

The IGiftCardLineItem interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("BFDD8CE3-8191-4CAC-854F-D6028AD9C8A4")> _
Public Interface IGiftCardLineItem _
    Inherits ISaleLineItem, ITaxableItem, ILineItem, ILineItemV1,  _
    ISaleLineItemV1, ISaleLineItemV2, ISaleLineItemV3, ISaleLineItemV4, IGiftCardLineItemV1
'Usage
Dim instance As IGiftCardLineItem
```

``` csharp
[GuidAttribute("BFDD8CE3-8191-4CAC-854F-D6028AD9C8A4")]
public interface IGiftCardLineItem : ISaleLineItem, 
    ITaxableItem, ILineItem, ILineItemV1, ISaleLineItemV1, ISaleLineItemV2, 
    ISaleLineItemV3, ISaleLineItemV4, IGiftCardLineItemV1
```

``` c++
[GuidAttribute(L"BFDD8CE3-8191-4CAC-854F-D6028AD9C8A4")]
public interface class IGiftCardLineItem : ISaleLineItem, 
    ITaxableItem, ILineItem, ILineItemV1, ISaleLineItemV1, ISaleLineItemV2, 
    ISaleLineItemV3, ISaleLineItemV4, IGiftCardLineItemV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

