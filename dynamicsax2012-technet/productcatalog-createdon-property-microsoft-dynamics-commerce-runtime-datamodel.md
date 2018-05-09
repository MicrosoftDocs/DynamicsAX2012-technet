---
title: ProductCatalog.CreatedOn Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CreatedOn Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog.CreatedOn
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productcatalog.createdon(v=AX.60)
ms:contentKeyID: 62209784
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog.CreatedOn
dev_langs:
- CSharp
- C++
- VB
---

# CreatedOn Property

Gets the date the catalog was created.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CREATEDDATETIME")> _
<DataMemberAttribute> _
Public Property CreatedOn As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As ProductCatalog
Dim value As DateTimeOffset

value = instance.CreatedOn
```

``` csharp
[ColumnAttribute("CREATEDDATETIME")]
[DataMemberAttribute]
public DateTimeOffset CreatedOn { get; internal set; }
```

``` c++
[ColumnAttribute(L"CREATEDDATETIME")]
[DataMemberAttribute]
public:
property DateTimeOffset CreatedOn {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[ProductCatalog Class](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

