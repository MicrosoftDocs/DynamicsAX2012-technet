---
title: SalesTransaction.NumberOfItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NumberOfItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.NumberOfItems
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.numberofitems(v=AX.60)
ms:contentKeyID: 62214912
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.NumberOfItems
dev_langs:
- CSharp
- C++
- VB
---

# NumberOfItems Property

Gets or sets the sum of the quantity of all sales lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("NUMBEROFITEMS")> _
Public Property NumberOfItems As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.NumberOfItems

instance.NumberOfItems = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("NUMBEROFITEMS")]
public decimal NumberOfItems { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"NUMBEROFITEMS")]
public:
property Decimal NumberOfItems {
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

