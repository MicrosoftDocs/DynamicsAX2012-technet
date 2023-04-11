---
title: ISaleLineItemV1.DeliveryDate Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: DeliveryDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.DeliveryDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.deliverydate(v=AX.60)
ms:contentKeyID: 49837526
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.DeliveryDate
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets os sets the delivery date.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property DeliveryDate As Nullable(Of DateTime)
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Nullable(Of DateTime)

value = instance.DeliveryDate

instance.DeliveryDate = value
```

``` csharp
Nullable<DateTime> DeliveryDate { get; set; }
```

``` c++
property Nullable<DateTime> DeliveryDate {
    Nullable<DateTime> get ();
    void set (Nullable<DateTime> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

