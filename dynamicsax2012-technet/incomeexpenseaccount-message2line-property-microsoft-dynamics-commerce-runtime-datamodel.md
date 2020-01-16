---
title: IncomeExpenseAccount.Message2Line Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Message2Line Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount.Message2Line
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.incomeexpenseaccount.message2line(v=AX.60)
ms:contentKeyID: 62209671
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount.Message2Line
dev_langs:
- CSharp
- C++
- VB
---

# Message2Line Property

Gets or sets the Message2 value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MESSAGELINE2")> _
Public Property Message2Line As String
    Get
    Set
'Usage
Dim instance As IncomeExpenseAccount
Dim value As String

value = instance.Message2Line

instance.Message2Line = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MESSAGELINE2")]
public string Message2Line { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MESSAGELINE2")]
public:
property String^ Message2Line {
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

