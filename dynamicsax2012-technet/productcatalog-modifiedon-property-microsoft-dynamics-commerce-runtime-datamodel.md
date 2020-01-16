---
title: ProductCatalog.ModifiedOn Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ModifiedOn Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog.ModifiedOn
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productcatalog.modifiedon(v=AX.60)
ms:contentKeyID: 62213366
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog.ModifiedOn
dev_langs:
- CSharp
- C++
- VB
---

# ModifiedOn Property


**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MODIFIEDDATETIME")> _
Public Property ModifiedOn As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As ProductCatalog
Dim value As DateTimeOffset

value = instance.ModifiedOn
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MODIFIEDDATETIME")]
public DateTimeOffset ModifiedOn { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MODIFIEDDATETIME")]
public:
property DateTimeOffset ModifiedOn {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[ProductCatalog Class](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

