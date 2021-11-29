---
title: SalesParameters.UseHeaderCharges Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseHeaderCharges Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesParameters.UseHeaderCharges
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesparameters.useheadercharges(v=AX.60)
ms:contentKeyID: 49853335
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesParameters.UseHeaderCharges
dev_langs:
- CSharp
- C++
- VB
---

# UseHeaderCharges Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether header auto-charges should be calculated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MARKUPHEADING")> _
<DataMemberAttribute> _
Public Property UseHeaderCharges As Boolean
    Get
    Friend Set
'Usage
Dim instance As SalesParameters
Dim value As Boolean

value = instance.UseHeaderCharges
```

``` csharp
[ColumnAttribute("MARKUPHEADING")]
[DataMemberAttribute]
public bool UseHeaderCharges { get; internal set; }
```

``` c++
[ColumnAttribute(L"MARKUPHEADING")]
[DataMemberAttribute]
public:
property bool UseHeaderCharges {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesParameters Class](salesparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

