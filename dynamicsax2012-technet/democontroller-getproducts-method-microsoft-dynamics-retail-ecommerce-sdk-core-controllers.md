---
title: DemoController.GetProducts Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetProducts Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.DemoController.GetProducts(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.democontroller.getproducts(v=AX.60)
ms:contentKeyID: 65318575
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.DemoController.GetProducts
dev_langs:
- CSharp
- C++
- VB
---

# GetProducts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetProducts ( _
    language As String _
) As ReadOnlyCollection(Of Product)
'Usage
Dim language As String
Dim returnValue As ReadOnlyCollection(Of Product)

returnValue = DemoController.GetProducts(language)
```

``` csharp
public static ReadOnlyCollection<Product> GetProducts(
    string language
)
```

``` c++
public:
static ReadOnlyCollection<Product^>^ GetProducts(
    String^ language
)
```

#### Parameters

  - language  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<Product\>  

## See Also

#### Reference

[DemoController Class](democontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

