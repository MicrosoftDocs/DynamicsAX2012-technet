---
title: SalesTransaction.AmountDue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AmountDue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.AmountDue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.amountdue(v=AX.60)
ms:contentKeyID: 62214372
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.AmountDue
dev_langs:
- CSharp
- C++
- VB
---

# AmountDue Property

Gets or sets the amount due.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("AMOUNTDUE")> _
<DataMemberAttribute> _
Public Property AmountDue As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.AmountDue

instance.AmountDue = value
```

``` csharp
[ColumnAttribute("AMOUNTDUE")]
[DataMemberAttribute]
public decimal AmountDue { get; set; }
```

``` c++
[ColumnAttribute(L"AMOUNTDUE")]
[DataMemberAttribute]
public:
property Decimal AmountDue {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## Remarks

This represents the amount that must yet be tendered prior checking out the transaction.

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

