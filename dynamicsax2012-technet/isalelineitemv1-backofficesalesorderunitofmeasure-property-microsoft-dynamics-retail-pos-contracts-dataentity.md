---
title: ISaleLineItemV1.BackofficeSalesOrderUnitOfMeasure Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BackofficeSalesOrderUnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.BackofficeSalesOrderUnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.backofficesalesorderunitofmeasure(v=AX.60)
ms:contentKeyID: 49824314
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.BackofficeSalesOrderUnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# BackofficeSalesOrderUnitOfMeasure Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

//The item unit comes from the InventTableModule

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property BackofficeSalesOrderUnitOfMeasure As String
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As String

value = instance.BackofficeSalesOrderUnitOfMeasure

instance.BackofficeSalesOrderUnitOfMeasure = value
```

``` csharp
string BackofficeSalesOrderUnitOfMeasure { get; set; }
```

``` c++
property String^ BackofficeSalesOrderUnitOfMeasure {
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

