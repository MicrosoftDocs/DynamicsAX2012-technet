---
title: ProductRefiner.Values Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Values Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.Values
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefiner.values(v=AX.60)
ms:contentKeyID: 65319983
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.Values
dev_langs:
- CSharp
- C++
- VB
---

# Values Property

Gets or sets the refiner values for this refiner.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Values As IEnumerable(Of ProductRefinerValue)
    Get
    Set
'Usage
Dim instance As ProductRefiner
Dim value As IEnumerable(Of ProductRefinerValue)

value = instance.Values

instance.Values = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ProductRefinerValue> Values { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ProductRefinerValue^>^ Values {
    IEnumerable<ProductRefinerValue^>^ get ();
    void set (IEnumerable<ProductRefinerValue^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ProductRefinerValue](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ProductRefiner Class](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

