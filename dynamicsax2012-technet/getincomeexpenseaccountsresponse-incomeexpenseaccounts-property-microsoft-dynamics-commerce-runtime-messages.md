---
title: GetIncomeExpenseAccountsResponse.IncomeExpenseAccounts Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IncomeExpenseAccounts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetIncomeExpenseAccountsResponse.IncomeExpenseAccounts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getincomeexpenseaccountsresponse.incomeexpenseaccounts(v=AX.60)
ms:contentKeyID: 62202608
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetIncomeExpenseAccountsResponse.IncomeExpenseAccounts
dev_langs:
- CSharp
- C++
- VB
---

# IncomeExpenseAccounts Property

Gets the income and expense accounts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IncomeExpenseAccounts As ReadOnlyCollection(Of IncomeExpenseAccount)
    Get
    Private Set
'Usage
Dim instance As GetIncomeExpenseAccountsResponse
Dim value As ReadOnlyCollection(Of IncomeExpenseAccount)

value = instance.IncomeExpenseAccounts
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<IncomeExpenseAccount> IncomeExpenseAccounts { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<IncomeExpenseAccount^>^ IncomeExpenseAccounts {
    ReadOnlyCollection<IncomeExpenseAccount^>^ get ();
    private: void set (ReadOnlyCollection<IncomeExpenseAccount^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[IncomeExpenseAccount](incomeexpenseaccount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetIncomeExpenseAccountsResponse Class](getincomeexpenseaccountsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

