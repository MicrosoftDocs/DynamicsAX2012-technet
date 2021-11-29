---
title: IRetailTransactionV1.SalesPersonName Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SalesPersonName Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.SalesPersonName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.salespersonname(v=AX.60)
ms:contentKeyID: 49844929
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.SalesPersonName
dev_langs:
- CSharp
- C++
- VB
---

# SalesPersonName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The name of a salesperson if other than other than the operator.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SalesPersonName As String
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As String

value = instance.SalesPersonName

instance.SalesPersonName = value
```

``` csharp
string SalesPersonName { get; set; }
```

``` c++
property String^ SalesPersonName {
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

