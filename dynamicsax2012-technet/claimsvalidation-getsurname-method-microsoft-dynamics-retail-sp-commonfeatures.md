---
title: ClaimsValidation.GetSurname Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: GetSurname Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.GetSurname
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.claimsvalidation.getsurname(v=AX.60)
ms:contentKeyID: 62202264
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.GetSurname
dev_langs:
- CSharp
- C++
- VB
---

# GetSurname Method

Gets the surname of the authenticated user.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetSurname As String
'Usage
Dim returnValue As String

returnValue = ClaimsValidation.GetSurname()
```

``` csharp
public static string GetSurname()
```

``` c++
public:
static String^ GetSurname()
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The surname.  

## See Also

#### Reference

[ClaimsValidation Class](claimsvalidation-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

