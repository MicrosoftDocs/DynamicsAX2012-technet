---
title: Utilities.ConvertRichMediaToJson Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core)
TOCTitle: ConvertRichMediaToJson Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Utilities.ConvertRichMediaToJson(Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocations)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.utilities.convertrichmediatojson(v=AX.60)
ms:contentKeyID: 65316336
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Utilities.ConvertRichMediaToJson
dev_langs:
- CSharp
- C++
- VB
---

# ConvertRichMediaToJson Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

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

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-ecommerce-sdk-core.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)

