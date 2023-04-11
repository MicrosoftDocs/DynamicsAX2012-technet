---
title: StringDataHelper.JoinStrings Method  (Microsoft.Dynamics.Commerce.Runtime.Helpers)
TOCTitle: JoinStrings Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Helpers.StringDataHelper.JoinStrings(System.String,System.String[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.helpers.stringdatahelper.joinstrings(v=AX.60)
ms:contentKeyID: 65319780
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Helpers.StringDataHelper.JoinStrings
dev_langs:
- CSharp
- C++
- VB
---

# JoinStrings Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Method to join strings using a separator.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Helpers](microsoft-dynamics-commerce-runtime-helpers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Function JoinStrings ( _
    separator As String, _
    ParamArray values As String() _
) As String
'Usage
Dim separator As String
Dim values As String()
Dim returnValue As String

returnValue = StringDataHelper.JoinStrings(separator, _
    values)
```

``` csharp
public static string JoinStrings(
    string separator,
    params string[] values
)
```

``` c++
public:
static String^ JoinStrings(
    String^ separator, 
    ... array<String^>^ values
)
```

#### Parameters

  - separator  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - values  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
A new string with all incoming strings joined using the separator.  

## Remarks

String.Join replaces any incoming null strings with String.Empty - this can lead to more than one consecutive separator in the target string. This method gets over that limitation by only joining strings that pass the IsNullOrWhiteSpace test.

## See Also

#### Reference

[StringDataHelper Class](stringdatahelper-class-microsoft-dynamics-commerce-runtime-helpers.md)

[Microsoft.Dynamics.Commerce.Runtime.Helpers Namespace](microsoft-dynamics-commerce-runtime-helpers-namespace.md)

