---
title: GetIncomeExpenseAccountsRequest.IncomeExpenseAccountType Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IncomeExpenseAccountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetIncomeExpenseAccountsRequest.IncomeExpenseAccountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getincomeexpenseaccountsrequest.incomeexpenseaccounttype(v=AX.60)
ms:contentKeyID: 62213736
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetIncomeExpenseAccountsRequest.IncomeExpenseAccountType
dev_langs:
- CSharp
- C++
- VB
---

# IncomeExpenseAccountType Property

Gets or sets income / expense account type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IncomeExpenseAccountType As IncomeExpenseAccountType
    Get
    Set
'Usage
Dim instance As GetIncomeExpenseAccountsRequest
Dim value As IncomeExpenseAccountType

value = instance.IncomeExpenseAccountType

instance.IncomeExpenseAccountType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public IncomeExpenseAccountType IncomeExpenseAccountType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property IncomeExpenseAccountType IncomeExpenseAccountType {
    IncomeExpenseAccountType get ();
    void set (IncomeExpenseAccountType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccountType](incomeexpenseaccounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [IncomeExpenseAccountType](incomeexpenseaccounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetIncomeExpenseAccountsRequest Class](getincomeexpenseaccountsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

