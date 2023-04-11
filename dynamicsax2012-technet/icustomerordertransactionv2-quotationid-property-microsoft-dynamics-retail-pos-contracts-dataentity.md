---
title: ICustomerOrderTransactionV2.QuotationId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: QuotationId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.QuotationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerordertransactionv2.quotationid(v=AX.60)
ms:contentKeyID: 49856747
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransactionV2.QuotationId
dev_langs:
- CSharp
- C++
- VB
---

# QuotationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Quotaion id

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property QuotationId As String
    Get
    Set
'Usage
Dim instance As ICustomerOrderTransactionV2
Dim value As String

value = instance.QuotationId

instance.QuotationId = value
```

``` csharp
string QuotationId { get; set; }
```

``` c++
property String^ QuotationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerOrderTransactionV2 Interface](icustomerordertransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

