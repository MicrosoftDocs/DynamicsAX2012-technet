---
title: ProductIdentity.MasterProductId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MasterProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.MasterProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productidentity.masterproductid(v=AX.60)
ms:contentKeyID: 62208570
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.MasterProductId
dev_langs:
- CSharp
- C++
- VB
---

# MasterProductId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the product master identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MASTERPRODUCT")> _
<DataMemberAttribute> _
Public Property MasterProductId As Long
    Get
    Friend Set
'Usage
Dim instance As ProductIdentity
Dim value As Long

value = instance.MasterProductId
```

``` csharp
[ColumnAttribute("MASTERPRODUCT")]
[DataMemberAttribute]
public long MasterProductId { get; internal set; }
```

``` c++
[ColumnAttribute(L"MASTERPRODUCT")]
[DataMemberAttribute]
public:
property long long MasterProductId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductIdentity Class](productidentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

