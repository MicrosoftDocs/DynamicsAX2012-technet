---
title: ClaimsValidation.GetUserName Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: GetUserName Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.GetUserName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.claimsvalidation.getusername(v=AX.60)
ms:contentKeyID: 62204297
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.GetUserName
dev_langs:
- CSharp
- C++
- VB
---

# GetUserName Method

Gets the UserName of the authenticated user.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetUserName As String
'Usage
Dim returnValue As String

returnValue = ClaimsValidation.GetUserName()
```

``` csharp
public static string GetUserName()
```

``` c++
public:
static String^ GetUserName()
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The username of the authenticated user.  

## See Also

#### Reference

[ClaimsValidation Class](claimsvalidation-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

