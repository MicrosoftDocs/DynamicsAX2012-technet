---
title: CatalogController.GetActiveProductCatalogs Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetActiveProductCatalogs Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CatalogController.GetActiveProductCatalogs(System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.catalogcontroller.getactiveproductcatalogs(v=AX.60)
ms:contentKeyID: 65318043
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CatalogController.GetActiveProductCatalogs
dev_langs:
- CSharp
- C++
- VB
---

# GetActiveProductCatalogs Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetActiveProductCatalogs ( _
    storeId As Long _
) As ReadOnlyCollection(Of Long)
'Usage
Dim instance As CatalogController
Dim storeId As Long
Dim returnValue As ReadOnlyCollection(Of Long)

returnValue = instance.GetActiveProductCatalogs(storeId)
```

``` csharp
public virtual ReadOnlyCollection<long> GetActiveProductCatalogs(
    long storeId
)
```

``` c++
public:
virtual ReadOnlyCollection<long long>^ GetActiveProductCatalogs(
    long long storeId
)
```

#### Parameters

  - storeId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[CatalogController Class](catalogcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

