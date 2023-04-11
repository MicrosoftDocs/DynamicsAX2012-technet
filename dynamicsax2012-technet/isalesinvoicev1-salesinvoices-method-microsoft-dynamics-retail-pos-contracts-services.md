---
title: ISalesInvoiceV1.SalesInvoices Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SalesInvoices Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesInvoiceV1.SalesInvoices(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesinvoicev1.salesinvoices(v=AX.60)
ms:contentKeyID: 47343944
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesInvoiceV1.SalesInvoices
dev_langs:
- CSharp
- C++
- VB
---

# SalesInvoices Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Manages sales invoice line items.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SalesInvoices ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ISalesInvoiceV1
Dim posTransaction As IPosTransaction

instance.SalesInvoices(posTransaction)
```

``` csharp
void SalesInvoices(
    IPosTransaction posTransaction
)
```

``` c++
void SalesInvoices(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ISalesInvoiceV1 Interface](isalesinvoicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

