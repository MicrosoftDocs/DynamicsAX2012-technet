---
title: TenderType.MaximumUndertenderAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumUndertenderAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MaximumUndertenderAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.maximumundertenderamount(v=AX.60)
ms:contentKeyID: 62207469
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MaximumUndertenderAmount
dev_langs:
- CSharp
- C++
- VB
---

# MaximumUndertenderAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the maximum undertender amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MAXIMUMUNDERTENDERAMOUNT")> _
Public Property MaximumUndertenderAmount As Decimal
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Decimal

value = instance.MaximumUndertenderAmount

instance.MaximumUndertenderAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MAXIMUMUNDERTENDERAMOUNT")]
public decimal MaximumUndertenderAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MAXIMUMUNDERTENDERAMOUNT")]
public:
property Decimal MaximumUndertenderAmount {
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

