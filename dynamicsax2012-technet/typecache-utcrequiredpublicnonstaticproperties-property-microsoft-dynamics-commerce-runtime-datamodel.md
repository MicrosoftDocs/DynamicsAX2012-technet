---
title: TypeCache.UtcRequiredPublicNonStaticProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UtcRequiredPublicNonStaticProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache.UtcRequiredPublicNonStaticProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.typecache.utcrequiredpublicnonstaticproperties(v=AX.60)
ms:contentKeyID: 65320585
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache.UtcRequiredPublicNonStaticProperties
dev_langs:
- CSharp
- C++
- VB
---

# UtcRequiredPublicNonStaticProperties Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of public non-static [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)) properties of the entity that are required to be represented in UTC.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property UtcRequiredPublicNonStaticProperties As IReadOnlyCollection(Of PropertyColumnPair)
    Get
'Usage
Dim instance As TypeCache
Dim value As IReadOnlyCollection(Of PropertyColumnPair)

value = instance.UtcRequiredPublicNonStaticProperties
```

``` csharp
public IReadOnlyCollection<PropertyColumnPair> UtcRequiredPublicNonStaticProperties { get; }
```

``` c++
public:
property IReadOnlyCollection<PropertyColumnPair^>^ UtcRequiredPublicNonStaticProperties {
    IReadOnlyCollection<PropertyColumnPair^>^ get ();
}
```

#### Property Value

Type: IReadOnlyCollection\<[PropertyColumnPair](propertycolumnpair-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns IReadOnlyCollection.  

## See Also

#### Reference

[TypeCache Class](typecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

