---
title: DataValidationException Constructor (String, IList(DataValidationFailure), String, Object ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DataValidationException Constructor (String, IList(DataValidationFailure), String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataValidationException.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure},System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datavalidationexception.datavalidationexception(v=AX.60)
ms:contentKeyID: 62210863
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DataValidationException Constructor (String, IList(DataValidationFailure), String, Object[])

Initializes a new instance of the [DataValidationException](datavalidationexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    validationResults As IList(Of DataValidationFailure), _
    message As String, _
    ParamArray args As Object() _
)
'Usage
Dim errorResourceId As String
Dim validationResults As IList(Of DataValidationFailure)
Dim message As String
Dim args As Object()

Dim instance As New DataValidationException(errorResourceId, _
    validationResults, message, args)
```

``` csharp
public DataValidationException(
    string errorResourceId,
    IList<DataValidationFailure> validationResults,
    string message,
    params Object[] args
)
```

``` c++
public:
DataValidationException(
    String^ errorResourceId, 
    IList<DataValidationFailure^>^ validationResults, 
    String^ message, 
    ... array<Object^>^ args
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - validationResults  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - args  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[DataValidationException Class](datavalidationexception-class-microsoft-dynamics-commerce-runtime.md)

[DataValidationException Overload](datavalidationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

