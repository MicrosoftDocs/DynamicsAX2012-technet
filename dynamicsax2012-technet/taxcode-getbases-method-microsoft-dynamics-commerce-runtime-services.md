---
title: TaxCode.GetBases Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetBases Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.GetBases(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode},System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.getbases(v=AX.60)
ms:contentKeyID: 65316872
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.GetBases
dev_langs:
- CSharp
- C++
- VB
---

# GetBases Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetBases ( _
    codes As ReadOnlyCollection(Of TaxCode), _
    taxInStoreCurrency As Boolean, _
    calculateBasePrice As Boolean _
) As Tuple(Of Decimal, Decimal)
'Usage
Dim codes As ReadOnlyCollection(Of TaxCode)
Dim taxInStoreCurrency As Boolean
Dim calculateBasePrice As Boolean
Dim returnValue As Tuple(Of Decimal, Decimal)

returnValue = Me.GetBases(codes, taxInStoreCurrency, _
    calculateBasePrice)
```

``` csharp
protected virtual Tuple<decimal, decimal> GetBases(
    ReadOnlyCollection<TaxCode> codes,
    bool taxInStoreCurrency,
    bool calculateBasePrice
)
```

``` c++
protected:
virtual Tuple<Decimal, Decimal>^ GetBases(
    ReadOnlyCollection<TaxCode^>^ codes, 
    bool taxInStoreCurrency, 
    bool calculateBasePrice
)
```

#### Parameters

  - codes  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxCode](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)\>  

<!-- end list -->

  - taxInStoreCurrency  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - calculateBasePrice  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: Tuple\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)), [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

