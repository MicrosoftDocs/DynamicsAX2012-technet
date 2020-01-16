---
title: ISalesOrderLineItem Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ISalesOrderLineItem Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesOrderLineItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalesorderlineitem(v=AX.60)
ms:contentKeyID: 49837896
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesOrderLineItem
dev_langs:
- CSharp
- C++
- VB
---

# ISalesOrderLineItem Interface

ISalesOrderLineItem interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("F5EC4410-884C-4FD1-B196-AC03D49D3EA6")> _
Public Interface ISalesOrderLineItem _
    Inherits ISaleLineItem, ITaxableItem, ILineItem, ILineItemV1,  _
    ISaleLineItemV1, ISaleLineItemV2, ISaleLineItemV3, ISaleLineItemV4, ISalesOrderLineItemV1
'Usage
Dim instance As ISalesOrderLineItem
```

``` csharp
[GuidAttribute("F5EC4410-884C-4FD1-B196-AC03D49D3EA6")]
public interface ISalesOrderLineItem : ISaleLineItem, 
    ITaxableItem, ILineItem, ILineItemV1, ISaleLineItemV1, ISaleLineItemV2, 
    ISaleLineItemV3, ISaleLineItemV4, ISalesOrderLineItemV1
```

``` c++
[GuidAttribute(L"F5EC4410-884C-4FD1-B196-AC03D49D3EA6")]
public interface class ISalesOrderLineItem : ISaleLineItem, 
    ITaxableItem, ILineItem, ILineItemV1, ISaleLineItemV1, ISaleLineItemV2, 
    ISaleLineItemV3, ISaleLineItemV4, ISalesOrderLineItemV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

