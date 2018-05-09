---
title: ClaimsValidation.IsWindowsIdentityProvider Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: IsWindowsIdentityProvider Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.IsWindowsIdentityProvider
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.claimsvalidation.iswindowsidentityprovider(v=AX.60)
ms:contentKeyID: 62206943
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.ClaimsValidation.IsWindowsIdentityProvider
dev_langs:
- CSharp
- C++
- VB
---

# IsWindowsIdentityProvider Method

Returns bool based on if Identity Provider is Windows

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function IsWindowsIdentityProvider As Boolean
'Usage
Dim returnValue As Boolean

returnValue = ClaimsValidation.IsWindowsIdentityProvider()
```

``` csharp
public static bool IsWindowsIdentityProvider()
```

``` c++
public:
static bool IsWindowsIdentityProvider()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if the identity provider is Windows, else false.  

## See Also

#### Reference

[ClaimsValidation Class](claimsvalidation-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

