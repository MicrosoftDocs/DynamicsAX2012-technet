---
title: TenderLine.IncomeExpenseAccountTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IncomeExpenseAccountTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine.IncomeExpenseAccountTypeValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tenderline.incomeexpenseaccounttypevalue(v=AX.60)
ms:contentKeyID: 62213197
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine.IncomeExpenseAccountTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# IncomeExpenseAccountTypeValue Property

Gets or sets the income / expense account type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INCOMEEXPENSEACCOUNT")> _
<DataMemberAttribute> _
Public Property IncomeExpenseAccountTypeValue As Integer
    Get
    Set
'Usage
Dim instance As TenderLine
Dim value As Integer

value = instance.IncomeExpenseAccountTypeValue

instance.IncomeExpenseAccountTypeValue = value
```

``` csharp
[ColumnAttribute("INCOMEEXPENSEACCOUNT")]
[DataMemberAttribute]
public int IncomeExpenseAccountTypeValue { get; set; }
```

``` c++
[ColumnAttribute(L"INCOMEEXPENSEACCOUNT")]
[DataMemberAttribute]
public:
property int IncomeExpenseAccountTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TenderLine Class](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

