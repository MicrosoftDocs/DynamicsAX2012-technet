---
title: SalesParameters.UseLineCharges Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseLineCharges Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesParameters.UseLineCharges
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesparameters.uselinecharges(v=AX.60)
ms:contentKeyID: 49849766
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesParameters.UseLineCharges
dev_langs:
- CSharp
- C++
- VB
---

# UseLineCharges Property

Gets a value indicating whether line auto-charges should be calculated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MARKUPLINE")> _
<DataMemberAttribute> _
Public Property UseLineCharges As Boolean
    Get
    Friend Set
'Usage
Dim instance As SalesParameters
Dim value As Boolean

value = instance.UseLineCharges
```

``` csharp
[ColumnAttribute("MARKUPLINE")]
[DataMemberAttribute]
public bool UseLineCharges { get; internal set; }
```

``` c++
[ColumnAttribute(L"MARKUPLINE")]
[DataMemberAttribute]
public:
property bool UseLineCharges {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesParameters Class](salesparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

