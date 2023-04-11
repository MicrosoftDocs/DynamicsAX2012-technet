---
title: IRetailTransactionV1.SaleIsReturnSale Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SaleIsReturnSale Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.SaleIsReturnSale
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.saleisreturnsale(v=AX.60)
ms:contentKeyID: 49826244
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.SaleIsReturnSale
dev_langs:
- CSharp
- C++
- VB
---

# SaleIsReturnSale Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

True if the sale is a credit sale.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SaleIsReturnSale As Boolean
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Boolean

value = instance.SaleIsReturnSale

instance.SaleIsReturnSale = value
```

``` csharp
bool SaleIsReturnSale { get; set; }
```

``` c++
property bool SaleIsReturnSale {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

