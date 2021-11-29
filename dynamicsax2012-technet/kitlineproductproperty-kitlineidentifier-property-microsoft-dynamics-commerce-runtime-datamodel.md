---
title: KitLineProductProperty.KitLineIdentifier Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitLineIdentifier Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductProperty.KitLineIdentifier
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitlineproductproperty.kitlineidentifier(v=AX.60)
ms:contentKeyID: 62208425
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductProperty.KitLineIdentifier
dev_langs:
- CSharp
- C++
- VB
---

# KitLineIdentifier Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the kit line id for the current product which is used as a component or substitute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitLineIdentifier As Long
    Get
    Set
'Usage
Dim instance As KitLineProductProperty
Dim value As Long

value = instance.KitLineIdentifier

instance.KitLineIdentifier = value
```

``` csharp
[DataMemberAttribute]
public long KitLineIdentifier { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long KitLineIdentifier {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[KitLineProductProperty Class](kitlineproductproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

