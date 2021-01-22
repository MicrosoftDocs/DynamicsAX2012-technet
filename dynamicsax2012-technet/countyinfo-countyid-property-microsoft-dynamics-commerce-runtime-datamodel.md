---
title: CountyInfo.CountyId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CountyId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CountyInfo.CountyId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.countyinfo.countyid(v=AX.60)
ms:contentKeyID: 49829621
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CountyInfo.CountyId
dev_langs:
- CSharp
- C++
- VB
---

# CountyId Property

Gets or sets the county identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COUNTYID")> _
<KeyAttribute> _
Public Property CountyId As String
    Get
    Set
'Usage
Dim instance As CountyInfo
Dim value As String

value = instance.CountyId

instance.CountyId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COUNTYID")]
[KeyAttribute]
public string CountyId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COUNTYID")]
[KeyAttribute]
public:
property String^ CountyId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CountyInfo Class](countyinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

