---
title: TypeCache.Properties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Properties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache.Properties
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.typecache.properties(v=AX.60)
ms:contentKeyID: 65318951
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache.Properties
dev_langs:
- CSharp
- C++
- VB
---

# Properties Property

Gets the enumerable of public non-static properties of the type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Properties As IReadOnlyCollection(Of PropertyInfo)
    Get
'Usage
Dim instance As TypeCache
Dim value As IReadOnlyCollection(Of PropertyInfo)

value = instance.Properties
```

``` csharp
public IReadOnlyCollection<PropertyInfo> Properties { get; }
```

``` c++
public:
property IReadOnlyCollection<PropertyInfo^>^ Properties {
    IReadOnlyCollection<PropertyInfo^>^ get ();
}
```

#### Property Value

Type: IReadOnlyCollection\<[PropertyInfo](https://technet.microsoft.com/en-us/library/8z852kf5\(v=ax.60\))\>  
Returns IReadOnlyCollection.  

## See Also

#### Reference

[TypeCache Class](typecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

