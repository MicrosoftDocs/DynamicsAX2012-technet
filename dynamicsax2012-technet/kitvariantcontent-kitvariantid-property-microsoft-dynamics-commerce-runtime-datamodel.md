---
title: KitVariantContent.KitVariantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitVariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitVariantContent.KitVariantId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitvariantcontent.kitvariantid(v=AX.60)
ms:contentKeyID: 62214430
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitVariantContent.KitVariantId
dev_langs:
- CSharp
- C++
- VB
---

# KitVariantId Property

Gets the Kit variant's distinct productId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitVariantId As Long
    Get
    Friend Set
'Usage
Dim instance As KitVariantContent
Dim value As Long

value = instance.KitVariantId
```

``` csharp
[DataMemberAttribute]
public long KitVariantId { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property long long KitVariantId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[KitVariantContent Class](kitvariantcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

