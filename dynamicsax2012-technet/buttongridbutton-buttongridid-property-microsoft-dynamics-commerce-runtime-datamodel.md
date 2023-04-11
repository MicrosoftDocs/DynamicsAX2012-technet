---
title: ButtonGridButton.ButtonGridId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ButtonGridId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.ButtonGridId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.buttongridid(v=AX.60)
ms:contentKeyID: 62212099
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.ButtonGridId
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGridId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the button grid identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("BUTTONGRIDID")> _
<IgnoreDataMemberAttribute> _
Public Property ButtonGridId As String
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As String

value = instance.ButtonGridId

instance.ButtonGridId = value
```

``` csharp
[ColumnAttribute("BUTTONGRIDID")]
[IgnoreDataMemberAttribute]
public string ButtonGridId { get; set; }
```

``` c++
[ColumnAttribute(L"BUTTONGRIDID")]
[IgnoreDataMemberAttribute]
public:
property String^ ButtonGridId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The button grid identifier.  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

