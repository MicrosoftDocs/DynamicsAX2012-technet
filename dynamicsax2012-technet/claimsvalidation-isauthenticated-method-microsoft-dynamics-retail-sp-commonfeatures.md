---
title: ClaimsValidation.IsAuthenticated Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: IsAuthenticated Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.IsAuthenticated
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.claimsvalidation.isauthenticated(v=AX.60)
ms:contentKeyID: 62204615
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.IsAuthenticated
dev_langs:
- CSharp
- C++
- VB
---

# IsAuthenticated Method

Gets or sets the bool that indicates whether or not this user is authenticated.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function IsAuthenticated As Boolean
'Usage
Dim returnValue As Boolean

returnValue = ClaimsValidation.IsAuthenticated()
```

``` csharp
public static bool IsAuthenticated()
```

``` c++
public:
static bool IsAuthenticated()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True, if the user is authenticated, else false.  

## See Also

#### Reference

[ClaimsValidation Class](claimsvalidation-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

