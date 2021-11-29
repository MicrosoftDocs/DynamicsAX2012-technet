---
title: StringDataHelper.TruncateString Method  (Microsoft.Dynamics.Commerce.Runtime.Helpers)
TOCTitle: TruncateString Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Helpers.StringDataHelper.TruncateString(System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.helpers.stringdatahelper.truncatestring(v=AX.60)
ms:contentKeyID: 65322930
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Helpers.StringDataHelper.TruncateString
dev_langs:
- CSharp
- C++
- VB
---

# TruncateString Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Truncate the given string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Helpers](microsoft-dynamics-commerce-runtime-helpers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Function TruncateString ( _
    value As String, _
    maximumLength As Integer _
) As String
'Usage
Dim value As String
Dim maximumLength As Integer
Dim returnValue As String

returnValue = StringDataHelper.TruncateString(value, _
    maximumLength)
```

``` csharp
public static string TruncateString(
    string value,
    int maximumLength
)
```

``` c++
public:
static String^ TruncateString(
    String^ value, 
    int maximumLength
)
```

#### Parameters

  - value  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - maximumLength  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The truncated string.  

## See Also

#### Reference

[StringDataHelper Class](stringdatahelper-class-microsoft-dynamics-commerce-runtime-helpers.md)

[Microsoft.Dynamics.Commerce.Runtime.Helpers Namespace](microsoft-dynamics-commerce-runtime-helpers-namespace.md)

