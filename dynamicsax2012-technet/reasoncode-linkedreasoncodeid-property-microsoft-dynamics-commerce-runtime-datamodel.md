---
title: ReasonCode.LinkedReasonCodeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LinkedReasonCodeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.LinkedReasonCodeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.linkedreasoncodeid(v=AX.60)
ms:contentKeyID: 62205561
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.LinkedReasonCodeId
dev_langs:
- CSharp
- C++
- VB
---

# LinkedReasonCodeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the linked reason code id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LINKEDINFOCODEID")> _
<DataMemberAttribute> _
Public Property LinkedReasonCodeId As String
    Get
    Friend Set
'Usage
Dim instance As ReasonCode
Dim value As String

value = instance.LinkedReasonCodeId
```

``` csharp
[ColumnAttribute("LINKEDINFOCODEID")]
[DataMemberAttribute]
public string LinkedReasonCodeId { get; internal set; }
```

``` c++
[ColumnAttribute(L"LINKEDINFOCODEID")]
[DataMemberAttribute]
public:
property String^ LinkedReasonCodeId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The linked reason code id.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

