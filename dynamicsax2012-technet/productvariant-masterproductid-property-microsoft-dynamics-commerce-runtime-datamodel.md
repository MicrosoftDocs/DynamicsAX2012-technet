---
title: ProductVariant.MasterProductId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MasterProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.MasterProductId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.masterproductid(v=AX.60)
ms:contentKeyID: 62211923
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.MasterProductId
dev_langs:
- CSharp
- C++
- VB
---

# MasterProductId Property

Gets the associated product master id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property MasterProductId As Long
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As Long

value = instance.MasterProductId

instance.MasterProductId = value
```

``` csharp
[DataMemberAttribute]
public long MasterProductId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long MasterProductId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

