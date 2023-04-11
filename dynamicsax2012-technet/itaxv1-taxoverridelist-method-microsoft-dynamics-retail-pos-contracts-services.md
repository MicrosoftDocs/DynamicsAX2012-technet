---
title: ITaxV1.TaxOverrideList Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: TaxOverrideList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITaxV1.TaxOverrideList(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TaxOverrideBy,System.String@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.itaxv1.taxoverridelist(v=AX.60)
ms:contentKeyID: 47344098
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITaxV1.TaxOverrideList
dev_langs:
- CSharp
- C++
- VB
---

# TaxOverrideList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Displays a list of available sales tax overrides.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function TaxOverrideList ( _
    overrideBy As TaxOverrideBy, _
    <OutAttribute> ByRef selectedTaxOverride As String _
) As DialogResult
'Usage
Dim instance As ITaxV1
Dim overrideBy As TaxOverrideBy
Dim selectedTaxOverride As String
Dim returnValue As DialogResult

returnValue = instance.TaxOverrideList(overrideBy, _
    selectedTaxOverride)
```

``` csharp
DialogResult TaxOverrideList(
    TaxOverrideBy overrideBy,
    out string selectedTaxOverride
)
```

``` c++
DialogResult TaxOverrideList(
    TaxOverrideBy overrideBy, 
    [OutAttribute] String^% selectedTaxOverride
)
```

#### Parameters

  - overrideBy  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.TaxOverrideBy](taxoverrideby-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - selectedTaxOverride  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/library/5ahe29t9\(v=ax.60\))  
One of the DialogResult values.  

## See Also

#### Reference

[ITaxV1 Interface](itaxv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

