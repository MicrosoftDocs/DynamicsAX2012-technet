---
title: ClaimsValidation.UpdateSPUserName Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: UpdateSPUserName Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.UpdateSPUserName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.claimsvalidation.updatespusername(v=AX.60)
ms:contentKeyID: 62205999
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.UpdateSPUserName
dev_langs:
- CSharp
- C++
- VB
---

# UpdateSPUserName Method

Update the Sharepoint User NAme property to a value more palatable for the end user.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function UpdateSPUserName As Boolean
'Usage
Dim returnValue As Boolean

returnValue = ClaimsValidation.UpdateSPUserName()
```

``` csharp
public static bool UpdateSPUserName()
```

``` c++
public:
static bool UpdateSPUserName()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if the UserName was updated, false if it wasn't.  

## Remarks

1\. GivenName claim if present -or- 2. Email claim if present

## See Also

#### Reference

[ClaimsValidation Class](claimsvalidation-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

