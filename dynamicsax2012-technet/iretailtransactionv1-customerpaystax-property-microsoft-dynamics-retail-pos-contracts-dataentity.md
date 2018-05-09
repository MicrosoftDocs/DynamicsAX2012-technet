---
title: IRetailTransactionV1.CustomerPaysTax Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CustomerPaysTax Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.CustomerPaysTax
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.customerpaystax(v=AX.60)
ms:contentKeyID: 49820819
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.CustomerPaysTax
dev_langs:
- CSharp
- C++
- VB
---

# CustomerPaysTax Property

Is set to true if the customer pays tax, else false.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CustomerPaysTax As Boolean
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Boolean

value = instance.CustomerPaysTax

instance.CustomerPaysTax = value
```

``` csharp
bool CustomerPaysTax { get; set; }
```

``` c++
property bool CustomerPaysTax {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

