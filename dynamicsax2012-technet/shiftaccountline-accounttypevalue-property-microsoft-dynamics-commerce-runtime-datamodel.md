---
title: ShiftAccountLine.AccountTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftAccountLine.AccountTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shiftaccountline.accounttypevalue(v=AX.60)
ms:contentKeyID: 62212889
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftAccountLine.AccountTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# AccountTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the IncomeExpenseAccountType enum.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ACCOUNTTYPE")> _
<DataMemberAttribute> _
Public Property AccountTypeValue As Integer
    Get
    Set
'Usage
Dim instance As ShiftAccountLine
Dim value As Integer

value = instance.AccountTypeValue

instance.AccountTypeValue = value
```

``` csharp
[ColumnAttribute("ACCOUNTTYPE")]
[DataMemberAttribute]
public int AccountTypeValue { get; set; }
```

``` c++
[ColumnAttribute(L"ACCOUNTTYPE")]
[DataMemberAttribute]
public:
property int AccountTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ShiftAccountLine Class](shiftaccountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

