---
title: ResultSourcePickerWebPart.QueryPropertiesTemplateUrl Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: QueryPropertiesTemplateUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ResultSourcePickerWebPart.QueryPropertiesTemplateUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.resultsourcepickerwebpart.querypropertiestemplateurl(v=AX.60)
ms:contentKeyID: 62202764
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ResultSourcePickerWebPart.QueryPropertiesTemplateUrl
dev_langs:
- CSharp
- C++
- VB
---

# QueryPropertiesTemplateUrl Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the queryPropertiesTemplateUrl string

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebBrowsableAttribute(False)> _
Public Property QueryPropertiesTemplateUrl As String
    Get
    Set
'Usage
Dim instance As ResultSourcePickerWebPart
Dim value As String

value = instance.QueryPropertiesTemplateUrl

instance.QueryPropertiesTemplateUrl = value
```

``` csharp
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebBrowsableAttribute(false)]
public string QueryPropertiesTemplateUrl { get; set; }
```

``` c++
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebBrowsableAttribute(false)]
public:
property String^ QueryPropertiesTemplateUrl {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ResultSourcePickerWebPart Class](resultsourcepickerwebpart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

