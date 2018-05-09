---
title: ReasonCodeLine.LineId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.LineId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.lineid(v=AX.60)
ms:contentKeyID: 62210732
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.LineId
dev_langs:
- CSharp
- C++
- VB
---

# LineId Property

Gets or sets the line id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LINEID")> _
<DataMemberAttribute> _
Public Property LineId As String
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As String

value = instance.LineId

instance.LineId = value
```

``` csharp
[ColumnAttribute("LINEID")]
[DataMemberAttribute]
public string LineId { get; set; }
```

``` c++
[ColumnAttribute(L"LINEID")]
[DataMemberAttribute]
public:
property String^ LineId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The line id.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

