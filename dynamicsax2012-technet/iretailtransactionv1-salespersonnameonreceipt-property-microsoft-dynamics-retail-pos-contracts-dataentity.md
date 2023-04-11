---
title: IRetailTransactionV1.SalesPersonNameOnReceipt Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SalesPersonNameOnReceipt Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.SalesPersonNameOnReceipt
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.salespersonnameonreceipt(v=AX.60)
ms:contentKeyID: 49851749
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.SalesPersonNameOnReceipt
dev_langs:
- CSharp
- C++
- VB
---

# SalesPersonNameOnReceipt Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The name of a salesperson if other than other than the operator.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SalesPersonNameOnReceipt As String
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As String

value = instance.SalesPersonNameOnReceipt

instance.SalesPersonNameOnReceipt = value
```

``` csharp
string SalesPersonNameOnReceipt { get; set; }
```

``` c++
property String^ SalesPersonNameOnReceipt {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

