---
title: CartLineValidationResults.ValidationResults Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ValidationResults Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults.ValidationResults
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cartlinevalidationresults.validationresults(v=AX.60)
ms:contentKeyID: 62212396
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults.ValidationResults
dev_langs:
- CSharp
- C++
- VB
---

# ValidationResults Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the dictionary containing validation results by index of the cart line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property ValidationResults As Dictionary(Of Integer, Collection(Of DataValidationFailure))
    Get
    Private Set
'Usage
Dim instance As CartLineValidationResults
Dim value As Dictionary(Of Integer, Collection(Of DataValidationFailure))

value = instance.ValidationResults
```

``` csharp
public Dictionary<int, Collection<DataValidationFailure>> ValidationResults { get; private set; }
```

``` c++
public:
property Dictionary<int, Collection<DataValidationFailure^>^>^ ValidationResults {
    Dictionary<int, Collection<DataValidationFailure^>^>^ get ();
    private: void set (Dictionary<int, Collection<DataValidationFailure^>^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)), [Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>\>  
Returns [Dictionary\<TKey, TValue\>](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\)).  

## See Also

#### Reference

[CartLineValidationResults Class](cartlinevalidationresults-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

