---
title: ITaxableItem.SalesOrderUnitOfMeasure Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SalesOrderUnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.SalesOrderUnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.salesorderunitofmeasure(v=AX.60)
ms:contentKeyID: 47129199
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.SalesOrderUnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrderUnitOfMeasure Property

The active item sale unit of measurement (based upon UOM set for the item by the user).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SalesOrderUnitOfMeasure As String
    Get
    Set
'Usage
Dim instance As ITaxableItem
Dim value As String

value = instance.SalesOrderUnitOfMeasure

instance.SalesOrderUnitOfMeasure = value
```

``` csharp
string SalesOrderUnitOfMeasure { get; set; }
```

``` c++
property String^ SalesOrderUnitOfMeasure {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

