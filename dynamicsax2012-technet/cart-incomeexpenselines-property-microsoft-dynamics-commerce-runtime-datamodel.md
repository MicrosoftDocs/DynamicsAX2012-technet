---
title: Cart.IncomeExpenseLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IncomeExpenseLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.IncomeExpenseLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.incomeexpenselines(v=AX.60)
ms:contentKeyID: 62209362
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.IncomeExpenseLines
dev_langs:
- CSharp
- C++
- VB
---

# IncomeExpenseLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cart lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IncomeExpenseLines As IList(Of IncomeExpenseLine)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As IList(Of IncomeExpenseLine)

value = instance.IncomeExpenseLines

instance.IncomeExpenseLines = value
```

``` csharp
[DataMemberAttribute]
public IList<IncomeExpenseLine> IncomeExpenseLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<IncomeExpenseLine^>^ IncomeExpenseLines {
    IList<IncomeExpenseLine^>^ get ();
    void set (IList<IncomeExpenseLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[IncomeExpenseLine](incomeexpenseline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

