---
title: TransactionProperty.SalesLineNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesLineNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionProperty.SalesLineNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactionproperty.saleslinenumber(v=AX.60)
ms:contentKeyID: 62213282
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionProperty.SalesLineNumber
dev_langs:
- CSharp
- C++
- VB
---

# SalesLineNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales line number related to the sales line that owns this property, or 0, if it's a header property.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SALELINENUM")> _
<DataMemberAttribute> _
Public Property SalesLineNumber As Decimal
    Get
    Set
'Usage
Dim instance As TransactionProperty
Dim value As Decimal

value = instance.SalesLineNumber

instance.SalesLineNumber = value
```

``` csharp
[ColumnAttribute("SALELINENUM")]
[DataMemberAttribute]
public decimal SalesLineNumber { get; set; }
```

``` c++
[ColumnAttribute(L"SALELINENUM")]
[DataMemberAttribute]
public:
property Decimal SalesLineNumber {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TransactionProperty Class](transactionproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

