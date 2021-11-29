---
title: ISalesInvoiceLineItemV1.CreationDate Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CreationDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesInvoiceLineItemV1.CreationDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalesinvoicelineitemv1.creationdate(v=AX.60)
ms:contentKeyID: 49832038
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesInvoiceLineItemV1.CreationDate
dev_langs:
- CSharp
- C++
- VB
---

# CreationDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

When was it created

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CreationDate As DateTime
    Get
    Set
'Usage
Dim instance As ISalesInvoiceLineItemV1
Dim value As DateTime

value = instance.CreationDate

instance.CreationDate = value
```

``` csharp
DateTime CreationDate { get; set; }
```

``` c++
property DateTime CreationDate {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[ISalesInvoiceLineItemV1 Interface](isalesinvoicelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

