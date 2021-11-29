---
title: SalesTransaction.IncomeExpenseLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IncomeExpenseLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IncomeExpenseLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.incomeexpenselines(v=AX.60)
ms:contentKeyID: 62209149
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.IncomeExpenseLines
dev_langs:
- CSharp
- C++
- VB
---

# IncomeExpenseLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the income (or) expense lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IncomeExpenseLines As Collection(Of IncomeExpenseLine)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Collection(Of IncomeExpenseLine)

value = instance.IncomeExpenseLines

instance.IncomeExpenseLines = value
```

``` csharp
[DataMemberAttribute]
public Collection<IncomeExpenseLine> IncomeExpenseLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<IncomeExpenseLine^>^ IncomeExpenseLines {
    Collection<IncomeExpenseLine^>^ get ();
    void set (Collection<IncomeExpenseLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[IncomeExpenseLine](incomeexpenseline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

