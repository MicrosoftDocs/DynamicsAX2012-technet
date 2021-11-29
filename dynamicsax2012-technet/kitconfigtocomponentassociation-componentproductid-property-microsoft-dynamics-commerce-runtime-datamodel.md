---
title: KitConfigToComponentAssociation.ComponentProductId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ComponentProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation.ComponentProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitconfigtocomponentassociation.componentproductid(v=AX.60)
ms:contentKeyID: 65322173
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation.ComponentProductId
dev_langs:
- CSharp
- C++
- VB
---

# ComponentProductId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the product identifier of the product used as a component in the kit variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COMPONENTPRODUCTLISTING")> _
<DataMemberAttribute> _
Public Property ComponentProductId As Long
    Get
    Friend Set
'Usage
Dim instance As KitConfigToComponentAssociation
Dim value As Long

value = instance.ComponentProductId
```

``` csharp
[ColumnAttribute("COMPONENTPRODUCTLISTING")]
[DataMemberAttribute]
public long ComponentProductId { get; internal set; }
```

``` c++
[ColumnAttribute(L"COMPONENTPRODUCTLISTING")]
[DataMemberAttribute]
public:
property long long ComponentProductId {
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

