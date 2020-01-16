---
title: ReasonCodeRequirement.SourceId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SourceId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequirement.SourceId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncoderequirement.sourceid(v=AX.60)
ms:contentKeyID: 62207797
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequirement.SourceId
dev_langs:
- CSharp
- C++
- VB
---

# SourceId Property

Gets or sets the source identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SOURCEID")> _
Public Property SourceId As String
    Get
    Set
'Usage
Dim instance As ReasonCodeRequirement
Dim value As String

value = instance.SourceId

instance.SourceId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SOURCEID")]
public string SourceId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SOURCEID")]
public:
property String^ SourceId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The source identifier.  

## See Also

#### Reference

[ReasonCodeRequirement Class](reasoncoderequirement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

