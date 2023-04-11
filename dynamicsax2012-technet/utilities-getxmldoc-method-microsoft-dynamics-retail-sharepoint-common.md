---
title: Utilities.GetXmlDoc Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetXmlDoc Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.GetXmlDoc(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.utilities.getxmldoc(v=AX.60)
ms:contentKeyID: 62204608
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.GetXmlDoc
dev_langs:
- CSharp
- C++
- VB
---

# GetXmlDoc Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Xml document object of the specified Xml file.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetXmlDoc ( _
    xmlFileFullName As String _
) As XmlDocument
'Usage
Dim xmlFileFullName As String
Dim returnValue As XmlDocument

returnValue = Utilities.GetXmlDoc(xmlFileFullName)
```

``` csharp
public static XmlDocument GetXmlDoc(
    string xmlFileFullName
)
```

``` c++
public:
static XmlDocument^ GetXmlDoc(
    String^ xmlFileFullName
)
```

#### Parameters

  - xmlFileFullName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Xml.XmlDocument](https://technet.microsoft.com/library/6kza7w4k\(v=ax.60\))  
XmlDocument representation of the Xml file.  

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

