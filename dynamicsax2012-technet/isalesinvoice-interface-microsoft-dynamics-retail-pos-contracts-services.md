---
title: ISalesInvoice Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ISalesInvoice Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesInvoice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesinvoice(v=AX.60)
ms:contentKeyID: 47344288
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesInvoice
dev_langs:
- CSharp
- C++
- VB
---

# ISalesInvoice Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesInvoice interface handles sales-invoice line items in the retail POS transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("739DE0FB-87E7-4FE2-9EE0-A74B066B7AD1")> _
Public Interface ISalesInvoice _
    Inherits IService, ISalesInvoiceV1, ISalesInvoiceV2
'Usage
Dim instance As ISalesInvoice
```

``` csharp
[GuidAttribute("739DE0FB-87E7-4FE2-9EE0-A74B066B7AD1")]
public interface ISalesInvoice : IService, 
    ISalesInvoiceV1, ISalesInvoiceV2
```

``` c++
[GuidAttribute(L"739DE0FB-87E7-4FE2-9EE0-A74B066B7AD1")]
public interface class ISalesInvoice : IService, 
    ISalesInvoiceV1, ISalesInvoiceV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

