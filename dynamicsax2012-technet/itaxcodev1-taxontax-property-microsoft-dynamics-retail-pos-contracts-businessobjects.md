---
title: ITaxCodeV1.TaxOnTax Property  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects)
TOCTitle: TaxOnTax Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.ITaxCodeV1.TaxOnTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businessobjects.itaxcodev1.taxontax(v=AX.60)
ms:contentKeyID: 47129221
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.ITaxCodeV1.TaxOnTax
dev_langs:
- CSharp
- C++
- VB
---

# TaxOnTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The tax code of the other sales tax that this tax is based on.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects](microsoft-dynamics-retail-pos-contracts-businessobjects-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TaxOnTax As String
    Get
'Usage
Dim instance As ITaxCodeV1
Dim value As String

value = instance.TaxOnTax
```

``` csharp
string TaxOnTax { get; }
```

``` c++
property String^ TaxOnTax {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[ITaxCodeV1 Interface](itaxcodev1-interface-microsoft-dynamics-retail-pos-contracts-businessobjects.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects Namespace](microsoft-dynamics-retail-pos-contracts-businessobjects-namespace.md)

