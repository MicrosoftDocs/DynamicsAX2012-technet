---
title: CustomClaimsProvider.AddCustomClaims Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: AddCustomClaims Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.AddCustomClaims(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.addcustomclaims(v=AX.60)
ms:contentKeyID: 62205415
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.AddCustomClaims
dev_langs:
- CSharp
- C++
- VB
---

# AddCustomClaims Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Add Custom claims name i.e. Email and customer Id

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub AddCustomClaims ( _
    customerId As String _
)
'Usage
Dim customerId As String

CustomClaimsProvider.AddCustomClaims(customerId)
```

``` csharp
public static void AddCustomClaims(
    string customerId
)
```

``` c++
public:
static void AddCustomClaims(
    String^ customerId
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomClaimsProvider Class](customclaimsprovider-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

