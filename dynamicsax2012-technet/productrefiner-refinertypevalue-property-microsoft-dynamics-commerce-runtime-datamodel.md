---
title: ProductRefiner.RefinerTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RefinerTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.RefinerTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefiner.refinertypevalue(v=AX.60)
ms:contentKeyID: 65319998
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.RefinerTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# RefinerTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the refiner type enumeration. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RefinerTypeValue As Integer
    Get
    Set
'Usage
Dim instance As ProductRefiner
Dim value As Integer

value = instance.RefinerTypeValue

instance.RefinerTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int RefinerTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int RefinerTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ProductRefiner Class](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

