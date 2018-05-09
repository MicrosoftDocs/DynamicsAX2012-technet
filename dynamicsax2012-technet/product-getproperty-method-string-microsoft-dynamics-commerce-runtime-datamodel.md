---
title: Product.GetProperty Method (String) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetProperty Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.GetProperty(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.product.getproperty(v=AX.60)
ms:contentKeyID: 62211395
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProperty Method (String)

Gets the property associated with the specified key and default language.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetProperty ( _
    propertyKey As String _
) As ProductProperty
'Usage
Dim instance As Product
Dim propertyKey As String
Dim returnValue As ProductProperty

returnValue = instance.GetProperty(propertyKey)
```

``` csharp
public ProductProperty GetProperty(
    string propertyKey
)
```

``` c++
public:
ProductProperty^ GetProperty(
    String^ propertyKey
)
```

#### Parameters

  - propertyKey  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The property object matching the specified property key and default language id.  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[GetProperty Overload](product-getproperty-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

