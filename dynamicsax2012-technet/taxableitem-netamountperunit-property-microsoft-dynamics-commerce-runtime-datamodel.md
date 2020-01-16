---
title: TaxableItem.NetAmountPerUnit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NetAmountPerUnit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.NetAmountPerUnit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxableitem.netamountperunit(v=AX.60)
ms:contentKeyID: 49851705
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.NetAmountPerUnit
dev_langs:
- CSharp
- C++
- VB
---

# NetAmountPerUnit Property

Gets the net amount per unit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NetAmountPerUnit As Decimal
    Get
    Set
'Usage
Dim instance As TaxableItem
Dim value As Decimal

value = instance.NetAmountPerUnit

instance.NetAmountPerUnit = value
```

``` csharp
[DataMemberAttribute]
public decimal NetAmountPerUnit { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal NetAmountPerUnit {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The net amount per unit.  

## See Also

#### Reference

[TaxableItem Class](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

