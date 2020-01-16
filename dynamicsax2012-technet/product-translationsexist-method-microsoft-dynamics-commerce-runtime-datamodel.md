---
title: Product.TranslationsExist Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TranslationsExist Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.TranslationsExist(System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.translationsexist(v=AX.60)
ms:contentKeyID: 65318968
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.TranslationsExist
dev_langs:
- CSharp
- C++
- VB
---

# TranslationsExist Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function TranslationsExist ( _
    id As Long, _
    languageId As String _
) As Boolean
'Usage
Dim instance As Product
Dim id As Long
Dim languageId As String
Dim returnValue As Boolean

returnValue = instance.TranslationsExist(id, _
    languageId)
```

``` csharp
public bool TranslationsExist(
    long id,
    string languageId
)
```

``` c++
public:
bool TranslationsExist(
    long long id, 
    String^ languageId
)
```

#### Parameters

  - id  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

