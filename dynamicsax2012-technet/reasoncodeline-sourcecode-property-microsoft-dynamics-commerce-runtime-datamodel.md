---
title: ReasonCodeLine.SourceCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SourceCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.SourceCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.sourcecode(v=AX.60)
ms:contentKeyID: 62204778
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.SourceCode
dev_langs:
- CSharp
- C++
- VB
---

# SourceCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the source code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SOURCECODE")> _
Public Property SourceCode As String
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As String

value = instance.SourceCode

instance.SourceCode = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SOURCECODE")]
public string SourceCode { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SOURCECODE")]
public:
property String^ SourceCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The source code.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

