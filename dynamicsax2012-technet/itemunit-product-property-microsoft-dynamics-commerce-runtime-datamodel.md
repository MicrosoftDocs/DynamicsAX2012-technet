---
title: ItemUnit.Product Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Product Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit.Product
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemunit.product(v=AX.60)
ms:contentKeyID: 65318248
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit.Product
dev_langs:
- CSharp
- C++
- VB
---

# Product Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRODUCT")> _
Public Property Product As Long
    Get
    Set
'Usage
Dim instance As ItemUnit
Dim value As Long

value = instance.Product

instance.Product = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRODUCT")]
public long Product { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRODUCT")]
public:
property long long Product {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[ItemUnit Class](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

