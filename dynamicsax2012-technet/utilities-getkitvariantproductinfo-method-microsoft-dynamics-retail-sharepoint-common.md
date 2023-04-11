---
title: Utilities.GetKitVariantProductInfo Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetKitVariantProductInfo Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.GetKitVariantProductInfo(System.SByte,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.utilities.getkitvariantproductinfo(v=AX.60)
ms:contentKeyID: 62205077
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.GetKitVariantProductInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetKitVariantProductInfo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetKitVariantProductInfo ( _
    kitMasterProductId As SByte, _
    catalogId As String, _
    kitLines As String _
) As Tuple
'Usage
Dim kitMasterProductId As SByte
Dim catalogId As String
Dim kitLines As String
Dim returnValue As Tuple

returnValue = Utilities.GetKitVariantProductInfo(kitMasterProductId, _
    catalogId, kitLines)
```

``` csharp
public static Tuple GetKitVariantProductInfo(
    sbyte kitMasterProductId,
    string catalogId,
    string kitLines
)
```

``` c++
public:
static Tuple^ GetKitVariantProductInfo(
    signed char kitMasterProductId, 
    String^ catalogId, 
    String^ kitLines
)
```

#### Parameters

  - kitMasterProductId  
    Type: [System.SByte](https://technet.microsoft.com/library/f71b253d\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - kitLines  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: Tuple  
Returns Tuple.  

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

