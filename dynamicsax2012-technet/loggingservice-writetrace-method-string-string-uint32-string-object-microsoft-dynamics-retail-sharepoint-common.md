---
title: LoggingService.WriteTrace Method (String, String, , UInt32, String, Object ) (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: WriteTrace Method (String, String, , UInt32, String, Object )
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.LoggingService.WriteTrace(System.String,System.String,Microsoft.SharePoint.Administration.TraceSeverity,System.UInt32,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.loggingservice.writetrace(v=AX.60)
ms:contentKeyID: 62205220
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# WriteTrace Method (String, String, , UInt32, String, Object[])


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Writes a trace.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub WriteTrace ( _
    loggingServiceName As String, _
    categoryName As String, _
    traceSeverity As TraceSeverity, _
    id As UInteger, _
    format As String, _
    ParamArray arg As Object() _
)
'Usage
Dim loggingServiceName As String
Dim categoryName As String
Dim traceSeverity As TraceSeverity
Dim id As UInteger
Dim format As String
Dim arg As Object()

LoggingService.WriteTrace(loggingServiceName, _
    categoryName, traceSeverity, id, _
    format, arg)
```

``` csharp
public static void WriteTrace(
    string loggingServiceName,
    string categoryName,
    TraceSeverity traceSeverity,
    uint id,
    string format,
    params Object[] arg
)
```

``` c++
public:
static void WriteTrace(
    String^ loggingServiceName, 
    String^ categoryName, 
    TraceSeverity traceSeverity, 
    unsigned int id, 
    String^ format, 
    ... array<Object^>^ arg
)
```

#### Parameters

  - loggingServiceName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - categoryName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - traceSeverity  
    Type: TraceSeverity  

<!-- end list -->

  - id  
    Type: [System.UInt32](https://technet.microsoft.com/library/ctys3981\(v=ax.60\))  

<!-- end list -->

  - format  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - arg  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[LoggingService Class](loggingservice-class-microsoft-dynamics-retail-sharepoint-common.md)

[WriteTrace Overload](loggingservice-writetrace-method-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

