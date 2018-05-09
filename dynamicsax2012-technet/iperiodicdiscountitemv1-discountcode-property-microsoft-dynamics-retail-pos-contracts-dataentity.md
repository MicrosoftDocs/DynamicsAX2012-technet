---
title: IPeriodicDiscountItemV1.DiscountCode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: DiscountCode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountItemV1.DiscountCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iperiodicdiscountitemv1.discountcode(v=AX.60)
ms:contentKeyID: 49844024
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountItemV1.DiscountCode
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCode Property

Which coupon/promotion code (if any?) activated this discount

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property DiscountCode As String
    Get
    Set
'Usage
Dim instance As IPeriodicDiscountItemV1
Dim value As String

value = instance.DiscountCode

instance.DiscountCode = value
```

``` csharp
string DiscountCode { get; set; }
```

``` c++
property String^ DiscountCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IPeriodicDiscountItemV1 Interface](iperiodicdiscountitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

