---
title: UnitOfMeasureConversion.IsBackward Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsBackward Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.IsBackward
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasureconversion.isbackward(v=AX.60)
ms:contentKeyID: 49852012
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.IsBackward
dev_langs:
- CSharp
- C++
- VB
---

# IsBackward Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the conversion is backward.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISBACKWARD")> _
<ReadOnlyAttribute("ISBACKWARD")> _
Public Property IsBackward As Boolean
    Get
    Set
'Usage
Dim instance As UnitOfMeasureConversion
Dim value As Boolean

value = instance.IsBackward

instance.IsBackward = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISBACKWARD")]
[ReadOnlyAttribute("ISBACKWARD")]
public bool IsBackward { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISBACKWARD")]
[ReadOnlyAttribute(L"ISBACKWARD")]
public:
property bool IsBackward {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether the conversion is backwards.  

## See Also

#### Reference

[UnitOfMeasureConversion Class](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

