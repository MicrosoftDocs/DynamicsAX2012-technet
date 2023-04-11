---
title: CartLineValidationResults.Item Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Item Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults.Item(System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.cartlinevalidationresults.item(v=AX.60)
ms:contentKeyID: 62206720
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CartLineValidationResults.Item
dev_langs:
- CSharp
- C++
- VB
---

# Item Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the validation results at index.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Item ( _
    index As Integer _
) As Collection(Of DataValidationFailure)
    Get
'Usage
Dim instance As CartLineValidationResults
Dim index As Integer
Dim value As Collection(Of DataValidationFailure)

value = instance.Item(index)
```

``` csharp
public Collection<DataValidationFailure> this[
    int index
] { get; }
```

``` c++
public:
property Collection<DataValidationFailure^>^ Item[int index] {
    Collection<DataValidationFailure^>^ get (int index);
}
```

#### Parameters

  - index  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  
The validation results for the line.  

## See Also

#### Reference

[CartLineValidationResults Class](cartlinevalidationresults-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

