---
title: IncomeExpenseAccount.AccountName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount.AccountName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.incomeexpenseaccount.accountname(v=AX.60)
ms:contentKeyID: 62210697
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount.AccountName
dev_langs:
- CSharp
- C++
- VB
---

# AccountName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the account name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ACCOUNTNAME")> _
Public Property AccountName As String
    Get
    Set
'Usage
Dim instance As IncomeExpenseAccount
Dim value As String

value = instance.AccountName

instance.AccountName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ACCOUNTNAME")]
public string AccountName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ACCOUNTNAME")]
public:
property String^ AccountName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IncomeExpenseAccount Class](incomeexpenseaccount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

