---
title: DemoController.GetProductsByIds Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetProductsByIds Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.DemoController.GetProductsByIds(System.Collections.Generic.IList{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.democontroller.getproductsbyids(v=AX.60)
ms:contentKeyID: 65317837
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.DemoController.GetProductsByIds
dev_langs:
- CSharp
- C++
- VB
---

# GetProductsByIds Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetProductsByIds ( _
    productIds As IList(Of Long) _
) As ReadOnlyCollection(Of Product)
'Usage
Dim productIds As IList(Of Long)
Dim returnValue As ReadOnlyCollection(Of Product)

returnValue = DemoController.GetProductsByIds(productIds)
```

``` csharp
public static ReadOnlyCollection<Product> GetProductsByIds(
    IList<long> productIds
)
```

``` c++
public:
static ReadOnlyCollection<Product^>^ GetProductsByIds(
    IList<long long>^ productIds
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<Product\>  

## See Also

#### Reference

[DemoController Class](democontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

