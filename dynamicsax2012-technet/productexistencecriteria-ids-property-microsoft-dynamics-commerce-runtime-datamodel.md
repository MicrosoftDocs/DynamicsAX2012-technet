---
title: ProductExistenceCriteria.Ids Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Ids Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductExistenceCriteria.Ids
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productexistencecriteria.ids(v=AX.60)
ms:contentKeyID: 62201819
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductExistenceCriteria.Ids
dev_langs:
- CSharp
- C++
- VB
---

# Ids Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets product existence Ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Ids As IEnumerable(Of ProductExistenceId)
    Get
    Set
'Usage
Dim instance As ProductExistenceCriteria
Dim value As IEnumerable(Of ProductExistenceId)

value = instance.Ids

instance.Ids = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ProductExistenceId> Ids { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ProductExistenceId^>^ Ids {
    IEnumerable<ProductExistenceId^>^ get ();
    void set (IEnumerable<ProductExistenceId^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ProductExistenceId](productexistenceid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ProductExistenceCriteria Class](productexistencecriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

