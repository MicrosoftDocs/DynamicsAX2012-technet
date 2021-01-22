---
title: ChannelDataManager.GetIncomeExpenseAccounts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetIncomeExpenseAccounts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetIncomeExpenseAccounts(Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccountType,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatamanager.getincomeexpenseaccounts(v=AX.60)
ms:contentKeyID: 65322468
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetIncomeExpenseAccounts
dev_langs:
- CSharp
- C++
- VB
---

# GetIncomeExpenseAccounts Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetIncomeExpenseAccounts ( _
    incomeExpenseType As IncomeExpenseAccountType, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of IncomeExpenseAccount)
'Usage
Dim instance As ChannelDataManager
Dim incomeExpenseType As IncomeExpenseAccountType
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of IncomeExpenseAccount)

returnValue = instance.GetIncomeExpenseAccounts(incomeExpenseType, _
    settings)
```

``` csharp
public ReadOnlyCollection<IncomeExpenseAccount> GetIncomeExpenseAccounts(
    IncomeExpenseAccountType incomeExpenseType,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<IncomeExpenseAccount^>^ GetIncomeExpenseAccounts(
    IncomeExpenseAccountType incomeExpenseType, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - incomeExpenseType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccountType](incomeexpenseaccounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[IncomeExpenseAccount](incomeexpenseaccount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelDataManager Class](channeldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

