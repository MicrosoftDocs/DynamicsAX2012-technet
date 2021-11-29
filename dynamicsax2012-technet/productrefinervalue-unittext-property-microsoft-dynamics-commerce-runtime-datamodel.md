---
title: ProductRefinerValue.UnitText Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnitText Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.UnitText
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefinervalue.unittext(v=AX.60)
ms:contentKeyID: 65322980
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.UnitText
dev_langs:
- CSharp
- C++
- VB
---

# UnitText Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets text representing the unit associated with property value (e.g.: Lbs, Kgs).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("UNIT")> _
<DataMemberAttribute> _
Public Property UnitText As String
    Get
    Set
'Usage
Dim instance As ProductRefinerValue
Dim value As String

value = instance.UnitText

instance.UnitText = value
```

``` csharp
[ColumnAttribute("UNIT")]
[DataMemberAttribute]
public string UnitText { get; set; }
```

``` c++
[ColumnAttribute(L"UNIT")]
[DataMemberAttribute]
public:
property String^ UnitText {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The unit text.  

## See Also

#### Reference

[ProductRefinerValue Class](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

