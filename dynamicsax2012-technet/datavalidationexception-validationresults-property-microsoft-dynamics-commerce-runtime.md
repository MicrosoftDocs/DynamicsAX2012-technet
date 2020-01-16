---
title: DataValidationException.ValidationResults Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ValidationResults Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataValidationException.ValidationResults
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datavalidationexception.validationresults(v=AX.60)
ms:contentKeyID: 49839102
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataValidationException.ValidationResults
dev_langs:
- CSharp
- C++
- VB
---

# ValidationResults Property

Gets the collection of validation errors encountered.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ValidationResults As ReadOnlyCollection(Of DataValidationFailure)
    Get
    Private Set
'Usage
Dim instance As DataValidationException
Dim value As ReadOnlyCollection(Of DataValidationFailure)

value = instance.ValidationResults
```

``` csharp
public ReadOnlyCollection<DataValidationFailure> ValidationResults { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<DataValidationFailure^>^ ValidationResults {
    ReadOnlyCollection<DataValidationFailure^>^ get ();
    private: void set (ReadOnlyCollection<DataValidationFailure^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[DataValidationException Class](datavalidationexception-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

