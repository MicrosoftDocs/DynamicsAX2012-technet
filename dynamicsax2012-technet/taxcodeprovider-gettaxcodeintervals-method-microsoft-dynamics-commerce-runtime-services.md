---
title: TaxCodeProvider.GetTaxCodeIntervals Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetTaxCodeIntervals Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.GetTaxCodeIntervals(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String,System.String,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeprovider.gettaxcodeintervals(v=AX.60)
ms:contentKeyID: 62214602
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.GetTaxCodeIntervals
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxCodeIntervals Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax code intervals.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetTaxCodeIntervals ( _
    context As RequestContext, _
    salesTaxGroupId As String, _
    itemTaxGroupId As String, _
    transDate As DateTimeOffset _
) As ReadOnlyCollection(Of TaxCodeInterval)
'Usage
Dim context As RequestContext
Dim salesTaxGroupId As String
Dim itemTaxGroupId As String
Dim transDate As DateTimeOffset
Dim returnValue As ReadOnlyCollection(Of TaxCodeInterval)

returnValue = Me.GetTaxCodeIntervals(context, _
    salesTaxGroupId, itemTaxGroupId, _
    transDate)
```

``` csharp
protected virtual ReadOnlyCollection<TaxCodeInterval> GetTaxCodeIntervals(
    RequestContext context,
    string salesTaxGroupId,
    string itemTaxGroupId,
    DateTimeOffset transDate
)
```

``` c++
protected:
virtual ReadOnlyCollection<TaxCodeInterval^>^ GetTaxCodeIntervals(
    RequestContext^ context, 
    String^ salesTaxGroupId, 
    String^ itemTaxGroupId, 
    DateTimeOffset transDate
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - salesTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxCodeInterval](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The taxcode object.  

## See Also

#### Reference

[TaxCodeProvider Class](taxcodeprovider-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

