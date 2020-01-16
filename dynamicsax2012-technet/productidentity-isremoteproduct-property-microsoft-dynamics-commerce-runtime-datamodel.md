---
title: ProductIdentity.IsRemoteProduct Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsRemoteProduct Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.IsRemoteProduct
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productidentity.isremoteproduct(v=AX.60)
ms:contentKeyID: 62213271
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.IsRemoteProduct
dev_langs:
- CSharp
- C++
- VB
---

# IsRemoteProduct Property

Gets a value indicating whether this product was loaded from a remote data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISREMOTE")> _
Public Property IsRemoteProduct As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductIdentity
Dim value As Boolean

value = instance.IsRemoteProduct
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISREMOTE")]
public bool IsRemoteProduct { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISREMOTE")]
public:
property bool IsRemoteProduct {
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

