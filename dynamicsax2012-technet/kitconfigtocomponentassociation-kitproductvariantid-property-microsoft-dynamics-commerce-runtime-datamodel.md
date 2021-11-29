---
title: KitConfigToComponentAssociation.KitProductVariantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitProductVariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation.KitProductVariantId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitconfigtocomponentassociation.kitproductvariantid(v=AX.60)
ms:contentKeyID: 65322673
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation.KitProductVariantId
dev_langs:
- CSharp
- C++
- VB
---

# KitProductVariantId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the product variant identifier of the kit variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("KITPRODUCTVARIANTLISTING")> _
<DataMemberAttribute> _
Public Property KitProductVariantId As Long
    Get
    Friend Set
'Usage
Dim instance As KitConfigToComponentAssociation
Dim value As Long

value = instance.KitProductVariantId
```

``` csharp
[ColumnAttribute("KITPRODUCTVARIANTLISTING")]
[DataMemberAttribute]
public long KitProductVariantId { get; internal set; }
```

``` c++
[ColumnAttribute(L"KITPRODUCTVARIANTLISTING")]
[DataMemberAttribute]
public:
property long long KitProductVariantId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[KitConfigToComponentAssociation Class](kitconfigtocomponentassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

