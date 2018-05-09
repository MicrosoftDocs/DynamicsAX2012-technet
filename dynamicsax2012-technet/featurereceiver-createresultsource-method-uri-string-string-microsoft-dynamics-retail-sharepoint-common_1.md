---
title: FeatureReceiver.CreateResultSource Method (, Uri, String, String, ) (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: CreateResultSource Method (, Uri, String, String, )
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.CreateResultSource(Microsoft.SharePoint.SPWeb,System.Uri,System.String,System.String,Microsoft.Office.Server.Search.Query.SortDirection)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.common.featurereceiver.createresultsource(v=AX.60)
ms:contentKeyID: 62205629
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateResultSource Method (, Uri, String, String, )

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
    sortBy As String, _
    sortDirection As SortDirection _
) As Source
'Usage
Dim publishingPortalWeb As SPWeb
Dim productCatalogUrl As Uri
Dim name As String
Dim sortBy As String
Dim sortDirection As SortDirection
Dim returnValue As Source

returnValue = FeatureReceiver.CreateResultSource(publishingPortalWeb, _
    productCatalogUrl, name, sortBy, _
    sortDirection)
```

``` csharp
public static Source CreateResultSource(
    SPWeb publishingPortalWeb,
    Uri productCatalogUrl,
    string name,
    string sortBy,
    SortDirection sortDirection
)
```

``` c++
public:
static Source^ CreateResultSource(
    SPWeb^ publishingPortalWeb, 
    Uri^ productCatalogUrl, 
    String^ name, 
    String^ sortBy, 
    SortDirection sortDirection
)
```

#### Parameters

  - publishingPortalWeb  
    Type: SPWeb  

<!-- end list -->

  - productCatalogUrl  
    Type: [System.Uri](https://technet.microsoft.com/en-us/library/txt7706a\(v=ax.60\))  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - sortBy  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - sortDirection  
    Type: SortDirection  

#### Return Value

Type: Source  
Result Source object  

## Remarks

This method is used to create result sources populated in the drop down in the product gallery page

## See Also

#### Reference

[FeatureReceiver Class](featurereceiver-class-microsoft-dynamics-retail-sharepoint-common.md)

[CreateResultSource Overload](featurereceiver-createresultsource-method-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

