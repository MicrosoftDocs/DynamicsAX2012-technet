---
title: ClaimsValidation.GetUserIdentifier Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: GetUserIdentifier Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.GetUserIdentifier
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.claimsvalidation.getuseridentifier(v=AX.60)
ms:contentKeyID: 62206666
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.GetUserIdentifier
dev_langs:
- CSharp
- C++
- VB
---

# GetUserIdentifier Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the UserIdentifier of the authenticated user.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetUserIdentifier As String
'Usage
Dim returnValue As String

returnValue = ClaimsValidation.GetUserIdentifier()
```

``` csharp
public static string GetUserIdentifier()
```

``` c++
public:
static String^ GetUserIdentifier()
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The user identifier of the authenticated user.  

## See Also

#### Reference

[ClaimsValidation Class](claimsvalidation-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

