---
title: ClaimsValidation.GetAssociatedId Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: GetAssociatedId Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.GetAssociatedId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.claimsvalidation.getassociatedid(v=AX.60)
ms:contentKeyID: 62206994
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.GetAssociatedId
dev_langs:
- CSharp
- C++
- VB
---

# GetAssociatedId Method

Gets the customer Id from the claims for the authenticated user.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetAssociatedId As String
'Usage
Dim returnValue As String

returnValue = ClaimsValidation.GetAssociatedId()
```

``` csharp
public static string GetAssociatedId()
```

``` c++
public:
static String^ GetAssociatedId()
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The Ax customer identifer.  

## See Also

#### Reference

[ClaimsValidation Class](claimsvalidation-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

