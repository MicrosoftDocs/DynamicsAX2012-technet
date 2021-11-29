---
title: ReasonSubCode.SubCodeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SubCodeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.SubCodeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasonsubcode.subcodeid(v=AX.60)
ms:contentKeyID: 62209278
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.SubCodeId
dev_langs:
- CSharp
- C++
- VB
---

# SubCodeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the subcode id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SUBCODEID")> _
Public Property SubCodeId As String
    Get
    Set
'Usage
Dim instance As ReasonSubCode
Dim value As String

value = instance.SubCodeId

instance.SubCodeId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SUBCODEID")]
public string SubCodeId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SUBCODEID")]
public:
property String^ SubCodeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The subcode id.  

## See Also

#### Reference

[ReasonSubCode Class](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

