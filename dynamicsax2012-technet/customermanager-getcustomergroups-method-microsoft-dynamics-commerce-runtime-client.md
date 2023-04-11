---
title: CustomerManager.GetCustomerGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCustomerGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.GetCustomerGroups(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.customermanager.getcustomergroups(v=AX.60)
ms:contentKeyID: 65323243
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.GetCustomerGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerGroups Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomerGroups ( _
    settings As QueryResultSettings _
) As PagedResult(Of CustomerGroup)
'Usage
Dim instance As CustomerManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of CustomerGroup)

returnValue = instance.GetCustomerGroups(settings)
```

``` csharp
public PagedResult<CustomerGroup> GetCustomerGroups(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<CustomerGroup^>^ GetCustomerGroups(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[CustomerGroup](customergroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CustomerManager Class](customermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

