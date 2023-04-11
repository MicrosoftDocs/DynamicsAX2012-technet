---
title: DataValidationFailure Constructor (String, ICollection(String)) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: DataValidationFailure Constructor (String, ICollection(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure.#ctor(System.String,System.Collections.Generic.ICollection{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datavalidationfailure.datavalidationfailure(v=AX.60)
ms:contentKeyID: 65319143
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DataValidationFailure Constructor (String, ICollection(String))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    memberNames As ICollection(Of String) _
)
'Usage
Dim errorResourceId As String
Dim memberNames As ICollection(Of String)

Dim instance As New DataValidationFailure(errorResourceId, _
    memberNames)
```

``` csharp
public DataValidationFailure(
    string errorResourceId,
    ICollection<string> memberNames
)
```

``` c++
public:
DataValidationFailure(
    String^ errorResourceId, 
    ICollection<String^>^ memberNames
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - memberNames  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[DataValidationFailure Class](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)

[DataValidationFailure Overload](datavalidationfailure-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

