---
title: ProductProperty.GroupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GroupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.GroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.groupid(v=AX.60)
ms:contentKeyID: 62208021
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.GroupId
dev_langs:
- CSharp
- C++
- VB
---

# GroupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the underlying attribute's group identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GroupId As Long
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As Long

value = instance.GroupId

instance.GroupId = value
```

``` csharp
[DataMemberAttribute]
public long GroupId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long GroupId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

