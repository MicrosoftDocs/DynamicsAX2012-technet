---
title: SalesTransaction.NetAmountWithTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NetAmountWithTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.NetAmountWithTax
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.netamountwithtax(v=AX.60)
ms:contentKeyID: 49829098
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.NetAmountWithTax
dev_langs:
- CSharp
- C++
- VB
---

# NetAmountWithTax Property

Gets or sets the total net amount (gross amount minus discounts) including tax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NetAmountWithTax As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.NetAmountWithTax

instance.NetAmountWithTax = value
```

``` csharp
[DataMemberAttribute]
public decimal NetAmountWithTax { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal NetAmountWithTax {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

