---
title: ClaimsValidation.GetGivenName Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: GetGivenName Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.GetGivenName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.claimsvalidation.getgivenname(v=AX.60)
ms:contentKeyID: 62207203
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.GetGivenName
dev_langs:
- CSharp
- C++
- VB
---

# GetGivenName Method

Gets the given name of the authenticated user.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetGivenName As String
'Usage
Dim returnValue As String

returnValue = ClaimsValidation.GetGivenName()
```

``` csharp
public static string GetGivenName()
```

``` c++
public:
static String^ GetGivenName()
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The given name of the authenticated user.  

## See Also

#### Reference

[ClaimsValidation Class](claimsvalidation-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

