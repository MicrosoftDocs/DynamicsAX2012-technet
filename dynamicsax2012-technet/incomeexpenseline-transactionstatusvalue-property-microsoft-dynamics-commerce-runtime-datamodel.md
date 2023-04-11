---
title: IncomeExpenseLine.TransactionStatusValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionStatusValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseLine.TransactionStatusValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.incomeexpenseline.transactionstatusvalue(v=AX.60)
ms:contentKeyID: 65315989
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseLine.TransactionStatusValue
dev_langs:
- CSharp
- C++
- VB
---

# TransactionStatusValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ReadOnlyAttribute("TRANSACTIONSTATUS")> _
Public Property TransactionStatusValue As Integer
    Get
    Set
'Usage
Dim instance As IncomeExpenseLine
Dim value As Integer

value = instance.TransactionStatusValue

instance.TransactionStatusValue = value
```

``` csharp
[DataMemberAttribute]
[ReadOnlyAttribute("TRANSACTIONSTATUS")]
public int TransactionStatusValue { get; set; }
```

``` c++
[DataMemberAttribute]
[ReadOnlyAttribute(L"TRANSACTIONSTATUS")]
public:
property int TransactionStatusValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[IncomeExpenseLine Class](incomeexpenseline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

