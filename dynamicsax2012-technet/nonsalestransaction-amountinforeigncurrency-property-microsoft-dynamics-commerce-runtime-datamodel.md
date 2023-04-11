---
title: NonSalesTransaction.AmountInForeignCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AmountInForeignCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.AmountInForeignCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.nonsalestransaction.amountinforeigncurrency(v=AX.60)
ms:contentKeyID: 65315995
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.AmountInForeignCurrency
dev_langs:
- CSharp
- C++
- VB
---

# AmountInForeignCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("AMOUNTCUR")> _
<IgnoreDataMemberAttribute> _
Public Property AmountInForeignCurrency As Decimal
    Get
    Set
'Usage
Dim instance As NonSalesTransaction
Dim value As Decimal

value = instance.AmountInForeignCurrency

instance.AmountInForeignCurrency = value
```

``` csharp
[ColumnAttribute("AMOUNTCUR")]
[IgnoreDataMemberAttribute]
public decimal AmountInForeignCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"AMOUNTCUR")]
[IgnoreDataMemberAttribute]
public:
property Decimal AmountInForeignCurrency {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[NonSalesTransaction Class](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

