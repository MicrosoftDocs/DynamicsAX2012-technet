---
title: OrderManager.GetDiscountCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetDiscountCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetDiscountCodes(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getdiscountcodes(v=AX.60)
ms:contentKeyID: 65318200
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetDiscountCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountCodes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetDiscountCodes ( _
    settings As QueryResultSettings _
) As PagedResult(Of DiscountCode)
'Usage
Dim instance As OrderManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of DiscountCode)

returnValue = instance.GetDiscountCodes(settings)
```

``` csharp
public PagedResult<DiscountCode> GetDiscountCodes(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<DiscountCode^>^ GetDiscountCodes(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

