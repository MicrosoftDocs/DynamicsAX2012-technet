---
title: ISaleLineItemV1.SalesOrderUnitOfMeasureName Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SalesOrderUnitOfMeasureName Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.SalesOrderUnitOfMeasureName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.salesorderunitofmeasurename(v=AX.60)
ms:contentKeyID: 49825783
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.SalesOrderUnitOfMeasureName
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrderUnitOfMeasureName Property

//The active item sale unit of measurement name (based upon UOM set for the item by the user)

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SalesOrderUnitOfMeasureName As String
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As String

value = instance.SalesOrderUnitOfMeasureName

instance.SalesOrderUnitOfMeasureName = value
```

``` csharp
string SalesOrderUnitOfMeasureName { get; set; }
```

``` c++
property String^ SalesOrderUnitOfMeasureName {
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

