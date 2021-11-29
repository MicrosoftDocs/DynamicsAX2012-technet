---
title: StringDataHelper.Equals Method  (Microsoft.Dynamics.Commerce.Runtime.Helpers)
TOCTitle: Equals Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Helpers.StringDataHelper.Equals(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.helpers.stringdatahelper.equals(v=AX.60)
ms:contentKeyID: 65318067
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Helpers.StringDataHelper.Equals
dev_langs:
- CSharp
- C++
- VB
---

# Equals Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Test if two string data values are equal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Helpers](microsoft-dynamics-commerce-runtime-helpers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Equals ( _
    value1 As String, _
    value2 As String _
) As Boolean
'Usage
Dim value1 As String
Dim value2 As String
Dim returnValue As Boolean

returnValue = StringDataHelper.Equals(value1, _
    value2)
```

``` csharp
public static bool Equals(
    string value1,
    string value2
)
```

``` c++
public:
static bool Equals(
    String^ value1, 
    String^ value2
)
```

#### Parameters

  - value1  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - value2  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if equal, false otherwise.  

## See Also

#### Reference

[StringDataHelper Class](stringdatahelper-class-microsoft-dynamics-commerce-runtime-helpers.md)

[Microsoft.Dynamics.Commerce.Runtime.Helpers Namespace](microsoft-dynamics-commerce-runtime-helpers-namespace.md)

