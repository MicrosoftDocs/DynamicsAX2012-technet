---
title: ISaleLineItem Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ISaleLineItem Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitem(v=AX.60)
ms:contentKeyID: 47129305
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem
dev_langs:
- CSharp
- C++
- VB
---

# ISaleLineItem Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The ISaleLineItem interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("9F5C2F7C-5870-4652-80FB-31D03C3CF986")> _
Public Interface ISaleLineItem _
    Inherits ITaxableItem, ILineItem, ILineItemV1, ISaleLineItemV1,  _
    ISaleLineItemV2, ISaleLineItemV3, ISaleLineItemV4
'Usage
Dim instance As ISaleLineItem
```

``` csharp
[GuidAttribute("9F5C2F7C-5870-4652-80FB-31D03C3CF986")]
public interface ISaleLineItem : ITaxableItem, 
    ILineItem, ILineItemV1, ISaleLineItemV1, ISaleLineItemV2, ISaleLineItemV3, 
    ISaleLineItemV4
```

``` c++
[GuidAttribute(L"9F5C2F7C-5870-4652-80FB-31D03C3CF986")]
public interface class ISaleLineItem : ITaxableItem, 
    ILineItem, ILineItemV1, ISaleLineItemV1, ISaleLineItemV2, ISaleLineItemV3, 
    ISaleLineItemV4
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

