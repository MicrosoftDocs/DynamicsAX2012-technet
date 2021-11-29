---
title: TaxCodeProvider.GetTaxCode Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetTaxCode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.GetTaxCode(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem,Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeprovider.gettaxcode(v=AX.60)
ms:contentKeyID: 62209696
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.GetTaxCode
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxCode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetTaxCode ( _
    context As RequestContext, _
    taxableItem As TaxableItem, _
    taxCodeInterval As TaxCodeInterval _
) As TaxCode
'Usage
Dim context As RequestContext
Dim taxableItem As TaxableItem
Dim taxCodeInterval As TaxCodeInterval
Dim returnValue As TaxCode

returnValue = Me.GetTaxCode(context, _
    taxableItem, taxCodeInterval)
```

``` csharp
protected virtual TaxCode GetTaxCode(
    RequestContext context,
    TaxableItem taxableItem,
    TaxCodeInterval taxCodeInterval
)
```

``` c++
protected:
virtual TaxCode^ GetTaxCode(
    RequestContext^ context, 
    TaxableItem^ taxableItem, 
    TaxCodeInterval^ taxCodeInterval
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - taxableItem  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - taxCodeInterval  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)  
The taxcode object.  

## See Also

#### Reference

[TaxCodeProvider Class](taxcodeprovider-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

