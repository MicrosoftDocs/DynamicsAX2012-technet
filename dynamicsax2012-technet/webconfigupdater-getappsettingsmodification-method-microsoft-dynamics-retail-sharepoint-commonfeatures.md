---
title: WebConfigUpdater.GetAppSettingsModification Method  (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures)
TOCTitle: GetAppSettingsModification Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.GetAppSettingsModification(Microsoft.SharePoint.SPFeaturePropertyCollection,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.webconfigupdater.getappsettingsmodification(v=AX.60)
ms:contentKeyID: 62206551
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.GetAppSettingsModification
dev_langs:
- CSharp
- C++
- VB
---

# GetAppSettingsModification Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the app settings modification.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Protected Function GetAppSettingsModification ( _
    properties As SPFeaturePropertyCollection, _
    propertyName As String _
) As SPWebConfigModification
'Usage
Dim properties As SPFeaturePropertyCollection
Dim propertyName As String
Dim returnValue As SPWebConfigModification

returnValue = Me.GetAppSettingsModification(properties, _
    propertyName)
```

``` csharp
protected SPWebConfigModification GetAppSettingsModification(
    SPFeaturePropertyCollection properties,
    string propertyName
)
```

``` c++
protected:
SPWebConfigModification^ GetAppSettingsModification(
    SPFeaturePropertyCollection^ properties, 
    String^ propertyName
)
```

#### Parameters

  - properties  
    Type: SPFeaturePropertyCollection  

<!-- end list -->

  - propertyName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: SPWebConfigModification  
An object representing the app settings changes in the web configuration file.  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>properties or propertyName</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[WebConfigUpdater Class](webconfigupdater-class-microsoft-dynamics-retail-sharepoint-commonfeatures.md)

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)

