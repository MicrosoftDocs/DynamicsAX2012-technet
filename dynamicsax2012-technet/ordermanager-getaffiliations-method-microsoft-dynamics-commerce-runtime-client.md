---
title: OrderManager.GetAffiliations Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetAffiliations Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetAffiliations(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getaffiliations(v=AX.60)
ms:contentKeyID: 65319173
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetAffiliations
dev_langs:
- CSharp
- C++
- VB
---

# GetAffiliations Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetAffiliations ( _
    settings As QueryResultSettings _
) As PagedResult(Of Affiliation)
'Usage
Dim instance As OrderManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of Affiliation)

returnValue = instance.GetAffiliations(settings)
```

``` csharp
public PagedResult<Affiliation> GetAffiliations(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<Affiliation^>^ GetAffiliations(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[Affiliation](affiliation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

