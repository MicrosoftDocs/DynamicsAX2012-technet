---
title: TaxCodeProvider.GetTaxCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetTaxCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.GetTaxCodes(Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem,Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeprovider.gettaxcodes(v=AX.60)
ms:contentKeyID: 49856242
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.GetTaxCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxCodes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves a list of TaxCodes for the given sale line item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetTaxCodes ( _
    taxableItem As TaxableItem, _
    context As RequestContext _
) As ReadOnlyCollection(Of TaxCode)
'Usage
Dim taxableItem As TaxableItem
Dim context As RequestContext
Dim returnValue As ReadOnlyCollection(Of TaxCode)

returnValue = Me.GetTaxCodes(taxableItem, _
    context)
```

``` csharp
protected virtual ReadOnlyCollection<TaxCode> GetTaxCodes(
    TaxableItem taxableItem,
    RequestContext context
)
```

``` c++
protected:
virtual ReadOnlyCollection<TaxCode^>^ GetTaxCodes(
    TaxableItem^ taxableItem, 
    RequestContext^ context
)
```

#### Parameters

  - taxableItem  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxCode](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)\>  
Tax codes applicablee with the taxableItem.  

## Remarks

No user Input or variable in string TaxSelectSqlText. No sql injection threat.

## See Also

#### Reference

[TaxCodeProvider Class](taxcodeprovider-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

