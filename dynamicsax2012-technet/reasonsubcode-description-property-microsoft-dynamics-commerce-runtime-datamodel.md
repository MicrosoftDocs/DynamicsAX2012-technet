---
title: ReasonSubCode.Description Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Description Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.Description
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasonsubcode.description(v=AX.60)
ms:contentKeyID: 62210510
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.Description
dev_langs:
- CSharp
- C++
- VB
---

# Description Property

Gets or sets the description.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DESCRIPTION")> _
<DataMemberAttribute> _
Public Property Description As String
    Get
    Set
'Usage
Dim instance As ReasonSubCode
Dim value As String

value = instance.Description

instance.Description = value
```

``` csharp
[ColumnAttribute("DESCRIPTION")]
[DataMemberAttribute]
public string Description { get; set; }
```

``` c++
[ColumnAttribute(L"DESCRIPTION")]
[DataMemberAttribute]
public:
property String^ Description {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The description.  

## See Also

#### Reference

[ReasonSubCode Class](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

