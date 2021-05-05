---
title: AttributeGroup.Id Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Id Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeGroup.Id
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributegroup.id(v=AX.60)
ms:contentKeyID: 49831977
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeGroup.Id
dev_langs:
- CSharp
- C++
- VB
---

# Id Property

Gets or sets the group identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ATTRIBUTEGROUP")> _
Public Property Id As Long
    Get
    Set
'Usage
Dim instance As AttributeGroup
Dim value As Long

value = instance.Id

instance.Id = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ATTRIBUTEGROUP")]
public long Id { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ATTRIBUTEGROUP")]
public:
property long long Id {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The group identifier.  

## See Also

#### Reference

[AttributeGroup Class](attributegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

