---
title: StringDataHelper.GetHashCodeForUpperCase Method  (Microsoft.Dynamics.Commerce.Runtime.Helpers)
TOCTitle: GetHashCodeForUpperCase Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Helpers.StringDataHelper.GetHashCodeForUpperCase(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.helpers.stringdatahelper.gethashcodeforuppercase(v=AX.60)
ms:contentKeyID: 65320805
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Helpers.StringDataHelper.GetHashCodeForUpperCase
dev_langs:
- CSharp
- C++
- VB
---

# GetHashCodeForUpperCase Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns hash code for the upper cases version of supplied string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Helpers](microsoft-dynamics-commerce-runtime-helpers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetHashCodeForUpperCase ( _
    data As String _
) As Integer
'Usage
Dim data As String
Dim returnValue As Integer

returnValue = StringDataHelper.GetHashCodeForUpperCase(data)
```

``` csharp
public static int GetHashCodeForUpperCase(
    string data
)
```

``` c++
public:
static int GetHashCodeForUpperCase(
    String^ data
)
```

#### Parameters

  - data  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The hash code.  

## See Also

#### Reference

[StringDataHelper Class](stringdatahelper-class-microsoft-dynamics-commerce-runtime-helpers.md)

[Microsoft.Dynamics.Commerce.Runtime.Helpers Namespace](microsoft-dynamics-commerce-runtime-helpers-namespace.md)

