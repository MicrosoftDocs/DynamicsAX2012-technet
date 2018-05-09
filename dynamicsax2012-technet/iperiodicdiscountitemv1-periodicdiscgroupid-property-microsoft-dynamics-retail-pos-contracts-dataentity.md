---
title: IPeriodicDiscountItemV1.PeriodicDiscGroupId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PeriodicDiscGroupId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountItemV1.PeriodicDiscGroupId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iperiodicdiscountitemv1.periodicdiscgroupid(v=AX.60)
ms:contentKeyID: 49822330
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountItemV1.PeriodicDiscGroupId
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicDiscGroupId Property

Identifies a particular application or 'instantiation' of a discount.

When choosing best prices, the whole group is considered together.

This is gives us the granularity to apply or skip parts of a discount or apply it to some of its eligible items, but not others.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PeriodicDiscGroupId As String
    Get
    Set
'Usage
Dim instance As IPeriodicDiscountItemV1
Dim value As String

value = instance.PeriodicDiscGroupId

instance.PeriodicDiscGroupId = value
```

``` csharp
string PeriodicDiscGroupId { get; set; }
```

``` c++
property String^ PeriodicDiscGroupId {
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

