---
title: ISaleLineItemV1.InventOrderUnitOfMeasureName Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InventOrderUnitOfMeasureName Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.InventOrderUnitOfMeasureName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.inventorderunitofmeasurename(v=AX.60)
ms:contentKeyID: 49831370
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.InventOrderUnitOfMeasureName
dev_langs:
- CSharp
- C++
- VB
---

# InventOrderUnitOfMeasureName Property

//The item unit name comes from the InventTableModule

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property InventOrderUnitOfMeasureName As String
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As String

value = instance.InventOrderUnitOfMeasureName

instance.InventOrderUnitOfMeasureName = value
```

``` csharp
string InventOrderUnitOfMeasureName { get; set; }
```

``` c++
property String^ InventOrderUnitOfMeasureName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

