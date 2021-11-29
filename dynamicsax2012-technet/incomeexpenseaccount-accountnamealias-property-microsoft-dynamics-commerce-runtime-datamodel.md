---
title: IncomeExpenseAccount.AccountNameAlias Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountNameAlias Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount.AccountNameAlias
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.incomeexpenseaccount.accountnamealias(v=AX.60)
ms:contentKeyID: 62206856
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount.AccountNameAlias
dev_langs:
- CSharp
- C++
- VB
---

# AccountNameAlias Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the account name alias.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ACCOUNTNAMEALIAS")> _
Public Property AccountNameAlias As String
    Get
    Set
'Usage
Dim instance As IncomeExpenseAccount
Dim value As String

value = instance.AccountNameAlias

instance.AccountNameAlias = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ACCOUNTNAMEALIAS")]
public string AccountNameAlias { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ACCOUNTNAMEALIAS")]
public:
property String^ AccountNameAlias {
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

