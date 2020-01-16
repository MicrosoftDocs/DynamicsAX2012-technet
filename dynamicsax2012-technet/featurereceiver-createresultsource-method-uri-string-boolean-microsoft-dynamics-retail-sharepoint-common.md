---
title: FeatureReceiver.CreateResultSource Method (, Uri, String, Boolean) (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: CreateResultSource Method (, Uri, String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.CreateResultSource(Microsoft.SharePoint.SPWeb,System.Uri,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.featurereceiver.createresultsource(v=AX.60)
ms:contentKeyID: 62204714
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateResultSource Method (, Uri, String, Boolean)

Creates ResultSource to be used by CBSs.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateResultSource ( _
    publishingPortalWeb As SPWeb, _
    productCatalogUrl As Uri, _
    name As String, _
    isGiftCard As Boolean _
) As Source
'Usage
Dim publishingPortalWeb As SPWeb
Dim productCatalogUrl As Uri
Dim name As String
Dim isGiftCard As Boolean
Dim returnValue As Source

returnValue = FeatureReceiver.CreateResultSource(publishingPortalWeb, _
    productCatalogUrl, name, isGiftCard)
```

``` csharp
public static Source CreateResultSource(
    SPWeb publishingPortalWeb,
    Uri productCatalogUrl,
    string name,
    bool isGiftCard
)
```

``` c++
public:
static Source^ CreateResultSource(
    SPWeb^ publishingPortalWeb, 
    Uri^ productCatalogUrl, 
    String^ name, 
    bool isGiftCard
)
```

#### Parameters

  - publishingPortalWeb  
    Type: SPWeb  

<!-- end list -->

  - productCatalogUrl  
    Type: [System.Uri](https://technet.microsoft.com/library/txt7706a\(v=ax.60\))  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isGiftCard  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: Source  
Result Source object  

## Remarks

This method is used to create result sources for all CBS webparts

## See Also

#### Reference

[FeatureReceiver Class](featurereceiver-class-microsoft-dynamics-retail-sharepoint-common.md)

[CreateResultSource Overload](featurereceiver-createresultsource-method-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

