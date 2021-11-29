---
title: ISalesInvoiceV2.PaySalesInvoice Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PaySalesInvoice Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesInvoiceV2.PaySalesInvoice(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesInvoiceLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesinvoicev2.paysalesinvoice(v=AX.60)
ms:contentKeyID: 62203524
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesInvoiceV2.PaySalesInvoice
dev_langs:
- CSharp
- C++
- VB
---

# PaySalesInvoice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Record payment of a single Sales Invoice Line in Headquarters

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PaySalesInvoice ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    invoiceLine As ISalesInvoiceLineItem, _
    transaction As IPosTransaction _
)
'Usage
Dim instance As ISalesInvoiceV2
Dim retValue As Boolean
Dim comment As String
Dim invoiceLine As ISalesInvoiceLineItem
Dim transaction As IPosTransaction

instance.PaySalesInvoice(retValue, comment, _
    invoiceLine, transaction)
```

``` csharp
void PaySalesInvoice(
    ref bool retValue,
    ref string comment,
    ISalesInvoiceLineItem invoiceLine,
    IPosTransaction transaction
)
```

``` c++
void PaySalesInvoice(
    bool% retValue, 
    String^% comment, 
    ISalesInvoiceLineItem^ invoiceLine, 
    IPosTransaction^ transaction
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - invoiceLine  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesInvoiceLineItem](isalesinvoicelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ISalesInvoiceV2 Interface](isalesinvoicev2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

