---
title: WebConfigUpdater.EnsureChildXmlNode Method  (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures)
TOCTitle: EnsureChildXmlNode Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.EnsureChildXmlNode(System.Xml.XmlDocument,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.webconfigupdater.ensurechildxmlnode(v=AX.60)
ms:contentKeyID: 62205855
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.EnsureChildXmlNode
dev_langs:
- CSharp
- C++
- VB
---

# EnsureChildXmlNode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the specified child XML node. Creates the child node, if it does not exist already.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Protected Function EnsureChildXmlNode ( _
    xmlDoc As XmlDocument, _
    parentXPath As String, _
    childName As String _
) As XmlNode
'Usage
Dim xmlDoc As XmlDocument
Dim parentXPath As String
Dim childName As String
Dim returnValue As XmlNode

returnValue = Me.EnsureChildXmlNode(xmlDoc, _
    parentXPath, childName)
```

``` csharp
protected XmlNode EnsureChildXmlNode(
    XmlDocument xmlDoc,
    string parentXPath,
    string childName
)
```

``` c++
protected:
XmlNode^ EnsureChildXmlNode(
    XmlDocument^ xmlDoc, 
    String^ parentXPath, 
    String^ childName
)
```

#### Parameters

  - xmlDoc  
    Type: [System.Xml.XmlDocument](https://technet.microsoft.com/library/6kza7w4k\(v=ax.60\))  

<!-- end list -->

  - parentXPath  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - childName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Xml.XmlNode](https://technet.microsoft.com/library/bxz4hfh3\(v=ax.60\))  
The specified child node.  

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
<td><p>xmlDoc</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[WebConfigUpdater Class](webconfigupdater-class-microsoft-dynamics-retail-sharepoint-commonfeatures.md)

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)

