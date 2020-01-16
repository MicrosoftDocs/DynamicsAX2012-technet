---
title: ButtonGridZone.ButtonGridId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ButtonGridId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridZone.ButtonGridId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridzone.buttongridid(v=AX.60)
ms:contentKeyID: 62203262
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridZone.ButtonGridId
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGridId Property

Gets or sets the value of button grid identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("BUTTONGRIDID")> _
Public Property ButtonGridId As String
    Get
    Set
'Usage
Dim instance As ButtonGridZone
Dim value As String

value = instance.ButtonGridId

instance.ButtonGridId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("BUTTONGRIDID")]
public string ButtonGridId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"BUTTONGRIDID")]
public:
property String^ ButtonGridId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ButtonGridZone Class](buttongridzone-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

