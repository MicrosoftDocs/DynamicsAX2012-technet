---
title: TypeCache.PublicNonStaticProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PublicNonStaticProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache.PublicNonStaticProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.typecache.publicnonstaticproperties(v=AX.60)
ms:contentKeyID: 65316967
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache.PublicNonStaticProperties
dev_langs:
- CSharp
- C++
- VB
---

# PublicNonStaticProperties Property

Gets the enumerable of public non-static properties of the type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property PublicNonStaticProperties As IReadOnlyCollection(Of PropertyInfo)
    Get
'Usage
Dim instance As TypeCache
Dim value As IReadOnlyCollection(Of PropertyInfo)

value = instance.PublicNonStaticProperties
```

``` csharp
public IReadOnlyCollection<PropertyInfo> PublicNonStaticProperties { get; }
```

``` c++
public:
property IReadOnlyCollection<PropertyInfo^>^ PublicNonStaticProperties {
    IReadOnlyCollection<PropertyInfo^>^ get ();
}
```

#### Property Value

Type: IReadOnlyCollection\<[PropertyInfo](https://technet.microsoft.com/library/8z852kf5\(v=ax.60\))\>  
Returns IReadOnlyCollection.  

## See Also

#### Reference

[TypeCache Class](typecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

