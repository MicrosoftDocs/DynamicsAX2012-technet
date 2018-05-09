---
title: ReasonCodeLine.ParentLineId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ParentLineId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.ParentLineId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.parentlineid(v=AX.60)
ms:contentKeyID: 62212906
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.ParentLineId
dev_langs:
- CSharp
- C++
- VB
---

# ParentLineId Property

Gets or sets the parent line id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PARENTLINENUM")> _
<DataMemberAttribute> _
Public Property ParentLineId As String
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As String

value = instance.ParentLineId

instance.ParentLineId = value
```

``` csharp
[ColumnAttribute("PARENTLINENUM")]
[DataMemberAttribute]
public string ParentLineId { get; set; }
```

``` c++
[ColumnAttribute(L"PARENTLINENUM")]
[DataMemberAttribute]
public:
property String^ ParentLineId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The parent line id.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

