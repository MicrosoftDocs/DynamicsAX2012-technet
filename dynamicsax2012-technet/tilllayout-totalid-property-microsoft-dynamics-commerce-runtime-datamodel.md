---
title: TillLayout.TotalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.TotalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.totalid(v=AX.60)
ms:contentKeyID: 62215095
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.TotalId
dev_langs:
- CSharp
- C++
- VB
---

# TotalId Property

Gets or sets the value of total identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TOTALID")> _
Public Property TotalId As String
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As String

value = instance.TotalId

instance.TotalId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TOTALID")]
public string TotalId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TOTALID")]
public:
property String^ TotalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The total identifier.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

