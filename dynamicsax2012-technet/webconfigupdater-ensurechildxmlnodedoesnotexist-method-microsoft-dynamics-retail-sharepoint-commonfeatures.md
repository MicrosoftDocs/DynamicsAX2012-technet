---
title: WebConfigUpdater.EnsureChildXmlNodeDoesNotExist Method  (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures)
TOCTitle: EnsureChildXmlNodeDoesNotExist Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.EnsureChildXmlNodeDoesNotExist(System.Xml.XmlDocument,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.commonfeatures.webconfigupdater.ensurechildxmlnodedoesnotexist(v=AX.60)
ms:contentKeyID: 62202611
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.EnsureChildXmlNodeDoesNotExist
dev_langs:
- CSharp
- C++
- VB
---

# EnsureChildXmlNodeDoesNotExist Method

Ensures the child XML node does not exist.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Protected Sub EnsureChildXmlNodeDoesNotExist ( _
    xmlDoc As XmlDocument, _
    parentXPath As String, _
    childXPath As String _
)
'Usage
Dim xmlDoc As XmlDocument
Dim parentXPath As String
Dim childXPath As String

Me.EnsureChildXmlNodeDoesNotExist(xmlDoc, _
    parentXPath, childXPath)
```

``` csharp
protected void EnsureChildXmlNodeDoesNotExist(
    XmlDocument xmlDoc,
    string parentXPath,
    string childXPath
)
```

``` c++
protected:
void EnsureChildXmlNodeDoesNotExist(
    XmlDocument^ xmlDoc, 
    String^ parentXPath, 
    String^ childXPath
)
```

#### Parameters

  - xmlDoc  
    Type: [System.Xml.XmlDocument](https://technet.microsoft.com/en-us/library/6kza7w4k\(v=ax.60\))  

<!-- end list -->

  - parentXPath  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - childXPath  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

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
<td><a href="https://technet.microsoft.com/en-us/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>xmlDoc</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[WebConfigUpdater Class](webconfigupdater-class-microsoft-dynamics-retail-sharepoint-commonfeatures.md)

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)

