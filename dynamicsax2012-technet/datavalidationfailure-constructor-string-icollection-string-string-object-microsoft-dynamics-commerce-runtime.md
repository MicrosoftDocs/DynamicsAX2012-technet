---
title: DataValidationFailure Constructor (String, ICollection(String), String, Object ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DataValidationFailure Constructor (String, ICollection(String), String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure.#ctor(System.String,System.Collections.Generic.ICollection{System.String},System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datavalidationfailure.datavalidationfailure(v=AX.60)
ms:contentKeyID: 65321859
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DataValidationFailure Constructor (String, ICollection(String), String, Object )

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    memberNames As ICollection(Of String), _
    message As String, _
    ParamArray arguments As Object() _
)
'Usage
Dim errorResourceId As String
Dim memberNames As ICollection(Of String)
Dim message As String
Dim arguments As Object()

Dim instance As New DataValidationFailure(errorResourceId, _
    memberNames, message, arguments)
```

``` csharp
public DataValidationFailure(
    string errorResourceId,
    ICollection<string> memberNames,
    string message,
    params Object[] arguments
)
```

``` c++
public:
DataValidationFailure(
    String^ errorResourceId, 
    ICollection<String^>^ memberNames, 
    String^ message, 
    ... array<Object^>^ arguments
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - memberNames  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - arguments  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[DataValidationFailure Class](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)

[DataValidationFailure Overload](datavalidationfailure-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

