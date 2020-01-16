---
title: ReasonCodeLine.Information Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Information Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.Information
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.information(v=AX.60)
ms:contentKeyID: 62208111
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.Information
dev_langs:
- CSharp
- C++
- VB
---

# Information Property

Gets or sets the information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INFORMATION")> _
Public Property Information As String
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As String

value = instance.Information

instance.Information = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INFORMATION")]
public string Information { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INFORMATION")]
public:
property String^ Information {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The information.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

