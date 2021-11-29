---
title: ReasonCodeSpecific.ReferenceRelation2 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReferenceRelation2 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.ReferenceRelation2
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodespecific.referencerelation2(v=AX.60)
ms:contentKeyID: 62211888
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.ReferenceRelation2
dev_langs:
- CSharp
- C++
- VB
---

# ReferenceRelation2 Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the reference relation 2 key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REFRELATION2")> _
<DataMemberAttribute> _
<KeyAttribute> _
Public Property ReferenceRelation2 As String
    Get
    Set
'Usage
Dim instance As ReasonCodeSpecific
Dim value As String

value = instance.ReferenceRelation2

instance.ReferenceRelation2 = value
```

``` csharp
[ColumnAttribute("REFRELATION2")]
[DataMemberAttribute]
[KeyAttribute]
public string ReferenceRelation2 { get; set; }
```

``` c++
[ColumnAttribute(L"REFRELATION2")]
[DataMemberAttribute]
[KeyAttribute]
public:
property String^ ReferenceRelation2 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The key value.  

## See Also

#### Reference

[ReasonCodeSpecific Class](reasoncodespecific-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

