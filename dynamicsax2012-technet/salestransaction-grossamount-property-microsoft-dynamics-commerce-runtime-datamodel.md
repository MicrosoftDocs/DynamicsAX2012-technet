---
title: SalesTransaction.GrossAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GrossAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.GrossAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.grossamount(v=AX.60)
ms:contentKeyID: 49836720
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.GrossAmount
dev_langs:
- CSharp
- C++
- VB
---

# GrossAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the total amount excluding tax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("GROSSAMOUNT")> _
Public Property GrossAmount As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.GrossAmount

instance.GrossAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("GROSSAMOUNT")]
public decimal GrossAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"GROSSAMOUNT")]
public:
property Decimal GrossAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

