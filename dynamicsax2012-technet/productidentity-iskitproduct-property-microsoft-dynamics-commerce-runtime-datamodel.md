---
title: ProductIdentity.IsKitProduct Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsKitProduct Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.IsKitProduct
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productidentity.iskitproduct(v=AX.60)
ms:contentKeyID: 62211048
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.IsKitProduct
dev_langs:
- CSharp
- C++
- VB
---

# IsKitProduct Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether this is a kit product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISKIT")> _
<DataMemberAttribute> _
Public Property IsKitProduct As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductIdentity
Dim value As Boolean

value = instance.IsKitProduct
```

``` csharp
[ColumnAttribute("ISKIT")]
[DataMemberAttribute]
public bool IsKitProduct { get; internal set; }
```

``` c++
[ColumnAttribute(L"ISKIT")]
[DataMemberAttribute]
public:
property bool IsKitProduct {
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

