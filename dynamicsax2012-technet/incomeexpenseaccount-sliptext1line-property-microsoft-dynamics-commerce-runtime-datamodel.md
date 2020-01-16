---
title: IncomeExpenseAccount.SlipText1Line Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SlipText1Line Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount.SlipText1Line
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.incomeexpenseaccount.sliptext1line(v=AX.60)
ms:contentKeyID: 62209148
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount.SlipText1Line
dev_langs:
- CSharp
- C++
- VB
---

# SlipText1Line Property

Gets or sets the Slip text1 value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SLIPTEXT1")> _
<DataMemberAttribute> _
Public Property SlipText1Line As String
    Get
    Set
'Usage
Dim instance As IncomeExpenseAccount
Dim value As String

value = instance.SlipText1Line

instance.SlipText1Line = value
```

``` csharp
[ColumnAttribute("SLIPTEXT1")]
[DataMemberAttribute]
public string SlipText1Line { get; set; }
```

``` c++
[ColumnAttribute(L"SLIPTEXT1")]
[DataMemberAttribute]
public:
property String^ SlipText1Line {
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

