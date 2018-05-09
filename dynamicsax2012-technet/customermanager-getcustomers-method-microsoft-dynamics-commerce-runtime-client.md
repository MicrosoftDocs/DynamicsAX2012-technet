---
title: CustomerManager.GetCustomers Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCustomers Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.GetCustomers(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.customermanager.getcustomers(v=AX.60)
ms:contentKeyID: 65316496
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.GetCustomers
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomers Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomers ( _
    settings As QueryResultSettings _
) As PagedResult(Of Customer)
'Usage
Dim instance As CustomerManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of Customer)

returnValue = instance.GetCustomers(settings)
```

``` csharp
public PagedResult<Customer> GetCustomers(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<Customer^>^ GetCustomers(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CustomerManager Class](customermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

