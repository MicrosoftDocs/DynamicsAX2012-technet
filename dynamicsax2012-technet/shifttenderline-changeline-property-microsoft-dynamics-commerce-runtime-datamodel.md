---
title: ShiftTenderLine.ChangeLine Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChangeLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.ChangeLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.changeline(v=AX.60)
ms:contentKeyID: 62214307
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.ChangeLine
dev_langs:
- CSharp
- C++
- VB
---

# ChangeLine Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the tender line is changed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CHANGELINE")> _
Public Property ChangeLine As Boolean
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Boolean

value = instance.ChangeLine

instance.ChangeLine = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CHANGELINE")]
public bool ChangeLine { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CHANGELINE")]
public:
property bool ChangeLine {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

