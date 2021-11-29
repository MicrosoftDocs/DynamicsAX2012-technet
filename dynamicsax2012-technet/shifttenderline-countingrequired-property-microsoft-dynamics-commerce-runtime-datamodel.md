---
title: ShiftTenderLine.CountingRequired Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CountingRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.CountingRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.countingrequired(v=AX.60)
ms:contentKeyID: 62213441
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.CountingRequired
dev_langs:
- CSharp
- C++
- VB
---

# CountingRequired Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether counting is required.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COUNTINGREQUIRED")> _
<DataMemberAttribute> _
Public Property CountingRequired As Boolean
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Boolean

value = instance.CountingRequired

instance.CountingRequired = value
```

``` csharp
[ColumnAttribute("COUNTINGREQUIRED")]
[DataMemberAttribute]
public bool CountingRequired { get; set; }
```

``` c++
[ColumnAttribute(L"COUNTINGREQUIRED")]
[DataMemberAttribute]
public:
property bool CountingRequired {
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

