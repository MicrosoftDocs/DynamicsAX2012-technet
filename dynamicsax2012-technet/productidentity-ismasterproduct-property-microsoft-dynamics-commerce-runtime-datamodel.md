---
title: ProductIdentity.IsMasterProduct Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsMasterProduct Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.IsMasterProduct
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productidentity.ismasterproduct(v=AX.60)
ms:contentKeyID: 62211024
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.IsMasterProduct
dev_langs:
- CSharp
- C++
- VB
---

# IsMasterProduct Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether this is a master or standalone product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISMASTER")> _
Public Property IsMasterProduct As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductIdentity
Dim value As Boolean

value = instance.IsMasterProduct
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISMASTER")]
public bool IsMasterProduct { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISMASTER")]
public:
property bool IsMasterProduct {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ProductIdentity Class](productidentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

