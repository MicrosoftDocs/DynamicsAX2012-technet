---
title: GetIncomeExpenseAccountsResponse Constructor (IEnumerable(IncomeExpenseAccount)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetIncomeExpenseAccountsResponse Constructor (IEnumerable(IncomeExpenseAccount))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetIncomeExpenseAccountsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getincomeexpenseaccountsresponse.getincomeexpenseaccountsresponse(v=AX.60)
ms:contentKeyID: 62210999
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetIncomeExpenseAccountsResponse Constructor (IEnumerable(IncomeExpenseAccount))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetIncomeExpenseAccountsResponse](getincomeexpenseaccountsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    incomeExpenseAccounts As IEnumerable(Of IncomeExpenseAccount) _
)
'Usage
Dim incomeExpenseAccounts As IEnumerable(Of IncomeExpenseAccount)

Dim instance As New GetIncomeExpenseAccountsResponse(incomeExpenseAccounts)
```

``` csharp
public GetIncomeExpenseAccountsResponse(
    IEnumerable<IncomeExpenseAccount> incomeExpenseAccounts
)
```

``` c++
public:
GetIncomeExpenseAccountsResponse(
    IEnumerable<IncomeExpenseAccount^>^ incomeExpenseAccounts
)
```

#### Parameters

  - incomeExpenseAccounts  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[IncomeExpenseAccount](incomeexpenseaccount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetIncomeExpenseAccountsResponse Class](getincomeexpenseaccountsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetIncomeExpenseAccountsResponse Overload](getincomeexpenseaccountsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

