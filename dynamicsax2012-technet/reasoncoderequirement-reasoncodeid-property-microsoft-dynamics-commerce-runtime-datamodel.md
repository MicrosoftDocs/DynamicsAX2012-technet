---
title: ReasonCodeRequirement.ReasonCodeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReasonCodeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequirement.ReasonCodeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncoderequirement.reasoncodeid(v=AX.60)
ms:contentKeyID: 62212524
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequirement.ReasonCodeId
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the reason code identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REASONCODEID")> _
<DataMemberAttribute> _
Public Property ReasonCodeId As String
    Get
    Set
'Usage
Dim instance As ReasonCodeRequirement
Dim value As String

value = instance.ReasonCodeId

instance.ReasonCodeId = value
```

``` csharp
[ColumnAttribute("REASONCODEID")]
[DataMemberAttribute]
public string ReasonCodeId { get; set; }
```

``` c++
[ColumnAttribute(L"REASONCODEID")]
[DataMemberAttribute]
public:
property String^ ReasonCodeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The reason code identifier.  

## See Also

#### Reference

[ReasonCodeRequirement Class](reasoncoderequirement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

