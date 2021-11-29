---
title: TransferOrderLine.QuantityRemainReceive Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityRemainReceive Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.QuantityRemainReceive
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorderline.quantityremainreceive(v=AX.60)
ms:contentKeyID: 62206522
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.QuantityRemainReceive
dev_langs:
- CSharp
- C++
- VB
---

# QuantityRemainReceive Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the quantity remaining to receive.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("QUANTITYREMAINRECEIVE")> _
Public Property QuantityRemainReceive As Decimal
    Get
    Set
'Usage
Dim instance As TransferOrderLine
Dim value As Decimal

value = instance.QuantityRemainReceive

instance.QuantityRemainReceive = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("QUANTITYREMAINRECEIVE")]
public decimal QuantityRemainReceive { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"QUANTITYREMAINRECEIVE")]
public:
property Decimal QuantityRemainReceive {
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

