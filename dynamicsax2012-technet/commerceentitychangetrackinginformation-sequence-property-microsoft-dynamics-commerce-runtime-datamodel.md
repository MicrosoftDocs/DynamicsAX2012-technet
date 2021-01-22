---
title: CommerceEntityChangeTrackingInformation.Sequence Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Sequence Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityChangeTrackingInformation.Sequence
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentitychangetrackinginformation.sequence(v=AX.60)
ms:contentKeyID: 62206556
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityChangeTrackingInformation.Sequence
dev_langs:
- CSharp
- C++
- VB
---

# Sequence Property

Gets or sets the timestamp of the entity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SEQUENCE")> _
<DataMemberAttribute> _
Public Property Sequence As Long
    Get
    Set
'Usage
Dim instance As CommerceEntityChangeTrackingInformation
Dim value As Long

value = instance.Sequence

instance.Sequence = value
```

``` csharp
[ColumnAttribute("SEQUENCE")]
[DataMemberAttribute]
public long Sequence { get; set; }
```

``` c++
[ColumnAttribute(L"SEQUENCE")]
[DataMemberAttribute]
public:
property long long Sequence {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[CommerceEntityChangeTrackingInformation Class](commerceentitychangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

