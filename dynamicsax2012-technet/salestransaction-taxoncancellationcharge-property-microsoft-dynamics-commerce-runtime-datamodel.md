---
title: SalesTransaction.TaxOnCancellationCharge Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxOnCancellationCharge Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.TaxOnCancellationCharge
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.taxoncancellationcharge(v=AX.60)
ms:contentKeyID: 62210890
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.TaxOnCancellationCharge
dev_langs:
- CSharp
- C++
- VB
---

# TaxOnCancellationCharge Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax on cancellation charge amount (customer order).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXONCANCELLATIONCHARGE")> _
<DataMemberAttribute> _
Public Property TaxOnCancellationCharge As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.TaxOnCancellationCharge

instance.TaxOnCancellationCharge = value
```

``` csharp
[ColumnAttribute("TAXONCANCELLATIONCHARGE")]
[DataMemberAttribute]
public decimal TaxOnCancellationCharge { get; set; }
```

``` c++
[ColumnAttribute(L"TAXONCANCELLATIONCHARGE")]
[DataMemberAttribute]
public:
property Decimal TaxOnCancellationCharge {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

