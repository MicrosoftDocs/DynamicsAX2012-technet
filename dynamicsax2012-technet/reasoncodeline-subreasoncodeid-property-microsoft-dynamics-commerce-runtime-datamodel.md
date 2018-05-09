---
title: ReasonCodeLine.SubReasonCodeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SubReasonCodeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.SubReasonCodeId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.subreasoncodeid(v=AX.60)
ms:contentKeyID: 62215199
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.SubReasonCodeId
dev_langs:
- CSharp
- C++
- VB
---

# SubReasonCodeId Property

Gets or sets the sub reason code id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SUBINFOCODEID")> _
<DataMemberAttribute> _
Public Property SubReasonCodeId As String
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As String

value = instance.SubReasonCodeId

instance.SubReasonCodeId = value
```

``` csharp
[ColumnAttribute("SUBINFOCODEID")]
[DataMemberAttribute]
public string SubReasonCodeId { get; set; }
```

``` c++
[ColumnAttribute(L"SUBINFOCODEID")]
[DataMemberAttribute]
public:
property String^ SubReasonCodeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The sub reason code id.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

