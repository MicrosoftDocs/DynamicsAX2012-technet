---
title: FeatureNotSupportedException Constructor (String, String, Exception) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: FeatureNotSupportedException Constructor (String, String, Exception)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.FeatureNotSupportedException.#ctor(System.String,System.String,System.Exception)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.featurenotsupportedexception.featurenotsupportedexception(v=AX.60)
ms:contentKeyID: 65321840
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# FeatureNotSupportedException Constructor (String, String, Exception)

Initializes a new instance of the [FeatureNotSupportedException](featurenotsupportedexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    message As String, _
    innerException As Exception _
)
'Usage
Dim errorResourceId As String
Dim message As String
Dim innerException As Exception

Dim instance As New FeatureNotSupportedException(errorResourceId, _
    message, innerException)
```

``` csharp
public FeatureNotSupportedException(
    string errorResourceId,
    string message,
    Exception innerException
)
```

``` c++
public:
FeatureNotSupportedException(
    String^ errorResourceId, 
    String^ message, 
    Exception^ innerException
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - innerException  
    Type: [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  

## See Also

#### Reference

[FeatureNotSupportedException Class](featurenotsupportedexception-class-microsoft-dynamics-commerce-runtime.md)

[FeatureNotSupportedException Overload](featurenotsupportedexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

