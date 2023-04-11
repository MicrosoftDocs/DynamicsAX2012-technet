---
title: LoggingService.GetLocalLoggingService Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetLocalLoggingService Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.LoggingService.GetLocalLoggingService(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.loggingservice.getlocalloggingservice(v=AX.60)
ms:contentKeyID: 62205428
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.LoggingService.GetLocalLoggingService
dev_langs:
- CSharp
- C++
- VB
---

# GetLocalLoggingService Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets an instance of the logging service with the specified name.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetLocalLoggingService ( _
    loggingServiceName As String _
) As LoggingService
'Usage
Dim loggingServiceName As String
Dim returnValue As LoggingService

returnValue = LoggingService.GetLocalLoggingService(loggingServiceName)
```

``` csharp
public static LoggingService GetLocalLoggingService(
    string loggingServiceName
)
```

``` c++
public:
static LoggingService^ GetLocalLoggingService(
    String^ loggingServiceName
)
```

#### Parameters

  - loggingServiceName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Common.LoggingService](loggingservice-class-microsoft-dynamics-retail-sharepoint-common.md)  
Instance of logging service with the specified name.  

## See Also

#### Reference

[LoggingService Class](loggingservice-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

