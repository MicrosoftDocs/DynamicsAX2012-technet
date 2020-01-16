---
title: CartLineValidationResults.AggregateValidationFailures Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: AggregateValidationFailures Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults.AggregateValidationFailures
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cartlinevalidationresults.aggregatevalidationfailures(v=AX.60)
ms:contentKeyID: 62206870
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults.AggregateValidationFailures
dev_langs:
- CSharp
- C++
- VB
---

# AggregateValidationFailures Property

Gets all line validation failures into a single collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property AggregateValidationFailures As ReadOnlyCollection(Of DataValidationFailure)
    Get
'Usage
Dim instance As CartLineValidationResults
Dim value As ReadOnlyCollection(Of DataValidationFailure)

value = instance.AggregateValidationFailures
```

``` csharp
public ReadOnlyCollection<DataValidationFailure> AggregateValidationFailures { get; }
```

``` c++
public:
property ReadOnlyCollection<DataValidationFailure^>^ AggregateValidationFailures {
    ReadOnlyCollection<DataValidationFailure^>^ get ();
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[CartLineValidationResults Class](cartlinevalidationresults-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

