---
title: KitConfigToComponentAssociation.KitLineIdentifier Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitLineIdentifier Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation.KitLineIdentifier
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitconfigtocomponentassociation.kitlineidentifier(v=AX.60)
ms:contentKeyID: 65321419
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation.KitLineIdentifier
dev_langs:
- CSharp
- C++
- VB
---

# KitLineIdentifier Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the kit line id for the current component product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("KITLINEIDENTIFIER")> _
Public Property KitLineIdentifier As Long
    Get
    Friend Set
'Usage
Dim instance As KitConfigToComponentAssociation
Dim value As Long

value = instance.KitLineIdentifier
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("KITLINEIDENTIFIER")]
public long KitLineIdentifier { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"KITLINEIDENTIFIER")]
public:
property long long KitLineIdentifier {
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

