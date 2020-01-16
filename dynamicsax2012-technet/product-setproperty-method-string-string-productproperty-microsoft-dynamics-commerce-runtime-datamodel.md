---
title: Product.SetProperty Method (String, String, ProductProperty) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SetProperty Method (String, String, ProductProperty)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.SetProperty(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.setproperty(v=AX.60)
ms:contentKeyID: 62207629
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SetProperty Method (String, String, ProductProperty)

Gets the property associated with the specified key and language.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub SetProperty ( _
    propertyKey As String, _
    languageKey As String, _
    value As ProductProperty _
)
'Usage
Dim instance As Product
Dim propertyKey As String
Dim languageKey As String
Dim value As ProductProperty

instance.SetProperty(propertyKey, languageKey, _
    value)
```

``` csharp
public void SetProperty(
    string propertyKey,
    string languageKey,
    ProductProperty value
)
```

``` c++
public:
void SetProperty(
    String^ propertyKey, 
    String^ languageKey, 
    ProductProperty^ value
)
```

#### Parameters

  - propertyKey  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - languageKey  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - value  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[SetProperty Overload](product-setproperty-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

