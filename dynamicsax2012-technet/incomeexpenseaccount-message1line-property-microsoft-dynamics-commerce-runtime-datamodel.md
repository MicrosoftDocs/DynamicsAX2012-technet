---
title: IncomeExpenseAccount.Message1Line Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Message1Line Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount.Message1Line
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.incomeexpenseaccount.message1line(v=AX.60)
ms:contentKeyID: 62214797
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount.Message1Line
dev_langs:
- CSharp
- C++
- VB
---

# Message1Line Property

Gets or sets the Message1 value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MESSAGELINE1")> _
<DataMemberAttribute> _
Public Property Message1Line As String
    Get
    Set
'Usage
Dim instance As IncomeExpenseAccount
Dim value As String

value = instance.Message1Line

instance.Message1Line = value
```

``` csharp
[ColumnAttribute("MESSAGELINE1")]
[DataMemberAttribute]
public string Message1Line { get; set; }
```

``` c++
[ColumnAttribute(L"MESSAGELINE1")]
[DataMemberAttribute]
public:
property String^ Message1Line {
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

