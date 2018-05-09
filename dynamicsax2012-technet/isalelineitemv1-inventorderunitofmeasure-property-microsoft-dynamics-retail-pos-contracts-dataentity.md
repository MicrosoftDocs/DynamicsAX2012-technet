---
title: ISaleLineItemV1.InventOrderUnitOfMeasure Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InventOrderUnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.InventOrderUnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.inventorderunitofmeasure(v=AX.60)
ms:contentKeyID: 49831458
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.InventOrderUnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# InventOrderUnitOfMeasure Property

//The item unit comes from the InventTableModule

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property InventOrderUnitOfMeasure As String
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As String

value = instance.InventOrderUnitOfMeasure

instance.InventOrderUnitOfMeasure = value
```

``` csharp
string InventOrderUnitOfMeasure { get; set; }
```

``` c++
property String^ InventOrderUnitOfMeasure {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

