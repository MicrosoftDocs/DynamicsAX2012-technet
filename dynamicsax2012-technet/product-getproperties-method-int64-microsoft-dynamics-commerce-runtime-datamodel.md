---
title: Product.GetProperties Method (Int64) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetProperties Method (Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.GetProperties(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.product.getproperties(v=AX.60)
ms:contentKeyID: 62202289
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProperties Method (Int64)

Enumerates the attributes of the specified subproduct, together with their default language values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetProperties ( _
    variantId As Long _
) As ReadOnlyCollection(Of ProductProperty)
'Usage
Dim instance As Product
Dim variantId As Long
Dim returnValue As ReadOnlyCollection(Of ProductProperty)

returnValue = instance.GetProperties(variantId)
```

``` csharp
public ReadOnlyCollection<ProductProperty> GetProperties(
    long variantId
)
```

``` c++
public:
ReadOnlyCollection<ProductProperty^>^ GetProperties(
    long long variantId
)
```

#### Parameters

  - variantId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ProductProperty](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A list of product properties.  

## Remarks

Please see the remarks of the EnumerateProperties(long, string) function below for more details.

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[GetProperties Overload](product-getproperties-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

