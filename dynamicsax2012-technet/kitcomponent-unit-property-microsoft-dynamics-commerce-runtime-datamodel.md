---
title: KitComponent.Unit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Unit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent.Unit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitcomponent.unit(v=AX.60)
ms:contentKeyID: 62209750
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent.Unit
dev_langs:
- CSharp
- C++
- VB
---

# Unit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the unit for the product used in a kit as a component or substitute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("UNIT")> _
Public Property Unit As String
    Get
    Friend Set
'Usage
Dim instance As KitComponent
Dim value As String

value = instance.Unit
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("UNIT")]
public string Unit { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"UNIT")]
public:
property String^ Unit {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[KitComponent Class](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

