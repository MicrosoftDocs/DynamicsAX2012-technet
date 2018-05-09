---
title: IPeriodicDiscountItemV1.ConcurrencyMode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ConcurrencyMode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountItemV1.ConcurrencyMode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iperiodicdiscountitemv1.concurrencymode(v=AX.60)
ms:contentKeyID: 49833420
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountItemV1.ConcurrencyMode
dev_langs:
- CSharp
- C++
- VB
---

# ConcurrencyMode Property

How should the discount be applied Exclusively, by best price, or compounded

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ConcurrencyMode As ConcurrencyMode
    Get
    Set
'Usage
Dim instance As IPeriodicDiscountItemV1
Dim value As ConcurrencyMode

value = instance.ConcurrencyMode

instance.ConcurrencyMode = value
```

``` csharp
ConcurrencyMode ConcurrencyMode { get; set; }
```

``` c++
property ConcurrencyMode ConcurrencyMode {
    ConcurrencyMode get ();
    void set (ConcurrencyMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ConcurrencyMode](concurrencymode-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [ConcurrencyMode](concurrencymode-enumeration-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[IPeriodicDiscountItemV1 Interface](iperiodicdiscountitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

