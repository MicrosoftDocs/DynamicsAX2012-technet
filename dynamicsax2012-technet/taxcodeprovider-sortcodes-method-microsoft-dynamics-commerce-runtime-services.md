---
title: TaxCodeProvider.SortCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: SortCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.SortCodes(System.Collections.Generic.Dictionary{System.String,Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeprovider.sortcodes(v=AX.60)
ms:contentKeyID: 49845764
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeProvider.SortCodes
dev_langs:
- CSharp
- C++
- VB
---

# SortCodes Method

Sorts the specified tax codes by priority.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function SortCodes ( _
    codes As Dictionary(Of String, TaxCode) _
) As ReadOnlyCollection(Of TaxCode)
'Usage
Dim codes As Dictionary(Of String, TaxCode)
Dim returnValue As ReadOnlyCollection(Of TaxCode)

returnValue = Me.SortCodes(codes)
```

``` csharp
protected virtual ReadOnlyCollection<TaxCode> SortCodes(
    Dictionary<string, TaxCode> codes
)
```

``` c++
protected:
virtual ReadOnlyCollection<TaxCode^>^ SortCodes(
    Dictionary<String^, TaxCode^>^ codes
)
```

#### Parameters

  - codes  
    Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [TaxCode](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxCode](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)\>  
An ordered collection of tax codes.  

## See Also

#### Reference

[TaxCodeProvider Class](taxcodeprovider-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

