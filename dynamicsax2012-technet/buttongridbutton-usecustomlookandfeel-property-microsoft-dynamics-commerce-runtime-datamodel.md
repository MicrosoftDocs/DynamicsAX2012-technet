---
title: ButtonGridButton.UseCustomLookAndFeel Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseCustomLookAndFeel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.UseCustomLookAndFeel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.usecustomlookandfeel(v=AX.60)
ms:contentKeyID: 62210666
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.UseCustomLookAndFeel
dev_langs:
- CSharp
- C++
- VB
---

# UseCustomLookAndFeel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether custom look and feel is used.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("USECUSTOMLOOKANDFEEL")> _
Public Property UseCustomLookAndFeel As Boolean
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As Boolean

value = instance.UseCustomLookAndFeel

instance.UseCustomLookAndFeel = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("USECUSTOMLOOKANDFEEL")]
public bool UseCustomLookAndFeel { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"USECUSTOMLOOKANDFEEL")]
public:
property bool UseCustomLookAndFeel {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True to use custom look and feel.  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

