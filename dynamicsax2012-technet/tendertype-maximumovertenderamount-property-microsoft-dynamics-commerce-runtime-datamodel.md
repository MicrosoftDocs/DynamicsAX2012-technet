---
title: TenderType.MaximumOvertenderAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumOvertenderAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MaximumOvertenderAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.maximumovertenderamount(v=AX.60)
ms:contentKeyID: 62206072
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MaximumOvertenderAmount
dev_langs:
- CSharp
- C++
- VB
---

# MaximumOvertenderAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the maximum overtender amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MAXIMUMOVERTENDERAMOUNT")> _
Public Property MaximumOvertenderAmount As Decimal
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Decimal

value = instance.MaximumOvertenderAmount

instance.MaximumOvertenderAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MAXIMUMOVERTENDERAMOUNT")]
public decimal MaximumOvertenderAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MAXIMUMOVERTENDERAMOUNT")]
public:
property Decimal MaximumOvertenderAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

