---
title: ClaimsValidation.IsAssociated Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: IsAssociated Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.IsAssociated
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.claimsvalidation.isassociated(v=AX.60)
ms:contentKeyID: 62204632
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.IsAssociated
dev_langs:
- CSharp
- C++
- VB
---

# IsAssociated Method

Gets or sets the bool that indicates if this identity is associated to an AX customer yet.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function IsAssociated As Boolean
'Usage
Dim returnValue As Boolean

returnValue = ClaimsValidation.IsAssociated()
```

``` csharp
public static bool IsAssociated()
```

``` c++
public:
static bool IsAssociated()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True, if the user is associated with an Ax customer.  

## See Also

#### Reference

[ClaimsValidation Class](claimsvalidation-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

