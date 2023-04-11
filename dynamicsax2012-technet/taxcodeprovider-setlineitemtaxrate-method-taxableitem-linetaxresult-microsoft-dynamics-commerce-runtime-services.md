---
title: TaxCodeProvider.SetLineItemTaxRate Method (TaxableItem, LineTaxResult) (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: SetLineItemTaxRate Method (TaxableItem, LineTaxResult)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.SetLineItemTaxRate(Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem,Microsoft.Dynamics.Commerce.Runtime.Services.LineTaxResult)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeprovider.setlineitemtaxrate(v=AX.60)
ms:contentKeyID: 49852426
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SetLineItemTaxRate Method (TaxableItem, LineTaxResult)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Sets the line item tax rate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Protected Shared Sub SetLineItemTaxRate ( _
    taxableItem As TaxableItem, _
    lineTaxResult As LineTaxResult _
)
'Usage
Dim taxableItem As TaxableItem
Dim lineTaxResult As LineTaxResult

TaxCodeProvider.SetLineItemTaxRate(taxableItem, _
    lineTaxResult)
```

``` csharp
protected static void SetLineItemTaxRate(
    TaxableItem taxableItem,
    LineTaxResult lineTaxResult
)
```

``` c++
protected:
static void SetLineItemTaxRate(
    TaxableItem^ taxableItem, 
    LineTaxResult^ lineTaxResult
)
```

#### Parameters

  - taxableItem  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - lineTaxResult  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.LineTaxResult](linetaxresult-class-microsoft-dynamics-commerce-runtime-services.md)  

## See Also

#### Reference

[TaxCodeProvider Class](taxcodeprovider-class-microsoft-dynamics-commerce-runtime-services.md)

[SetLineItemTaxRate Overload](taxcodeprovider-setlineitemtaxrate-method-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

