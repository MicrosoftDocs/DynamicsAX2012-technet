---
title: IRetailTransactionV1.InvoiceComment Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InvoiceComment Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.InvoiceComment
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.invoicecomment(v=AX.60)
ms:contentKeyID: 49851131
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.InvoiceComment
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceComment Property

Comment to be printed on the invoice

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property InvoiceComment As String
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As String

value = instance.InvoiceComment

instance.InvoiceComment = value
```

``` csharp
string InvoiceComment { get; set; }
```

``` c++
property String^ InvoiceComment {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

