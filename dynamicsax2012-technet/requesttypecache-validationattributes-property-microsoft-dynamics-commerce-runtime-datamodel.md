---
title: RequestTypeCache.ValidationAttributes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidationAttributes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RequestTypeCache.ValidationAttributes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.requesttypecache.validationattributes(v=AX.60)
ms:contentKeyID: 65318977
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RequestTypeCache.ValidationAttributes
dev_langs:
- CSharp
- C++
- VB
---

# ValidationAttributes Property

Gets the mapping between property info and validation attributes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property ValidationAttributes As IReadOnlyDictionary(Of PropertyInfo, IEnumerable(Of ValidationAttribute))
    Get
'Usage
Dim instance As RequestTypeCache
Dim value As IReadOnlyDictionary(Of PropertyInfo, IEnumerable(Of ValidationAttribute))

value = instance.ValidationAttributes
```

``` csharp
public IReadOnlyDictionary<PropertyInfo, IEnumerable<ValidationAttribute>> ValidationAttributes { get; }
```

``` c++
public:
property IReadOnlyDictionary<PropertyInfo^, IEnumerable<ValidationAttribute^>^>^ ValidationAttributes {
    IReadOnlyDictionary<PropertyInfo^, IEnumerable<ValidationAttribute^>^>^ get ();
}
```

#### Property Value

Type: IReadOnlyDictionary\<[PropertyInfo](https://technet.microsoft.com/library/8z852kf5\(v=ax.60\)), [IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ValidationAttribute](validationattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)\>\>  
Returns IReadOnlyDictionary.  

## See Also

#### Reference

[RequestTypeCache Class](requesttypecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

