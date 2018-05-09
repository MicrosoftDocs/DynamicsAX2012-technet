---
title: ReasonCodeSpecific.ReferenceRelation3 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReferenceRelation3 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.ReferenceRelation3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodespecific.referencerelation3(v=AX.60)
ms:contentKeyID: 62209894
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.ReferenceRelation3
dev_langs:
- CSharp
- C++
- VB
---

# ReferenceRelation3 Property

Gets or sets the reference relation 3 key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REFRELATION3")> _
<DataMemberAttribute> _
<KeyAttribute> _
Public Property ReferenceRelation3 As String
    Get
    Set
'Usage
Dim instance As ReasonCodeSpecific
Dim value As String

value = instance.ReferenceRelation3

instance.ReferenceRelation3 = value
```

``` csharp
[ColumnAttribute("REFRELATION3")]
[DataMemberAttribute]
[KeyAttribute]
public string ReferenceRelation3 { get; set; }
```

``` c++
[ColumnAttribute(L"REFRELATION3")]
[DataMemberAttribute]
[KeyAttribute]
public:
property String^ ReferenceRelation3 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The key value.  

## See Also

#### Reference

[ReasonCodeSpecific Class](reasoncodespecific-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

