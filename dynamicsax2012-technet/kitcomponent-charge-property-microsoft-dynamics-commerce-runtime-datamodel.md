---
title: KitComponent.Charge Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Charge Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent.Charge
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitcomponent.charge(v=AX.60)
ms:contentKeyID: 62209824
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent.Charge
dev_langs:
- CSharp
- C++
- VB
---

# Charge Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the charge price associated with the current product used in a kit as a component or substitute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CHARGE")> _
<DataMemberAttribute> _
Public Property Charge As Decimal
    Get
    Friend Set
'Usage
Dim instance As KitComponent
Dim value As Decimal

value = instance.Charge
```

``` csharp
[ColumnAttribute("CHARGE")]
[DataMemberAttribute]
public decimal Charge { get; internal set; }
```

``` c++
[ColumnAttribute(L"CHARGE")]
[DataMemberAttribute]
public:
property Decimal Charge {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[KitComponent Class](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

