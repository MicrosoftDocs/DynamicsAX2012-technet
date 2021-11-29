---
title: TaxCodeProvider.SetLineItemTaxRate Method (TaxableItem, Decimal) (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: SetLineItemTaxRate Method (TaxableItem, Decimal)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.SetLineItemTaxRate(Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeprovider.setlineitemtaxrate(v=AX.60)
ms:contentKeyID: 49849770
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SetLineItemTaxRate Method (TaxableItem, Decimal)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Sets the line item tax rate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Protected Shared Sub SetLineItemTaxRate ( _
    taxableItem As TaxableItem, _
    taxAmount As Decimal _
)
'Usage
Dim taxableItem As TaxableItem
Dim taxAmount As Decimal

TaxCodeProvider.SetLineItemTaxRate(taxableItem, _
    taxAmount)
```

``` csharp
protected static void SetLineItemTaxRate(
    TaxableItem taxableItem,
    decimal taxAmount
)
```

``` c++
protected:
static void SetLineItemTaxRate(
    TaxableItem^ taxableItem, 
    Decimal taxAmount
)
```

#### Parameters

  - taxableItem  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - taxAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[TaxCodeProvider Class](taxcodeprovider-class-microsoft-dynamics-commerce-runtime-services.md)

[SetLineItemTaxRate Overload](taxcodeprovider-setlineitemtaxrate-method-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

