---
title: ProductCatalog.ValidFrom Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidFrom Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog.ValidFrom
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productcatalog.validfrom(v=AX.60)
ms:contentKeyID: 62210405
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog.ValidFrom
dev_langs:
- CSharp
- C++
- VB
---

# ValidFrom Property

Gets the start date of the catalog.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("VALIDFROM")> _
Public Property ValidFrom As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As ProductCatalog
Dim value As DateTimeOffset

value = instance.ValidFrom
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("VALIDFROM")]
public DateTimeOffset ValidFrom { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"VALIDFROM")]
public:
property DateTimeOffset ValidFrom {
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

