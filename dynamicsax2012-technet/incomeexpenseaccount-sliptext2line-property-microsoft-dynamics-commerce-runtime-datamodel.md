---
title: IncomeExpenseAccount.SlipText2Line Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SlipText2Line Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount.SlipText2Line
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.incomeexpenseaccount.sliptext2line(v=AX.60)
ms:contentKeyID: 62206475
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseAccount.SlipText2Line
dev_langs:
- CSharp
- C++
- VB
---

# SlipText2Line Property

Gets or sets the Slip text2 value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SLIPTEXT2")> _
Public Property SlipText2Line As String
    Get
    Set
'Usage
Dim instance As IncomeExpenseAccount
Dim value As String

value = instance.SlipText2Line

instance.SlipText2Line = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SLIPTEXT2")]
public string SlipText2Line { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SLIPTEXT2")]
public:
property String^ SlipText2Line {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IncomeExpenseAccount Class](incomeexpenseaccount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

