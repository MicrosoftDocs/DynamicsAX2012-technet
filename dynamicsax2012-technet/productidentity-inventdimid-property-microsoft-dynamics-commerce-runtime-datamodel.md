---
title: ProductIdentity.InventDimId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventDimId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.InventDimId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productidentity.inventdimid(v=AX.60)
ms:contentKeyID: 62209025
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.InventDimId
dev_langs:
- CSharp
- C++
- VB
---

# InventDimId Property

Gets the inventory dimension id of the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTDIMID")> _
<DataMemberAttribute> _
Public Property InventDimId As String
    Get
    Friend Set
'Usage
Dim instance As ProductIdentity
Dim value As String

value = instance.InventDimId
```

``` csharp
[ColumnAttribute("INVENTDIMID")]
[DataMemberAttribute]
public string InventDimId { get; internal set; }
```

``` c++
[ColumnAttribute(L"INVENTDIMID")]
[DataMemberAttribute]
public:
property String^ InventDimId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductIdentity Class](productidentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

