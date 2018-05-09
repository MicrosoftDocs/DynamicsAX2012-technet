---
title: ITaxCodeV1.TaxLimitMax Property  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects)
TOCTitle: TaxLimitMax Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.ITaxCodeV1.TaxLimitMax
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businessobjects.itaxcodev1.taxlimitmax(v=AX.60)
ms:contentKeyID: 47128882
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.ITaxCodeV1.TaxLimitMax
dev_langs:
- CSharp
- C++
- VB
---

# TaxLimitMax Property

The maximum amount that is required to calculate the tax.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects](microsoft-dynamics-retail-pos-contracts-businessobjects-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TaxLimitMax As Decimal
    Get
'Usage
Dim instance As ITaxCodeV1
Dim value As Decimal

value = instance.TaxLimitMax
```

``` csharp
decimal TaxLimitMax { get; }
```

``` c++
property Decimal TaxLimitMax {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)) value.  

## Remarks

If the price is more than the maximum amount, the tax will not be calculated.

## See Also

#### Reference

[ITaxCodeV1 Interface](itaxcodev1-interface-microsoft-dynamics-retail-pos-contracts-businessobjects.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects Namespace](microsoft-dynamics-retail-pos-contracts-businessobjects-namespace.md)

