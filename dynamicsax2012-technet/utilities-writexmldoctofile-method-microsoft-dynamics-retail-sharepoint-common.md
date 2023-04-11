---
title: Utilities.WriteXmlDocToFile Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: WriteXmlDocToFile Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.WriteXmlDocToFile(System.Xml.XmlDocument,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.utilities.writexmldoctofile(v=AX.60)
ms:contentKeyID: 62202251
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.WriteXmlDocToFile
dev_langs:
- CSharp
- C++
- VB
---

# WriteXmlDocToFile Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Saves the xml document to the specified file.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub WriteXmlDocToFile ( _
    xmlDoc As XmlDocument, _
    targetFileFullName As String _
)
'Usage
Dim xmlDoc As XmlDocument
Dim targetFileFullName As String

Utilities.WriteXmlDocToFile(xmlDoc, targetFileFullName)
```

``` csharp
public static void WriteXmlDocToFile(
    XmlDocument xmlDoc,
    string targetFileFullName
)
```

``` c++
public:
static void WriteXmlDocToFile(
    XmlDocument^ xmlDoc, 
    String^ targetFileFullName
)
```

#### Parameters

  - xmlDoc  
    Type: [System.Xml.XmlDocument](https://technet.microsoft.com/library/6kza7w4k\(v=ax.60\))  

<!-- end list -->

  - targetFileFullName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

