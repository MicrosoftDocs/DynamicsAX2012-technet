---
title: TransferOrderLine.QuantityShipped Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityShipped Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.QuantityShipped
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorderline.quantityshipped(v=AX.60)
ms:contentKeyID: 62212372
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.QuantityShipped
dev_langs:
- CSharp
- C++
- VB
---

# QuantityShipped Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the total quantity shipped.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("QUANTITYSHIPPED")> _
<DataMemberAttribute> _
Public Property QuantityShipped As Decimal
    Get
    Set
'Usage
Dim instance As TransferOrderLine
Dim value As Decimal

value = instance.QuantityShipped

instance.QuantityShipped = value
```

``` csharp
[ColumnAttribute("QUANTITYSHIPPED")]
[DataMemberAttribute]
public decimal QuantityShipped { get; set; }
```

``` c++
[ColumnAttribute(L"QUANTITYSHIPPED")]
[DataMemberAttribute]
public:
property Decimal QuantityShipped {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrderLine Class](transferorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

