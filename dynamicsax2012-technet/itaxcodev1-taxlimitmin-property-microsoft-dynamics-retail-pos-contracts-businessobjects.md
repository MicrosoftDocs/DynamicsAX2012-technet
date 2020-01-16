---
title: ITaxCodeV1.TaxLimitMin Property  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects)
TOCTitle: TaxLimitMin Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.ITaxCodeV1.TaxLimitMin
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businessobjects.itaxcodev1.taxlimitmin(v=AX.60)
ms:contentKeyID: 47128791
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.ITaxCodeV1.TaxLimitMin
dev_langs:
- CSharp
- C++
- VB
---

# TaxLimitMin Property

The minimum amount that is required to calculate this tax.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects](microsoft-dynamics-retail-pos-contracts-businessobjects-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TaxLimitMin As Decimal
    Get
'Usage
Dim instance As ITaxCodeV1
Dim value As Decimal

value = instance.TaxLimitMin
```

``` csharp
decimal TaxLimitMin { get; }
```

``` c++
property Decimal TaxLimitMin {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)) value.  

## Remarks

If the price is less than the minimum amount, the tax will not be calculated.

## See Also

#### Reference

[ITaxCodeV1 Interface](itaxcodev1-interface-microsoft-dynamics-retail-pos-contracts-businessobjects.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects Namespace](microsoft-dynamics-retail-pos-contracts-businessobjects-namespace.md)

