---
title: CartLine.DeliveryModeChargeAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryModeChargeAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.DeliveryModeChargeAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.deliverymodechargeamount(v=AX.60)
ms:contentKeyID: 62213384
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.DeliveryModeChargeAmount
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryModeChargeAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the overriden delivery mode charge.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryModeChargeAmount As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Nullable(Of Decimal)

value = instance.DeliveryModeChargeAmount

instance.DeliveryModeChargeAmount = value
```

``` csharp
[DataMemberAttribute]
public Nullable<decimal> DeliveryModeChargeAmount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<Decimal> DeliveryModeChargeAmount {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## Remarks

When providing a delivery mode, client might provide a charge associated with the delivery.

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

