---
title: StoreOperationsManager.GetIncomeExpenseAccount Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetIncomeExpenseAccount Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.GetIncomeExpenseAccount(Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccountType,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.storeoperationsmanager.getincomeexpenseaccount(v=AX.60)
ms:contentKeyID: 65320945
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.GetIncomeExpenseAccount
dev_langs:
- CSharp
- C++
- VB
---

# GetIncomeExpenseAccount Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetIncomeExpenseAccount ( _
    incomeExpenseAccountType As IncomeExpenseAccountType, _
    settings As QueryResultSettings _
) As PagedResult(Of IncomeExpenseAccount)
'Usage
Dim instance As StoreOperationsManager
Dim incomeExpenseAccountType As IncomeExpenseAccountType
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of IncomeExpenseAccount)

returnValue = instance.GetIncomeExpenseAccount(incomeExpenseAccountType, _
    settings)
```

``` csharp
public PagedResult<IncomeExpenseAccount> GetIncomeExpenseAccount(
    IncomeExpenseAccountType incomeExpenseAccountType,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<IncomeExpenseAccount^>^ GetIncomeExpenseAccount(
    IncomeExpenseAccountType incomeExpenseAccountType, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - incomeExpenseAccountType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccountType](incomeexpenseaccounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[IncomeExpenseAccount](incomeexpenseaccount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[StoreOperationsManager Class](storeoperationsmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

