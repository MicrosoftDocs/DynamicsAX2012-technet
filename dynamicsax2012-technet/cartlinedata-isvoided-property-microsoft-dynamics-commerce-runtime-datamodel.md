---
title: CartLineData.IsVoided Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsVoided Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsVoided
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.isvoided(v=AX.60)
ms:contentKeyID: 62205726
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.IsVoided
dev_langs:
- CSharp
- C++
- VB
---

# IsVoided Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether this line is voided.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IsVoided As Boolean
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Boolean

value = instance.IsVoided

instance.IsVoided = value
```

``` csharp
[IgnoreDataMemberAttribute]
public bool IsVoided { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property bool IsVoided {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

