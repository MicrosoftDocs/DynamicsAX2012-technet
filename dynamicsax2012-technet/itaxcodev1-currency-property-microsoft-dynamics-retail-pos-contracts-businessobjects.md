---
title: ITaxCodeV1.Currency Property  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects)
TOCTitle: Currency Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.ITaxCodeV1.Currency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businessobjects.itaxcodev1.currency(v=AX.60)
ms:contentKeyID: 47128609
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.ITaxCodeV1.Currency
dev_langs:
- CSharp
- C++
- VB
---

# Currency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The currency code for the currency that the tax is calculated in.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects](microsoft-dynamics-retail-pos-contracts-businessobjects-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Currency As String
    Get
'Usage
Dim instance As ITaxCodeV1
Dim value As String

value = instance.Currency
```

``` csharp
string Currency { get; }
```

``` c++
property String^ Currency {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## Remarks

For example, “USD”.

## See Also

#### Reference

[ITaxCodeV1 Interface](itaxcodev1-interface-microsoft-dynamics-retail-pos-contracts-businessobjects.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects Namespace](microsoft-dynamics-retail-pos-contracts-businessobjects-namespace.md)

