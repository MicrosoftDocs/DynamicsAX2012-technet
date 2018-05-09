---
title: FeatureReceiver.RemoveWebPartFromPage Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: RemoveWebPartFromPage Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.RemoveWebPartFromPage(Microsoft.SharePoint.SPWeb,System.Web.UI.WebControls.WebParts.WebPart,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.common.featurereceiver.removewebpartfrompage(v=AX.60)
ms:contentKeyID: 62206050
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.RemoveWebPartFromPage
dev_langs:
- CSharp
- C++
- VB
---

# RemoveWebPartFromPage Method

Programmatically adds a web part to a SharePoint site page.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub RemoveWebPartFromPage ( _
    web As SPWeb, _
    webPart As WebPart, _
    zoneId As String, _
    page As String _
)
'Usage
Dim web As SPWeb
Dim webPart As WebPart
Dim zoneId As String
Dim page As String

FeatureReceiver.RemoveWebPartFromPage(web, _
    webPart, zoneId, page)
```

``` csharp
public static void RemoveWebPartFromPage(
    SPWeb web,
    WebPart webPart,
    string zoneId,
    string page
)
```

``` c++
public:
static void RemoveWebPartFromPage(
    SPWeb^ web, 
    WebPart^ webPart, 
    String^ zoneId, 
    String^ page
)
```

#### Parameters

  - web  
    Type: SPWeb  

<!-- end list -->

  - webPart  
    Type: [System.Web.UI.WebControls.WebParts.WebPart](https://technet.microsoft.com/en-us/library/h0t1fxe7\(v=ax.60\))  

<!-- end list -->

  - zoneId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - page  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[FeatureReceiver Class](featurereceiver-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

