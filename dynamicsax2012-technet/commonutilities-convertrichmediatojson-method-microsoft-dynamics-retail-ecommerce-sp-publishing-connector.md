---
title: CommonUtilities.ConvertRichMediaToJson Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector)
TOCTitle: ConvertRichMediaToJson Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CommonUtilities.ConvertRichMediaToJson(Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocations)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.commonutilities.convertrichmediatojson(v=AX.60)
ms:contentKeyID: 65316108
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CommonUtilities.ConvertRichMediaToJson
dev_langs:
- CSharp
- C++
- VB
---

# ConvertRichMediaToJson Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertRichMediaToJson ( _
    enrichments As RichMediaLocations _
) As String
'Usage
Dim enrichments As RichMediaLocations
Dim returnValue As String

returnValue = CommonUtilities.ConvertRichMediaToJson(enrichments)
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

## See Also

#### Reference

[CommonUtilities Class](commonutilities-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)

