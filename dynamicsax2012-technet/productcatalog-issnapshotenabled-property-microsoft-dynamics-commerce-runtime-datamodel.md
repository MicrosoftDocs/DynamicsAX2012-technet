---
title: ProductCatalog.IsSnapshotEnabled Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsSnapshotEnabled Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog.IsSnapshotEnabled
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productcatalog.issnapshotenabled(v=AX.60)
ms:contentKeyID: 62212616
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog.IsSnapshotEnabled
dev_langs:
- CSharp
- C++
- VB
---

# IsSnapshotEnabled Property

Gets a value indicating whether this catalog is snapshot-enabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ENABLESNAPSHOT")> _
Public Property IsSnapshotEnabled As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductCatalog
Dim value As Boolean

value = instance.IsSnapshotEnabled
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ENABLESNAPSHOT")]
public bool IsSnapshotEnabled { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ENABLESNAPSHOT")]
public:
property bool IsSnapshotEnabled {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ProductCatalog Class](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

