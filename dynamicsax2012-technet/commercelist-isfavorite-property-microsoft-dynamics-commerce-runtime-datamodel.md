---
title: CommerceList.IsFavorite Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsFavorite Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList.IsFavorite
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercelist.isfavorite(v=AX.60)
ms:contentKeyID: 62208147
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList.IsFavorite
dev_langs:
- CSharp
- C++
- VB
---

# IsFavorite Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the commerce list is favorite.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsFavorite As Boolean
    Get
    Set
'Usage
Dim instance As CommerceList
Dim value As Boolean

value = instance.IsFavorite

instance.IsFavorite = value
```

``` csharp
[DataMemberAttribute]
public bool IsFavorite { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsFavorite {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CommerceList Class](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

