---
title: KitComponent.IsComponent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsComponent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent.IsComponent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitcomponent.iscomponent(v=AX.60)
ms:contentKeyID: 62204762
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent.IsComponent
dev_langs:
- CSharp
- C++
- VB
---

# IsComponent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the current kit line product is used as the default component of the kit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISDEFAULTCOMPONENT")> _
Public Property IsComponent As Boolean
    Get
    Friend Set
'Usage
Dim instance As KitComponent
Dim value As Boolean

value = instance.IsComponent
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISDEFAULTCOMPONENT")]
public bool IsComponent { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISDEFAULTCOMPONENT")]
public:
property bool IsComponent {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[KitComponent Class](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

