---
title: ISalesInvoiceLineItem Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ISalesInvoiceLineItem Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesInvoiceLineItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalesinvoicelineitem(v=AX.60)
ms:contentKeyID: 49855258
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesInvoiceLineItem
dev_langs:
- CSharp
- C++
- VB
---

# ISalesInvoiceLineItem Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

ISalesInvoiceLineItem interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("439732B1-9941-421B-A71E-FA61FE6798E8")> _
Public Interface ISalesInvoiceLineItem _
    Inherits ISaleLineItem, ITaxableItem, ILineItem, ILineItemV1,  _
    ISaleLineItemV1, ISaleLineItemV2, ISaleLineItemV3, ISaleLineItemV4, ISalesInvoiceLineItemV1
'Usage
Dim instance As ISalesInvoiceLineItem
```

``` csharp
[GuidAttribute("439732B1-9941-421B-A71E-FA61FE6798E8")]
public interface ISalesInvoiceLineItem : ISaleLineItem, 
    ITaxableItem, ILineItem, ILineItemV1, ISaleLineItemV1, ISaleLineItemV2, 
    ISaleLineItemV3, ISaleLineItemV4, ISalesInvoiceLineItemV1
```

``` c++
[GuidAttribute(L"439732B1-9941-421B-A71E-FA61FE6798E8")]
public interface class ISalesInvoiceLineItem : ISaleLineItem, 
    ITaxableItem, ILineItem, ILineItemV1, ISaleLineItemV1, ISaleLineItemV2, 
    ISaleLineItemV3, ISaleLineItemV4, ISalesInvoiceLineItemV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

