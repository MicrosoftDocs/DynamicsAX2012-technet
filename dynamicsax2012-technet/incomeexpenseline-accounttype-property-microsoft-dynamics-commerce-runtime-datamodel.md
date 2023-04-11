---
title: IncomeExpenseLine.AccountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseLine.AccountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.incomeexpenseline.accounttype(v=AX.60)
ms:contentKeyID: 62213807
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseLine.AccountType
dev_langs:
- CSharp
- C++
- VB
---

# AccountType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the account type alias.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ACCOUNTTYPE")> _
Public Property AccountType As IncomeExpenseAccountType
    Get
    Set
'Usage
Dim instance As IncomeExpenseLine
Dim value As IncomeExpenseAccountType

value = instance.AccountType

instance.AccountType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("ACCOUNTTYPE")]
public IncomeExpenseAccountType AccountType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ACCOUNTTYPE")]
public:
property IncomeExpenseAccountType AccountType {
    IncomeExpenseAccountType get ();
    void set (IncomeExpenseAccountType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccountType](incomeexpenseaccounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [IncomeExpenseAccountType](incomeexpenseaccounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[IncomeExpenseLine Class](incomeexpenseline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

