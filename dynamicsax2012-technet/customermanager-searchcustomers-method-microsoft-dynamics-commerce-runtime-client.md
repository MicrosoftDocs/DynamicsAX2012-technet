---
title: CustomerManager.SearchCustomers Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SearchCustomers Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.SearchCustomers(Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.customermanager.searchcustomers(v=AX.60)
ms:contentKeyID: 65321066
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.SearchCustomers
dev_langs:
- CSharp
- C++
- VB
---

# SearchCustomers Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function SearchCustomers ( _
    criteria As CustomerSearchCriteria, _
    settings As QueryResultSettings _
) As PagedResult(Of GlobalCustomer)
'Usage
Dim instance As CustomerManager
Dim criteria As CustomerSearchCriteria
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of GlobalCustomer)

returnValue = instance.SearchCustomers(criteria, _
    settings)
```

``` csharp
public PagedResult<GlobalCustomer> SearchCustomers(
    CustomerSearchCriteria criteria,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<GlobalCustomer^>^ SearchCustomers(
    CustomerSearchCriteria^ criteria, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerSearchCriteria](customersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[GlobalCustomer](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CustomerManager Class](customermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

