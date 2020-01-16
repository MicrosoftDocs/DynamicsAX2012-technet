---
title: KitLineProductProperty.Charge Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Charge Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductProperty.Charge
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitlineproductproperty.charge(v=AX.60)
ms:contentKeyID: 62202989
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductProperty.Charge
dev_langs:
- CSharp
- C++
- VB
---

# Charge Property

Gets or sets the unit for the product used in a kit as a component or substitute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Charge As Decimal
    Get
    Set
'Usage
Dim instance As KitLineProductProperty
Dim value As Decimal

value = instance.Charge

instance.Charge = value
```

``` csharp
[DataMemberAttribute]
public decimal Charge { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal Charge {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[KitLineProductProperty Class](kitlineproductproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

