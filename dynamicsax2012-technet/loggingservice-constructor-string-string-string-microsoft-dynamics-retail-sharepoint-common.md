---
title: LoggingService Constructor (String, String, String) (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: LoggingService Constructor (String, String, String)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.LoggingService.#ctor(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.loggingservice.loggingservice(v=AX.60)
ms:contentKeyID: 62203825
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# LoggingService Constructor (String, String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [LoggingService](loggingservice-class-microsoft-dynamics-retail-sharepoint-common.md) class.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    loggingServiceName As String, _
    areaName As String, _
    loggingCategoryName As String _
)
'Usage
Dim loggingServiceName As String
Dim areaName As String
Dim loggingCategoryName As String

Dim instance As New LoggingService(loggingServiceName, _
    areaName, loggingCategoryName)
```

``` csharp
public LoggingService(
    string loggingServiceName,
    string areaName,
    string loggingCategoryName
)
```

``` c++
public:
LoggingService(
    String^ loggingServiceName, 
    String^ areaName, 
    String^ loggingCategoryName
)
```

#### Parameters

  - loggingServiceName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - areaName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - loggingCategoryName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[LoggingService Class](loggingservice-class-microsoft-dynamics-retail-sharepoint-common.md)

[LoggingService Overload](loggingservice-constructor-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

