---
title: ReasonCodeSpecific.ReferenceRelation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReferenceRelation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.ReferenceRelation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodespecific.referencerelation(v=AX.60)
ms:contentKeyID: 62214446
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.ReferenceRelation
dev_langs:
- CSharp
- C++
- VB
---

# ReferenceRelation Property

Gets or sets the reference relation key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<KeyAttribute> _
<ColumnAttribute("REFRELATION")> _
Public Property ReferenceRelation As String
    Get
    Set
'Usage
Dim instance As ReasonCodeSpecific
Dim value As String

value = instance.ReferenceRelation

instance.ReferenceRelation = value
```

``` csharp
[DataMemberAttribute]
[KeyAttribute]
[ColumnAttribute("REFRELATION")]
public string ReferenceRelation { get; set; }
```

``` c++
[DataMemberAttribute]
[KeyAttribute]
[ColumnAttribute(L"REFRELATION")]
public:
property String^ ReferenceRelation {
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

