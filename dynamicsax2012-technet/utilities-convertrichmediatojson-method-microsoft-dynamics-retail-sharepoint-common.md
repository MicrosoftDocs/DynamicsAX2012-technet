---
title: Utilities.ConvertRichMediaToJson Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: ConvertRichMediaToJson Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.ConvertRichMediaToJson(Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocations)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.utilities.convertrichmediatojson(v=AX.60)
ms:contentKeyID: 62204246
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.ConvertRichMediaToJson
dev_langs:
- CSharp
- C++
- VB
---

# ConvertRichMediaToJson Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Converts Enrichment to JSON format.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertRichMediaToJson ( _
    enrichments As RichMediaLocations _
) As String
'Usage
Dim enrichments As RichMediaLocations
Dim returnValue As String

returnValue = Utilities.ConvertRichMediaToJson(enrichments)
```

``` csharp
public static string ConvertRichMediaToJson(
    RichMediaLocations enrichments
)
```

``` c++
public:
static String^ ConvertRichMediaToJson(
    RichMediaLocations^ enrichments
)
```

#### Parameters

  - enrichments  
    Type: RichMediaLocations  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
JSON which was created from the enrichment.  

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

