---
title: Utilities.RegisterWebApplicationForMonitoringDiscovery Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: RegisterWebApplicationForMonitoringDiscovery Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.RegisterWebApplicationForMonitoringDiscovery(System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.utilities.registerwebapplicationformonitoringdiscovery(v=AX.60)
ms:contentKeyID: 62202585
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.RegisterWebApplicationForMonitoringDiscovery
dev_langs:
- CSharp
- C++
- VB
---

# RegisterWebApplicationForMonitoringDiscovery Method

Register web application in the registry, so monitoring applications can discover it.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub RegisterWebApplicationForMonitoringDiscovery ( _
    webAppName As String, _
    url As String, _
    publisherName As String, _
    publisherNameMonitoring As String _
)
'Usage
Dim webAppName As String
Dim url As String
Dim publisherName As String
Dim publisherNameMonitoring As String

Utilities.RegisterWebApplicationForMonitoringDiscovery(webAppName, _
    url, publisherName, publisherNameMonitoring)
```

``` csharp
public static void RegisterWebApplicationForMonitoringDiscovery(
    string webAppName,
    string url,
    string publisherName,
    string publisherNameMonitoring
)
```

``` c++
public:
static void RegisterWebApplicationForMonitoringDiscovery(
    String^ webAppName, 
    String^ url, 
    String^ publisherName, 
    String^ publisherNameMonitoring
)
```

#### Parameters

  - webAppName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - url  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - publisherName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - publisherNameMonitoring  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

