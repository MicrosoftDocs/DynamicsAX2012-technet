---
title: ReasonCodeLine.SourceCode3 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SourceCode3 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.SourceCode3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.sourcecode3(v=AX.60)
ms:contentKeyID: 62205748
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.SourceCode3
dev_langs:
- CSharp
- C++
- VB
---

# SourceCode3 Property

Gets or sets the source code3.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SOURCECODE3")> _
Public Property SourceCode3 As String
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As String

value = instance.SourceCode3

instance.SourceCode3 = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SOURCECODE3")]
public string SourceCode3 { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SOURCECODE3")]
public:
property String^ SourceCode3 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The source code3.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

