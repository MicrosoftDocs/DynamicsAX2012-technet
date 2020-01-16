---
title: ShiftAccountLine.AccountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftAccountLine.AccountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shiftaccountline.accounttype(v=AX.60)
ms:contentKeyID: 62208784
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftAccountLine.AccountType
dev_langs:
- CSharp
- C++
- VB
---

# AccountType Property

Gets or sets account type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property AccountType As IncomeExpenseAccountType
    Get
    Set
'Usage
Dim instance As ShiftAccountLine
Dim value As IncomeExpenseAccountType

value = instance.AccountType

instance.AccountType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public IncomeExpenseAccountType AccountType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
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

[ShiftAccountLine Class](shiftaccountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

