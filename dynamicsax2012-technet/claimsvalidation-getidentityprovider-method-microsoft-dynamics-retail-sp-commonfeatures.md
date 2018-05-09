---
title: ClaimsValidation.GetIdentityProvider Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: GetIdentityProvider Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.GetIdentityProvider
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.claimsvalidation.getidentityprovider(v=AX.60)
ms:contentKeyID: 62204054
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.GetIdentityProvider
dev_langs:
- CSharp
- C++
- VB
---

# GetIdentityProvider Method

Returns Identity Provider Claim Value if claim is found.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetIdentityProvider As String
'Usage
Dim returnValue As String

returnValue = ClaimsValidation.GetIdentityProvider()
```

``` csharp
public static string GetIdentityProvider()
```

``` c++
public:
static String^ GetIdentityProvider()
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The identity provider.  

## See Also

#### Reference

[ClaimsValidation Class](claimsvalidation-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

