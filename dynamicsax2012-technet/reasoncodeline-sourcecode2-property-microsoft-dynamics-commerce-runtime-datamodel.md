---
title: ReasonCodeLine.SourceCode2 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SourceCode2 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.SourceCode2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.sourcecode2(v=AX.60)
ms:contentKeyID: 62212480
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.SourceCode2
dev_langs:
- CSharp
- C++
- VB
---

# SourceCode2 Property

Gets or sets the source code2.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SOURCECODE2")> _
Public Property SourceCode2 As String
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As String

value = instance.SourceCode2

instance.SourceCode2 = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SOURCECODE2")]
public string SourceCode2 { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SOURCECODE2")]
public:
property String^ SourceCode2 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The source code2.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

